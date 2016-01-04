#### Test 50388019831b9e1_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/art     ( 1441): Explicit concurrent mark sweep GC freed 3796(164KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 247us total 10.951ms
--------- beginning of system
I/ActivityManager(  757): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2129 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
W/ResourcesManager( 2129): Asset path '/system/framework/serviceitems.jar' does not exist or contains no resources.
W/ResourcesManager( 2129): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  757): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2147 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/QcrilMsgTunnelAutoboot( 2147): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 2147): onCreate method
D/QcrilMsgTunnelIfaceManager( 2147): : Instantiated
V/QcrilMsgTunnelSocket( 2147): Starting QcRil Sender & Receiver threads
D/QcrilMsgTunnelIfaceManager( 2147):  Registered for UNSOL OEM HOOK Responses to deliver external apps
I/QcrilMsgTunnelSocket( 2147): Connected to 'qmux_radio/rild_oem0' socket
D/FileApkUtils( 1565): Spent 34ms computing apk sha1.
D/FileApkUtils( 1565): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 1565): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 1565): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1565): Keeping up-to-date module: module-71c764a6f3cb92bdc5525a965b589e7c5ed304f3
D/ChimeraCfgMgr( 1565): Reading stored module config
I/art     ( 1565): Explicit concurrent mark sweep GC freed 53046(3MB) AllocSpace objects, 37(592KB) LOS objects, 39% free, 19MB/32MB, paused 776us total 38.332ms
D/GmsModuleFndr( 1565): Beginning GMS chimera module scan
D/GmsModuleFndr( 1565): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1565): Beginning module configuration check
D/ChimeraCfgMgr( 1565): Module APKs unchanged, check complete
W/InstanceID/Rpc( 1565): Found 10008
D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/BootCompletedReceiver( 1565): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 1565): Got an BootCompleted event.
D/BootCompletedReceiver( 1565): Will NOT schedule AdAttestation signal task because it's disabled.
V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1565): COMPAT: Multi user ser=0 current=0
I/GCoreUlr( 1565): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/CheckinService( 1565): Checkin interval check for package: unspecified last checkin: 1451326504256 min interval config: 0 actual interval: 595114442
I/CheckinService( 1565): Disabling old GoogleServicesFramework version
D/SystemUpdateService( 1565): onCreate
D/SystemUpdateService( 1565): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 1565): Handling intent: android.intent.action.BOOT_COMPLETED
I/art     ( 1288): Explicit concurrent mark sweep GC freed 24785(1616KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 21MB/35MB, paused 1.180ms total 43.558ms
D/AuthZenEventHandler( 1565): Handling event: android.intent.action.BOOT_COMPLETED
W/BaseAppContext( 1565): Using Auth Proxy for data requests.
I/CheckinService( 1565): Checking schedule, now: 1451921618812 next: 1451368671234
I/CheckinService( 1565): active receiver: enabled
I/SystemUpdateService( 1565): active receiver: enabled
I/art     (  757): Explicit concurrent mark sweep GC freed 16189(811KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/40MB, paused 1.028ms total 61.932ms
I/art     ( 1441): Explicit concurrent mark sweep GC freed 2557(99KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 562us total 18.419ms
E/BaseAppContext( 1565): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/AuthZen ( 1565): Fetching signing key...
I/SystemUpdateService( 1565): showing system update notification
I/AuthZen ( 1565): Signing key fetched successfully!
W/BaseAppContext( 1565): Using Auth Proxy for data requests.
I/ValidateNoPeople(  757): skipping global notification
V/SystemUpdateService( 1565): retry (wakeup: false) in 3599862 ms
D/SystemUpdateService( 1565): onDestroy
W/ResourcesManager(  901): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  901): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/a       ( 1565): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 1565): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1565): Clearing transaction cache
D/GCM     ( 1288): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1288): DispatchingService.onCreate()
I/art     ( 1441): Explicit concurrent mark sweep GC freed 2701(105KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/26MB, paused 682us total 11.910ms
I/GCoreUlr( 1288): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/GCoreFlp( 1288): No location to return for getLastLocation()
W/FusedLocationProvider( 1288): location=null
W/GCoreFlp( 1288): No location to return for getLastLocation()
W/FusedLocationProvider( 1288): location=null
W/Auth    ( 1288): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PersistentNotificationBroadcastReceiver( 1288): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/GCoreUlr( 1288): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/ActivityManager(  757): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2223 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/GCoreUlr( 1288): Unbound from all location providers
I/GCoreUlr( 1288): Place inference reporting - stopped
I/GCoreUlr( 1288): DispatchingService.onDestroy()
I/GCoreUlr( 1288): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1288): Unbound from all location providers
I/GCoreUlr( 1288): Place inference reporting - stopped
W/ResourcesManager( 2223): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2223): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 2240): 
D/AndroidRuntime( 2240): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2240): CheckJNI is OFF
V/JNIHelp ( 2223): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2223): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2223): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 2240): Calling main entry com.android.commands.am.Am
I/ActivityManager(  757): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2240): Shutting down VM
I/ActivityManager(  757): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2260 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1344): mic_close gfk@7e1ad60
D/audio_hw_primary(  188): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  188): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1344): Hotword detection finished
I/HotwordRecognitionRnr( 1344): Stopping hotword detection.
I/WebViewFactory( 2260): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2260): Time to load native libraries: 1 ms (timestamps 5224-5225)
I/LibraryLoader( 2260): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2260): Binding Chromium to main looper Looper (main, tid 1) {21549498}
I/LibraryLoader( 2260): Expected native library version number "",actual native library version number ""
I/chromium( 2260): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/dex2oat ( 2283): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1687171112.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads-1687171112.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/YouTube MDX( 2223): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/BrowserStartupController( 2260): Initializing chromium process, singleProcess=true
W/art     ( 2260): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2260): ApplicationContext is null in ApplicationStatus
W/chromium( 2260): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2260): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2260): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2260): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2260): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/dex2oat ( 2283): dex2oat took 49.532ms (threads: 4)
,D/BluetoothManagerService(  757): Message: 20
D/BluetoothManagerService(  757): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33134f9c:true
,D/BluetoothAdapter( 2260): 70565677: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2260): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2260): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2260): CordovaWebView is running on device made by: LGE
,W/art     ( 2260): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2260): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2260): Render dirty regions requested: true
,D/Atlas   ( 2260): Validating map...
,W/chromium( 2260): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2260): Initialized EGL, version 1.4
D/OpenGLRenderer( 2260): Enabling debug mode 0
,I/Keyboard.Facilitator( 1077): onFinishInput()
,I/ActivityManager(  757): Displayed com.example.hello/.MainActivity: +446ms (total +12s42ms)
,W/InstanceID/Rpc( 2223): Found 10008
,W/BindingManager( 2260): Cannot call determinedVisibility() - never saw a connection for the pid: 2260
,I/chromium( 2260): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2260): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2260): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager(  757): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=2371 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/jxcore_app_log( 2260): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2260): jxcore cordova android initializing
,W/ResourcesManager( 2371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/jxcore-log( 2260): Initializing JXcore engine
W/jxcore-log( 2260): JXcore engine is ready
,W/jxcore-log( 2260): Starting JXcore engine
,W/m.example.hello( 2260): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7772]" dev="sockfs" ino=7772 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 2260): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 2260): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9827]" dev="sockfs" ino=9827 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2260): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[15527]" dev="sockfs" ino=15527 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/jxcore-log( 2260): Platform android
W/jxcore-log( 2260): 
W/jxcore-log( 2260): Process ARCH arm
W/jxcore-log( 2260): 
,I/jxcore-log( 2260): JXcore Cordova bridge is ready!
I/jxcore-log( 2260): 
,W/jxcore-log( 2260): JXcore engine is started
,E/jxcore-log( 2260): >> LGE-Nexus 5
E/jxcore-log( 2260): 
I/jxcore-log( 2260): Total memory 1946181632
I/jxcore-log( 2260): 
I/jxcore-log( 2260): Free memory 447389696
I/jxcore-log( 2260): 
I/jxcore-log( 2260): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2260): 
I/jxcore-log( 2260): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2260): 
I/jxcore-log( 2260): userPath [ 'www' ]
I/jxcore-log( 2260): 
,I/jxcore-log( 2260): Size 1080 1776
I/jxcore-log( 2260): 
,I/jxcore-log( 2260): Screen Brightness 82
I/jxcore-log( 2260): 
E/jxcore-log( 2260): Dummy Error Log.
E/jxcore-log( 2260): 
,I/Babel_SMS( 2371): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 2371): MmsConfig.loadMmsSettings
,I/Babel_SMS( 2371): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2371): MmsConfig.loadFromDatabase
,E/Babel_SMS( 2371): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 2371): MmsConfig.loadFromResources
,E/Babel_SMS( 2371): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 2371): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
,I/Babel_SMS( 2371): ApnsOta: OTA version -1
,W/Settings( 2371): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 2371): startup - clean
,I/Babel   ( 2371): deleted: false for 0
,V/Babel   ( 2371): babel boot account: thalitester@gmail.com
,W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
,I/VideoCapabilities( 2371): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 2371): onServiceConnected
W/Babel   ( 2371): Attempted to change video mute state without an active call.
,I/ActivityManager(  757): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2407 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,E/SQLiteLog( 2371): (284) automatic index on conversation_participants_view(conversation_id)
,I/jxcore-log( 2260): getBuffer is called!!!!
I/jxcore-log( 2260): 
,W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2371): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 2371): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 2371): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  757): Killing 1634:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  757): Client connection lost with reason: 4
,I/GAv4    ( 2407): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2407):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2407):   adb logcat -s GAv4
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_1634/cgroup.procs: No such file or directory
,W/GAv4    ( 2407): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2407): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2407): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  757): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2436 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 1667:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10061/pid_1667/cgroup.procs: No such file or directory
,I/Gmail   ( 2436): getAccountsCursor
,D/ActivityThread( 2436): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  757): Explicit concurrent mark sweep GC freed 15196(733KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/40MB, paused 742us total 74.602ms
,I/ActivityManager(  757): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2475 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2436): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  757): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 2436): getAccountsCursor
,I/Gmail   ( 2436): Observing account changes for notifications
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  757): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2508 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  199): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 175us total 9.852ms
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  199): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.599ms
,I/art     (  199): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 164us total 7.433ms
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 2475): EasService.onCreate
,I/Exchange( 2475): RestartPingTask
,E/ActivityThread( 2436): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@27ff05d3 that was originally bound here
E/ActivityThread( 2436): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@27ff05d3 that was originally bound here
E/ActivityThread( 2436): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2436): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2436): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2436): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2436): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2436): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2436): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2436): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2436): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2436): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2436): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2436): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2436): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2436): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/a       ( 2436): RuntimeException when trying to unbind from service
E/a       ( 2436): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@27ff05d3
E/a       ( 2436): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/a       ( 2436): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/a       ( 2436): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/a       ( 2436): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2436): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2436): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/a       ( 2436): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2436): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2436): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2436): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2436): 	at java.lang.Thread.run(Thread.java:818)
,I/Exchange( 2475): RestartPingsTask did not start any pings.
I/Exchange( 2475): PSS stopIfIdle
I/Exchange( 2475): PSS has no active accounts; stopping service.
,I/Exchange( 2475): onDestroy
,I/ActivityManager(  757): Killing 1249:com.android.printspooler/u0a72 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10072/pid_1249/cgroup.procs: No such file or directory
,E/SQLiteLog( 2436): (283) recovered 91 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 2436): notifyAccountChanged
,I/Gmail   ( 2436): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2436): getAccountsCursor
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2436): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2436): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2436): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2436): getAccountsCursor
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2508): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 2508): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Settings( 2508): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2508): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Volley  ( 2508): [233] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2508): [226] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  757): Killing 1850:com.google.android.dialer/u0a10 (adj 15): empty #17
,I/ActivityManager(  757): Killing 1833:com.android.keychain/1000 (adj 15): empty #18
,I/SystemBroadcastReceiver( 1077): Boot has been completed
I/SystemBroadcastReceiver( 1077): toggleAppIcon() : FLAG_SYSTEM = true
,W/libprocessgroup(  757): failed to open /acct/uid_10010/pid_1850/cgroup.procs: No such file or directory
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_1833/cgroup.procs: No such file or directory
,D/Finsky  ( 2508): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2508): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 2508): Skipping gmscore version check
,V/UserPresentBroadcastReceiver( 1288): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/Finsky  ( 2508): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  757): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2559 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,D/Finsky  ( 2508): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/GAV2    ( 1344): Thread[GAThread,5,main]: No campaign data found.
,D/CellBroadcastReceiver( 2559): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2559): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2559): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  757): Killing 1309:android.process.acore/u0a4 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10004/pid_1309/cgroup.procs: No such file or directory
,I/GAv4-SVC( 1565): Google Analytics 8.4.89 is starting up.
,W/ContextImpl( 2012): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2012): Thread[GAThread,5,main]: No campaign data found.
,D/SIP     ( 1201): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  757): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=2595 uid=10004 gids={50004, 9997} abi=armeabi-v7a
,I/ActivityManager(  757): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2616 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 1956:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,I/ContactLocale( 2595): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,W/libprocessgroup(  757): failed to open /acct/uid_10012/pid_1956/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1344): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PackageBroadcastService( 1565): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Loading module APK com.google.android.play.games
,I/ActivityManager(  757): Killing 1984:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10014/pid_1984/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  757): Resuming delayed broadcast
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1565): Submit a task: k
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1565): Processing package: com.example.hello
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/UpdateIcingCorporaServi( 1344): UpdateCorporaTask done [took 245 ms] updated apps [took 245 ms] 
,D/GassUtils( 1565): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/k       ( 1565): Found info for package com.example.hello in db.
,I/ActivityManager(  757): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2645 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,I/art     ( 1565): Explicit concurrent mark sweep GC freed 44385(3MB) AllocSpace objects, 38(608KB) LOS objects, 24% free, 20MB/27MB, paused 589us total 55.551ms
,I/PeopleDatabaseHelper( 1565): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 2645): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2645):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2645):   adb logcat -s GAv4
,W/GAv4    ( 2645): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2645): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2645): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  757): Explicit concurrent mark sweep GC freed 11256(571KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/40MB, paused 796us total 53.027ms
,I/art     (  757): WaitForGcToComplete blocked for 17.421ms for cause HeapTrim
,W/AnalyticsTrackerProxyImpl( 2645): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,D/Finsky  ( 2508): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/ActivityManager(  757): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2692 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2645): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2645): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  757): Killing 1925:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10002/pid_1925/cgroup.procs: No such file or directory
,W/ResourcesManager( 2692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 2645): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 2645): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2645): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1288): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 1565): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,D/Icing   ( 1565): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1565): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/Icing   ( 1565): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/Icing   ( 1565): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
,I/ActivityManager(  757): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2721 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 2059:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10036/pid_2059/cgroup.procs: No such file or directory
,I/MusicStore( 2721): Database version: 120
,W/ResourcesManager( 2721): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2721): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2721): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2721): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2721): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@320e6646: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2721): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2721): GMSCore installation verified
,I/ConfigStore( 2721): Config Database version: 1
,I/MediaRouter( 2721): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2721): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2721): Using platform SSLCertificateSocketFactory
,I/art     ( 1288): Explicit concurrent mark sweep GC freed 17456(1157KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 21MB/35MB, paused 705us total 33.595ms
,D/GCM     ( 1288): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GCoreFlp( 1288): No location to return for getLastLocation()
,W/FusedLocationProvider( 1288): location=null
,I/MediaStoreImporter( 2721): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  757): Killing 2094:com.google.android.keep/u0a71 (adj 15): empty #17
,D/BluetoothManagerService(  757): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  757): disable(): mBluetooth = null mBinding = false
W/libprocessgroup(  757): failed to open /acct/uid_10071/pid_2094/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  757): Message: 2
,D/WifiService(  757): New client listening to asynchronous messages
,D/WifiService(  757): setWifiEnabled: false pid=2260, uid=10278
E/WifiService(  757): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2260): ****TEST TOOK:  5035  ms ****
I/jxcore-log( 2260): 
I/jxcore-log( 2260): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2260): 
,I/ActivityManager(  757): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2793 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2371): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2371): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2793): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 2371): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CalendarProvider2( 2793): Created com.android.providers.calendar.CalendarAlarmManager@3915ce7b(com.android.providers.calendar.CalendarProvider2@21549498)
,E/SQLiteLog( 2793): (284) automatic index on view_events(_id)
,W/System  ( 2371): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2371): Installed default security provider GmsCore_OpenSSL
,D/AndroidRuntime( 2787): 
D/AndroidRuntime( 2787): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2787): CheckJNI is OFF
,E/PhoneInterfaceManager( 1201): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/Babel   ( 2371): connection state changed from UNKNOWN to DISCONNECTED
,D/AndroidRuntime( 2787): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  757): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
,I/ActivityManager(  757): Killing 2260:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  757): WIN DEATH: Window{2f29db82 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  757): Client connection lost with reason: 4
,W/PackageSettings(  757): Skipping PackageSetting{344e4275 com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  757): Force removing ActivityRecord{22fd25e6 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  757): Spurious death for ProcessRecord{b51c02b 2260:com.example.hello/u0a278}, curProc for 2260: null
,I/ActivityManager(  757): Force stopping com.example.hello appid=10278 user=0: pkg removed
,I/Keyboard.Facilitator( 1077): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1077): run()
W/GeofencerStateMachine( 1288): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1077): createOrResetDecoder
I/InputReader(  757): Reconfiguring input devices.  changes=0x00000010
D/VoicemailCleanupService( 2595): Cleaning up data for package: com.example.hello
,I/UpdateIcingCorporaServi( 1344): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ConfigService( 1288): onCreate
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1077): run()
,I/UpdateIcingCorporaServi( 1344): UpdateCorporaTask done [took 69 ms] updated apps [took 69 ms] 
,D/BackupManagerService(  757): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  757): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1077): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loading LM = contacts
,D/TaskPersister(  757): removeObsoleteFile: deleting file=214_task.xml
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1077): run() : Missing File = Personal.en_US.dict
W/InputMethodManagerService(  757): Got RemoteException sending setActive(false) notification to pid 2260 uid 10278
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1077): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1077): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1077): run()
I/StatsUtilsManager( 1077): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1077): shouldRecordStats() = Too Soon
W/Launcher( 1229): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3bd9c4f1 new=com.google.android.velvet.VelvetApplication@3bd9c4f1
,I/Keyboard.Facilitator( 1077): onFinishInput()
,I/art     (  757): Explicit concurrent mark sweep GC freed 18485(1130KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.289ms total 129.468ms
,I/ActivityManager(  757): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2843 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,D/AndroidRuntime( 2787): Shutting down VM
,I/MicrophoneInputStream( 1344): mic_starting gfk@1bd964e4
,I/HotwordRecognitionRnr( 1344): Starting hotword detection.
,I/AudioFlinger(  188): AudioFlinger's thread 0xb1bba000 ready to run
,I/MicrophoneInputStream( 1344): mic_started gfk@1bd964e4
,D/audio_hw_primary(  188): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  188): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  188): Failed to fetch the lookup information of the device 0000003E 
,E/ACDB-LOADER(  188): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  188): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  188): enable_audio_route: apply and update mixer path: audio-record
,W/ContextImpl( 2843): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1565): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1565): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
,W/ResourcesManager( 1229): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/LocationSettingsChecker( 1565): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1288): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1288): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1565): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
W/ResourcesManager( 1229): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/gH_CompatibleDatabase( 1565): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1565): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1565): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/HotwordWorker( 1344): onReady
,D/gH_CompatibleDatabase( 1565): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1565): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1565): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1565): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1565): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1565): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1565): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1565): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1565): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,I/GMPM-SVC( 1565): App measurement is starting up, version: 8489
I/GMPM-SVC( 1565): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,I/ActivityManager(  757): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2881 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,I/Icing   ( 1565): doRemovePackageData com.example.hello
,I/ActivityManager(  757): Killing 2129:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_1000/pid_2129/cgroup.procs: No such file or directory
,D/ConnectivityService(  757): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/OpenGLRenderer( 1229): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1229): Incorrectly called buildLayer on View: adg, destroying layer...
,W/DriveInitializer( 1565): Awaiting to be initialized
,W/DriveInitializer( 1565): Background init thread started
,E/DocListDatabase( 1565): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 1565): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/DocListDatabase( 1565): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1565): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1565): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1565): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1565): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1565): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 1565): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 1565): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 1565): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 1565): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1565): Process: com.google.android.gms, PID: 1565
E/AndroidRuntime( 1565): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 1565): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1565): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1565): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1565): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1565): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1565): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 1565): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 1565): 	at com.google.android.gms.drive.t.run(SourceFile:62)
,E/SQLiteLog( 1565): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1565): disk I/O error (code 3850)
E/DriveAsyncService( 1565): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1565): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1565): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1565): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1565): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1565): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1565): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1565): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1565): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1565): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1565): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1565): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1565): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1565): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1565): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1565): 	at java.lang.Thread.run(Thread.java:818)
,I/ActivityManager(  757): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2908 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  757): Killing 2223:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10080/pid_2223/cgroup.procs: No such file or directory
,I/ActivityManager(  757): Killing 2407:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  757): failed to open /acct/uid_10038/pid_2407/cgroup.procs: No such file or directory
,D/OpenGLRenderer(  757): Render dirty regions requested: true
,D/Atlas   (  757): Validating map...
,E/qdhwcomposer(  181): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  181): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
,E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  181): MdpData failed to play
E/qdoverlay(  181): == Dump MdpData start ==
E/qdoverlay(  181): == Dump OvFD fd=28 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  181): mOvData msmfb_overlay_data id=64
E/qdoverlay(  181): data msmfb_data offset=0 memid=52 id=0 flags=0x0 priv=0
E/qdoverlay(  181): == Dump MdpData end ==
E/qdhwcomposer(  181): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  181): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  181): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  181): hwc_set_primary: display commit fail!
,I/CalendarProvider2( 2793): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2793): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  757): Killing 2475:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,I/Adreno-EGL(  757): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,I/OpenGLRenderer(  757): Initialized EGL, version 1.4
,D/OpenGLRenderer(  757): Enabling debug mode 0
,W/libprocessgroup(  757): failed to open /acct/uid_10069/pid_2475/cgroup.procs: No such file or directory
,E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  181): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  181): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  181): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): Ctrl commit failed set overlay
E/qdhwcomposer(  181): configureLowRes: commit failed for low res panel
E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  181): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  181): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  181): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  181): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  181): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  181): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  181): Ctrl commit failed set overlay
E/qdhwcomposer(  181): configure: commit fails
E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl close error in unset
,E/qdoverlay(  181): GenericPipe failed to close ctrl
E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl close error in unset
E/qdoverlay(  181): GenericPipe failed to close ctrl
,E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl close error in unset
E/qdoverlay(  181): GenericPipe failed to close ctrl
E/qdoverlay(  181): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  181): MdpCtrl close error in unset
E/qdoverlay(  181): GenericPipe failed to close ctrl

```
