#### Test 50388019aa1a16d_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2041): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2041): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
V/JNIHelp ( 2041): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/ActivityThread( 2041): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 2041): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b56ffa4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2041): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 2041): GMSCore installation verified
I/ConfigStore( 2041): Config Database version: 1
I/MediaRouter( 2041): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 2041): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 2041): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 2041): type=WIFI subType= reason=null isConnected=true
I/GHttpClientFactory( 2041): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 2041): Using platform SSLCertificateSocketFactory
I/iu.SyncManager( 1699): SYNC; picasa accounts
D/NetworkLogImpl( 1699): Loaded NetworkSpeedPredictor
I/iu.Environment( 1699): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/art     ( 1356): Explicit concurrent mark sweep GC freed 14255(916KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 19MB/32MB, paused 969us total 64.283ms
W/SQLiteConnectionPool( 1356): A SQLiteConnection object for database '/data/data/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 1356): A SQLiteConnection object for database '/data/data/com.google.android.gsf/databases/gservices.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/iu.UploadsManager( 1699): num queued entries: 0
I/iu.UploadsManager( 1699): num updated entries: 0
I/iu.SyncManager( 1699): NEXT; no task
D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/SystemUpdateService( 1699): receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
D/SystemUpdateService( 1699): onCreate
D/SystemUpdateService( 1699): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  760): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=2117 uid=10054 gids={50054, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SystemUpdateService( 1699): active receiver: enabled
V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 2117): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SystemUpdateService( 1699): showing system update notification
I/ValidateNoPeople(  760): skipping global notification
V/SystemUpdateService( 1699): retry (wakeup: false) in 3599871 ms
W/ResourcesManager(  900): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(  900): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/SystemUpdateService( 1699): onDestroy
I/Babel_SMS( 2117): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 2117): MmsConfig.loadMmsSettings
I/Babel_SMS( 2117): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2117): MmsConfig.loadFromDatabase
E/Babel_SMS( 2117): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 2117): MmsConfig.loadFromResources
E/Babel_SMS( 2117): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 2117): MmsConfig.loadMmsSettings: mUserAgent=Nexus5, mUaProfUrl=http://gsm.lge.com/html/gsm/Nexus5-M3.xml
I/Babel_SMS( 2117): ApnsOta: OTA version -1
I/Babel   ( 2117): deleted: false for 0
,W/Settings( 2117): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 2117): startup - clean
I/ActivityManager(  760): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=2168 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 2164): 
D/AndroidRuntime( 2164): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2164): CheckJNI is OFF
W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
W/ResourcesManager( 2168): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/VideoCapabilities( 2117): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 2117): onServiceConnected
W/Babel   ( 2117): Attempted to change video mute state without an active call.
D/AndroidRuntime( 2164): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/Babel   ( 2117): connection state changed from UNKNOWN to CONNECTED
D/AndroidRuntime( 2164): Shutting down VM
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2201 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 329us total 26.223ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.635ms total 46.993ms
I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 241us total 21.574ms
I/MicrophoneInputStream( 1437): mic_close gfk@e85be01
,D/audio_hw_primary(  185): disable_audio_route: reset and update mixer path: audio-record
,D/audio_hw_primary(  185): disable_snd_device: snd_device(55: voice-rec-mic)
,I/HotwordRecognitionRnr( 1437): Stopping hotword detection.
I/HotwordRecognitionRnr( 1437): Hotword detection finished
,I/WebViewFactory( 2201): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 2201): Time to load native libraries: 3 ms (timestamps 1583-1586)
I/LibraryLoader( 2201): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 2201): Binding Chromium to main looper Looper (main, tid 1) {336d45c6}
I/LibraryLoader( 2201): Expected native library version number "",actual native library version number ""
,I/chromium( 2201): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 2201): Initializing chromium process, singleProcess=true
,W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 2201): ApplicationContext is null in ApplicationStatus
,W/chromium( 2201): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 2201): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2201): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2201): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@280f1049:true
,D/BluetoothAdapter( 2201): 23917017: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2201): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2201): CordovaWebView is running on device made by: LGE
,W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2201): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2201): Render dirty regions requested: true
,D/Atlas   ( 2201): Validating map...
,I/ActivityManager(  760): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=2249 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/chromium( 2201): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 2201): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2201): Enabling debug mode 0
,I/art     (  760): Explicit concurrent mark sweep GC freed 13905(641KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 1.044ms total 109.732ms
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +1s85ms (total +19s750ms)
I/Keyboard.Facilitator( 1096): onFinishInput()
,W/BindingManager( 2201): Cannot call determinedVisibility() - never saw a connection for the pid: 2201
,I/chromium( 2201): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 2201): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 2201): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/SQLiteLog( 2249): (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  760): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=2280 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/jxcore_app_log( 2201): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
D/JX-Cordova( 2201): jxcore cordova android initializing
,W/ResourcesManager( 2280): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/jxcore-log( 2201): Initializing JXcore engine
W/jxcore-log( 2201): JXcore engine is ready
,W/jxcore-log( 2201): Starting JXcore engine
I/AnalyticsLogBase( 2249): PlayLogger.onLoggerConnected
,I/ActivityManager(  760): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=2299 uid=10076 gids={50076, 9997} abi=armeabi-v7a
,W/m.example.hello( 2201): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8567]" dev="sockfs" ino=8567 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2201): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/m.example.hello( 2201): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9500]" dev="sockfs" ino=9500 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,W/m.example.hello( 2201): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[13262]" dev="sockfs" ino=13262 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,I/CalendarProvider2( 2280): Created com.android.providers.calendar.CalendarAlarmManager@15b6efa1(com.android.providers.calendar.CalendarProvider2@336d45c6)
,D/TimeService( 2299): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448020192975
D/        ( 2299): TimeServiceNative: User Time to be set is 1448020192975
D/QC-time-services( 2299): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 2299): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 2299): Lib:time_genoff_operation: pargs->ts_val = 1448020192975
,D/QC-time-services(  199): Daemon: Connection accepted:time_genoff
D/QC-time-services( 2299): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  199): Daemon:Received base = 2, unit = 1, operation = 0,value = 1448020192975
D/QC-time-services(  199): Daemon:genoff_opr: Base = 2, val = 1448020192975, operation = 0
,D/QC-time-services(  199): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/24/70 17:40:45
D/QC-time-services(  199): Daemon:Value read from RTC seconds = 7148445000
D/QC-time-services(  199): Daemon:new time 1448020192975 
D/QC-time-services(  199): Daemon: delta 1440871747975 genoff 1440871747975 
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871747975 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_2
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Updating the TOD offset
D/QC-time-services(  199): Daemon:genoff_persistent_update: Writing genoff = 1440871747975 to memory
D/QC-time-services(  199): Daemon:Opening File: /data/system/time/ats_1
D/QC-time-services(  199): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  199): Daemon:Update to modem bit set
D/QC-time-services(  199): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  199): Daemon: Base = 2, Value being sent to MODEM = 1132055392975
,E/QC-time-services( 2299): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,D/QC-time-services(  199): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,D/QC-time-services(  199): Daemon: Time-services: Waiting to acceptconnection
,W/jxcore-log( 2201): Platform android
W/jxcore-log( 2201): 
W/jxcore-log( 2201): Process ARCH arm
W/jxcore-log( 2201): 
,I/CheckinService( 1699): Checkin interval check for package: unspecified last checkin: 1448007304244 min interval config: 0 actual interval: 12888831
,I/jxcore-log( 2201): JXcore Cordova bridge is ready!
I/jxcore-log( 2201): 
,W/jxcore-log( 2201): JXcore engine is started
,E/jxcore-log( 2201): >> LGE-Nexus 5
E/jxcore-log( 2201): 
,I/jxcore-log( 2201): Total memory 1946181632
I/jxcore-log( 2201): 
I/jxcore-log( 2201): Free memory 469454848
I/jxcore-log( 2201): 
I/jxcore-log( 2201): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2201): 
I/jxcore-log( 2201): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2201): 
,I/jxcore-log( 2201): userPath [ 'www' ]
I/jxcore-log( 2201): 
,I/jxcore-log( 2201): Size 1080 1776
I/jxcore-log( 2201): 
,I/jxcore-log( 2201): Screen Brightness 82
I/jxcore-log( 2201): 
E/jxcore-log( 2201): Dummy Error Log.
E/jxcore-log( 2201): 
,I/ActivityManager(  760): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2322 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
,I/GAv4    ( 2322): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 2322):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 2322):   adb logcat -s GAv4
,W/GAv4    ( 2322): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2322): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 2322): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/MDM     ( 1667): [164] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1356): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 1699): Restart initialization of location
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1699): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/BluetoothManagerService(  760): Auto-enabling Bluetooth.
,D/BluetoothManagerService(  760): Message: 1
D/BluetoothManagerService(  760): MESSAGE_ENABLE: mBluetooth = null
,I/ActivityManager(  760): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=2357 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/jxcore-log( 2201): getBuffer is called!!!!
I/jxcore-log( 2201): 
,W/GCoreFlp( 1667): No location to return for getLastLocation()
W/FusedLocationProvider( 1356): location=null
,I/ActivityManager(  760): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=2372 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,W/ResourcesManager( 2357): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,I/RecoverySystem(  760): No recovery log file
,I/ActivityManager(  760): Start proc com.google.android.dialer for broadcast com.google.android.dialer/com.android.dialer.calllog.CallLogReceiver: pid=2407 uid=10010 gids={50010, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/BootReceiver(  760): Copying /proc/last_kmsg to DropBox (SYSTEM_LAST_KMSG)
,E/SharedPreferencesImpl(  760): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/BootReceiver(  760): Copying audit failures to DropBox
E/SharedPreferencesImpl(  760): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,I/CalendarProvider2( 2280): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 2280): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/BootReceiver(  760): Copied 508 worth of audits to DropBox
,I/BootReceiver(  760): Checking for fsck errors
,I/BootReceiver(  760): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  760): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/AdapterServiceConfig( 2357): Adding HeadsetService
D/AdapterServiceConfig( 2357): Adding A2dpService
D/AdapterServiceConfig( 2357): Adding HidService
D/AdapterServiceConfig( 2357): Adding HealthService
D/AdapterServiceConfig( 2357): Adding PanService
D/AdapterServiceConfig( 2357): Adding GattService
D/AdapterServiceConfig( 2357): Adding BluetoothMapService
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@208cc47d:true
,D/BluetoothAdapterState( 2357): make
,I/bluedroid( 2357): init
I/BluetoothAdapterState( 2357): Entering OffState
,I/bte_conf( 2357): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 2357): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 2357): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 2357): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
I/bluedroid( 2357): get_profile_interface socket
W/ResourcesManager( 2407): Asset path '/system/framework/com.google.android.dialer.support.jar' does not exist or contains no resources.
I/bluedroid( 2357): get_profile_interface map_client
,I/GKI_LINUX( 2357): gki_task_entry task_id=1 [BTIF] starting
D/BluetoothAdapterProperties( 2357): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothAdapterProperties( 2357): Name is: Nexus 5
D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,I/bluedroid( 2357): config_hci_snoop_log
,D/BluetoothManagerService(  760): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceUp() to 9 receivers.
,D/BluetoothAdapterState( 2357): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,D/BluetoothAdapterProperties( 2357): Setting state to 11
I/BluetoothAdapterState( 2357): Bluetooth adapter state changed: 10-> 11
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothBondStateMachine( 2357): make
,I/BluetoothBondStateMachine( 2357): StableState(): Entering Off State
,D/BluetoothHeadset(  760): Proxy object connected
,D/BluetoothHeadset( 1223): Proxy object connected
,D/HeadsetService( 2357): Received start request. Starting profile...
D/BluetoothHeadset( 1223): Proxy object connected
I/BluetoothHeadsetServiceJni( 2357): classInitNative: succeeds
,D/HeadsetStateMachine( 2357): make
,D/HeadsetStateMachine( 2357): max_hf_connections = 1
I/bluedroid( 2357): get_profile_interface handsfree
,D/HeadsetStateMachine( 2357): Enter Disconnected: -2, size: 0
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,D/BluetoothA2dp(  760): Proxy object connected
D/A2dpService( 2357): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 2357): classInitNative: succeeds
,I/bluedroid( 2357): get_profile_interface avrcp
,I/BluetoothAdapterState( 2357): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,E/RemoteController( 2357): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2357): classInitNative: succeeds
D/A2dpStateMachine( 2357): make
,I/bluedroid( 2357): get_profile_interface a2dp
,I/GKI_LINUX( 2357): gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
D/A2dpStateMachine( 2357): Enter Disconnected: -2
,I/BluetoothHidServiceJni( 2357): classInitNative: succeeds
,D/BluetoothInputDevice( 1044): Proxy object connected
,D/HidService( 2357): Received start request. Starting profile...
D/HidProfile( 1044): Bluetooth service connected
I/bluedroid( 2357): get_profile_interface hidhost
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
I/BluetoothHealthServiceJni( 2357): classInitNative: succeeds
D/HealthService( 2357): Received start request. Starting profile...
I/bluedroid( 2357): get_profile_interface health
D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
I/BluetoothPanServiceJni( 2357): classInitNative(L105): succeeds
,D/HeadsetStateMachine( 2357): Proxy object connected
,D/PanService( 2357): Received start request. Starting profile...
D/BluetoothPan( 1044): BluetoothPAN Proxy object connected
D/BluetoothPanServiceJni( 2357): initializeNative(L110): pan
I/bluedroid( 2357): get_profile_interface pan
D/PanProfile( 1044): Bluetooth service connected
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,I/BtGatt.JNI( 2357): classInitNative(L863): classInitNative: Success!
,D/BtGatt.DebugUtils( 2357): handleDebugAction() action=null
,D/BtGatt.GattService( 2357): Received start request. Starting profile...
D/BtGatt.GattService( 2357): start()
I/bluedroid( 2357): get_profile_interface gatt
D/BtGatt.AdvertiseManager( 2357): advertise manager created
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,D/HeadsetStateMachine( 2357): Disconnected process message: 10, size: 0
,D/HeadsetPhoneState( 2357): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 2357): Disconnected process message: 11, size: 0
,V/BluetoothMapService( 2357): BluetoothMapBinder()
,D/BluetoothMap( 1044): Proxy object connected
,D/MapProfile( 1044): Bluetooth service connected
,D/BluetoothMap( 1044): getConnectedDevices()
,D/BluetoothMapService( 2357): Received start request. Starting profile...
,D/BluetoothMapService( 2357): start()
D/BluetoothMap( 1044): Bluetooth is Not enabled
,D/BluetoothMapEmailSettingsLoader( 2357): Found 0 applications
D/BluetoothMapEmailAppObserver( 2357): createReceiver()
,D/BluetoothMapEmailAppObserver( 2357): initObservers()
D/BluetoothMapEmailAppObserver( 2357): getEnabledAccountItems()
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,V/BluetoothMapService( 2357): Handler(): got msg=1
,D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2357): enable
,I/GKI_LINUX( 2357): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2357): btu_task pending for preload complete event
I/bt_hci_bdroid( 2357): init
,I/bt_vendor( 2357): init
I/bt_vnd_conf( 2357): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2357): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 2357): userial_init
,I/bt_userial_vendor( 2357): userial vendor open: opening /dev/ttyHS99
,I/bt_userial_vendor( 2357): device fd = 53 open
D/bt_userial( 2357): Entering userial_read_thread()
,E/Auth.Api.Credentials( 1699): [CredentialSyncAdapter] Unknown sync event.
,I/bt_hwcfg( 2357): bt vendor lib: set UART baud 4000000
,D/bt_hwcfg( 2357): Chipset BCM4335C0
D/bt_hwcfg( 2357): Target name = [BCM4335C0]
I/bt_hwcfg( 2357): Found patchfile: /vendor/firmware//bcm4335c0.hcd
,D/ConnectivityService(  760): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  760): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  760): apparently satisfied.  currentScore=60
,D/ConnectivityManager.CallbackHandler( 1699): CM callback handler got msg 524290
,D/ConnectivityService(  760): Got NetworkFactory Messenger for Telephony
,D/GpsLocationProvider(  760): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
,D/GpsLocationProvider(  760): SIM MCC/MNC is still not available
,D/DcSwitchState( 1267): [DcSwitchState-0] DcSwitchState constructor E
D/DcSwitchState( 1267): [DcSwitchState-0] DcSwitchState constructor X
,D/DctController( 1267): [DctController] DctController(phones): Connect success: 0
,W/ResourcesManager( 1267): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  760): Message: 20
I/art     (  760): Explicit concurrent mark sweep GC freed 21747(1189KB) AllocSpace objects, 26(2MB) LOS objects, 33% free, 27MB/41MB, paused 2.805ms total 214.679ms
,D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9011c7:true
,D/BluetoothManagerService(  760): Message: 30
,D/ConnectivityService(  760): Got NetworkFactory Messenger for WIFI
,D/WIFI    (  760): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,I/bt_hwcfg( 2357): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2357): Settlement delay -- 100 ms
I/bt_hwcfg( 2357): Setting fw settlement delay to 100 
,I/ActivityManager(  760): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=2486 uid=10012 gids={50012, 9997} abi=armeabi-v7a
,I/bt_hwcfg( 2357): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2357): Setting local bd addr to 34:FC:EF:11:AE:67
,I/bt_hwcfg( 2357): vendor lib fwcfg completed
I/bt-btu  ( 2357): btu_task received preload complete event
,I/        ( 2357): BTE_InitTraceLevels -- TRC_HCI
I/        ( 2357): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 2357): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 2357): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 2357): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 2357): BTE_InitTraceLevels -- TRC_A2D
I/        ( 2357): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 2357): BTE_InitTraceLevels -- TRC_BTM
I/        ( 2357): BTE_InitTraceLevels -- TRC_GAP
I/        ( 2357): BTE_InitTraceLevels -- TRC_PAN
I/        ( 2357): BTE_InitTraceLevels -- TRC_SDP
I/        ( 2357): BTE_InitTraceLevels -- TRC_GATT
I/        ( 2357): BTE_InitTraceLevels -- TRC_SMP
I/        ( 2357): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 2357): BTE_InitTraceLevels -- TRC_BTIF
,W/DriveInitializer( 1699): Awaiting to be initialized
,W/DriveInitializer( 1699): Background init thread started
,V/OneTimeInitializerReceiver( 2486): OneTimeInitializerReceiver.onReceive
,V/OneTimeService( 2486): OneTimeService.onHandleIntent
,D/TelephonyNetworkFactory( 1267): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/DctController( 1267): [DctController] EVENT_PHONE1_RADIO_OFF.
,D/TelephonyDebugService( 1267): TelephonyDebugService()
,D/WifiService(  760): New client listening to asynchronous messages
,E/bt-btm  ( 2357): BTM_SecRegister:p_cb_info->p_le_callback == 0xa3dd99d5 
E/bt-btm  ( 2357): BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3dd99d5 
,I/ActivityManager(  760): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=2521 uid=10014 gids={50014, 9997, 1028, 3003} abi=armeabi-v7a
,D/BluetoothHeadset( 1267): Proxy object connected
,I/art     ( 1356): Explicit concurrent mark sweep GC freed 8468(566KB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 19MB/32MB, paused 3.966ms total 101.337ms
,D/DctController( 1267): [DctController] DataStateReceiver: phoneId= 0
D/DctController( 1267): [DctController] DataStateReceiver: ignore invalid subId=-1
,E/bt-btif ( 2357): Calling BTA_HhEnable
E/bt-btif ( 2357): btif_storage_get_adapter_property service_mask:0x2140040
D/BluetoothAdapterProperties( 2357): Address is:34:FC:EF:11:AE:67
,D/BluetoothManagerService(  760): Bluetooth Adapter name changed to Nexus 5
,D/BluetoothManagerService(  760): Stored Bluetooth name: Nexus 5
,D/BluetoothAdapterProperties( 2357): Name is: Nexus 5
,W/bt-smp  ( 2357): Key(LSB ~ MSB) = ab c5 ba 55 b6 95 24 da 98 d0 34 2d 0b cd f5 20 
W/bt-smp  ( 2357): Plain text(LSB ~ MSB) = a9 c5 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2357): Encrypted text(LSB ~ MSB) = 5b ff c9 e9 30 62 19 23 fb b1 77 e0 53 dd 34 7a 
W/bt-btm  ( 2357): Stopping oneshot timer
,D/BluetoothAdapterProperties( 2357): Scan Mode:20
,D/BluetoothAdapterProperties( 2357): Discoverable Timeout:120
,D/bte_conf( 2357): Device ID record 1 : primary
D/bte_conf( 2357):   vendorId            = 000f
D/bte_conf( 2357):   vendorIdSource      = 0001
D/bte_conf( 2357):   product             = 1200
D/bte_conf( 2357):   version             = 1436
D/bte_conf( 2357):   clientExecutableURL = 
D/bte_conf( 2357):   serviceDescription  = 
D/bte_conf( 2357):   documentationURL    = 
D/bte_conf( 2357): bte_load_did_conf no section named DID2.
D/BluetoothPanServiceJni( 2357): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2357): ScanMode =  20
D/BluetoothAdapterProperties( 2357): State =  11
D/BluetoothAdapterProperties( 2357): Setting state to 12
I/BluetoothAdapterState( 2357): Bluetooth adapter state changed: 11-> 12
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
,D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(true) to 9 receivers.
,I/BluetoothAdapterState( 2357): Entering On State
,D/BluetoothAdapterProperties( 2357): Scan Mode:21
D/BluetoothInputDevice( 1044): onBluetoothStateChange: up=true
D/BluetoothAdapterProperties( 2357): Discoverable Timeout:120
,D/BluetoothHeadset( 1267): onBluetoothStateChange: up=true
,E/bt_h4   ( 2357): vendor lib postload completed
,D/BluetoothPan( 1044): onBluetoothStateChange(on) call bindService
,D/GpsLocationProvider(  760): received SIM realted action: android.intent.action.SIM_STATE_CHANGED
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=true
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=true
D/BluetoothA2dp(  760): onBluetoothStateChange: up=true
,D/GpsLocationProvider(  760): SIM MCC/MNC is still not available
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=true
,D/BluetoothPbap( 1044): onBluetoothStateChange: up=true
,D/BluetoothMap( 1044): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 11 -> 12
,D/BluetoothManagerService(  760): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  760): Message: 40
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,D/BluetoothMapService( 2357): onReceive
D/BluetoothMapService( 2357): STATE_ON
V/BluetoothMapService( 2357): Handler(): got msg=1
I/MmsService( 1267): mReceiver action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
,I/Telephony( 1267): : SUBINFO_RECORD_UPDATED : 4.
,D/BluetoothMapMasInstance( 2357): Map Service startRfcommSocketListener
I/MmsService( 1267): MmsConfigManager.loadInBackground(): mcc/mnc: 0/0
,D/BluetoothMapMasInstance( 2357): MAS initSocket()
D/BluetoothMapMasInstance( 2357):   masId = 00
D/BluetoothMapMasInstance( 2357):   msgTypes = 0e
D/BluetoothMapMasInstance( 2357):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2357):   SDP string = 000eSMS/MMS
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/Telecom ( 1223): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,W/BluetoothAdapter( 2357): getBluetoothService() called with no BluetoothManagerCallback
,E/MmsService( 1267): MmsConfigManager.load -- empty getActiveSubInfoList
D/GpsLocationProvider(  760): received SIM realted action: android.intent.action.ACTION_SUBINFO_RECORD_UPDATED
,V/BluetoothMapMasInstance( 2357): Succeed to create listening socket 
D/BluetoothMapMasInstance( 2357): Accepting socket connection...
D/HeadsetStateMachine( 2357): Disconnected process message: 9, size: 0
D/HeadsetStateMachine( 2357): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/HeadsetStateMachine( 2357): mNumber:  mType: 128
D/HeadsetStateMachine( 2357): terminateScoUsingVirtualVoiceCall: Received
,E/HeadsetStateMachine( 2357): terminateScoUsingVirtualVoiceCall:No present call to terminate
,D/LocalBluetoothProfileManager( 1044): Adding local A2DP profile
,D/BluetoothManagerService(  760): Message: 30
,E/PhoneInterfaceManager( 1267): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/GpsLocationProvider(  760): SIM MCC/MNC is still not available
,D/LocalBluetoothProfileManager( 1044): Adding local HEADSET profile
,D/BluetoothManagerService(  760): Message: 30
,I/RlzPingService( 1509): Setting next ping for 1448624995775
,I/ActivityManager(  760): Killing 1308:com.android.printspooler/u0a72 (adj 15): empty #17
,I/Telephony( 1267): PstnIncomingCallNotifier: Registering: Handler (com.android.internal.telephony.gsm.GSMPhone) {28af0c8}
,I/art     ( 1667): Explicit concurrent mark sweep GC freed 21029(1232KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 19MB/32MB, paused 2.800ms total 191.569ms
,W/libprocessgroup(  760): failed to open /acct/uid_10072/pid_1308/cgroup.procs: No such file or directory
,D/BluetoothA2dp( 1044): Proxy object connected
D/A2dpProfile( 1044): Bluetooth service connected
,W/DriveInitializer( 1699): Background init thread ended
,D/BluetoothHeadset( 1044): Proxy object connected
,I/art     ( 1699): Explicit concurrent mark sweep GC freed 24447(1714KB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 19MB/32MB, paused 10.650ms total 370.099ms
,W/art     ( 2168): Suspending all threads took: 10.771ms
D/HeadsetProfile( 1044): Bluetooth service connected
,I/ActivityManager(  760): Killing 1044:com.android.settings/1000 (adj 15): empty #17
,D/WifiService(  760): Client connection lost with reason: 4
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_1044/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2013:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10045/pid_2013/cgroup.procs: No such file or directory
,D/MtpService(  922): updating state; isCurrentUser=true, mMtpLocked=false
,I/ContactAccountLoggerTas( 1437): canRun() : Opted Out
,E/SQLiteLog(  922): (283) recovered 240 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,I/ActivityManager(  760): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=2569 uid=10036 gids={50036, 9997, 3003} abi=armeabi-v7a
,W/MediaScanner(  922): Error opening directory '/oem/media/', skipping: No such file or directory.
,E/UpdateRequestReceiver( 2569): ignoring update request
,E/UpdateRequestReceiver( 2569): ignoring update request
,E/UpdateRequestReceiver( 2569): ignoring update request
,E/UpdateRequestReceiver( 2569): ignoring update request
,E/UpdateRequestReceiver( 2569): ignoring update request
,I/iu.UploadsManager( 1699): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,E/UpdateRequestReceiver( 2569): ignoring update request
,W/BroadcastQueue(  760): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.google.android.gallery3d/com.android.camera.DisableCameraReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,I/GoogleHttpClient( 1356): GMS http client unavailable, use old client
,I/ActivityManager(  760): Start proc com.lge.SprintHiddenMenu for broadcast com.lge.SprintHiddenMenu/.sprintspec.data.UaproflieSettingReceiver: pid=2605 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  196): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 196us total 17.099ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 175us total 11.654ms
,I/art     (  196): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 238us total 19.342ms
,I/art     (  760): Explicit concurrent mark sweep GC freed 12660(558KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.466ms total 81.799ms
,V/MediaScanner(  922): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@b52596f
V/MediaScanner(  922): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@b52596f
I/iu.UploadsManager( 1699): End new media; added: 0, uploading: 0, time: 288 ms
W/ResourcesManager( 2605): Asset path '/system/framework/serviceitems.jar' does not exist or contains no resources.
W/ResourcesManager( 2605): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  760): Start proc com.qualcomm.qcrilmsgtunnel for broadcast com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot: pid=2623 uid=1001 gids={41001, 9997, 3003, 2001, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/QcrilMsgTunnelAutoboot( 2623): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
,D/QcrilMsgTunnelService( 2623): onCreate method
,D/QcrilMsgTunnelIfaceManager( 2623): : Instantiated
,V/QcrilMsgTunnelSocket( 2623): Starting QcRil Sender & Receiver threads
,D/QcrilMsgTunnelIfaceManager( 2623):  Registered for UNSOL OEM HOOK Responses to deliver external apps
,I/QcrilMsgTunnelSocket( 2623): Connected to 'qmux_radio/rild_oem0' socket
,D/FileApkUtils( 1699): Spent 19ms computing apk sha1.
,D/FileApkUtils( 1699): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 1699): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-2707d05c501ef4bf821813f1789ad0e56682eb5a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,D/DexOptUtils( 1699): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-2707d05c501ef4bf821813f1789ad0e56682eb5a/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 1699): Keeping up-to-date module: module-2707d05c501ef4bf821813f1789ad0e56682eb5a
,D/GmsModuleFndr( 1699): Beginning GMS chimera module scan
,D/GmsModuleFndr( 1699): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 1699): Beginning module configuration check
,D/ChimeraCfgMgr( 1699): Module APKs unchanged, check complete
,D/GCM     ( 1699): COMPAT: Multi user ser=0 current=0
,D/GCM     ( 1356): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/CheckinService( 1699): Checkin interval check for package: unspecified last checkin: 1448007304244 min interval config: 0 actual interval: 12892933
,I/GCoreUlr( 1699): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1667): DispatchingService.onCreate()
,I/CheckinService( 1699): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 1699): onCreate
,D/SystemUpdateService( 1699): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 1699): active receiver: enabled
,I/SystemUpdateService( 1699): showing system update notification
,V/AuthZen ( 1699): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 1699): Handling event: android.intent.action.BOOT_COMPLETED
,W/BaseAppContext( 1699): Using Auth Proxy for data requests.
,I/ValidateNoPeople(  760): skipping global notification
,V/SystemUpdateService( 1699): retry (wakeup: false) in 3599935 ms
,I/CheckinService( 1699): Checking schedule, now: 1448020197280 next: 1448049471216
I/CheckinService( 1699): active receiver: disabled
,D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 1699): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 1699): onDestroy
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Kids    ( 1699): [AbstractKidsOperation] Invalid device state 3
,W/GCoreFlp( 1667): No location to return for getLastLocation()
,W/FusedLocationProvider( 1699): location=null
,I/AuthZen ( 1699): Fetching signing key...
,W/Auth    ( 1356): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/AuthZen ( 1699): Signing key fetched successfully!
,W/BaseAppContext( 1699): Using Auth Proxy for data requests.
,W/GCoreFlp( 1667): No location to return for getLastLocation()
,W/FusedLocationProvider( 1699): location=null
V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/a       ( 1699): Opening database auth.proximity.permit_store...
,I/GCoreUlr( 1667): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/AuthZenTransactionCache( 1699): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1699): Clearing transaction cache
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1356): Explicit concurrent mark sweep GC freed 6557(393KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 19MB/32MB, paused 611us total 23.735ms
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 1699): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,D/PersistentNotificationBroadcastReceiver( 1356): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  760): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=2687 uid=10080 gids={50080, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1667): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1667): Unbound from all location providers
,W/ContextImpl( 2249): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/GCoreUlr( 1667): DispatchingService.onDestroy()
,I/GCoreUlr( 1667): Stopping handler for UlrDispSvcFast
,I/GAV2    ( 2249): Thread[GAThread,5,main]: No campaign data found.
,I/GCoreUlr( 1667): Unbound from all location providers
,W/ResourcesManager( 2687): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2687): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2687): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 2687): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2687): Installed default security provider GmsCore_OpenSSL
,E/YouTube MDX( 2687): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 2728): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads125448509.jar --oat-fd=24 --oat-location=/data/data/com.google.android.youtube/cache/ads125448509.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 2728): dex2oat took 36.830ms (threads: 4)
,W/InstanceID/Rpc( 2687): Found 10008
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@16f23237 mBinding = false
,D/BluetoothManagerService(  760): Message: 2
D/BluetoothManagerService(  760): Sending off request.
D/BluetoothAdapterState( 2357): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2357): Setting state to 13
I/BluetoothAdapterState( 2357): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 2357): onBluetoothDisable()
I/BluetoothAdapterState( 2357): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 2357): Scan Mode:20
D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 2357): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 2357): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
V/BluetoothMapMasInstance( 2357): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2357): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2357): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2357): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,D/BluetoothMapService( 2357): onReceive
D/BluetoothMapService( 2357): STATE_TURNING_OFF
V/BluetoothMapService( 2357): Handler(): got msg=4
D/BluetoothMapService( 2357): MAP Service closeService in
D/BluetoothMapMasInstance( 2357): MAP Service shutdown
V/BluetoothMapService( 2357): MAP Service closeService out
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: false pid=2201, uid=10277
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 2201): ****TEST TOOK:  5081  ms ****
I/jxcore-log( 2201): 
I/jxcore-log( 2201): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2201): 
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  181): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1356): Read error: ssl=0x9dc29e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1356): SSL shutdown failed: ssl=0x9dc29e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/bt_userial( 2357): RX termination
W/bt_userial( 2357): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2357): Leaving userial_read_thread()
W/bt-btif ( 2357): ag scb idx 1 not allocated
E/bt-btif ( 2357): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2357): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt_userial( 2357): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2357): hw_epilog_process
,I/bt_userial_vendor( 2357): device fd = 53 close
,I/GKI_LINUX( 2357): gki_task task_id=0 [BTU] terminating
,I/GKI_LINUX( 2357): GKI_exit_task 0 done
I/GKI_LINUX( 2357): GKI_shutdown(): task [BTU] terminated
,D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 2357): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,D/HeadsetStateMachine( 2357): Exit Disconnected: -1
,D/A2dpService( 2357): Received stop request...Stopping profile...
D/A2dpStateMachine( 2357): Exit Disconnected: -1
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,D/BluetoothHeadset( 1223): Proxy object disconnected
,D/BluetoothHeadset( 1223): Proxy object disconnected
,D/BluetoothHeadset(  760): Proxy object disconnected
D/BluetoothA2dp(  760): Proxy object disconnected
,D/HidService( 2357): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
D/BluetoothHeadset( 1267): Proxy object disconnected
,D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,D/BluetoothAdapterState( 2357): Stopping profile services that were post enabled
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/HeadsetStateMachine( 2357): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2357): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2357): Cleaning up Bluetooth Handsfree callback object
D/HealthService( 2357): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
E/WifiStateMachine(  760): scanCount==0 - aborting
D/WifiScanningService(  760): SCAN_AVAILABLE : 1
D/RttService(  760): SCAN_AVAILABLE : 1
D/WifiScanningService(  760): StartedState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  760): DefaultState
D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
,D/RttService(  760): EnabledState got{ when=-12ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,I/GKI_LINUX( 2357): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2357): GKI_exit_task 2 done
I/GKI_LINUX( 2357): GKI_shutdown(): task [A2DP-MEDIA] terminated
,D/PanService( 2357): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,D/BtGatt.DebugUtils( 2357): handleDebugAction() action=null
,D/BtGatt.GattService( 2357): Received stop request...Stopping profile...
D/BtGatt.GattService( 2357): stop()
D/BtGatt.AdvertiseManager( 2357): advertise clients cleared
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,D/BluetoothMapService( 2357): Received stop request...Stopping profile...
,D/BluetoothMapService( 2357): stop()
D/BluetoothMapEmailAppObserver( 2357): deinitObservers()
D/BluetoothMapEmailAppObserver( 2357): removeReceiver()
,D/BluetoothAdapterService( 2357): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2ded3987
,W/BluetoothHidServiceJni( 2357): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2357): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2357): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 2357): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2357): Cleaning up Bluetooth Health object
,W/BluetoothPanServiceJni( 2357): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2357): Cleaning up Bluetooth PAN callback object
,V/BluetoothMapService( 2357): Handler(): got msg=4
D/BluetoothMapService( 2357): MAP Service closeService in
V/BluetoothMapService( 2357): MAP Service closeService out
D/BluetoothMapService( 2357): cleanup()
D/BluetoothMapService( 2357): MAP Service closeService in
V/BluetoothMapService( 2357): MAP Service closeService out
,D/BluetoothAdapterState( 2357): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2357): Setting state to 10
I/BluetoothAdapterState( 2357): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(false) to 5 receivers.
I/BluetoothAdapterState( 2357): Entering OffState
,D/BluetoothHeadset( 1267): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=false
D/BluetoothA2dp(  760): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1223): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  760): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  760): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@16f23237 mBinding = false
,D/BluetoothManagerService(  760): Sending unbind request.
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  900): 342573016: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  900): 342573016: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  900): 342573016: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1667): 643304015: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1667): 643304015: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2357): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2357): GKI_exit_task 1 done
I/GKI_LINUX( 2357): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 2357): cleanupNative: return from cleanup
,I/art     ( 2357): System.exit called, status: 0
I/AndroidRuntime( 2357): VM exiting with result code 0, cleanup skipped.
,V/Babel   ( 2117): babel boot account: thalitester@gmail.com
,D/CommandListener(  181): Clearing all IP addresses on wlan0
D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1699): CM callback handler got msg 524292
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
,D/ConnectivityManager.CallbackHandler(  900): CM callback handler got msg 524292
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,E/SQLiteLog( 2117): (284) automatic index on conversation_participants_view(conversation_id)
,D/AndroidRuntime( 2798): 
D/AndroidRuntime( 2798): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 2798): CheckJNI is OFF
,I/ActivityManager(  760): Process com.android.bluetooth (pid 2357) has died
,W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 2117): Unrecognized profile 2130706433 for video/avc
,E/SQLiteLog( 2117): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager(  760): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2812 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  760): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,E/SQLiteLog( 2117): (284) automatic index on conversation_participants_view(conversation_id)
,D/TelephonyNetworkFactory( 1267): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/AndroidRuntime( 2798): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
,I/ActivityManager(  760): Killing 2201:com.example.hello/u0a277 (adj 0): stop com.example.hello
,I/wpa_supplicant( 1020): p2p0: CTRL-EVENT-TERMINATING 
,I/WindowState(  760): WIN DEATH: Window{a2787ac u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,I/wpa_supplicant( 1020): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,W/PackageSettings(  760): Skipping PackageSetting{1a0e138f com.test.thalitest/10270} due to missing metadata
,D/Tethering(  760): InitialState.processMessage what=4
,I/wpa_supplicant( 1020): wlan0: CTRL-EVENT-TERMINATING 
,W/ActivityManager(  760): Force removing ActivityRecord{1fafe1dd u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  760): Spurious death for ProcessRecord{401340 2201:com.example.hello/u0a277}, curProc for 2201: null
,I/ActivityManager(  760): Force stopping com.example.hello appid=10277 user=0: pkg removed
,D/Tethering(  760): sendTetherStateChangedBroadcast 0, 0, 0
,I/Keyboard.Facilitator( 1096): resetDictionaries() : en_US
,I/ActivityManager(  760): Killing 2041:com.google.android.music:main/u0a60 (adj 15): empty #17
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator.DecoderInitializer( 1096): run()
,I/FitnessApp( 2812): Initializers took 0 milliseconds
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  760): Explicit concurrent mark sweep GC freed 33206(1851KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/41MB, paused 1.727ms total 96.598ms
I/art     (  760): WaitForGcToComplete blocked for 89.506ms for cause Explicit
,W/libprocessgroup(  760): failed to open /acct/uid_10060/pid_2041/cgroup.procs: No such file or directory
,W/Settings( 2117): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
,W/Settings( 1667): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AndroidRuntime( 2798): Shutting down VM
,I/art     (  760): Explicit concurrent mark sweep GC freed 3325(170KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 1.004ms total 59.176ms
,W/GeofencerStateMachine( 1667): Ignoring removeGeofence because network location is disabled.
,I/Decoder ( 1096): createOrResetDecoder
,I/ConfigService( 1356): onCreate
,I/ActivityManager(  760): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2847 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): run()
,I/ActivityManager(  760): Killing 1844:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
,W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2201 uid 10277
,I/Keyboard.Facilitator( 1096): onFinishInput()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1096): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1096): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1096): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1096): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1096): run()
I/StatsUtilsManager( 1096): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1096): shouldRecordStats() = Too Soon
,W/libprocessgroup(  760): failed to open /acct/uid_10061/pid_1844/cgroup.procs: No such file or directory
,I/MicrophoneInputStream( 1437): mic_starting gfk@3d080aa7
,I/HotwordRecognitionRnr( 1437): Starting hotword detection.
,I/AudioFlinger(  185): AudioFlinger's thread 0xb48b9000 ready to run
,I/MicrophoneInputStream( 1437): mic_started gfk@3d080aa7
,D/audio_hw_primary(  185): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,D/msm8974_platform(  185): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  185): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  185): Error: ACDB AudProc vol returned = -19
D/audio_hw_primary(  185): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  185): enable_audio_route: apply and update mixer path: audio-record
,W/ResourcesManager( 1326): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1326): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1699): Explicit concurrent mark sweep GC freed 25337(1972KB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 20MB/33MB, paused 1.521ms total 41.981ms
,W/SQLiteConnectionPool( 1699): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/HotwordWorker( 1437): onReady
,E/qdhwcomposer(  173): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  173): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
,E/qdoverlay(  173): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  173): MdpData failed to play
E/qdoverlay(  173): == Dump MdpData start ==
E/qdoverlay(  173): == Dump OvFD fd=40 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  173): mOvData msmfb_overlay_data id=64
E/qdoverlay(  173): data msmfb_data offset=0 memid=59 id=0 flags=0x0 priv=0
E/qdoverlay(  173): == Dump MdpData end ==
E/qdhwcomposer(  173): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  173): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  173): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  173): hwc_set_primary: display commit fail!
,W/OpenGLRenderer( 1326): Incorrectly called buildLayer on View: adg, destroying layer...
,W/OpenGLRenderer( 1326): Incorrectly called buildLayer on View: adg, destroying layer...
,E/qdhwcomposer(  173): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  173): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  173): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  173): MdpData failed to play
E/qdoverlay(  173): == Dump MdpData start ==
E/qdoverlay(  173): == Dump OvFD fd=40 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  173): mOvData msmfb_overlay_data id=64
E/qdoverlay(  173): data msmfb_data offset=0 memid=59 id=0 flags=0x0 priv=0
E/qdoverlay(  173): == Dump MdpData end ==
E/qdhwcomposer(  173): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  173): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  173): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  173): hwc_set_primary: display commit fail!

```
