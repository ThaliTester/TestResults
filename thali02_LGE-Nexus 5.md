#### Test 503880196b4ec73_thali02_LGE-Nexus 5 Logs


```
--------- beginning of main
I/GAv4    ( 1985): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 1985):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 1985):   adb logcat -s GAv4
W/GAv4    ( 1985): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 1985): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 1985): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 1985): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
--------- beginning of system
I/ActivityManager(  756): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2035 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 1985): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1985): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 2035): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 1985): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 1985): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1985): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  756): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=2062 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  195): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 14.293ms
I/art     (  195): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 244us total 10.684ms
I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 648us total 10.662ms
I/Icing   ( 1616): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1616): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1616): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
D/Finsky  ( 2062): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 2062): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 2062): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2062): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/RecoverySystem(  756): No recovery log file
I/ActivityManager(  756): Start proc com.google.android.dialer for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver: pid=2110 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/BootReceiver(  756): Copying /proc/last_kmsg to DropBox (SYSTEM_LAST_KMSG)
E/SharedPreferencesImpl(  756): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  756): Copying audit failures to DropBox
E/SharedPreferencesImpl(  756): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/BootReceiver(  756): Copied 312 worth of audits to DropBox
I/BootReceiver(  756): Checking for fsck errors
I/BootReceiver(  756): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
E/SharedPreferencesImpl(  756): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
D/Ads     ( 2062): Skipping gmscore version check
D/AndroidRuntime( 2100): 
D/AndroidRuntime( 2100): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  756): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2138 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
D/AndroidRuntime( 2100): CheckJNI is OFF
D/Finsky  ( 2062): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2062): [1] Libraries$2.run: Finished loading 1 libraries.
W/ResourcesManager( 2110): Asset path '/system/framework/com.google.android.dialer.support.jar' does not exist or contains no resources.
D/Finsky  ( 2062): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 2062): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
D/Finsky  ( 2062): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/AndroidRuntime( 2100): Calling main entry com.android.commands.am.Am
I/ActivityManager(  756): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2100): Shutting down VM
I/ActivityManager(  756): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2176 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1411): mic_close gfk@21fccc18
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1411): Hotword detection finished
I/HotwordRecognitionRnr( 1411): Stopping hotword detection.
I/WebViewFactory( 2176): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2176): Time to load native libraries: 1 ms (timestamps 3700-3701)
I/LibraryLoader( 2176): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2176): Binding Chromium to main looper Looper (main, tid 1) {18dad77c}
I/LibraryLoader( 2176): Expected native library version number "",actual native library version number ""
I/chromium( 2176): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/ConnectivityService(  756): Got NetworkFactory Messenger for Telephony
,D/TelephonyProvider( 1212): dbh.onOpen: ok, queried table=siminfo
D/TelephonyProvider( 1212): dbh.onOpen: ok, queried table=carriers
,I/BrowserStartupController( 2176): Initializing chromium process, singleProcess=true
,W/art     ( 2176): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2176): ApplicationContext is null in ApplicationStatus
,W/chromium( 2176): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 2176): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2176): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2176): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2176): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/GpsLocationProvider(  756): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
,D/GpsLocationProvider(  756): SIM MCC/MNC is still not available
,D/DcSwitchState( 1212): [DcSwitchState-0] DcSwitchState constructor E
D/DcSwitchState( 1212): [DcSwitchState-0] DcSwitchState constructor X
,D/DctController( 1212): [DctController] DctController(phones): Connect success: 0
,W/ResourcesManager( 1212): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  756): Message: 20
,D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f2f44c:true
D/BluetoothAdapter( 2176): 818272294: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  756): Message: 20
D/BluetoothManagerService(  756): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32c7b913:true
,W/art     ( 2176): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  756): Explicit concurrent mark sweep GC freed 23085(1247KB) AllocSpace objects, 19(1795KB) LOS objects, 33% free, 27MB/40MB, paused 829us total 56.699ms
,D/BluetoothManagerService(  756): Message: 30
,W/AwContents( 2176): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2176): CordovaWebView is running on device made by: LGE
,D/ConnectivityService(  756): Got NetworkFactory Messenger for WIFI
D/WIFI    (  756): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
,W/art     ( 2176): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2176): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  756): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=2242 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2242): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/TelephonyNetworkFactory( 1212): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 0
D/TelephonyNetworkFactory( 1212): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/DctController( 1212): [DctController] EVENT_PHONE1_RADIO_OFF.
,D/TelephonyDebugService( 1212): TelephonyDebugService()
,D/WifiService(  756): New client listening to asynchronous messages
I/CalendarProvider2( 2242): Created com.android.providers.calendar.CalendarAlarmManager@2f397e6f(com.android.providers.calendar.CalendarProvider2@18dad77c)
,D/DctController( 1212): [DctController] DataStateReceiver: phoneId= 0
D/DctController( 1212): [DctController] DataStateReceiver: ignore invalid subId=-1
,D/SurfaceFlinger(  172): shader cache generated - 24 shaders in 150.859634 ms
,D/OpenGLRenderer( 2176): Render dirty regions requested: true
,D/Atlas   ( 2176): Validating map...
,I/ActivityManager(  756): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2273 uid=10012 gids={50012, 9997} abi=armeabi-v7a
,D/GpsLocationProvider(  756): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
,W/chromium( 2176): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/GpsLocationProvider(  756): SIM MCC/MNC is still not available
,I/MmsService( 1212): mReceiver action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
,D/GpsLocationProvider(  756): received SIM realted action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
I/Telephony( 1212): : SUBINFO_RECORD_UPDATED : 4.
I/MmsService( 1212): MmsConfigManager.loadInBackground(): mcc/mnc: 0/0
E/MmsService( 1212): MmsConfigManager.load -- empty getActiveSubInfoList
,E/PhoneInterfaceManager( 1212): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/GpsLocationProvider(  756): SIM MCC/MNC is still not available
,I/OpenGLRenderer( 2176): Initialized EGL, version 1.4
D/OpenGLRenderer( 2176): Enabling debug mode 0
I/Telephony( 1212): PstnIncomingCallNotifier: Registering: Handler (com.android.internal.telephony.gsm.GSMPhone) {2478180e}
V/OneTimeInitializerReceiver( 2273): OneTimeInitializerReceiver.onReceive
V/OneTimeService( 2273): OneTimeService.onHandleIntent
,I/Keyboard.Facilitator( 1060): onFinishInput()
,I/ActivityManager(  756): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2301 uid=10014 gids={50014, 9997, 1028, 3003} abi=armeabi-v7a
,I/ActivityManager(  756): Displayed com.example.hello/.MainActivity: +731ms (total +12s439ms)
,W/BindingManager( 2176): Cannot call determinedVisibility() - never saw a connection for the pid: 2176
I/chromium( 2176): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2176): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2176): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/RlzPingService( 1460): Setting next ping for 1448911238272
,I/ActivityManager(  756): Killing 1680:com.android.settings/1000 (adj 15): empty #17
,D/jxcore_app_log( 2176): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2176): jxcore cordova android initializing
,D/WifiService(  756): Client connection lost with reason: 4
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_1680/cgroup.procs: No such file or directory
,W/jxcore-log( 2176): Initializing JXcore engine
W/jxcore-log( 2176): JXcore engine is ready
I/Velvet.VelvetFactory( 1411): refreshing internal icing corpora
I/ContactAccountLoggerTas( 1411): canRun() : Opted Out
,D/MtpService(  907): updating state; isCurrentUser=true, mMtpLocked=false
W/jxcore-log( 2176): Starting JXcore engine
,I/Velvet.VelvetFactory( 1411): refreshing search history.
,W/GAV2    ( 1411): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 1411): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 1411): canRun() : Opted Out
I/ContactAccountLoggerTas( 1411): canRun() : Opted Out
I/ContactAccountLoggerTas( 1411): canRun() : Opted Out
I/ContactAccountLoggerTas( 1411): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1411): canRun() : Opted Out
,I/UpdateIcingCorporaServi( 1411): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,E/SQLiteLog(  907): (283) recovered 282 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,W/m.example.hello( 2176): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6519]" dev="sockfs" ino=6519 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2176): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 2176): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9635]" dev="sockfs" ino=9635 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2176): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[13024]" dev="sockfs" ino=13024 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/UpdateIcingCorporaServi( 1411): UpdateCorporaTask done [took 23 ms] updated apps [took 23 ms] 
,I/ActivityManager(  756): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.alerts.AlertReceiver: pid=2328 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WebViewFactory( 1411): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/jxcore-log( 2176): Platform android
W/jxcore-log( 2176): 
W/jxcore-log( 2176): Process ARCH arm
W/jxcore-log( 2176): 
,I/LibraryLoader( 1411): Time to load native libraries: 2 ms (timestamps 4640-4642)
I/LibraryLoader( 1411): Expected native library version number "",actual native library version number ""
,W/art     ( 1411): Attempt to remove local handle scope entry from IRT, ignoring
,I/jxcore-log( 2176): JXcore Cordova bridge is ready!
I/jxcore-log( 2176): 
,W/jxcore-log( 2176): JXcore engine is started
,W/MediaScanner(  907): Error opening directory '/oem/media/', skipping: No such file or directory.
,E/jxcore-log( 2176): >> LGE-Nexus 5
E/jxcore-log( 2176): 
,I/jxcore-log( 2176): Total memory 1946181632
I/jxcore-log( 2176): 
,I/jxcore-log( 2176): Free memory 448061440
I/jxcore-log( 2176): 
,I/jxcore-log( 2176): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2176): 
,I/jxcore-log( 2176): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2176): 
E/SQLiteLog( 2328): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/jxcore-log( 2176): userPath [ 'www' ]
I/jxcore-log( 2176): 
,I/jxcore-log( 2176): Size 1080 1776
I/jxcore-log( 2176): 
,I/jxcore-log( 2176): Screen Brightness 82
I/jxcore-log( 2176): 
,E/jxcore-log( 2176): Dummy Error Log.
E/jxcore-log( 2176): 
,W/NetworkUtils( 1411): OkHttp exception
,I/ContactAccountLoggerTas( 1411): canRun() : Opted Out
,I/iu.UploadsManager( 1616): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,V/MediaScanner(  907): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@39019af1
,V/MediaScanner(  907): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@39019af1
,I/iu.UploadsManager( 1616): End new media; added: 0, uploading: 0, time: 27 ms
,I/ActivityManager(  756): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2366 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,I/AnalyticsLogBase( 2328): PlayLogger.onLoggerConnected
,E/UpdateRequestReceiver( 2366): ignoring update request
,E/UpdateRequestReceiver( 2366): ignoring update request
,E/UpdateRequestReceiver( 2366): ignoring update request
,E/UpdateRequestReceiver( 2366): ignoring update request
,E/UpdateRequestReceiver( 2366): ignoring update request
,E/UpdateRequestReceiver( 2366): ignoring update request
W/BroadcastQueue(  756): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.gallery3d/com.android.camera.DisableCameraReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/GoogleHttpClient( 1370): GMS http client unavailable, use old client
,I/ActivityManager(  756): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=2404 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 2242): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 2242): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     (  756): Explicit concurrent mark sweep GC freed 9632(460KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 1.386ms total 49.401ms
,I/jxcore-log( 2176): getBuffer is called!!!!
I/jxcore-log( 2176): 
,I/art     ( 1370): Explicit concurrent mark sweep GC freed 12218(669KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 19MB/32MB, paused 812us total 22.575ms
,I/ActivityManager(  756): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2436 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 1711:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10061/pid_1711/cgroup.procs: No such file or directory
,W/ResourcesManager( 2436): Asset path '/system/framework/serviceitems.jar' does not exist or contains no resources.
W/ResourcesManager( 2436): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  756): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2454 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 1820:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,I/art     (  195): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 217us total 8.847ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 8.100ms
,I/art     (  195): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 170us total 8.219ms
,W/libprocessgroup(  756): failed to open /acct/uid_10045/pid_1820/cgroup.procs: No such file or directory
,D/QcrilMsgTunnelAutoboot( 2454): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
,D/QcrilMsgTunnelService( 2454): onCreate method
,D/QcrilMsgTunnelIfaceManager( 2454): : Instantiated
,V/QcrilMsgTunnelSocket( 2454): Starting QcRil Sender & Receiver threads
,D/QcrilMsgTunnelIfaceManager( 2454):  Registered for UNSOL OEM HOOK Responses to deliver external apps
,I/QcrilMsgTunnelSocket( 2454): Connected to 'qmux_radio/rild_oem0' socket
,D/FileApkUtils( 1616): Spent 26ms computing apk sha1.
,D/FileApkUtils( 1616): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1616): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-2707d05c501ef4bf821813f1789ad0e56682eb5a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 1616): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1616): Keeping up-to-date module: module-2707d05c501ef4bf821813f1789ad0e56682eb5a
D/GmsModuleFndr( 1616): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1616): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 1616): Beginning module configuration check
,D/ChimeraCfgMgr( 1616): Module APKs unchanged, check complete
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 1616): Checkin interval check for package: unspecified last checkin: 1448260896395 min interval config: 0 actual interval: 45543442
,D/GCM     ( 1616): COMPAT: Multi user ser=0 current=0
,I/CheckinService( 1616): Disabling old GoogleServicesFramework version
,D/GCM     ( 1370): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1616): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1285): DispatchingService.onCreate()
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/CheckinService( 1616): Checking schedule, now: 1448306439891 next: 1448303063366
I/CheckinService( 1616): active receiver: enabled
,I/ActivityManager(  756): Delay finish: com.google.android.gms/.kids.chimera.SystemEventReceiverProxy
D/SystemUpdateService( 1616): onCreate
,D/SystemUpdateService( 1616): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1616): active receiver: enabled
,V/AuthZen ( 1616): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 1616): Handling event: android.intent.action.BOOT_COMPLETED
,W/BaseAppContext( 1616): Using Auth Proxy for data requests.
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1285): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/AuthZen ( 1616): Fetching signing key...
,I/art     ( 1616): Explicit concurrent mark sweep GC freed 39434(2MB) AllocSpace objects, 33(528KB) LOS objects, 39% free, 21MB/35MB, paused 816us total 56.514ms
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/AuthZen ( 1616): Signing key fetched successfully!
,I/ActivityManager(  756): Resuming delayed broadcast
,W/BaseAppContext( 1616): Using Auth Proxy for data requests.
I/art     ( 1370): Explicit concurrent mark sweep GC freed 6107(332KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 19MB/32MB, paused 635us total 28.674ms
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUpdateService( 1616): showing system update notification
,I/art     ( 1285): Explicit concurrent mark sweep GC freed 16694(1033KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 19MB/32MB, paused 1.485ms total 34.594ms
,W/Kids    ( 1616): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 1616): [KidAccountFixer] No network connection
D/a       ( 1616): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 1616): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1616): Clearing transaction cache
,I/ValidateNoPeople(  756): skipping global notification
,V/SystemUpdateService( 1616): retry (wakeup: false) in 3599845 ms
,W/ResourcesManager(  897): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  897): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GCoreFlp( 1285): No location to return for getLastLocation()
,W/FusedLocationProvider( 1616): location=null
,D/SystemUpdateService( 1616): onDestroy
,W/Auth    ( 1370): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1616): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,W/GCoreFlp( 1285): No location to return for getLastLocation()
,W/FusedLocationProvider( 1616): location=null
,I/GCoreUlr( 1285): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1285): Unbound from all location providers
,I/GCoreUlr( 1285): DispatchingService.onDestroy()
I/GCoreUlr( 1285): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1285): Unbound from all location providers
,D/PersistentNotificationBroadcastReceiver( 1370): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  756): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2517 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 2517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 2517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 2517): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 2517): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 2549): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads1650623349.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads1650623349.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 2549): dex2oat took 47.532ms (threads: 4)
,W/InstanceID/Rpc( 2517): Found 10008
,V/Babel   ( 1845): babel boot account: thalitester@gmail.com
,I/ActivityManager(  756): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2613 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,E/SQLiteLog( 1845): (284) automatic index on conversation_participants_view(conversation_id)
,I/art     (  756): Explicit concurrent mark sweep GC freed 13248(663KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/40MB, paused 1.039ms total 57.853ms
,W/VideoCapabilities( 1845): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 1845): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 1845): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 1845): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 1845): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  756): Killing 1223:com.android.printspooler/u0a72 (adj 15): empty #17
,I/FitnessApp( 2613): Initializers took 0 milliseconds
,I/ActivityManager(  756): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2633 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  756): Killing 1915:com.android.musicfx/u0a15 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10072/pid_1223/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_10015/pid_1915/cgroup.procs: No such file or directory
,I/GAv4    ( 2633): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2633):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2633):   adb logcat -s GAv4
,W/GAv4    ( 2633): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2633): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2633): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  756): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2661 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  756): Killing 1985:com.google.android.apps.docs/u0a40 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10040/pid_1985/cgroup.procs: No such file or directory
,I/Gmail   ( 2661): getAccountsCursor
,D/ActivityThread( 2661): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  756): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2684 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GAV2    ( 2661): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  756): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 2661): Observing account changes for notifications
,I/Gmail   ( 2661): getAccountsCursor
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemBroadcastReceiver( 1060): Boot has been completed
I/SystemBroadcastReceiver( 1060): toggleAppIcon() : FLAG_SYSTEM = true
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 2684): EasService.onCreate
,I/Exchange( 2684): RestartPingTask
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Volley  ( 2062): [171] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2062): [178] DiskBasedCache.clear: Cache cleared.
,V/UserPresentBroadcastReceiver( 1285): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/Exchange( 2684): RestartPingsTask did not start any pings.
,I/Exchange( 2684): PSS stopIfIdle
I/Exchange( 2684): PSS has no active accounts; stopping service.
,I/Exchange( 2684): onDestroy
,I/Exchange( 2684): EasService.onCreate
,E/SQLiteLog( 2661): (283) recovered 93 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager(  756): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2735 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/Exchange( 2684): RestartPingTask
,I/Gmail   ( 2661): notifyAccountChanged
,I/Gmail   ( 2661): getAccountsCursor
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 2661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  756): Killing 2035:com.google.android.apps.plus/u0a67 (adj 15): empty #17
,I/Gmail   ( 2661): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2661): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Exchange( 2684): RestartPingsTask did not start any pings.
I/Exchange( 2684): PSS stopIfIdle
I/Exchange( 2684): PSS has no active accounts; stopping service.
,W/libprocessgroup(  756): failed to open /acct/uid_10067/pid_2035/cgroup.procs: No such file or directory
,I/Exchange( 2684): onDestroy
,I/ActivityManager(  756): Killing 2138:com.android.keychain/1000 (adj 15): empty #17
,D/CellBroadcastReceiver( 2735): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
,D/CellBroadcastReceiver( 2735): Intent ACTION_SERVICE_STATE_CHANGED
D/CellBroadcastReceiver( 2735): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  756): Killing 2110:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10010/pid_2110/cgroup.procs: No such file or directory
,W/libprocessgroup(  756): failed to open /acct/uid_1000/pid_2138/cgroup.procs: No such file or directory
,I/Gmail   ( 2661): getAccountsCursor
,V/GLSActivity( 1370): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SIP     ( 1212): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,I/ActivityManager(  756): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2760 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 2760): Database version: 120
,W/ResourcesManager( 2760): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 2760): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2760): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 2760): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2760): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2cc20aca: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2760): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2760): GMSCore installation verified
,I/ConfigStore( 2760): Config Database version: 1
,I/MediaRouter( 2760): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/GHttpClientFactory( 2760): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  756): Explicit concurrent mark sweep GC freed 8613(423KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/40MB, paused 1.079ms total 64.225ms
,I/GoogleURLConnFactory( 2760): Using platform SSLCertificateSocketFactory
,W/GCoreFlp( 1285): No location to return for getLastLocation()
,W/FusedLocationProvider( 1370): location=null
,I/art     ( 1370): Explicit concurrent mark sweep GC freed 7660(409KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 879us total 25.196ms
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 1616): [KidAccountFixer] No network connection
,D/GCM     ( 1370): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MediaStoreImporter( 2760): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  756): Killing 2273:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10012/pid_2273/cgroup.procs: No such file or directory
,E/SQLiteLog( 2242): (284) automatic index on view_events(_id)
,W/ResourcesManager( 1845): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1845): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 1845): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 1845): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1845): Installed default security provider GmsCore_OpenSSL
,I/GAv4-SVC( 1616): Google Analytics 8.3.01 is starting up.
,I/GAV2    ( 1411): Thread[GAThread,5,main]: No campaign data found.
,D/BluetoothManagerService(  756): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  756): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  756): Message: 2
,D/WifiService(  756): New client listening to asynchronous messages
,D/WifiService(  756): setWifiEnabled: false pid=2176, uid=10277
E/WifiService(  756): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2176): ****TEST TOOK:  5025  ms ****
I/jxcore-log( 2176): 
I/jxcore-log( 2176): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2176): 
,W/ContextImpl( 2328): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GAV2    ( 2328): Thread[GAThread,5,main]: No campaign data found.
,D/AndroidRuntime( 2848): 
D/AndroidRuntime( 2848): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2848): CheckJNI is OFF
,D/AndroidRuntime( 2848): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  756): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
I/ActivityManager(  756): Killing 2176:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/WindowState(  756): WIN DEATH: Window{21212db0 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  756): Client connection lost with reason: 4
,W/PackageSettings(  756): Skipping PackageSetting{774d84d com.test.thalitest/10270} due to missing metadata
,W/ActivityManager(  756): Force removing ActivityRecord{246d5d42 u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  756): Spurious death for ProcessRecord{3de215e0 2176:com.example.hello/u0a277}, curProc for 2176: null
,I/ActivityManager(  756): Force stopping com.example.hello appid=10277 user=0: pkg removed
,I/Keyboard.Facilitator( 1060): resetDictionaries() : en_US
,I/InputReader(  756): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1060): run()
,D/VoicemailCleanupService( 1341): Cleaning up data for package: com.example.hello
I/Decoder ( 1060): createOrResetDecoder
,W/GeofencerStateMachine( 1285): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager(  756): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2870 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,D/BackupManagerService(  756): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  756): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  756): removeObsoleteFile: deleting file=214_task.xml
,I/ConfigService( 1370): onCreate
,I/art     (  756): Explicit concurrent mark sweep GC freed 11140(794KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 3.759ms total 133.083ms
,W/InputMethodManagerService(  756): Got RemoteException sending setActive(false) notification to pid 2176 uid 10277
,I/Keyboard.Facilitator( 1060): onFinishInput()
,I/HotwordRecognitionRnr( 1411): Starting hotword detection.
,I/MicrophoneInputStream( 1411): mic_starting gfk@35f462f0
,I/UpdateIcingCorporaServi( 1411): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/AudioFlinger(  183): AudioFlinger's thread 0xb1dbe000 ready to run
,W/Launcher( 1247): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@28bdb805 new=com.google.android.velvet.VelvetApplication@28bdb805
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1060): run()
I/MicrophoneInputStream( 1411): mic_started gfk@35f462f0
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,I/ActivityManager(  756): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2911 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1060): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loading LM = contacts
,D/AndroidRuntime( 2848): Shutting down VM
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1060): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1060): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1060): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1060): run()
I/StatsUtilsManager( 1060): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1060): shouldRecordStats() = Too Soon
,I/UpdateIcingCorporaServi( 1411): UpdateCorporaTask done [took 99 ms] updated apps [took 99 ms] 
,W/ContextImpl( 2911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,D/PackageBroadcastService( 1616): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1616): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1616): Module APK com.google.android.play.games already loaded
,I/HotwordWorker( 1411): onReady
,D/ChimeraCfgMgr( 1616): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1616): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1616): Removing dialog suppression flag for package com.example.hello
,W/ResourcesManager( 1247): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/NetworkScheduler.SchedulerReceiver( 1370): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1370): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/ActivityManager(  756): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2940 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/ResourcesManager( 1247): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/gH_CompatibleDatabase( 1616): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 1616): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1616): 0 metrics were deleted when clearing package com.example.hello.
,D/gH_CompatibleDatabase( 1616): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1616): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1616): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1616): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1616): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1616): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1616): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1616): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1616): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1616): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  756): Killing 2301:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10014/pid_2301/cgroup.procs: No such file or directory
,I/ActivityManager(  756): Killing 2366:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  756): failed to open /acct/uid_10036/pid_2366/cgroup.procs: No such file or directory
,I/GMPM-SVC( 1616): App measurement is starting up
,W/BaseAppContext( 1616): Using Auth Proxy for data requests.
,I/PeopleContactsSync( 1616): CP2 sync disabled
I/Icing   ( 1616): doRemovePackageData com.example.hello
,W/BaseAppContext( 1616): Using Auth Proxy for data requests.
,D/ConnectivityService(  756): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/SQLiteLog( 1616): (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
E/GMPM-SVC( 1616): Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
,E/SharedPreferencesImpl( 1616): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
,W/FileUtils( 1616): Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,I/art     ( 1616): Explicit concurrent mark sweep GC freed 22355(1596KB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 21MB/36MB, paused 884us total 40.876ms
,W/DriveInitializer( 1616): Awaiting to be initialized
,W/OpenGLRenderer( 1247): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1247): Incorrectly called buildLayer on View: adg, destroying layer...
W/DriveInitializer( 1616): Background init thread started
,E/SQLiteLog( 1616): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock154] disk I/O error
,E/DocListDatabase( 1616): Failed to delete from ContentFileDeletionLock154 table
E/DocListDatabase( 1616): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 1616): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 1616): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 1616): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 1616): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 1616): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/DocListDatabase( 1616): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/DocListDatabase( 1616): 	at com.google.android.gms.drive.s.run(SourceFile:62)
,W/DriveInitializer( 1616): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 1616): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 1616): Process: com.google.android.gms, PID: 1616
E/AndroidRuntime( 1616): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1616): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1616): 	at com.google.android.gms.drive.database.k.a(SourceFile:329)
E/AndroidRuntime( 1616): 	at com.google.android.gms.drive.database.f.h(SourceFile:1062)
E/AndroidRuntime( 1616): 	at com.google.android.gms.drive.s.run(SourceFile:62)
,E/SQLiteLog( 1616): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 1616): disk I/O error (code 3850)
E/DriveAsyncService( 1616): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1616): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1616): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1616): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1616): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1616): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1616): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1616): 	at java.lang.Thread.run(Thread.java:818)
,E/qdhwcomposer(  172): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  172): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  172): MdpData failed to play
E/qdoverlay(  172): == Dump MdpData start ==
E/qdoverlay(  172): == Dump OvFD fd=75 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  172): mOvData msmfb_overlay_data id=64
E/qdoverlay(  172): data msmfb_data offset=0 memid=46 id=0 flags=0x0 priv=0
E/qdoverlay(  172): == Dump MdpData end ==
E/qdhwcomposer(  172): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  172): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  172): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  172): hwc_set_primary: display commit fail!
,W/ResourcesManager(  756): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager(  756): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/OpenGLRenderer(  756): Render dirty regions requested: true
,D/Atlas   (  756): Validating map...
,E/qdhwcomposer(  172): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  172): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
,E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  172): MdpData failed to play
E/qdoverlay(  172): == Dump MdpData start ==
E/qdoverlay(  172): == Dump OvFD fd=75 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  172): mOvData msmfb_overlay_data id=64
E/qdoverlay(  172): data msmfb_data offset=0 memid=46 id=0 flags=0x0 priv=0
E/qdoverlay(  172): == Dump MdpData end ==
E/qdhwcomposer(  172): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  172): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  172): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  172): hwc_set_primary: display commit fail!
,I/Adreno-EGL(  756): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  756): Initialized EGL, version 1.4
,D/OpenGLRenderer(  756): Enabling debug mode 0
,E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl failed to setOverlay, restoring last known good ov info
,E/qdoverlay(  172): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  172): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
E/qdoverlay(  172): src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
,E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): Ctrl commit failed set overlay
E/qdhwcomposer(  172): configureLowRes: commit failed for low res panel
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl failed to setOverlay, restoring last known good ov info
E/qdoverlay(  172): == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
E/qdoverlay(  172): src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=1920
E/qdoverlay(  172): == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
E/qdoverlay(  172): src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
E/qdoverlay(  172): src_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  172): dst_rect mdp_rect x=0 y=0 w=1080 h=75
E/qdoverlay(  172): Ctrl commit failed set overlay
E/qdhwcomposer(  172): configure: commit fails
E/qdoverlay(  172): Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
E/qdoverlay(  172): MdpCtrl close error in unset

```
