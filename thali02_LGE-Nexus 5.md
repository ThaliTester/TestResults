#### Test 503880191ec81a5_thali02_LGE-Nexus 5 Logs


```
--------- beginning of system
W/ResourcesManager( 2567): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2567): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
V/JNIHelp ( 2567): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 2567): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2567): Installed default security provider GmsCore_OpenSSL
E/YouTube MDX( 2567): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
W/ContextImpl( 1982): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
I/dex2oat ( 2608): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads553788447.jar --oat-fd=25 --oat-location=/data/data/com.google.android.youtube/cache/ads553788447.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/GAv4-SVC( 1574): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 1982): Thread[GAThread,5,main]: No campaign data found.
I/dex2oat ( 2608): dex2oat took 56.660ms (threads: 4)
I/Icing   ( 1574): Indexing 151DCA48A94F9E0802CE7932870A9D23A106FA10 from com.google.android.googlequicksearchbox
D/Icing   ( 1574): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1574): Indexing done 151DCA48A94F9E0802CE7932870A9D23A106FA10
W/InstanceID/Rpc( 2567): Found 10008
V/Babel   ( 1899): babel boot account: thalitester@gmail.com
I/ActivityManager(  760): Start proc com.google.android.apps.fitness for broadcast com.google.android.apps.fitness/.FitnessBootReceiver: pid=2680 uid=10045 gids={50045, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SQLiteLog( 1899): (284) automatic index on conversation_participants_view(conversation_id)
,W/VideoCapabilities( 1899): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1899): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 1899): Unrecognized profile 2130706433 for video/avc
E/SQLiteLog( 1899): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 1899): (284) automatic index on conversation_participants_view(conversation_id)
I/ActivityManager(  760): Killing 2037:com.qualcomm.timeservice/u0a76 (adj 15): empty #17
I/FitnessApp( 2680): Initializers took 0 milliseconds
W/libprocessgroup(  760): failed to open /acct/uid_10076/pid_2037/cgroup.procs: No such file or directory
I/ActivityManager(  760): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=2701 uid=10070 gids={50070, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  760): Killing 2140:com.android.keychain/1000 (adj 15): empty #17
D/AndroidRuntime( 2698): 
D/AndroidRuntime( 2698): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 2698): CheckJNI is OFF
W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2140/cgroup.procs: No such file or directory
D/AndroidRuntime( 2698): Calling main entry com.android.commands.am.Am
I/ActivityManager(  760): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 2698): Shutting down VM
I/ActivityManager(  760): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2734 uid=10278 gids={50278, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MicrophoneInputStream( 1344): mic_close gfk@d4d7351
D/audio_hw_primary(  183): disable_audio_route: reset and update mixer path: audio-record
D/audio_hw_primary(  183): disable_snd_device: snd_device(55: voice-rec-mic)
I/HotwordRecognitionRnr( 1344): Hotword detection finished
I/HotwordRecognitionRnr( 1344): Stopping hotword detection.
I/WebViewFactory( 2734): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 2734): Time to load native libraries: 1 ms (timestamps 7893-7894)
I/LibraryLoader( 2734): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 2734): Binding Chromium to main looper Looper (main, tid 1) {3cf29f3}
I/LibraryLoader( 2734): Expected native library version number "",actual native library version number ""
I/chromium( 2734): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2734): Initializing chromium process, singleProcess=true
W/art     ( 2734): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 2734): ApplicationContext is null in ApplicationStatus
D/ActivityThread( 2701): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/Gmail   ( 2701): getAccountsCursor
,W/chromium( 2734): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/libEGL  ( 2734): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 2734): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 2734): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae0cd2:true
,W/art     ( 2734): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 2734): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 2734): CordovaWebView is running on device made by: LGE
,W/art     ( 2734): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 2734): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 2734): Render dirty regions requested: true
,D/Atlas   ( 2734): Validating map...
,W/chromium( 2734): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  760): Explicit concurrent mark sweep GC freed 27984(1261KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 926us total 54.472ms
,I/ActivityManager(  760): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=2800 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SurfaceFlinger(  171): shader cache generated - 24 shaders in 144.560623 ms
,I/OpenGLRenderer( 2734): Initialized EGL, version 1.4
,D/OpenGLRenderer( 2734): Enabling debug mode 0
,W/GAV2    ( 2701): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  760): Displayed com.example.hello/.MainActivity: +667ms (total +15s532ms)
,I/Keyboard.Facilitator( 1069): onFinishInput()
,W/BindingManager( 2734): Cannot call determinedVisibility() - never saw a connection for the pid: 2734
,I/Gmail   ( 2701): getAccountsCursor
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/chromium( 2734): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/ActivityManager(  760): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2838 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/JsMessageQueue( 2734): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/AndroidProtocolHandler( 2734): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/SQLiteLog( 2701): (283) recovered 89 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,D/jxcore_app_log( 2734): JniHelper::setJavaVM(0xb505c280), pthread_self() = -1257332480
,D/JX-Cordova( 2734): jxcore cordova android initializing
,W/ActivityManager(  760): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Exchange( 2800): EasService.onCreate
,I/Gmail   ( 2701): Observing account changes for notifications
,I/Exchange( 2800): RestartPingTask
,I/Exchange( 2800): RestartPingsTask did not start any pings.
,I/Exchange( 2800): PSS stopIfIdle
I/Exchange( 2800): PSS has no active accounts; stopping service.
,E/ActivityThread( 2701): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@268be4d4 that was originally bound here
E/ActivityThread( 2701): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@268be4d4 that was originally bound here
E/ActivityThread( 2701): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1072)
E/ActivityThread( 2701): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:966)
E/ActivityThread( 2701): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1768)
E/ActivityThread( 2701): 	at android.app.ContextImpl.bindService(ContextImpl.java:1751)
E/ActivityThread( 2701): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 2701): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 2701): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 2701): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 2701): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 2701): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 2701): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 2701): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 2701): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 2701): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 2701): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 2701): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/a       ( 2701): RuntimeException when trying to unbind from service
E/a       ( 2701): java.lang.IllegalArgumentException: Service not registered: com.android.emailcommon.service.am@268be4d4
E/a       ( 2701): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1024)
E/a       ( 2701): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1802)
E/a       ( 2701): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
E/a       ( 2701): 	at com.android.emailcommon.service.an.a(SourceFile:124)
E/a       ( 2701): 	at com.android.emailcommon.service.an.doInBackground(SourceFile:111)
E/a       ( 2701): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/a       ( 2701): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/a       ( 2701): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/a       ( 2701): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/a       ( 2701): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/a       ( 2701): 	at java.lang.Thread.run(Thread.java:818)
,I/Exchange( 2800): onDestroy
I/ActivityManager(  760): Killing 2167:com.google.android.dialer/u0a10 (adj 15): empty #17
,W/jxcore-log( 2734): Initializing JXcore engine
W/jxcore-log( 2734): JXcore engine is ready
,W/jxcore-log( 2734): Starting JXcore engine
,I/Gmail   ( 2701): notifyAccountChanged
,I/Gmail   ( 2701): getAccountsCursor
,I/Gmail   ( 2701): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2701): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 2701): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 2701): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  760): failed to open /acct/uid_10010/pid_2167/cgroup.procs: No such file or directory
,W/m.example.hello( 2734): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8096]" dev="sockfs" ino=8096 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2734): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3033 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,W/m.example.hello( 2734): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6607]" dev="sockfs" ino=6607 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 2734): type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[18635]" dev="sockfs" ino=18635 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Killing 2255:com.google.android.onetimeinitializer/u0a12 (adj 15): empty #17
,W/jxcore-log( 2734): Platform android
W/jxcore-log( 2734): 
W/jxcore-log( 2734): Process ARCH arm
W/jxcore-log( 2734): 
,W/libprocessgroup(  760): failed to open /acct/uid_10012/pid_2255/cgroup.procs: No such file or directory
,I/jxcore-log( 2734): JXcore Cordova bridge is ready!
I/jxcore-log( 2734): 
W/jxcore-log( 2734): JXcore engine is started
,E/jxcore-log( 2734): >> LGE-Nexus 5
E/jxcore-log( 2734): 
,I/jxcore-log( 2734): Total memory 1946181632
I/jxcore-log( 2734): 
I/jxcore-log( 2734): Free memory 317718528
I/jxcore-log( 2734): 
,I/jxcore-log( 2734): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2734): 
I/jxcore-log( 2734): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2734): 
,I/jxcore-log( 2734): userPath [ 'www' ]
I/jxcore-log( 2734): 
,I/jxcore-log( 2734): Size 1080 1776
I/jxcore-log( 2734): 
,I/jxcore-log( 2734): Screen Brightness 82
I/jxcore-log( 2734): 
E/jxcore-log( 2734): Dummy Error Log.
E/jxcore-log( 2734): 
,D/Finsky  ( 2838): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 2701): getAccountsCursor
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 2838): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 2838): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2838): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Volley  ( 2838): [261] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 2838): [268] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager(  760): Killing 2322:com.android.managedprovisioning/u0a14 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10014/pid_2322/cgroup.procs: No such file or directory
I/SystemBroadcastReceiver( 1069): Boot has been completed
,I/SystemBroadcastReceiver( 1069): toggleAppIcon() : FLAG_SYSTEM = true
,D/Ads     ( 2838): Skipping gmscore version check
D/Finsky  ( 2838): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2838): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 2838): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 2838): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/UserPresentBroadcastReceiver( 1604): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/ActivityManager(  760): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=2904 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/ActivityManager(  760): Killing 2017:com.android.providers.calendar/u0a2 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10002/pid_2017/cgroup.procs: No such file or directory
,D/WifiService(  760): New client listening to asynchronous messages
,D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  760): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=2924 uid=10003 gids={50003, 9997} abi=armeabi-v7a
,I/jxcore-log( 2734): getBuffer is called!!!!
I/jxcore-log( 2734): 
,D/CellBroadcastReceiver( 2924): onReceive Intent { act=android.intent.action.SERVICE_STATE flg=0x10 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/CellBroadcastReceiver( 2924): Intent ACTION_SERVICE_STATE_CHANGED
,D/CellBroadcastReceiver( 2924): Service state changed! 3 Full: 3 3 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=false Current state=-1
,I/ActivityManager(  760): Killing 2378:com.google.android.configupdater/u0a36 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10036/pid_2378/cgroup.procs: No such file or directory
,D/SIP     ( 1196): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,W/ContextImpl( 2904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/BluetoothManagerService(  760): Message: 20
D/BluetoothManagerService(  760): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4eff751:true
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2125): getBluetoothService() called with no BluetoothManagerCallback
,D/LocalBluetoothProfileManager( 2904): Adding local A2DP profile
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2904): Adding local HEADSET profile
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2904): Adding local MAP profile
,D/BluetoothMap( 2904): Create BluetoothMap proxy object
,D/BluetoothManagerService(  760): Message: 30
,D/BluetoothManagerService(  760): Message: 30
,D/LocalBluetoothProfileManager( 2904): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 2904): finishStartingService: stopping service
,D/BluetoothA2dp( 2904): Proxy object connected
,D/A2dpProfile( 2904): Bluetooth service connected
,D/BluetoothHeadset( 2904): Proxy object connected
D/HeadsetProfile( 2904): Bluetooth service connected
,D/BluetoothInputDevice( 2904): Proxy object connected
,D/HidProfile( 2904): Bluetooth service connected
,D/BluetoothPan( 2904): BluetoothPAN Proxy object connected
,D/PanProfile( 2904): Bluetooth service connected
,D/BluetoothMap( 2904): Proxy object connected
D/MapProfile( 2904): Bluetooth service connected
D/BluetoothMap( 2904): getConnectedDevices()
,V/BluetoothMapService( 2125): getConnectedDevices()
,D/BluetoothPbap( 2904): Proxy object connected
D/PbapServerProfile( 2904): Bluetooth service connected
D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/ActivityManager(  760): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=2950 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 2125): getBluetoothService() called with no BluetoothManagerCallback
I/BtOppRfcommListener( 2125): Accept thread started.
,I/MusicStore( 2950): Database version: 120
,I/art     (  760): Explicit concurrent mark sweep GC freed 9888(502KB) AllocSpace objects, 2(36KB) LOS objects, 33% free, 27MB/41MB, paused 996us total 77.621ms
,I/GAV2    ( 1344): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 2950): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 2950): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 2950): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 2950): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 2950): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10456c59: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 2950): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 2950): GMSCore installation verified
,I/ConfigStore( 2950): Config Database version: 1
,I/MediaRouter( 2950): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=11, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 2950): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 2950): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 2950): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 2950): Using platform SSLCertificateSocketFactory
,D/WearableService( 1604): callingUid 10008, callindPid: 1604
,E/WifiStateMachine(  760): WifiStateMachine CMD_START_SCAN source -2 txSuccessRate=36.19 rxSuccessRate=34.44 targetRoamBSSID=c0:ff:d4:d3:aa:4a RSSI=-50
E/WifiStateMachine(  760): WifiStateMachine starting scan for "NG7005g"WPA_PSK with 2412,5220
,I/wpa_supplicant( 1080): wlan0: CTRL-EVENT-SCAN-STARTED 
,I/MusicLeanback( 2950): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 2950): Stop autocaching.
,I/ActivityManager(  760): Start proc com.android.musicfx for broadcast com.android.musicfx/.Compatibility$Receiver: pid=2999 uid=10015 gids={50015, 9997, 3003, 3002} abi=armeabi-v7a
,I/art     (  194): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 176us total 8.149ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.804ms
,I/art     (  194): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 167us total 7.425ms
,E/GmsUtils( 2950): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
E/GmsUtils( 2950): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/UpdateIcingCorporaServi( 1344): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PackageBroadcastService( 1574): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1574): Loading module APK com.google.android.play.games
,I/MediaStoreImporter( 2950): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  760): Killing 1532:com.google.android.keep/u0a71 (adj 15): empty #17
,I/UpdateIcingCorporaServi( 1344): UpdateCorporaTask done [took 23 ms] updated apps [took 23 ms] 
,W/libprocessgroup(  760): failed to open /acct/uid_10071/pid_1532/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Killing 2469:com.lge.SprintHiddenMenu/1000 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_1000/pid_2469/cgroup.procs: No such file or directory
,I/ActivityManager(  760): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,I/ActivityManager(  760): Resuming delayed broadcast
,D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1574): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1574): Submit a task: k
,D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1574): Processing package: com.example.hello
,D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/GassUtils( 1574): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 1574): Found info for package com.example.hello in db.
,I/ActivityManager(  760): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3045 uid=10040 gids={50040, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,W/BaseAppContext( 1574): Using Auth Proxy for data requests.
W/BaseAppContext( 1574): Using Auth Proxy for data requests.
,I/art     ( 1604): Explicit concurrent mark sweep GC freed 40631(2MB) AllocSpace objects, 35(560KB) LOS objects, 39% free, 21MB/36MB, paused 958us total 44.631ms
,I/PeopleDatabaseHelper( 1574): cleanUpNonGplusAccounts done.
,I/art     ( 1474): Explicit concurrent mark sweep GC freed 3200(131KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/21MB, paused 351us total 11.227ms
,W/BaseAppContext( 1574): Using Auth Proxy for data requests.
,I/art     ( 1574): Explicit concurrent mark sweep GC freed 33885(2MB) AllocSpace objects, 25(400KB) LOS objects, 24% free, 21MB/28MB, paused 533us total 46.068ms
,W/BaseAppContext( 1574): Using Auth Proxy for data requests.
,W/BaseAppContext( 1574): Using Auth Proxy for data requests.
W/BaseAppContext( 1574): Using Auth Proxy for data requests.
,W/BaseAppContext( 1574): Using Auth Proxy for data requests.
,D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1574): Module APK com.google.android.play.games already loaded
I/GAv4    ( 3045): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 3045):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 3045):   adb logcat -s GAv4
,W/GAv4    ( 3045): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3045): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 3045): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 3045): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.35
,E/SQLiteLog( 3045): (283) recovered 24 frames from WAL file /data/data/com.google.android.apps.docs/databases/DocList.db-wal
,D/Finsky  ( 2838): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,I/ActivityManager(  760): Killing 2328:com.google.android.videos/u0a77 (adj 15): empty #17
,W/ResourcesManager( 3045): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3045): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  760): failed to open /acct/uid_10077/pid_2328/cgroup.procs: No such file or directory
,W/GCoreFlp( 1604): No location to return for getLastLocation()
W/FusedLocationProvider( 1604): location=null
,V/JNIHelp ( 3045): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/GCM     ( 1604): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/System  ( 3045): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3045): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1604): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  760): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=3123 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 1574): Indexing BC4F6C1F86EB04EF66858206009B317E84123D05 from com.google.android.gms
,I/art     (  760): Explicit concurrent mark sweep GC freed 14582(739KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 878us total 50.408ms
,W/ResourcesManager( 3123): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Icing   ( 1574): Indexing done BC4F6C1F86EB04EF66858206009B317E84123D05
W/ResourcesManager( 1899): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1899): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CalendarProvider2( 3123): Created com.android.providers.calendar.CalendarAlarmManager@23504462(com.android.providers.calendar.CalendarProvider2@3cf29f3)
,V/JNIHelp ( 1899): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/SQLiteLog( 3123): (284) automatic index on view_events(_id)
,W/System  ( 1899): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 1899): Installed default security provider GmsCore_OpenSSL
,I/CalendarProvider2( 3123): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3123): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/GAV2    ( 2701): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  760): Killing 2567:com.google.android.youtube/u0a80 (adj 15): empty #17
,D/BluetoothManagerService(  760): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  760): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@242e2335 mBinding = false
,W/libprocessgroup(  760): failed to open /acct/uid_10080/pid_2567/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  760): Message: 2
,D/BluetoothManagerService(  760): Sending off request.
,D/BluetoothAdapterState( 2125): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2125): Setting state to 13
I/BluetoothAdapterState( 2125): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterProperties( 2125): onBluetoothDisable()
,I/BluetoothAdapterState( 2125): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,D/BluetoothAdapterProperties( 2125): Scan Mode:20
,D/BluetoothAdapterState( 2125): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,V/BluetoothMapMasInstance( 2125): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2125): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:512)
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:489)
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:399)
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2125): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2125): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,E/BtOppRfcommListener( 2125): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/btif_config_util( 2125): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,W/bt-btif ( 2125): bta_dm_disable BTA_DISABLE_DELAY set to 100 ms
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  760): Bluetooth State Change Intent: 12 -> 13
,W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
,D/BluetoothMapService( 2125): onReceive
D/BluetoothMapService( 2125): STATE_TURNING_OFF
V/BluetoothMapService( 2125): Handler(): got msg=4
D/BluetoothMapService( 2125): MAP Service closeService in
D/BluetoothMapMasInstance( 2125): MAP Service shutdown
,V/BluetoothMapService( 2125): MAP Service closeService out
,I/BtOppRfcommListener( 2125): stopping Accept Thread
,I/BtOppRfcommListener( 2125): BluetoothSocket listen thread finished
,D/WifiService(  760): New client listening to asynchronous messages
,D/WifiService(  760): setWifiEnabled: false pid=2734, uid=10278
E/WifiService(  760): Invoking mWifiStateMachine.setWifiEnabled
,W/ContextImpl( 2904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,E/WifiStateMachine(  760): WifiStateMachine: Leaving Connected state
,I/jxcore-log( 2734): ****TEST TOOK:  5130  ms ****
I/jxcore-log( 2734): 
,I/jxcore-log( 2734): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2734): 
,E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
D/CommandListener(  179): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1604): Read error: ssl=0xaffc5e00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1604): SSL shutdown failed: ssl=0xaffc5e00: I/O error during system call, Broken pipe
,D/ConnectivityService(  760): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10008
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): ValidatedState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=0 what=532488 arg1=10008 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Checking http://clients3.google.com/generate_204 on "NG7005g"
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/DockEventReceiver( 2904): finishStartingService: stopping service
,D/BluetoothPbap( 2904): Proxy object disconnected
D/PbapServerProfile( 2904): Bluetooth service disconnected
D/bt_userial( 2125): RX termination
W/bt_userial( 2125): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 2125): Leaving userial_read_thread()
W/bt-btif ( 2125): ag scb idx 1 not allocated
E/bt-btif ( 2125): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2125): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_userial( 2125): userial_close_reader Joined userial reader thread: 0
D/bt_hwcfg( 2125): hw_epilog_process
E/WifiConfigStore(  760): saveWifiConfigBSSID Setting BSSID for "NG7005g"WPA_PSK to any
I/bt_userial_vendor( 2125): device fd = 53 close
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  760): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
I/GKI_LINUX( 2125): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2125): GKI_exit_task 0 done
I/GKI_LINUX( 2125): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 2125): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
E/WifiStateMachine(  760): scanCount==0 - aborting
D/WifiScanningService(  760): SCAN_AVAILABLE : 1
D/RttService(  760): SCAN_AVAILABLE : 1
D/RttService(  760): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiScanningService(  760): StartedState got{ when=-13ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService(  760): DefaultState
,D/WifiNetworkAgent(  760): NetworkAgent: NetworkAgent channel lost
D/HeadsetService( 2125): Received stop request...Stopping profile...
,D/ConnectivityService(  760): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/BluetoothAdapterService( 2125): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22ef16b0
D/ConnectivityManager.CallbackHandler(  898): CM callback handler got msg 524292
D/Nat464Xlat(  760): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/CSLegacyTypeTracker(  760): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/HeadsetStateMachine( 2125): Exit Disconnected: -1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  760): Disconnected - quitting
D/CommandListener(  179): Clearing all IP addresses on wlan0
D/BluetoothHeadset( 1155): Proxy object disconnected
D/ConnectivityManager.CallbackHandler( 1574): CM callback handler got msg 524292
D/BluetoothHeadset(  760): Proxy object disconnected
D/BluetoothHeadset( 1155): Proxy object disconnected
D/BluetoothHeadset( 1196): Proxy object disconnected
D/BluetoothAdapterState( 2125): Stopping profile services that were post enabled
,D/A2dpService( 2125): Received stop request...Stopping profile...
D/ConnectivityService(  760): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityService(  760): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/BluetoothAdapterService( 2125): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22ef16b0
,D/A2dpStateMachine( 2125): Exit Disconnected: -1
D/TelephonyNetworkFactory( 1196): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/BluetoothHeadset( 2904): Proxy object disconnected
D/HeadsetProfile( 2904): Bluetooth service disconnected
,D/BluetoothA2dp(  760): Proxy object disconnected
,D/HidService( 2125): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2125): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22ef16b0
,D/BluetoothA2dp( 2904): Proxy object disconnected
D/A2dpProfile( 2904): Bluetooth service disconnected
,D/BluetoothInputDevice( 2904): Proxy object disconnected
D/HidProfile( 2904): Bluetooth service disconnected
,D/HealthService( 2125): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2125): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22ef16b0
,D/PanService( 2125): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 2125): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22ef16b0
,D/BluetoothPan( 2904): BluetoothPAN Proxy object disconnected
D/PanProfile( 2904): Bluetooth service disconnected
,D/BtGatt.DebugUtils( 2125): handleDebugAction() action=null
,D/BtGatt.GattService( 2125): Received stop request...Stopping profile...
D/BtGatt.GattService( 2125): stop()
D/BtGatt.AdvertiseManager( 2125): advertise clients cleared
,D/BluetoothAdapterService( 2125): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22ef16b0
,D/HeadsetStateMachine( 2125): Unbinding service...
,W/BluetoothHeadsetServiceJni( 2125): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2125): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothMapService( 2125): Received stop request...Stopping profile...
D/BluetoothMapService( 2125): stop()
,D/BluetoothMapEmailAppObserver( 2125): deinitObservers()
,D/BluetoothMapEmailAppObserver( 2125): removeReceiver()
D/BluetoothAdapterService( 2125): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22ef16b0
,I/GKI_LINUX( 2125): gki_task task_id=2 [A2DP-MEDIA] terminating
,I/GKI_LINUX( 2125): GKI_exit_task 2 done
I/GKI_LINUX( 2125): GKI_shutdown(): task [A2DP-MEDIA] terminated
,W/BluetoothHidServiceJni( 2125): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2125): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2125): Cleaning up Bluetooth GID callback object
,W/BluetoothHealthServiceJni( 2125): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2125): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 2125): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2125): Cleaning up Bluetooth PAN callback object
,D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/BluetoothMapService( 2125): Handler(): got msg=4
D/BluetoothMapService( 2125): MAP Service closeService in
V/BluetoothMapService( 2125): MAP Service closeService out
D/BluetoothMapService( 2125): cleanup()
D/BluetoothMapService( 2125): MAP Service closeService in
V/BluetoothMapService( 2125): MAP Service closeService out
D/BluetoothAdapterState( 2125): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2125): Setting state to 10
I/BluetoothAdapterState( 2125): Bluetooth adapter state changed: 13-> 10
,D/BluetoothManagerService(  760): Message: 60
D/BluetoothManagerService(  760): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 2125): Entering OffState
D/BluetoothManagerService(  760): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset( 1196): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  760): onBluetoothStateChange: up=false
,D/BluetoothMap( 2904): Proxy object disconnected
D/MapProfile( 2904): Bluetooth service disconnected
D/BluetoothA2dp( 2904): onBluetoothStateChange: up=false
,D/BluetoothMap( 2904): onBluetoothStateChange: up=false
,D/BluetoothHeadset(  760): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 2904): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1155): onBluetoothStateChange: up=false
,D/BluetoothPbap( 2904): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1155): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 2904): onBluetoothStateChange: up=false
,D/BluetoothManagerService(  760): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  760): Broadcasting onBluetoothServiceDown() to 9 receivers.
,D/BluetoothManagerService(  760): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@242e2335 mBinding = false
,D/BluetoothManagerService(  760): Sending unbind request.
,D/BluetoothManagerService(  760): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapter(  898): 774196157: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter(  898): 774196157: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter(  898): 774196157: getState() :  mService = null. Returning STATE_OFF
,I/GKI_LINUX( 2125): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 2125): GKI_exit_task 1 done
,I/GKI_LINUX( 2125): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2125): cleanupNative: return from cleanup
,D/BluetoothAdapter( 1604): 617225887: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1604): 617225887: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 2125): System.exit called, status: 0
I/AndroidRuntime( 2125): VM exiting with result code 0, cleanup skipped.
,I/wpa_supplicant( 1080): p2p0: CTRL-EVENT-TERMINATING 
,I/ActivityManager(  760): Start proc com.google.android.keep for broadcast com.google.android.keep/.notification.AlertReceiver: pid=3194 uid=10071 gids={50071, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/wpa_supplicant( 1080): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:4a reason=3 locally_generated=1
,D/AndroidRuntime( 3183): 
D/AndroidRuntime( 3183): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 3183): CheckJNI is OFF
,I/ActivityManager(  760): Process com.android.bluetooth (pid 2125) has died
,D/AndroidRuntime( 3183): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  760): Force stopping com.example.hello appid=10278 user=-1: uninstall pkg
I/ActivityManager(  760): Killing 2734:com.example.hello/u0a278 (adj 0): stop com.example.hello
,I/WindowState(  760): WIN DEATH: Window{30ef4e82 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  760): Client connection lost with reason: 4
,W/PackageSettings(  760): Skipping PackageSetting{8fd644 com.test.thalitest/10270} due to missing metadata
,D/Tethering(  760): InitialState.processMessage what=4
I/wpa_supplicant( 1080): wlan0: CTRL-EVENT-TERMINATING 
,E/libprocessgroup(  760): failed to kill 1 processes for processgroup 2734
W/ActivityManager(  760): Force removing ActivityRecord{3abe6a3b u0 com.example.hello/.MainActivity t214}: app died, no saved state
,W/ActivityManager(  760): Spurious death for ProcessRecord{31e4e296 2734:com.example.hello/u0a278}, curProc for 2734: null
,D/Tethering(  760): sendTetherStateChangedBroadcast 0, 0, 0
,W/Settings( 1899): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  760): Force stopping com.example.hello appid=10278 user=0: pkg removed
W/Settings( 1604): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Keyboard.Facilitator( 1069): resetDictionaries() : en_US
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1604): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator.DecoderInitializer( 1069): run()
,I/Decoder ( 1069): createOrResetDecoder
,I/ConfigService( 1604): onCreate
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  760): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  760): removeObsoleteFile: deleting file=214_task.xml
W/InputMethodManagerService(  760): Got RemoteException sending setActive(false) notification to pid 2734 uid 10278
I/Keyboard.Facilitator( 1069): onFinishInput()
,I/MicrophoneInputStream( 1344): mic_starting gfk@4848c68
,I/HotwordRecognitionRnr( 1344): Starting hotword detection.
I/AudioFlinger(  183): AudioFlinger's thread 0xb48b7000 ready to run
,I/MicrophoneInputStream( 1344): mic_started gfk@4848c68
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1069): run()
,D/audio_hw_primary(  183): select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
D/msm8974_platform(  183): platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
D/        (  183): Failed to fetch the lookup information of the device 0000003E 
E/ACDB-LOADER(  183): Error: ACDB AudProc vol returned = -19
,D/audio_hw_primary(  183): enable_snd_device: snd_device(55: voice-rec-mic)
,D/audio_hw_primary(  183): enable_audio_route: apply and update mixer path: audio-record
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1069): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1069): run() : Missing File = Personal.en_US.dict
,I/Keyboard.Facilitator.PersonalDictionaryLoader( 1069): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1069): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1069): run()
I/StatsUtilsManager( 1069): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1069): shouldRecordStats() = Too Soon
,I/art     (  760): Explicit concurrent mark sweep GC freed 28685(1658KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 1.301ms total 160.613ms
,W/ResourcesManager( 1254): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/HotwordWorker( 1344): onReady
,W/ResourcesManager( 1254): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/AndroidRuntime( 3183): Shutting down VM
,I/ActivityManager(  760): Killing 2068:com.google.android.deskclock/u0a38 (adj 15): empty #17
,W/libprocessgroup(  760): failed to open /acct/uid_10038/pid_2068/cgroup.procs: No such file or directory
,W/ContextImpl( 2904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,I/ActivityManager(  760): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=3243 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,D/DockEventReceiver( 2904): finishStartingService: stopping service
,I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
I/InputReader(  760): Reconfiguring input devices.  changes=0x00000010
,I/iu.UploadsManager( 1574): End new media; added: 0, uploading: 0, time: 94 ms
,W/ResourcesManager( 3243): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,D/AdapterServiceConfig( 3243): Adding HeadsetService
,D/AdapterServiceConfig( 3243): Adding A2dpService
D/AdapterServiceConfig( 3243): Adding HidService
,D/AdapterServiceConfig( 3243): Adding HealthService
D/AdapterServiceConfig( 3243): Adding PanService
D/AdapterServiceConfig( 3243): Adding GattService
,D/AdapterServiceConfig( 3243): Adding BluetoothMapService
,D/BluetoothAdapter( 2904): 681354653: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  760): Killing 2800:com.google.android.gm.exchange/u0a69 (adj 15): empty #17
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.videos flg=0x4000010 (has extras) }
,W/libprocessgroup(  760): failed to open /acct/uid_10069/pid_2800/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1604): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/BluetoothAdapter( 2904): 681354653: getState() :  mService = null. Returning STATE_OFF
,D/BackupManagerService(  760): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  760): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  760): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/VoicemailCleanupService( 1290): Cleaning up data for package: com.example.hello
,I/UpdateIcingCorporaServi( 1344): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
V/BackupManagerService(  760): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  760): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@20306b29
,W/Launcher( 1254): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@22ef16b0 new=com.google.android.velvet.VelvetApplication@22ef16b0
,I/ActivityManager(  760): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=3269 uid=1000 gids={41000, 9997, 1028, 1015, 3002, 3001, 3003} abi=armeabi-v7a
,I/GCoreNlp( 1604): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ContextImpl( 3269): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1686 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2579 
,E/SQLiteDatabase( 3269): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 3269): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 3269): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 3269): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 3269): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 3269): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 3269): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 3269): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3269): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3269): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 3269): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 3269): Process: com.android.keychain, PID: 3269
E/AndroidRuntime( 3269): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 3269): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/AndroidRuntime( 3269): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 3269): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 3269): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 3269): 	at com.android.keychain.KeyChainService.onHandleI,ntent(KeyChainService.java:396)
E/AndroidRuntime( 3269): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3269): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 3269): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PackageBroadcastService( 1574): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1574): Clearing selected account for com.example.hello
I/UpdateIcingCorporaServi( 1344): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1574): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1574): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1574): Module APK com.google.android.play.games already loaded
E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  760): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  760): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  760): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  760): 	... 5 more
E/SQLiteLog( 1574): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 1574): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1574): Process: com.google.android.gms, PID: 1574
E/AndroidRuntime( 1574): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1574): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1574): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1574): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1574): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1574): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1574): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/AndroidRuntime( 1574): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1574): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1574): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1574): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/AndroidRuntime( 1574): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/AndroidRuntime( 1574): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1574): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1574): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1574): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1574): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1574): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1574): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1254): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
W/OpenGLRenderer( 1254): Incorrectly called buildLayer on View: adg, destroying layer...
W/OpenGLRenderer( 1254): Incorrectly called buildLayer on View: adg, destroying layer...
E/SQLiteLog( 1604): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 1604): Shutting down VM
E/SQLiteLog( 1574): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/OpenGLRenderer(  760): Render dirty regions requested: true
D/Atlas   (  760): Validating map...
,I/LocationSettingsChecker( 1574): Removing dialog suppression flag for package com.example.hello
E/DropBoxManagerService(  760): Can't write: system_app_crash
E/DropBoxManagerService(  760): java.io.FileNotFoundException: /data/system/dropbox/drop97.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  760): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  760): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  760): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  760): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12006)
E/DropBoxManagerService(  760): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  760): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  760): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  760): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  760): 	... 5 more
E/qdhwcomposer(  171): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  171): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  171): MdpData failed to play
E/qdoverlay(  171): == Dump MdpData start ==
E/qdoverlay(  171): == Dump OvFD fd=29 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  171): mOvData msmfb_overlay_data id=64
E/qdoverlay(  171): data msmfb_data offset=0 memid=41 id=0 flags=0x0 priv=0
E/qdoverlay(  171): == Dump MdpData end ==
E/qdhwcomposer(  171): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  171): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  171): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  171): hwc_set_primary: display commit fail!
E/SQLiteDatabase( 1574): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/SQLiteDatabase( 1574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1574): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1574): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1574): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1574): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1574): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 1574): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1574): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1142)
E/PhenotypeInitializer( 1574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1574): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1574): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1574): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1574): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1574): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1574): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1574): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/qdhwcomposer(  171): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
E/qdhwcomposer(  171): hwc_sync: acq_fen_fd_cnt=4 flags=0 fd=13 dpy=0 numHwLayers=5
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  171): MdpData failed to play
E/qdoverlay(  171): == Dump MdpData start ==
E/qdoverlay(  171): == Dump OvFD fd=29 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  171): mOvData msmfb_overlay_data id=64
E/qdoverlay(  171): data msmfb_data offset=0 memid=41 id=0 flags=0x0 priv=0
E/qdoverlay(  171): == Dump MdpData end ==
E/qdhwcomposer(  171): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  171): hwc_set_primary: MDPComp draw failed
E/qdhwcomposer(  171): display_commit: MSMFB_DISPLAY_COMMIT for primary failed
E/qdhwcomposer(  171): hwc_set_primary: display commit fail!
W/BaseAppContext( 1574): Using Auth Proxy for data requests.
W/BaseAppContext( 1574): Using Auth Proxy for data requests.
I/Adreno-EGL(  760): <qeglDrvAPI_eglInitialize:410>: QUALCOMM Build: 10/24/14, 167c270, I68fa98814b
I/OpenGLRenderer(  760): Initialized EGL, version 1.4
D/OpenGLRenderer(  760): Enabling debug mode 0
E/qdoverlay(  171): Failed to call ioctl MSMFB_OVERLAY_SET err=Operation not permitted
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

```
