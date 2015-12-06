#### Test 502422853393492_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
E/UpdateRequestReceiver( 2082): ignoring update request
E/UpdateRequestReceiver( 2082): ignoring update request
E/UpdateRequestReceiver( 2082): ignoring update request
E/UpdateRequestReceiver( 2082): ignoring update request
E/UpdateRequestReceiver( 2082): ignoring update request
E/UpdateRequestReceiver( 2082): ignoring update request
--------- beginning of system
W/BroadcastQueue(  734): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.gallery3d/com.android.camera.DisableCameraReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/GoogleHttpClient( 1333): GMS http client unavailable, use old client
I/ActivityManager(  734): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2121 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/CalendarProvider2( 1966): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 1966): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  734): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2147 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
W/ResourcesManager( 2147): Asset path '/system/framework/serviceitems.jar' does not exist or contains no resources.
W/ResourcesManager( 2147): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  734): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2164 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/QcrilMsgTunnelAutoboot( 2164): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/QcrilMsgTunnelService( 2164): onCreate method
D/QcrilMsgTunnelIfaceManager( 2164): : Instantiated
V/QcrilMsgTunnelSocket( 2164): Starting QcRil Sender & Receiver threads
D/QcrilMsgTunnelIfaceManager( 2164):  Registered for UNSOL OEM HOOK Responses to deliver external apps
I/QcrilMsgTunnelSocket( 2164): Connected to 'qmux_radio/rild_oem0' socket
I/art     ( 1316): Explicit concurrent mark sweep GC freed 11877(660KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 19MB/32MB, paused 775us total 29.607ms
D/FileApkUtils( 1565): Spent 22ms computing apk sha1.
D/FileApkUtils( 1565): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 1565): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-2707d05c501ef4bf821813f1789ad0e56682eb5a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 1565): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1565): Keeping up-to-date module: module-2707d05c501ef4bf821813f1789ad0e56682eb5a
D/GmsModuleFndr( 1565): Beginning GMS chimera module scan
D/GmsModuleFndr( 1565): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1565): Beginning module configuration check
D/ChimeraCfgMgr( 1565): Module APKs unchanged, check complete
I/art     ( 1333): Explicit concurrent mark sweep GC freed 11391(625KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 561us total 22.887ms
D/GCM     ( 1565): COMPAT: Multi user ser=0 current=0
I/CheckinService( 1565): Checkin interval check for package: unspecified last checkin: 1449216236131 min interval config: 0 actual interval: 197723189
I/GCoreUlr( 1565): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/GCM     ( 1333): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/GCoreUlr( 1316): DispatchingService.onCreate()
I/CheckinService( 1565): Disabling old GoogleServicesFramework version
I/art     (  734): Explicit concurrent mark sweep GC freed 13207(636KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/40MB, paused 959us total 73.075ms
D/SystemUpdateService( 1565): onCreate
I/CheckinService( 1565): Checking schedule, now: 1449413959419 next: 1449258403101
I/CheckinService( 1565): active receiver: enabled
D/SystemUpdateService( 1565): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 1565): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1565): Handling event: android.intent.action.BOOT_COMPLETED
W/BaseAppContext( 1565): Using Auth Proxy for data requests.
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/SystemUpdateService( 1565): active receiver: enabled
I/GCoreUlr( 1316): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/AuthZen ( 1565): Fetching signing key...
I/AuthZen ( 1565): Signing key fetched successfully!
I/SystemUpdateService( 1565): showing system update notification
W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,D/a       ( 1565): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 1565): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1565): Clearing transaction cache
I/ValidateNoPeople(  734): skipping global notification
V/SystemUpdateService( 1565): retry (wakeup: false) in 3599917 ms
W/ResourcesManager(  898): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  898): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.kids from APK com.google.android.gms
D/SystemUpdateService( 1565): onDestroy
W/GCoreFlp( 1316): No location to return for getLastLocation()
W/FusedLocationProvider( 1565): location=null
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Auth    ( 1333): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/GCoreUlr( 1316): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1316): Unbound from all location providers
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 1565): Explicit concurrent mark sweep GC freed 32965(2MB) AllocSpace objects, 37(592KB) LOS objects, 39% free, 19MB/32MB, paused 1.921ms total 46.965ms
W/Kids    ( 1565): [AbstractKidsOperation] Invalid device state 3
I/Kids    ( 1565): [KidAccountFixer] No network connection
V/GmsCoreStatsServiceLauncher( 1565): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PersistentNotificationBroadcastReceiver( 1333): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/ActivityManager(  734): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2240 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1316): No location to return for getLastLocation()
W/FusedLocationProvider( 1565): location=null
I/GCoreUlr( 1316): DispatchingService.onDestroy()
I/GCoreUlr( 1316): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1316): Unbound from all location providers
D/AndroidRuntime( 2236): 
D/AndroidRuntime( 2236): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2236): CheckJNI is OFF
D/AndroidRuntime( 2236): Calling main entry com.android.commands.am.Am
I/ActivityManager(  734): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2236): Shutting down VM
I/ActivityManager(  734): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2272 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ResourcesManager( 2240): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2240): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MicrophoneInputStream( 1355): mic_close gfk@1c937648
D/audio_hw_primary(  185): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  185): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1355): Hotword detection finished
I/HotwordRecognitionRnr( 1355): Stopping hotword detection.
I/WebViewFactory( 2272): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/JNIHelp ( 2240): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/LibraryLoader( 2272): Time to load native libraries: 1 ms (timestamps 4453-4454)
I/LibraryLoader( 2272): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2272): Binding Chromium to main looper Looper (main, tid 1) {12a34b99}
I/LibraryLoader( 2272): Expected native library version number "",actual native library version number ""
I/chromium( 2272): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/System  ( 2240): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2240): Installed default security provider GmsCore_OpenSSL
I/BrowserStartupController( 2272): Initializing chromium process, singleProcess=true
W/art     ( 2272): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2272): ApplicationContext is null in ApplicationStatus
W/chromium( 2272): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 2272): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 2272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2272): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 2272): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  734): Message: 20
D/BluetoothManagerService(  734): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17cb52a5:true
D/BluetoothAdapter( 2272): 705667690: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2272): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2272): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2272): CordovaWebView is running on device made by: LGE
,W/art     ( 2272): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2272): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2272): Render dirty regions requested: true
,D/Atlas   ( 2272): Validating map...
,W/chromium( 2272): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/dex2oat ( 2325): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1412539630.jar --oat-fd=22 --oat-location=/data/data/com.google.android.youtube/cache/ads1412539630.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/YouTube MDX( 2240): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/OpenGLRenderer( 2272): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2272): Enabling debug mode 0
,I/ActivityManager(  734): Displayed com.example.hello/.MainActivity: +435ms (total +12s466ms)
,W/BindingManager( 2272): Cannot call determinedVisibility() - never saw a connection for the pid: 2272
,I/dex2oat ( 2325): dex2oat took 79.674ms (threads: 4)
,I/chromium( 2272): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2272): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2272): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 2272): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 2272): jxcore cordova android initializing
,W/InstanceID/Rpc( 2240): Found 10008
,W/jxcore-log( 2272): Initializing JXcore engine
W/jxcore-log( 2272): JXcore engine is ready
W/jxcore-log( 2272): Starting JXcore engine
,W/m.example.hello( 2272): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9415]" dev="sockfs" ino=9415 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2272): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 2272): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9468]" dev="sockfs" ino=9468 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2272): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[15777]" dev="sockfs" ino=15777 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,V/Babel   ( 1792): babel boot account: thalitester@gmail.com
,W/jxcore-log( 2272): Platform android
W/jxcore-log( 2272): 
W/jxcore-log( 2272): Process ARCH arm
W/jxcore-log( 2272): 
,I/ActivityManager(  734): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2392 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
E/SQLiteLog( 1792): (284) automatic index on conversation_participants_view(conversation_id)
,I/jxcore-log( 2272): JXcore Cordova bridge is ready!
I/jxcore-log( 2272): 
W/jxcore-log( 2272): JXcore engine is started
,W/VideoCapabilities( 1792): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 1792): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1792): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 1792): (284) automatic index on conversation_participants_view(conversation_id)
,E/jxcore-log( 2272): >> LGE-Nexus 5
E/jxcore-log( 2272): 
,I/jxcore-log( 2272): Total memory 1946181632
I/jxcore-log( 2272): 
,I/jxcore-log( 2272): Free memory 447774720
I/jxcore-log( 2272): 
I/jxcore-log( 2272): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2272): 
,I/jxcore-log( 2272): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2272): 
,E/SQLiteLog( 1792): (284) automatic index on conversation_participants_view(conversation_id)
,I/jxcore-log( 2272): userPath [ 'www' ]
I/jxcore-log( 2272): 
,I/jxcore-log( 2272): Size 1080 1776
I/jxcore-log( 2272): 
,I/jxcore-log( 2272): Screen Brightness 82
I/jxcore-log( 2272): 
E/jxcore-log( 2272): Dummy Error Log.
E/jxcore-log( 2272): 
,I/GAv4    ( 2392): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2392):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2392):   adb logcat -s GAv4
,I/art     (  734): Explicit concurrent mark sweep GC freed 12080(592KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/40MB, paused 903us total 65.519ms
,W/GAv4    ( 2392): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2392): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2392): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  734): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2416 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 1628:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  734): Client connection lost with reason: 4
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_1628/cgroup.procs: No such file or directory
,I/Gmail   ( 2416): getAccountsCursor
,D/ActivityThread( 2416): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1333): Explicit concurrent mark sweep GC freed 7475(422KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 19MB/32MB, paused 602us total 21.370ms
,I/jxcore-log( 2272): getBuffer is called!!!!
I/jxcore-log( 2272): 
,I/ActivityManager(  734): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2445 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2416): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 2416): getAccountsCursor
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemBroadcastReceiver( 1075): Boot has been completed
I/SystemBroadcastReceiver( 1075): toggleAppIcon() : FLAG_SYSTEM = true
V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2482 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  734): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/art     (  196): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 187us total 9.580ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.538ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.231ms
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Exchange( 2445): EasService.onCreate
,I/Gmail   ( 2416): Observing account changes for notifications
,I/Exchange( 2445): RestartPingTask
,E/ActivityThread( 2416): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@38baeb3b that was originally bound here
E/ActivityThread( 2416): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@38baeb3b that was originally bound here
E/ActivityThread( 2416): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2416): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2416): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2416): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2416): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2416): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2416): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2416): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2416): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2416): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2416): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2416): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2416): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2416): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2416): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2416): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Exchange( 2445): RestartPingsTask did not start any pings.
E/a       ( 2416): RuntimeException when trying to unbind from service
E/a       ( 2416): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@38baeb3b
E/a       ( 2416): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/a       ( 2416): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/a       ( 2416): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/a       ( 2416): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2416): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2416): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/a       ( 2416): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2416): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2416): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2416): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2416): 	at java.lang.Thread.run(Thread.java:818)
I/Exchange( 2445): PSS stopIfIdle
I/Exchange( 2445): PSS has no active accounts; stopping service.
,I/Exchange( 2445): onDestroy
,I/ActivityManager(  734): Killing 1660:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,E/SQLiteLog( 2416): (283) recovered 77 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Gmail   ( 2416): notifyAccountChanged
,I/Gmail   ( 2416): getAccountsCursor
,I/Gmail   ( 2416): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2416): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2416): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2416): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  734): failed to open /acct/uid_10061/pid_1660/cgroup.procs: No such file or directory
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  734): Killing 1243:com.android.printspooler/u0a72 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10072/pid_1243/cgroup.procs: No such file or directory
,D/Finsky  ( 2482): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 2416): getAccountsCursor
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2482): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 2482): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 2482): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Volley  ( 2482): [233] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 2482): [226] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager(  734): Killing 1895:com.android.keychain/1000 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_1895/cgroup.procs: No such file or directory
,V/UserPresentBroadcastReceiver( 1316): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/Ads     ( 2482): Skipping gmscore version check
,I/ActivityManager(  734): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2544 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,D/Finsky  ( 2482): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2482): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 2482): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2482): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/CellBroadcastReceiver( 2544): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2544): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2544): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  734): Killing 1918:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10010/pid_1918/cgroup.procs: No such file or directory
,D/SIP     ( 1212): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  734): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2583 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1355): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Loading module APK com.google.android.play.games
,D/PackageBroadcastService( 1565): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/ActivityManager(  734): Killing 2000:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10012/pid_2000/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleContactsSync( 1565): CP2 sync disabled
,D/AsyncTaskServiceImpl( 1565): Submit a task: h
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 1565): Processing package: com.example.hello
,D/GassUtils( 1565): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/h       ( 1565): Found info for package com.example.hello in db.
,I/ActivityManager(  734): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2609 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,I/UpdateIcingCorporaServi( 1355): UpdateCorporaTask done [took 387 ms] updated apps [took 387 ms] 
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
,I/art     (  734): Explicit concurrent mark sweep GC freed 9993(492KB) AllocSpace objects, 3(52KB) LOS objects, 33% free, 27MB/40MB, paused 859us total 47.779ms
,I/GAv4    ( 2609): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2609):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2609):   adb logcat -s GAv4
,W/GAv4    ( 2609): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/GAV2    ( 1355): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1565): Google Analytics 8.3.01 is starting up.
,W/GAv4    ( 2609): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2609): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 2609): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,I/ActivityManager(  734): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2655 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2026:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/ResourcesManager( 2609): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2609): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  734): failed to open /acct/uid_10014/pid_2026/cgroup.procs: No such file or directory
,W/ResourcesManager( 2655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ContextImpl( 2053): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2053): Thread[GAThread,5,main]: No campaign data found.
,V/JNIHelp ( 2609): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 2609): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2609): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1333): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2482): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/ActivityManager(  734): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2681 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 1966:com.android.providers.calendar/u0a2 (adj 15): empty #17
,I/Icing   ( 1565): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,D/Icing   ( 1565): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1565): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,I/MusicStore( 2681): Database version: 120
,W/ResourcesManager( 2681): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2681): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2681): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 2681): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2681): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@11380cef: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2681): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2681): GMSCore installation verified
,I/ConfigStore( 2681): Config Database version: 1
,I/MediaRouter( 2681): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2681): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2681): Using platform SSLCertificateSocketFactory
,I/art     ( 1333): Explicit concurrent mark sweep GC freed 7040(354KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 875us total 33.353ms
,I/MediaStoreImporter( 2681): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  734): Killing 2082:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10036/pid_2082/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/GCoreFlp( 1316): No location to return for getLastLocation()
,W/FusedLocationProvider( 1333): location=null
D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1565): [KidAccountFixer] No network connection
,D/GCM     ( 1333): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  734): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2732 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 1792): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1792): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 2732): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/JNIHelp ( 1792): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,I/CalendarProvider2( 2732): Created com.android.providers.calendar.CalendarAlarmManager@1cdaece0(com.android.providers.calendar.CalendarProvider2@12a34b99)
,E/SQLiteLog( 2732): (284) automatic index on view_events(_id)
,W/System  ( 1792): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 1792): Installed default security provider GmsCore_OpenSSL
,I/CalendarProvider2( 2732): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2732): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/BluetoothManagerService(  734): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  734): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  734): Message: 2
,D/WifiService(  734): New client listening to asynchronous messages
,D/WifiService(  734): setWifiEnabled: false pid=2272, uid=10277
E/WifiService(  734): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2272): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 2272): 
I/jxcore-log( 2272): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2272): 
,D/AndroidRuntime( 2766): 
D/AndroidRuntime( 2766): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2766): CheckJNI is OFF
,D/AndroidRuntime( 2766): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  734): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  734): Killing 2272:com.example.hello/u0a277 (adj 0): stop com.example.hello
,W/PackageSettings(  734): Skipping PackageSetting{24e1c086 com.test.thalitest/10270} due to missing metadata
,I/WindowState(  734): WIN DEATH: Window{1a74ddb8 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  734): Client connection lost with reason: 4
,W/ActivityManager(  734): Force removing ActivityRecord{c9accbe u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  734): Spurious death for ProcessRecord{d7a93b1 2272:com.example.hello/u0a277}, curProc for 2272: null
,I/ActivityManager(  734): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/Keyboard.Facilitator( 1075): resetDictionaries() : en_US
,I/InputReader(  734): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1316): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1075): run()
,I/Decoder ( 1075): createOrResetDecoder
,I/art     ( 1355): Explicit concurrent mark sweep GC freed 24034(1709KB) AllocSpace objects, 16(2MB) LOS objects, 40% free, 18MB/31MB, paused 602us total 109.720ms
,I/UpdateIcingCorporaServi( 1355): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/VoicemailCleanupService( 1380): Cleaning up data for package: com.example.hello
,D/BackupManagerService(  734): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  734): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  734): removeObsoleteFile: deleting file=214_task.xml
,I/ConfigService( 1333): onCreate
,W/Launcher( 1271): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1e5fe5e new=com.google.android.velvet.VelvetApplication@1e5fe5e
,I/MicrophoneInputStream( 1355): mic_starting gfk@1c14d4d9
,I/AudioFlinger(  185): AudioFlinger's thread 0xb1ab9000 ready to run
,I/HotwordRecognitionRnr( 1355): Starting hotword detection.
,I/MicrophoneInputStream( 1355): mic_started gfk@1c14d4d9
,I/ActivityManager(  734): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2811 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/audio_hw_primary(  185): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  185): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  185): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  185): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  185): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  185): enable_audio_route: apply and update mixer path: audio-record
,I/art     (  734): Explicit concurrent mark sweep GC freed 17321(1067KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.256ms total 198.486ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): run()
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/AndroidRuntime( 2766): Shutting down VM
,I/HotwordWorker( 1355): onReady
,W/ResourcesManager( 1271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GAV2    ( 2416): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  734): Killing 2121:com.google.android.keep/u0a71 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 1355): UpdateCorporaTask done [took 186 ms] updated apps [took 186 ms] 
,W/ContextImpl( 2811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
I/Keyboard.Facilitator.MainLanguageModelLoader( 1075): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loaded File = UserHistory.en_US.dict
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1075): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1075): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1075): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1075): run()
I/StatsUtilsManager( 1075): startPeriodStatsRecorder() : Success
,I/PeriodicStatsRecorder( 1075): shouldRecordStats() = Too Soon
,W/libprocessgroup(  734): failed to open /acct/uid_10071/pid_2121/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 1565): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1565): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1565): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1565): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1333): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1333): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/LocationSettingsChecker( 1565): Removing dialog suppression flag for package com.example.hello
,D/gH_CompatibleDatabase( 1565): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1565): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1565): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1565): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  734): Killing 2147:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,D/gH_CompatibleDatabase( 1565): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1565): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1565): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1565): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1565): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1565): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1565): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1565): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1565): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  734): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2848 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,W/libprocessgroup(  734): failed to open /acct/uid_1000/pid_2147/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1565): App measurement is starting up
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1565): CP2 sync disabled
,I/Icing   ( 1565): doRemovePackageData com.example.hello
,W/BaseAppContext( 1565): Using Auth Proxy for data requests.
,W/OpenGLRenderer( 1271): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1271): Incorrectly called buildLayer on View: adg, destroying layer...
,I/art     ( 1565): Explicit concurrent mark sweep GC freed 33977(2MB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 21MB/36MB, paused 832us total 66.347ms
,D/ConnectivityService(  734): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,I/ActivityManager(  734): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2876 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  734): Killing 2240:com.google.android.youtube/u0a80 (adj 15): empty #17
,W/libprocessgroup(  734): failed to open /acct/uid_10080/pid_2240/cgroup.procs: No such file or directory

```
