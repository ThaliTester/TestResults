#### Test 50242285576d0b0_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  319): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5022): 
D/AndroidRuntime( 5022): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5022): CheckJNI is OFF
D/AndroidRuntime( 5022): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5041 uid=10353 gids={50353, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5022): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5041): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5041): Time to load native libraries: 3 ms (timestamps 7344-7347)
I/LibraryLoader( 5041): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5041): Binding Chromium to main looper Looper (main, tid 1) {220b9c08}
I/LibraryLoader( 5041): Expected native library version number "",actual native library version number ""
I/chromium( 5041): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5041): Initializing chromium process, singleProcess=true
W/art     ( 5041): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5041): ApplicationContext is null in ApplicationStatus
W/chromium( 5041): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5041): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5041): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5041): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5041): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5041): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5041): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5041): Local Branch: 
I/Adreno-EGL( 5041): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5041): Local Patches: NONE
I/Adreno-EGL( 5041): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27963fac:true
D/BluetoothAdapter( 5041): 5281874: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  883): Activity pause timeout for ActivityRecord{28bf5781 u0 com.example.hello/.MainActivity t3}
W/art     ( 5041): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5041): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5041): CordovaWebView is running on device made by: motorola
W/art     ( 5041): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5041): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5041): Render dirty regions requested: true
D/Atlas   ( 5041): Validating map...
W/chromium( 5041): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5041): Initialized EGL, version 1.4
D/OpenGLRenderer( 5041): Enabling debug mode 0
I/Keyboard.Facilitator( 1408): onFinishInput()
I/LaunchCheckinHandler(  883): Displayed com.example.hello/.MainActivity,cp,ca,868
I/ActivityManager(  883): Displayed com.example.hello/.MainActivity: +798ms (total +868ms)
W/IInputConnectionWrapper( 5041): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 5041): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5041): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5041): Cannot call determinedVisibility() - never saw a connection for the pid: 5041
,I/chromium( 5041): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5041): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5041): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5041): JniHelper::setJavaVM(0xb8baa310), pthread_self() = -1191986064
D/JX-Cordova( 5041): jxcore cordova android initializing
,W/jxcore-log( 5041): Initializing JXcore engine
W/jxcore-log( 5041): JXcore engine is ready
,W/jxcore-log( 5041): Starting JXcore engine
,W/m.example.hello( 5041): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10353 path="socket:[6484]" dev="sockfs" ino=6484 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5041): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10353 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3091 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5041): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10353 path="socket:[6592]" dev="sockfs" ino=6592 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5041): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10353 path="socket:[22054]" dev="sockfs" ino=22054 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5041): Platform android
W/jxcore-log( 5041): 
,W/jxcore-log( 5041): Process ARCH arm
W/jxcore-log( 5041): 
,I/jxcore-log( 5041): JXcore Cordova bridge is ready!
I/jxcore-log( 5041): 
W/jxcore-log( 5041): JXcore engine is started
,E/jxcore-log( 5041): >> motorola-XT1072
E/jxcore-log( 5041): 
,I/jxcore-log( 5041): Total memory 916258816
I/jxcore-log( 5041): 
,I/jxcore-log( 5041): Free memory 34476032
I/jxcore-log( 5041): 
I/jxcore-log( 5041): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5041): 
I/jxcore-log( 5041): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5041): 
I/jxcore-log( 5041): userPath [ 'www' ]
I/jxcore-log( 5041): 
,I/jxcore-log( 5041): Size 720 1184
I/jxcore-log( 5041): 
,I/jxcore-log( 5041): Screen Brightness 82
I/jxcore-log( 5041): 
,E/jxcore-log( 5041): Dummy Error Log.
E/jxcore-log( 5041): 
,I/jxcore-log( 5041): getBuffer is called!!!!
I/jxcore-log( 5041): 
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  883): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  883): Message: 2
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: false pid=5041, uid=10353
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5041): ****TEST TOOK:  5051  ms ****
I/jxcore-log( 5041): 
I/jxcore-log( 5041): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5041): 
,D/AndroidRuntime( 5115): 
D/AndroidRuntime( 5115): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5115): CheckJNI is OFF
,D/AndroidRuntime( 5115): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  883): Force stopping com.example.hello appid=10353 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 5041:com.example.hello/u0a353 (adj 0): stop com.example.hello
,I/WindowState(  883): WIN DEATH: Window{2c7eebdc u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  883): Client connection lost with reason: 4
,W/PackageSettings(  883): Skipping PackageSetting{777775b com.test.thalitest/10351} due to missing metadata
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{28bf5781 u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  883): Spurious death for ProcessRecord{239aaa61 5041:com.example.hello/u0a353}, curProc for 5041: null
,W/ContextImpl( 1460): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/ActivityManager(  883): Force stopping com.example.hello appid=10353 user=0: pkg removed
I/ActivityManager(  883):   Force finishing activity ActivityRecord{28bf5781 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  883): Duplicate finish request for ActivityRecord{28bf5781 u0 com.example.hello/.MainActivity t3 f}
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
,W/GeofencerStateMachine( 1727): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 2445): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2445): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,I/art     ( 2830): Explicit concurrent mark sweep GC freed 3249(632KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 7MB/12MB, paused 550us total 48.704ms
,I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
,D/Checkin ( 2445): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2445): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2445): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,I/Decoder ( 1408): createOrResetDecoder
I/art     ( 1559): Explicit concurrent mark sweep GC freed 7290(530KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 480us total 94.118ms
,D/Checkin ( 2445): publish the event [tag = MOT_OTA event name = LOG]
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5146 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/VoicemailCleanupService( 4720): Cleaning up data for package: com.example.hello
,I/art     ( 4842): Explicit concurrent mark sweep GC freed 652(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 576us total 135.227ms
,I/ConfigService( 1620): onCreate
,I/art     (  883): Explicit concurrent mark sweep GC freed 15108(979KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 19MB/29MB, paused 2.489ms total 184.421ms
,I/art     (  883): WaitForGcToComplete blocked for 154.472ms for cause Explicit
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 5041 uid 10353
,I/Keyboard.Facilitator( 1408): onFinishInput()
,W/asset   ( 5146): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5146): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5146): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5146): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5172 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,I/art     (  323): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.586ms
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.986ms
,I/art     (  323): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 19.915ms
,I/ActivityManager(  883): Killing 4923:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/Launcher( 1559): Deferring update until onResume
,I/art     (  883): Explicit concurrent mark sweep GC freed 6753(376KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 2.161ms total 193.879ms
,D/AndroidRuntime( 5115): Shutting down VM
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_4923/cgroup.procs: No such file or directory
,W/ContextImpl( 5172): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@509852 new=com.google.android.velvet.VelvetApplication@509852
I/UpdateIcingCorporaServi( 4842): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PackageBroadcastService( 1948): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1948): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1948): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1948): Removing dialog suppression flag for package com.example.hello
E/NetworkScheduler.SchedulerReceiver( 1620): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1620): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1948): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1948): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1948): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1948): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1948): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1948): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1948): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1948): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1948): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1948): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1948): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1948): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1948): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1948): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5199 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/PeopleContactsSync( 1948): CP2 sync disabled
,E/SQLiteLog( 4842): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/AppDataSearchHelper( 4842): Exception thrown from onTableChanged
E/AppDataSearchHelper( 4842): java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 4842): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
E/AppDataSearchHelper( 4842): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.d.j(InternalIcingCorporaProvider.java:709)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.d.a(InternalIcingCorporaProvider.java:700)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.d.i(InternalIcingCorporaProvider.java:627)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:298)
E/AppDataSearchHelper( 4842): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AppDataSearchHelper( 4842): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AppDataSearchHelper( 4842): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AppDataSearchHelper( 4842): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AppDataSearchHelper( 4842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AppDataSearchHelper( 4842): 	at android.os.Looper.loop(Looper.java:135)
E/AppDataSearchHelper( 4842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AppDataSearchHelper( 4842): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AppDataSearchHelper( 4842): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AppDataSearchHelper( 4842): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AppDataSearchHelper( 4842): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AppDataSearchHelper( 4842): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AppDataSearchHelper( 4842): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AppDataSearchHelper( 4842): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AppDataSearchHelper( 4842): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
E/AppDataSearchHelper( 4842): 	at com.google.android.gms.appdatasearch.a.a$1.JA(AppDataSearchDbOpenHelperBase.java:246)
E/AppDataSearchHelper( 4842): 	at com.google.android.gms.appdatasearch.a.a$1.call(AppDataSearchDbOpenHelperBase.java:227)
E/AppDataSearchHelper( 4842): 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
E/AppDataSearchHelper( 4842): 	... 16 more
,W/AppDataSearchHelper( 4842): Table change notification failed for com.google.android.gms.appdatasearch.a.h@be7fd6a1
I/UpdateIcingCorporaServi( 4842): UpdateCorporaTask done [took 141 ms] updated apps [took 140 ms] 
,I/Icing   ( 1948): doRemovePackageData com.example.hello
,I/qdhwcomposer(  282): handle_blank_event: dpy:0 panel power state: 0

```
