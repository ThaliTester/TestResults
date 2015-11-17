#### Test 50388019c82294c_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  309): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 4871): 
D/AndroidRuntime( 4871): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4871): CheckJNI is OFF
D/AndroidRuntime( 4871): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  892): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4890 uid=10297 gids={50297, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 4871): Shutting down VM
V/ActivityManager(  892): Display changed displayId=0
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 4890): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4890): Time to load native libraries: 1 ms (timestamps 7191-7192)
I/LibraryLoader( 4890): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4890): Binding Chromium to main looper Looper (main, tid 1) {2c2cf308}
I/LibraryLoader( 4890): Expected native library version number "",actual native library version number ""
I/chromium( 4890): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4890): Initializing chromium process, singleProcess=true
,W/art     ( 4890): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4890): ApplicationContext is null in ApplicationStatus
,W/chromium( 4890): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4890): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4890): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4890): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4890): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4890): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4890): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4890): Local Branch: 
I/Adreno-EGL( 4890): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4890): Local Patches: NONE
I/Adreno-EGL( 4890): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  892): Message: 20
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d02b176:true
,D/BluetoothAdapter( 4890): 385989155: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  892): Activity pause timeout for ActivityRecord{1906d823 u0 com.example.hello/.MainActivity t29}
,W/art     ( 4890): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4890): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4890): CordovaWebView is running on device made by: motorola
,W/art     ( 4890): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4890): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4890): Render dirty regions requested: true
,D/Atlas   ( 4890): Validating map...
,W/chromium( 4890): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4890): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4890): Enabling debug mode 0
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/LaunchCheckinHandler(  892): Displayed com.example.hello/.MainActivity,cp,ca,827
I/ActivityManager(  892): Displayed com.example.hello/.MainActivity: +740ms (total +827ms)
,W/IInputConnectionWrapper( 4890): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 4890): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4890): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4890): Cannot call determinedVisibility() - never saw a connection for the pid: 4890
,I/chromium( 4890): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4890): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4890): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 4890): JniHelper::setJavaVM(0xb7468310), pthread_self() = -1216370976
,D/JX-Cordova( 4890): jxcore cordova android initializing
,W/jxcore-log( 4890): Initializing JXcore engine
W/jxcore-log( 4890): JXcore engine is ready
,W/jxcore-log( 4890): Starting JXcore engine
,W/m.example.hello( 4890): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10297 path="socket:[9494]" dev="sockfs" ino=9494 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4890): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10297 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4890): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10297 path="socket:[9612]" dev="sockfs" ino=9612 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4890): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10297 path="socket:[20973]" dev="sockfs" ino=20973 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4890): Platform android
W/jxcore-log( 4890): 
W/jxcore-log( 4890): Process ARCH arm
W/jxcore-log( 4890): 
,I/jxcore-log( 4890): JXcore Cordova bridge is ready!
I/jxcore-log( 4890): 
,W/jxcore-log( 4890): JXcore engine is started
,E/jxcore-log( 4890): >> motorola-XT1072
E/jxcore-log( 4890): 
,I/jxcore-log( 4890): Total memory 916258816
I/jxcore-log( 4890): 
,I/jxcore-log( 4890): Free memory 35061760
I/jxcore-log( 4890): 
I/jxcore-log( 4890): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4890): 
I/jxcore-log( 4890): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4890): 
I/jxcore-log( 4890): userPath [ 'www' ]
I/jxcore-log( 4890): 
,I/jxcore-log( 4890): Size 720 1184
I/jxcore-log( 4890): 
,I/jxcore-log( 4890): Screen Brightness 82
I/jxcore-log( 4890): 
E/jxcore-log( 4890): Dummy Error Log.
E/jxcore-log( 4890): 
,I/jxcore-log( 4890): getBuffer is called!!!!
I/jxcore-log( 4890): 
,D/BluetoothManagerService(  892): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  892): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  892): Message: 2
,D/WifiService(  892): New client listening to asynchronous messages
,D/WifiService(  892): setWifiEnabled: false pid=4890, uid=10297
E/WifiService(  892): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 4890): ****TEST TOOK:  5053  ms ****
I/jxcore-log( 4890): 
I/jxcore-log( 4890): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4890): 
,D/AndroidRuntime( 4942): 
D/AndroidRuntime( 4942): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4942): CheckJNI is OFF
,D/AndroidRuntime( 4942): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  892): Force stopping com.example.hello appid=10297 user=-1: uninstall pkg
I/ActivityManager(  892): Killing 4890:com.example.hello/u0a297 (adj 0): stop com.example.hello
,I/WindowState(  892): WIN DEATH: Window{14586426 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  892): Client connection lost with reason: 4
,W/PackageSettings(  892): Skipping PackageSetting{2e818a5b com.test.thalitest/10291} due to missing metadata
,I/ActivityManager(  892):   Force finishing activity ActivityRecord{1906d823 u0 com.example.hello/.MainActivity t29}
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  892): Spurious death for ProcessRecord{20cb2403 4890:com.example.hello/u0a297}, curProc for 4890: null
I/ActivityManager(  892): Force stopping com.example.hello appid=10297 user=0: pkg removed
,I/ActivityManager(  892):   Force finishing activity ActivityRecord{1906d823 u0 com.example.hello/.MainActivity t29 f}
W/ActivityManager(  892): Duplicate finish request for ActivityRecord{1906d823 u0 com.example.hello/.MainActivity t29 f}
,W/ContextImpl( 1477): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/art     ( 2959): Explicit concurrent mark sweep GC freed 2842(670KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.208ms total 30.478ms
I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1752): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 2547): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2547): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2547): publish the event [tag = MOT_OTA event name = LOG]
,D/VoicemailCleanupService( 4572): Cleaning up data for package: com.example.hello
,I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
,I/Decoder ( 1417): createOrResetDecoder
,I/art     ( 1567): Explicit concurrent mark sweep GC freed 3591(238KB) AllocSpace objects, 1(36KB) LOS objects, 25% free, 13MB/17MB, paused 959us total 82.679ms
,I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4972 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2547): [debug] > cancelling the previous pending intent set for download later
,I/art     (  892): Explicit concurrent mark sweep GC freed 16523(1173KB) AllocSpace objects, 5(260KB) LOS objects, 33% free, 19MB/29MB, paused 1.315ms total 135.503ms
I/art     (  892): WaitForGcToComplete blocked for 91.246ms for cause Explicit
,I/ConfigService( 1630): onCreate
,I/OtaApp  ( 2547): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2547): publish the event [tag = MOT_OTA event name = LOG]
,W/InputMethodManagerService(  892): Got RemoteException sending setActive(false) notification to pid 4890 uid 10297
,I/Keyboard.Facilitator( 1417): onFinishInput()
,W/asset   ( 4972): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 4972): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 4972): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4972): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
,I/art     (  892): Explicit concurrent mark sweep GC freed 4204(216KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.092ms total 172.659ms
,I/ActivityManager(  892): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5000 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  892): removeObsoleteFile: deleting file=29_task.xml
,D/TaskPersister(  892): removeObsoleteFile: deleting file=28_task.xml
,I/ActivityManager(  892): Killing 4666:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/AndroidRuntime( 4942): Shutting down VM
,W/libprocessgroup(  892): failed to open /acct/uid_10057/pid_4666/cgroup.procs: No such file or directory
,I/Launcher( 1567): Deferring update until onResume
,W/ContextImpl( 5000): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5018 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  892): Killing 4710:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_4710/cgroup.procs: No such file or directory
,W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@334f3752 new=com.google.android.velvet.VelvetApplication@334f3752
,E/SQLiteLog( 1567): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/PackageBroadcastService( 1955): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,D/AccountUtils( 1955): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1955): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1955): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1955): Removing dialog suppression flag for package com.example.hello
,E/SQLiteLog( 1630): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,E/SQLiteLog( 1955): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 1955): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1955): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 1630): Shutting down VM
,--------- beginning of crash
E/AndroidRuntime( 1630): FATAL EXCEPTION: main
E/AndroidRuntime( 1630): Process: com.google.process.gapps, PID: 1630
E/AndroidRuntime( 1630): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1630): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1630): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1630): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1630): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1630): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1630): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1630): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1630): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1630): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1630): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1630): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1630): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1630): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1630): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1630): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1630): 	... 9 more
,I/Process ( 1630): Sending signal. PID: 1630 SIG: 9
,E/SQLiteLog( 1955): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1955): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 1955): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1955): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DriveAsyncService( 1955): disk I/O error (code 3850)
E/DriveAsyncService( 1955): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1955): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1955): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1955): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1955): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1955): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1955): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1955): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1955): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1955): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1955): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1955): 	at java.lang.Thread.run(Thread.java:818)
,E/SQLiteOpenHelper( 1955): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1955): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 1955): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1955): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1955): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/ClearPendingStateOp( 1955): Runtime exception while performing operation
E/ClearPendingStateOp( 1955): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
E/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
E/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
E/ClearPendingStateOp( 1955): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
E/ClearPendingStateOp( 1955): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
E/ClearPendingStateOp( 1955): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 1955): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/ClearPendingStateOp( 1955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 1955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 1955): 	at java.lang.Thread.run(Thread.java:818)
F/ClearPendingStateOp( 1955): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1955): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
F/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
F/ClearPendingStateOp( 1955): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
F/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.i.a.b(SourceFile:283)
F/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.i.a.delete(SourceFile:273)
F/ClearPendingStateOp( 1955): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:309)
F/ClearPendingStateOp( 1955): 	at android.content.ContentResolver.delete(ContentResolver.java:1299)
F/ClearPendingStateOp( 1955): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 1955): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
F/ClearPendingStateOp( 1955): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 1955): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 1955): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 1955): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  892): Can't write: system_app_crash
E/DropBoxManagerService(  892): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  892): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  892): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  892): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  892): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  892): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  892): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  892): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  892): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  892): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  892): 	... 5 more
E/SQLiteDatabase( 1955): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1955): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1955): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1955): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1955): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1955): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1955): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1955): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1955): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1955): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1955): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1955): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1955): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1955): Opened phenotype.db in read-only mode
D/WifiService(  892): Client connection lost with reason: 4
E/SQLiteLog( 1955): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1955): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1955): Sending signal. PID: 1955 SIG: 9
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
D/ConnectivityService(  892): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2beca7a3)
,D/ConnectivityService(  892): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  892): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
