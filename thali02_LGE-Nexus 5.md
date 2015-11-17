#### Test 503880196ac79ce_thali02_LGE-Nexus 5 Logs


```--------- beginning of system
11-17 18:30:36.403  2231  2252 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:30:36.403  2231  2252 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
11-17 18:30:36.434  2231  2252 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-17 18:30:36.482  2231  2252 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
11-17 18:30:36.482  2231  2252 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 18:30:36.659  2266  2266 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-503729324.jar --oat-fd=21 --oat-location=/data/data/com.google.android.youtube/cache/ads-503729324.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
11-17 18:30:36.672  2231  2231 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
11-17 18:30:36.699  2266  2266 I dex2oat : dex2oat took 39.987ms (threads: 4)
11-17 18:30:36.878  2231  2231 W InstanceID/Rpc: Found 10008
11-17 18:30:37.001  1784  1784 V Babel   : babel boot account: thalitester@gmail.com
11-17 18:30:37.046   734   749 I ActivityManager: Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver: pid=2330 uid=10038 gids={50038, 9997, 3003, 1028} abi=armeabi-v7a
11-17 18:30:37.054  1784  2327 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
11-17 18:30:37.082  1784  2327 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:30:37.083  1784  2327 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:30:37.086  1784  2327 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
11-17 18:30:37.088  1784  2327 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
11-17 18:30:37.092  1784  2327 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
11-17 18:30:37.136  2330  2330 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
11-17 18:30:37.136  2330  2330 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-17 18:30:37.136  2330  2330 I GAv4    :   adb logcat -s GAv4
11-17 18:30:37.150  2330  2330 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
11-17 18:30:37.173  2330  2330 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
11-17 18:30:37.178  2330  2349 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
11-17 18:30:37.259   734   939 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2352 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:30:37.260   734   939 I ActivityManager: Killing 1624:com.android.settings/1000 (adj 15): empty #17
11-17 18:30:37.278   734   850 D WifiService: Client connection lost with reason: 4
11-17 18:30:37.314   734  1261 W libprocessgroup: failed to open /acct/uid_1000/pid_1624/cgroup.procs: No such file or directory
,11-17 18:30:37.564  2352  2378 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
11-17 18:30:37.564  2352  2377 I Gmail   : getAccountsCursor
11-17 18:30:37.595  1348  1348 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:37.625   734   749 I art     : Explicit concurrent mark sweep GC freed 17665(838KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/40MB, paused 756us total 47.547ms
11-17 18:30:37.650  2373  2373 D AndroidRuntime: 
11-17 18:30:37.650  2373  2373 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:30:37.652  2373  2373 D AndroidRuntime: CheckJNI is OFF
11-17 18:30:37.726   734  1247 I ActivityManager: Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2404 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:30:37.747  2373  2373 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:30:37.754   734  1354 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:30:37.763  2373  2373 D AndroidRuntime: Shutting down VM
11-17 18:30:37.794   734  1331 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2425 uid=10277 gids={50277, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:30:37.823  1390  1592 I MicrophoneInputStream: mic_close gfk@7d6a686
11-17 18:30:37.853  2352  2352 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
11-17 18:30:37.885   183  1606 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
11-17 18:30:37.885   183  1606 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
11-17 18:30:37.896  1390  1603 I HotwordRecognitionRnr: Hotword detection finished
11-17 18:30:37.899  1390  1597 I HotwordRecognitionRnr: Stopping hotword detection.
11-17 18:30:37.905  2425  2425 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
11-17 18:30:37.918   734  1279 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
11-17 18:30:37.923  2404  2404 I Exchange: EasService.onCreate
11-17 18:30:37.925  2352  2451 I Gmail   : getAccountsCursor
11-17 18:30:37.932  1348  1348 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:37.933  2425  2425 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7068-7070)
11-17 18:30:37.933  2425  2425 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:37.936  2352  2452 I Gmail   : Observing account changes for notifications
11-17 18:30:37.942  2404  2456 I Exchange: RestartPingTask
11-17 18:30:37.949  2425  2425 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3017c560}
11-17 18:30:37.951  2425  2425 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:30:37.951  2425  2425 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:30:37.963  2425  2425 I BrowserStartupController: Initializing chromium process, singleProcess=true
11-17 18:30:37.964  2425  2425 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:37.965  2425  2425 E SysUtils: ApplicationContext is null in ApplicationStatus
11-17 18:30:37.967   734   749 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2462 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
11-17 18:30:37.977  2425  2468 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
11-17 18:30:37.977   194   194 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 194us total 11.018ms
11-17 18:30:37.985   194   194 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.483ms
11-17 18:30:37.988  1348  1348 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:37.994   194   194 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 166us total 7.769ms
11-17 18:30:37.998  2425  2425 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
11-17 18:30:38.003  2425  2425 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:30:38.003  2425  2425 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 18:30:38.004  2425  2425 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
11-17 18:30:38.020  1348  1379 I art     : Explicit concurrent mark sweep GC freed 7591(431KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 19MB/32MB, paused 599us total 30.408ms
11-17 18:30:38.048  2404  2404 I Exchange: RestartPingsTask did not start any pings.
11-17 18:30:38.048  2404  2404 I Exchange: PSS stopIfIdle
11-17 18:30:38.049  2404  2404 I Exchange: PSS has no active accounts; stopping service.
11-17 18:30:38.049  2404  2404 I Exchange: onDestroy
11-17 18:30:38.050   734  1247 I ActivityManager: Killing 1650:com.google.android.apps.magazines/u0a61 (adj 15): empty #17
11-17 18:30:38.053   734   827 D BluetoothManagerService: Message: 20
11-17 18:30:38.053   734   827 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@94a113f:true
11-17 18:30:38.055  2425  2492 D BluetoothAdapter: 876060373: getState() :  mService = null. Returning STATE_OFF
11-17 18:30:38.087  2352  2453 E SQLiteLog: (283) recovered 123 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
11-17 18:30:38.173   734  1375 W libprocessgroup: failed to open /acct/uid_10061/pid_1650/cgroup.procs: No such file or directory
11-17 18:30:38.193  2352  2484 I Gmail   : notifyAccountChanged
11-17 18:30:38.200  2352  2377 I Gmail   : getAccountsCursor
11-17 18:30:38.201  2352  2484 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
11-17 18:30:38.203  1348  1348 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:38.210   734  1375 I ActivityManager: Killing 1280:com.android.printspooler/u0a72 (adj 15): empty #17
11-17 18:30:38.215  2425  2425 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:38.221  2352  2484 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
11-17 18:30:38.222  2425  2425 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:30:38.231  2352  2484 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
11-17 18:30:38.232  2352  2484 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
11-17 18:30:38.234  2425  2425 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
11-17 18:30:38.283   734   939 W libprocessgroup: failed to open /acct/uid_10072/pid_1280/cgroup.procs: No such file or directory
11-17 18:30:38.325   171   171 D SurfaceFlinger: shader cache generated - 24 shaders in 149.208755 ms
11-17 18:30:38.335  2425  2425 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:38.335  2425  2425 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:30:38.396  2425  2507 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:30:38.401  2425  2425 D Atlas   : Validating map...
11-17 18:30:38.413  2425  2490 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
11-17 18:30:38.446  2462  2462 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
11-17 18:30:38.464  2425  2507 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:30:38.467  2425  2507 D OpenGLRenderer: Enabling debug mode 0
11-17 18:30:38.514  2352  2377 I Gmail   : getAccountsCursor
11-17 18:30:38.517  1348  1348 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
11-17 18:30:38.528   734   828 I ActivityManager: Displayed com.example.hello/.MainActivity: +762ms (total +15s656ms)
11-17 18:30:38.548  2425  2425 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2425
11-17 18:30:38.550  2425  2425 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:30:38.577  2462  2462 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
11-17 18:30:38.594  2462  2462 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:38.594  2462  2462 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
11-17 18:30:38.608  2425  2425 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:30:38.626  2425  2498 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:30:38.628  2462  2511 D Volley  : [226] DiskBasedCache.clear: Cache cleared.
11-17 18:30:38.628  2462  2524 D Volley  : [233] DiskBasedCache.clear: Cache cleared.
11-17 18:30:38.629   734  1399 I ActivityManager: Killing 1839:com.android.keychain/1000 (adj 15): empty #17
11-17 18:30:38.675   734  1375 W libprocessgroup: failed to open /acct/uid_1000/pid_1839/cgroup.procs: No such file or directory
11-17 18:30:38.678  1088  1088 I SystemBroadcastReceiver: Boot has been completed
11-17 18:30:38.678  1088  1088 I SystemBroadcastReceiver: toggleAppIcon() : FLAG_SYSTEM = true
11-17 18:30:38.701  2462  2462 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
11-17 18:30:38.701  2462  2462 D Finsky  : [1] 2.run: Finished loading 1 libraries.
11-17 18:30:38.709  1321  1321 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
11-17 18:30:38.723  2425  2517 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258381056
11-17 18:30:38.723  2425  2517 D JX-Cordova: jxcore cordova android initializing
11-17 18:30:38.744  2462  2537 D Ads     : Skipping gmscore version check
11-17 18:30:38.761  2462  2462 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
11-17 18:30:38.772  2425  2425 W jxcore-log: Initializing JXcore engine
11-17 18:30:38.772  2425  2425 W jxcore-log: JXcore engine is ready
11-17 18:30:38.776  2425  2425 W jxcore-log: Starting JXcore engine
11-17 18:30:38.783   734  1331 I ActivityManager: Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2547 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,11-17 18:30:38.811  2425  2425 W m.example.hello: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[9456]" dev="sockfs" ino=9456 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
11-17 18:30:38.811  2425  2425 W m.example.hello: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
11-17 18:30:38.811  2425  2425 W m.example.hello: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8438]" dev="sockfs" ino=8438 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
11-17 18:30:38.811  2425  2425 W m.example.hello: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[14989]" dev="sockfs" ino=14989 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,11-17 18:30:38.836  2462  2462 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,11-17 18:30:38.871  2547  2547 D CellBroadcastReceiver: onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
11-17 18:30:38.871  2547  2547 D CellBroadcastReceiver: Intent ACTION_SERVICE_STATE_CHANGED
,11-17 18:30:38.873  2547  2547 D CellBroadcastReceiver: Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,11-17 18:30:38.874   734  1399 I ActivityManager: Killing 1874:com.google.android.dialer/u0a10 (adj 15): empty #17
,11-17 18:30:38.906  2425  2425 W jxcore-log: Platform android
11-17 18:30:38.906  2425  2425 W jxcore-log: 
11-17 18:30:38.906  2425  2425 W jxcore-log: Process ARCH arm
11-17 18:30:38.906  2425  2425 W jxcore-log: 
,11-17 18:30:38.941  2425  2425 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:30:38.941  2425  2425 I jxcore-log: 
,11-17 18:30:38.942  2425  2425 W jxcore-log: JXcore engine is started
,11-17 18:30:38.953   734  2219 W libprocessgroup: failed to open /acct/uid_10010/pid_1874/cgroup.procs: No such file or directory
,11-17 18:30:38.999  2425  2425 E jxcore-log: >> LGE-Nexus 5
11-17 18:30:38.999  2425  2425 E jxcore-log: 
,11-17 18:30:39.001  2425  2425 I jxcore-log: Total memory 1946181632
11-17 18:30:39.001  2425  2425 I jxcore-log: 
,11-17 18:30:39.001  2425  2425 I jxcore-log: Free memory 413229056
11-17 18:30:39.001  2425  2425 I jxcore-log: 
11-17 18:30:39.001  2425  2425 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:30:39.001  2425  2425 I jxcore-log: 
11-17 18:30:39.001  2425  2425 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:30:39.001  2425  2425 I jxcore-log: 
,11-17 18:30:39.005  2425  2425 I jxcore-log: userPath [ 'www' ]
11-17 18:30:39.005  2425  2425 I jxcore-log: 
,11-17 18:30:39.006  2425  2425 I jxcore-log: Size 1080 1776
11-17 18:30:39.006  2425  2425 I jxcore-log: 
,11-17 18:30:39.009  2425  2425 I jxcore-log: Screen Brightness 82
11-17 18:30:39.009  2425  2425 I jxcore-log: 
11-17 18:30:39.009  2425  2425 E jxcore-log: Dummy Error Log.
11-17 18:30:39.009  2425  2425 E jxcore-log: 
,11-17 18:30:39.034  1249  2568 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,11-17 18:30:39.077   734  1279 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2571 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:30:39.519  2425  2425 I jxcore-log: getBuffer is called!!!!
11-17 18:30:39.519  2425  2425 I jxcore-log: 
,11-17 18:30:39.671  2571  2571 I MusicStore: Database version: 120
,11-17 18:30:39.734  2029  2050 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,11-17 18:30:39.751  2029  2050 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:30:39.795  1563  1563 I art     : Explicit concurrent mark sweep GC freed 31420(2MB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 19MB/32MB, paused 761us total 43.340ms
,11-17 18:30:39.804  1563  1563 I GAv4-SVC: Google Analytics 8.3.01 is starting up.
,11-17 18:30:39.883  2571  2571 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:30:39.883  2571  2571 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:30:39.904  2571  2571 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-17 18:30:39.941  2571  2571 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-17 18:30:39.941  2571  2571 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ba9924e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
11-17 18:30:39.941  2571  2571 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 18:30:39.941  2571  2571 D AndroidMusic: GMSCore installation verified
,11-17 18:30:39.959  2571  2571 I ConfigStore: Config Database version: 1
,11-17 18:30:40.047   734  1354 I art     : Explicit concurrent mark sweep GC freed 10615(536KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/40MB, paused 778us total 45.391ms
,11-17 18:30:40.079  2571  2571 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,11-17 18:30:40.119  2571  2571 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,11-17 18:30:40.122  2571  2571 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-17 18:30:40.181   734  1071 I ActivityManager: Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2628 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,11-17 18:30:40.253  1390  2645 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:30:40.258  1563  2647 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
11-17 18:30:40.258  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:40.258  1563  1563 D ChimeraModuleLdr: Loading module APK com.google.android.play.games
,11-17 18:30:40.295   734   750 I ActivityManager: Killing 1957:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,11-17 18:30:40.352   734  1354 W libprocessgroup: failed to open /acct/uid_10012/pid_1957/cgroup.procs: No such file or directory
,11-17 18:30:40.362  2571  2625 I MediaStoreImporter: Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,11-17 18:30:40.364   734  1331 I ActivityManager: Killing 2006:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,11-17 18:30:40.382   734   939 W libprocessgroup: failed to open /acct/uid_10014/pid_2006/cgroup.procs: No such file or directory
,11-17 18:30:40.388  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:40.388  1563  1563 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:30:40.392  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.gass from APK com.google.android.gms
,11-17 18:30:40.398  1563  1563 D AsyncTaskServiceImpl: Submit a task: h
,11-17 18:30:40.399  1563  2662 I PeopleContactsSync: CP2 sync disabled
,11-17 18:30:40.402  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.gass from APK com.google.android.gms
,11-17 18:30:40.403  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
,11-17 18:30:40.405  1563  2665 D h       : Processing package: com.example.hello
,11-17 18:30:40.415  1563  2665 D GassUtils: Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
11-17 18:30:40.415  1563  2665 D h       : Found info for package com.example.hello in db.
,11-17 18:30:40.438   734  1071 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=2668 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,11-17 18:30:40.476  1563  2663 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:30:40.476  1563  2663 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:40.501  1563  2663 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:40.508  1563  2663 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:40.510  1563  2663 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:40.521  1563  2663 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:40.658  1390  2645 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 404 ms] updated apps [took 404 ms] 
,11-17 18:30:40.833  1563  2663 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:40.833  1563  2663 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:30:40.945  2668  2668 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
11-17 18:30:40.945  2668  2668 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-17 18:30:40.945  2668  2668 I GAv4    :   adb logcat -s GAv4
,11-17 18:30:40.954  2668  2668 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:30:40.966  2668  2668 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:30:40.970  2668  2703 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-17 18:30:40.983  2668  2668 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,11-17 18:30:41.074  2462  2462 D Finsky  : [1] ExternalReferrer.access$100: Package state data is missing for com.example.hello
,11-17 18:30:41.084  2668  2709 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:30:41.085  2668  2709 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:30:41.091   734  1375 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=2710 uid=10067 gids={50067, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
11-17 18:30:41.092   734  1375 I ActivityManager: Killing 1919:com.android.providers.calendar/u0a2 (adj 15): empty #17
,11-17 18:30:41.113   734  1279 W libprocessgroup: failed to open /acct/uid_10002/pid_1919/cgroup.procs: No such file or directory
,11-17 18:30:41.137  2710  2710 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:30:41.169  2668  2709 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-17 18:30:41.206  2668  2709 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,11-17 18:30:41.206  2668  2709 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-17 18:30:41.211  1348  1348 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,11-17 18:30:41.500  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 18:30:41.504  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 18:30:41.508  1563  2745 I Kids    : [KidAccountFixer] No network connection
,11-17 18:30:41.511  1348  2746 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,11-17 18:30:41.521   734  2219 I ActivityManager: Killing 2053:com.google.android.configupdater/u0a36 (adj 15): empty #17
,11-17 18:30:41.544   734  1279 W libprocessgroup: failed to open /acct/uid_10036/pid_2053/cgroup.procs: No such file or directory
,11-17 18:30:41.583  1348  1742 I art     : Explicit concurrent mark sweep GC freed 6973(349KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 19MB/32MB, paused 919us total 38.074ms
,11-17 18:30:41.619  1321  1588 W GCoreFlp: No location to return for getLastLocation()
,11-17 18:30:41.620  1348  2747 W FusedLocationProvider: location=null
,11-17 18:30:41.680   734   954 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=2756 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,11-17 18:30:41.696  1563  1616 I Icing   : Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
,11-17 18:30:41.711  2756  2756 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:30:41.713  1784  1784 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
11-17 18:30:41.714  1784  1784 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,11-17 18:30:41.734  1784  1784 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-17 18:30:41.737  2756  2756 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@2a67a563(com.android.providers.calendar.CalendarProvider2@3017c560)
,11-17 18:30:41.757  2756  2775 E SQLiteLog: (284) automatic index on view_events(_id)
,11-17 18:30:41.790  1563  1616 D Icing   : Loaded CLD2 Version V2.0 - 20141016
,11-17 18:30:41.794  1784  1784 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,11-17 18:30:41.794  1784  1784 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-17 18:30:41.830  1563  1616 I Icing   : Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
,11-17 18:30:41.851   734   749 I art     : Explicit concurrent mark sweep GC freed 9888(499KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 772us total 49.661ms
,11-17 18:30:42.786  2756  2756 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,11-17 18:30:42.790  2756  2756 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,11-17 18:30:42.876  2352  2442 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:30:44.013   734   939 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
11-17 18:30:44.013   734   939 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,11-17 18:30:44.016   734   827 D BluetoothManagerService: Message: 2
,11-17 18:30:44.018   734   850 D WifiService: New client listening to asynchronous messages
,11-17 18:30:44.019   734  1331 D WifiService: setWifiEnabled: false pid=2425, uid=10277
11-17 18:30:44.019   734  1331 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 18:30:44.020  2425  2425 I jxcore-log: ****TEST TOOK:  5025  ms ****
11-17 18:30:44.020  2425  2425 I jxcore-log: 
11-17 18:30:44.021  2425  2425 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:30:44.021  2425  2425 I jxcore-log: 
,11-17 18:30:44.242   734  1279 I ActivityManager: Killing 2097:com.google.android.keep/u0a71 (adj 15): empty #17
,11-17 18:30:44.295  2824  2824 D AndroidRuntime: 
11-17 18:30:44.295  2824  2824 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:30:44.297  2824  2824 D AndroidRuntime: CheckJNI is OFF
,11-17 18:30:44.313   734   750 W libprocessgroup: failed to open /acct/uid_10071/pid_2097/cgroup.procs: No such file or directory
,11-17 18:30:44.384  2824  2824 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:30:44.390   734   823 I ActivityManager: Force stopping com.example.hello appid=10277 user=-1: uninstall pkg
11-17 18:30:44.390   734   823 I ActivityManager: Killing 2425:com.example.hello/u0a277 (adj 0): stop com.example.hello
,11-17 18:30:44.412   734   850 D WifiService: Client connection lost with reason: 4
,11-17 18:30:44.412   734   939 I WindowState: WIN DEATH: Window{2e206e40 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:30:44.427   734   834 W PackageSettings: Skipping PackageSetting{14181148 com.test.thalitest/10270} due to missing metadata
,11-17 18:30:44.496   734   823 W ActivityManager: Force removing ActivityRecord{1d44088b u0 com.example.hello/.MainActivity t214}: app died, no saved state
,11-17 18:30:44.500   734  1261 W ActivityManager: Spurious death for ProcessRecord{2663c9bb 2425:com.example.hello/u0a277}, curProc for 2425: null
11-17 18:30:44.501   734   834 I ActivityManager: Force stopping com.example.hello appid=10277 user=0: pkg removed
,11-17 18:30:44.528  1088  1088 I Keyboard.Facilitator: resetDictionaries() : en_US
11-17 18:30:44.530  1088  2852 I Keyboard.Facilitator.DecoderInitializer: run()
,11-17 18:30:44.535  1321  1610 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:30:44.538  1088  2852 I Decoder : createOrResetDecoder
,11-17 18:30:44.540   734   841 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:30:44.546  1390  1390 I art     : Explicit concurrent mark sweep GC freed 22896(1623KB) AllocSpace objects, 15(2MB) LOS objects, 25% free, 18MB/24MB, paused 546us total 42.140ms
,11-17 18:30:44.552  1368  2853 D VoicemailCleanupService: Cleaning up data for package: com.example.hello
,11-17 18:30:44.568  1348  1348 I ConfigService: onCreate
,11-17 18:30:44.596  1390  2857 I UpdateIcingCorporaServi: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:30:44.642  1088  2852 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-17 18:30:44.649   734   734 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:30:44.649   734   734 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 18:30:44.651   734   877 D TaskPersister: removeObsoleteFile: deleting file=214_task.xml
,11-17 18:30:44.655  1390  2857 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 59 ms] updated apps [took 59 ms] 
,11-17 18:30:44.659  1267  1267 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@827a19 new=com.google.android.velvet.VelvetApplication@827a19
,11-17 18:30:44.661  1088  2852 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,11-17 18:30:44.663  1088  2852 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
11-17 18:30:44.663  1088  2852 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,11-17 18:30:44.667  1088  2852 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,11-17 18:30:44.667  1088  2852 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,11-17 18:30:44.669  1088  2852 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
11-17 18:30:44.669  1088  2852 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
11-17 18:30:44.670  1088  2852 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,11-17 18:30:44.670  1088  2852 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
11-17 18:30:44.670  1088  2852 I Keyboard.Facilitator.Delight2FileSweeper: run()
11-17 18:30:44.670  1088  2852 I Keyboard.Facilitator.RecurringTaskScheduler: run()
11-17 18:30:44.670  1088  2852 I StatsUtilsManager: startPeriodStatsRecorder() : Success
11-17 18:30:44.670  1088  2852 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,11-17 18:30:44.677   734   834 I art     : Explicit concurrent mark sweep GC freed 10385(751KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 5.007ms total 152.075ms
,11-17 18:30:44.689   734  1331 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=2868 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,11-17 18:30:44.728  2824  2824 D AndroidRuntime: Shutting down VM
,11-17 18:30:44.731  1390  2879 I MicrophoneInputStream: mic_starting gfk@2e4c9fed
,11-17 18:30:44.734  1390  2882 I HotwordRecognitionRnr: Starting hotword detection.
,11-17 18:30:44.744   183  2888 I AudioFlinger: AudioFlinger's thread 0xb3001000 ready to run
,11-17 18:30:44.753  1390  2879 I MicrophoneInputStream: mic_started gfk@2e4c9fed
,11-17 18:30:44.762   183  2888 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
,11-17 18:30:44.762   183  2888 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
,11-17 18:30:44.762   183  2888 D         : Failed to fetch the lookup information of the device 0000003E 
11-17 18:30:44.762   183  2888 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
11-17 18:30:44.762   183  2888 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,11-17 18:30:44.768   183  2888 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,11-17 18:30:44.781  1563  2876 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 56 ms
,11-17 18:30:44.788  2868  2868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,11-17 18:30:44.800  1563  2891 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
11-17 18:30:44.800  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:44.800  1563  1563 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:30:44.801  1563  2891 D AccountUtils: Clearing selected account for com.example.hello
,11-17 18:30:44.812  1563  1563 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:30:44.812  1563  1563 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 18:30:44.815  1563  2891 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:30:44.824  1267  1491 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,11-17 18:30:44.839  1563  2897 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,11-17 18:30:44.841  1563  2897 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,11-17 18:30:44.841  1563  2897 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
11-17 18:30:44.841  1563  2897 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,11-17 18:30:44.843  1348  1348 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-17 18:30:44.843  1348  1348 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 18:30:44.850  1563  2897 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
11-17 18:30:44.850  1563  2897 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,11-17 18:30:44.851  1563  2897 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:30:44.855  1390  1390 I HotwordWorker: onReady
,11-17 18:30:44.862  1563  2897 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,11-17 18:30:44.862  1563  2897 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-17 18:30:44.864  1563  2897 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,11-17 18:30:44.866  1563  2897 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
11-17 18:30:44.866  1563  2897 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
11-17 18:30:44.867  1563  2897 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,11-17 18:30:44.871  1267  1491 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:30:44.882  1563  2900 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:44.940   734  1097 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=2904 uid=10039 gids={50039, 9997} abi=armeabi-v7a
,11-17 18:30:44.941  1563  2900 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:30:44.952   734  1247 I ActivityManager: Killing 2144:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,11-17 18:30:44.966  1563  2891 I art     : Explicit concurrent mark sweep GC freed 32373(2MB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 21MB/36MB, paused 2.232ms total 73.978ms
,11-17 18:30:44.977  1563  2921 I GMPM-SVC: App measurement is starting up
,11-17 18:30:45.003   734   750 W libprocessgroup: failed to open /acct/uid_1000/pid_2144/cgroup.procs: No such file or directory
,11-17 18:30:45.009  1563  2924 I PeopleContactsSync: CP2 sync disabled
,11-17 18:30:45.010  1563  1616 I Icing   : doRemovePackageData com.example.hello
,11-17 18:30:45.045   734  1331 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,11-17 18:30:45.064  1563  2926 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/databases/DocList.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,11-17 18:30:45.091  2904  2904 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5221)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
11-17 18:30:45.091  2904  2904 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
,11-17 18:30:45.092  2904  2904 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
11-17 18:30:45.092  2904  2904 E AndroidRuntime: FATAL EXCEPTION: main
11-17 18:30:45.092  2904  2904 E AndroidRuntime: Process: com.android.documentsui, PID: 2904
11-17 18:30:45.092  2904  2904 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:144)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1355)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5221)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:899)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:694)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:367)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1372)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.jav,a:35)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2579)
11-17 18:30:45.092  2904  2904 E AndroidRuntime: 	... 9 more
,11-17 18:30:45.097  1267  1548 W OpenGLRenderer: Incorrectly called buildLayer on View: adg, destroying layer...
11-17 18:30:45.097  1267  1548 W OpenGLRenderer: Incorrectly called buildLayer on View: adg, destroying layer...
,11-17 18:30:45.113   734  1375 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=2930 uid=10007 gids={50007, 9997, 1028, 1015, 1023} abi=armeabi-v7a
,11-17 18:30:45.116   734   749 I ActivityManager: Killing 2231:com.google.android.youtube/u0a80 (adj 15): empty #17
,11-17 18:30:45.158   734  1279 W libprocessgroup: failed to open /acct/uid_10080/pid_2231/cgroup.procs: No such file or directory
,11-17 18:30:45.181   734  2949 D OpenGLRenderer: Render dirty regions requested: true
,11-17 18:30:45.181   734   823 D Atlas   : Validating map...
,11-17 18:30:45.193  1563  2896 W DriveInitializer: Awaiting to be initialized
,11-17 18:30:45.193  1563  2950 W DriveInitializer: Background init thread started
,11-17 18:30:45.194  1563  2950 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock154] disk I/O error
,11-17 18:30:45.218   171   171 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:30:45.218   171   171 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
11-17 18:30:45.218   171   171 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:30:45.218   171   171 E qdoverlay: MdpData failed to play
,11-17 18:30:45.218   171   171 E qdoverlay: == Dump MdpData start ==
11-17 18:30:45.218   171   171 E qdoverlay: == Dump OvFD fd=48 path=/dev/graphics/fb0 start/end ==
11-17 18:30:45.218   171   171 E qdoverlay: mOvData msmfb_overlay_data id=64
11-17 18:30:45.218   171   171 E qdoverlay: data msmfb_data offset=0 memid=37 id=0 flags=0x0 priv=0
11-17 18:30:45.218   171   171 E qdoverlay: == Dump MdpData end ==
11-17 18:30:45.218   171   171 E qdhwcomposer: draw: queueBuffer failed for display:0 
11-17 18:30:45.218   171   171 E qdhwcomposer: hwc_set_primary: MDPComp draw failed
11-17 18:30:45.218   171   171 E qdhwcomposer: display_commit: MSMFB_DISPLAY_COMMIT for primary failed
11-17 18:30:45.218   171   171 E qdhwcomposer: hwc_set_primary: display commit fail!
,11-17 18:30:45.220   734  2949 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
11-17 18:30:45.220   734  2949 I OpenGLRenderer: Initialized EGL, version 1.4
,11-17 18:30:45.224   734  2949 D OpenGLRenderer: Enabling debug mode 0
,11-17 18:30:45.233   171   171 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
11-17 18:30:45.233   171   171 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
11-17 18:30:45.234   171   171 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
11-17 18:30:45.234   171   171 E qdoverlay: src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
11-17 18:30:45.234   171   171 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:45.234   171   171 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:45.234   171   171 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x44000 id=64
11-17 18:30:45.234   171   171 E qdoverlay: src msmfb_img w=3200 h=1920 format=5 MDP_RGB_888
11-17 18:30:45.234   171   171 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:45.234   171   171 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
,11-17 18:30:45.234   171   171 E qdoverlay: Ctrl commit failed set overlay
11-17 18:30:45.234   171   171 E qdhwcomposer: configureLowRes: commit failed for low res panel
11-17 18:30:45.234   171   171 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
11-17 18:30:45.234   171   171 E qdoverlay: MdpCtrl failed to setOverlay, restoring last known good ov info
11-17 18:30:45.234   171   171 E qdoverlay: == Bad OVInfo is:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
11-17 18:30:45.234   171   171 E qdoverlay: src msmfb_img w=1152 h=1920 format=13 MDP_RGBA_8888
11-17 18:30:45.234   171   171 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:45.234   171   171 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=1920
11-17 18:30:45.234   171   171 E qdoverlay: == Last good known OVInfo is:  mdp_overlay z=2 fg=0 alpha=255 mask=-1 flags=0x60000 id=8
11-17 18:30:45.234   171   171 E qdoverlay: src msmfb_img w=1152 h=96 format=13 MDP_RGBA_8888
11-17 18:30:45.234   171   171 E qdoverlay: src_rect mdp_rect x=0 y=0 w=1080 h=75
11-17 18:30:45.234   171   171 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=1080 h=75
11-17 18:30:45.234   171   171 E qdoverlay: Ctrl commit failed set overlay
11-17 18:30:45.234   171   171 E qdhwcomposer: configure: commit fails
11-17 18:30:45.234   171   171 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
11-17 18:30:45.234   171   171 E qdoverlay: MdpCtrl close error in unset
```
