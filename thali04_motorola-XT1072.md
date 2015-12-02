#### Test 50388019193a02f_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 4938): 
D/AndroidRuntime( 4938): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4938): CheckJNI is OFF
D/AndroidRuntime( 4938): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4957 uid=10343 gids={50343, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 4938): Shutting down VM
I/art     (  319): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 22.392ms
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 21.650ms
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 23.831ms
I/WebViewFactory( 4957): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4957): Time to load native libraries: 3 ms (timestamps 7574-7577)
I/LibraryLoader( 4957): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4957): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 4957): Expected native library version number "",actual native library version number ""
,I/chromium( 4957): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4957): Initializing chromium process, singleProcess=true
,W/art     ( 4957): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4957): ApplicationContext is null in ApplicationStatus
,W/chromium( 4957): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4957): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4957): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4957): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4957): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4957): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4957): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4957): Local Branch: 
I/Adreno-EGL( 4957): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4957): Local Patches: NONE
I/Adreno-EGL( 4957): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@100d9650:true
D/BluetoothAdapter( 4957): 174437516: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{3200ef95 u0 com.example.hello/.MainActivity t3}
,W/art     ( 4957): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4957): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4957): CordovaWebView is running on device made by: motorola
,W/art     ( 4957): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4957): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4957): Render dirty regions requested: true
,D/Atlas   ( 4957): Validating map...
,W/chromium( 4957): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4957): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4957): Enabling debug mode 0
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.example.hello/.MainActivity,cp,ca,935
I/ActivityManager(  881): Displayed com.example.hello/.MainActivity: +838ms (total +935ms)
,W/IInputConnectionWrapper( 4957): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 4957): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4957): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 4957): Cannot call determinedVisibility() - never saw a connection for the pid: 4957
I/chromium( 4957): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 4957): Set native->JS mode to OnlineEventsBridgeMode
E/AndroidProtocolHandler( 4957): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/jxcore_app_log( 4957): JniHelper::setJavaVM(0xb884b310), pthread_self() = -1195521912
D/JX-Cordova( 4957): jxcore cordova android initializing
W/jxcore-log( 4957): Initializing JXcore engine
W/jxcore-log( 4957): JXcore engine is ready
W/jxcore-log( 4957): Starting JXcore engine
W/m.example.hello( 4957): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10343 path="socket:[5912]" dev="sockfs" ino=5912 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4957): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10343 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4957): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10343 path="socket:[9530]" dev="sockfs" ino=9530 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4957): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10343 path="socket:[21356]" dev="sockfs" ino=21356 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4957): Platform android
W/jxcore-log( 4957): 
W/jxcore-log( 4957): Process ARCH arm
W/jxcore-log( 4957): 
,I/jxcore-log( 4957): JXcore Cordova bridge is ready!
I/jxcore-log( 4957): 
,W/jxcore-log( 4957): JXcore engine is started
,E/jxcore-log( 4957): >> motorola-XT1072
E/jxcore-log( 4957): 
,I/jxcore-log( 4957): Total memory 916258816
I/jxcore-log( 4957): 
,I/jxcore-log( 4957): Free memory 35319808
I/jxcore-log( 4957): 
I/jxcore-log( 4957): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4957): 
I/jxcore-log( 4957): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4957): 
,I/jxcore-log( 4957): userPath [ 'www' ]
I/jxcore-log( 4957): 
,I/jxcore-log( 4957): Size 720 1184
I/jxcore-log( 4957): 
,I/jxcore-log( 4957): Screen Brightness 82
I/jxcore-log( 4957): 
,E/jxcore-log( 4957): Dummy Error Log.
E/jxcore-log( 4957): 
,I/jxcore-log( 4957): getBuffer is called!!!!
I/jxcore-log( 4957): 
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  881): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  881): Message: 2
,D/WifiService(  881): New client listening to asynchronous messages
,D/WifiService(  881): setWifiEnabled: false pid=4957, uid=10343
E/WifiService(  881): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 4957): ****TEST TOOK:  5057  ms ****
I/jxcore-log( 4957): 
I/jxcore-log( 4957): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4957): 
,D/AndroidRuntime( 5031): 
D/AndroidRuntime( 5031): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5031): CheckJNI is OFF
,D/AndroidRuntime( 5031): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  881): Force stopping com.example.hello appid=10343 user=-1: uninstall pkg
,I/ActivityManager(  881): Killing 4957:com.example.hello/u0a343 (adj 0): stop com.example.hello
,I/WindowState(  881): WIN DEATH: Window{2b1b3380 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  881): Client connection lost with reason: 4
,W/PackageSettings(  881): Skipping PackageSetting{62c8e4d com.test.thalitest/10342} due to missing metadata
,I/ActivityManager(  881):   Force finishing activity ActivityRecord{3200ef95 u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  881): Spurious death for ProcessRecord{1d21dc75 4957:com.example.hello/u0a343}, curProc for 4957: null
,I/ActivityManager(  881): Force stopping com.example.hello appid=10343 user=0: pkg removed
I/ActivityManager(  881):   Force finishing activity ActivityRecord{3200ef95 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{3200ef95 u0 com.example.hello/.MainActivity t3 f}
,I/art     ( 3031): Explicit concurrent mark sweep GC freed 3107(600KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 844us total 42.737ms
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1740): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 2626): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2626): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2626): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2626): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2626): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2626): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1405): resetDictionaries() : en_US
,I/art     ( 1559): Explicit concurrent mark sweep GC freed 7369(536KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 14.134ms total 125.027ms
I/art     ( 4813): Explicit concurrent mark sweep GC freed 669(38KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 565us total 66.929ms
,I/Keyboard.Facilitator.DecoderInitializer( 1405): run()
,I/Decoder ( 1405): createOrResetDecoder
,W/InputMethodManagerService(  881): Got RemoteException sending setActive(false) notification to pid 4957 uid 10343
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/art     (  881): Explicit concurrent mark sweep GC freed 19969(1248KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 19MB/29MB, paused 1.632ms total 167.687ms
,I/art     (  881): WaitForGcToComplete blocked for 85.981ms for cause Explicit
,D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
,I/art     (  881): Explicit concurrent mark sweep GC freed 6220(358KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.371ms total 125.577ms
,I/art     (  881): WaitForGcToComplete blocked for 213.970ms for cause Explicit
,D/AndroidRuntime( 5031): Shutting down VM
,I/art     (  881): Explicit concurrent mark sweep GC freed 1985(110KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.348ms total 104.792ms
,D/VoicemailCleanupService( 4732): Cleaning up data for package: com.example.hello
,I/ConfigService( 1624): onCreate
,I/Launcher( 1559): Deferring update until onResume
,I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5066 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): run()
,W/asset   ( 5066): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 5066): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5066): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5066): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1405): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1405): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1405): run()
I/StatsUtilsManager( 1405): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1405): shouldRecordStats() = Too Soon
,I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5094 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,W/ContextImpl( 5094): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/UpdateIcingCorporaServi( 4813): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,E/SQLiteDatabase( 5094): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5094): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 5094): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 5094): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5094): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
E/AndroidRuntime( 5094): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5094): Process: com.android.keychain, PID: 5094
E/AndroidRuntime( 5094): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5094): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 5094): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5094): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5094): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 5094): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 5094): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5094): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5094): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5094): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 1559): (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1943): Clearing selected account for com.example.hello
,I/Process ( 5094): Sending signal. PID: 5094 SIG: 9
,E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  881): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  881): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  881): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  881): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  881): 	... 5 more
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1943): Removing dialog suppression flag for package com.example.hello
E/SQLiteLog( 1943): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 1624): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 1624): Shutting down VM
,E/AndroidRuntime( 1624): FATAL EXCEPTION: main
E/AndroidRuntime( 1624): Process: com.google.process.gapps, PID: 1624
E/AndroidRuntime( 1624): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1624): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1624): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1624): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1624): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1624): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1624): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1624): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1624): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1624): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1624): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1624): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1624): 	at com.google.android.gms.gcm.bq.a(SourceFile:310)
E/AndroidRuntime( 1624): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1624): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1624): 	... 9 more
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 1943): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteDatabase( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1943): Couldn't open phenotype.db for writing (will try read-only):
E/SQLiteOpenHelper( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:68)
E/SQLiteOpenHelper( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  881): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  881): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  881): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  881): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  881): 	... 5 more
E/DriveAsyncService( 1943): disk I/O error (code 3850)
E/DriveAsyncService( 1943): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1943): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1943): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1943): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1943): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1943): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1943): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1943): 	at com.google.android.gms.drive.database.k.k(SourceFile:485)
E/DriveAsyncService( 1943): 	at com.google.android.gms.drive.database.k.b(SourceFile:460)
E/DriveAsyncService( 1943): 	at com.google.android.gms.drive.database.f.i(SourceFile:1516)
E/DriveAsyncService( 1943): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1943): 	at com.google.android.gms.common.service.f.run(SourceFile:178)
E/DriveAsyncService( 1943): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1943): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1943): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1943): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 1943): Opened phenotype.db in read-only mode
E/SQLiteLog( 4813): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1943): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1943): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1943): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteOpenHelper( 1943): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1943): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1943): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1943): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1943): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1943): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1943): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1943): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1943): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1943): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 1943): Opened metrics.db in read-only mode
E/SQLiteLog( 1943): (3850) statement aborts at 22: [DELETE FROM events WHERE app_id=?] disk I/O error
D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1943): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/GMPM-SVC( 1943): Error deleting application data. appId, error: com.example.hello, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.d.d(SourceFile:911)
I/Process ( 1943): Sending signal. PID: 1943 SIG: 9
,D/ConnectivityService(  881): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@1700c61e)
D/ConnectivityService(  881): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  881): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  881): Process com.android.keychain (pid 5094) has died
W/ActivityManager(  881): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
W/ActivityManager(  881): Application dead when creating service ServiceRecord{20e5aeff u0 com.google.android.gms/.people.service.bg.PeopleBackgroundTasks}

```
