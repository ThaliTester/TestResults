#### Test 50388019f4ce509_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,D/CdsService( 2460): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
I/CdsService( 2460): [i] > Retry handler returned true; Retry web request after backoff time: 15000
D/Checkin ( 2460): publish the event [tag = MOT_OTA event name = LOG]
D/AndroidRuntime( 4940): 
D/AndroidRuntime( 4940): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4940): CheckJNI is OFF
D/AndroidRuntime( 4940): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  278): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (139 us)
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 4940): Shutting down VM
I/ActivityManager(  880): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4959 uid=10299 gids={50299, 9997, 3003, 3001, 3002} abi=armeabi-v7a
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 4959): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4959): Time to load native libraries: 2 ms (timestamps 9834-9836)
I/LibraryLoader( 4959): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4959): Binding Chromium to main looper Looper (main, tid 1) {2e45b68}
,I/LibraryLoader( 4959): Expected native library version number "",actual native library version number ""
,I/chromium( 4959): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4959): Initializing chromium process, singleProcess=true
,W/art     ( 4959): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4959): ApplicationContext is null in ApplicationStatus
,W/chromium( 4959): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4959): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4959): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4959): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4959): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4959): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4959): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4959): Local Branch: 
I/Adreno-EGL( 4959): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4959): Local Patches: NONE
I/Adreno-EGL( 4959): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f0ef007:true
,D/BluetoothAdapter( 4959): 741449405: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 4959): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4959): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4959): CordovaWebView is running on device made by: motorola
,I/art     (  880): Explicit concurrent mark sweep GC freed 18937(903KB) AllocSpace objects, 2(126KB) LOS objects, 33% free, 20MB/30MB, paused 1.985ms total 133.909ms
,W/art     ( 4959): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4959): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4959): Render dirty regions requested: true
,D/Atlas   ( 4959): Validating map...
,W/chromium( 4959): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4959): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4959): Enabling debug mode 0
,I/Keyboard.Facilitator( 1408): onFinishInput()
,I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:251 vsyncs) (1:1150)
,I/LaunchCheckinHandler(  880): Displayed com.example.hello/.MainActivity,cp,ca,977
I/ActivityManager(  880): Displayed com.example.hello/.MainActivity: +978ms
,E/Adreno-ES20( 4959): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4959): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4959): Cannot call determinedVisibility() - never saw a connection for the pid: 4959
,I/chromium( 4959): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4959): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4959): Unable to open asset URL: file:///android_asset/www/jxcore.js
,E/Adreno-ES20( 4959): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4959): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/jxcore_app_log( 4959): JniHelper::setJavaVM(0xb7768310), pthread_self() = -1213158336
D/JX-Cordova( 4959): jxcore cordova android initializing
,W/jxcore-log( 4959): Initializing JXcore engine
W/jxcore-log( 4959): JXcore engine is ready
,W/jxcore-log( 4959): Starting JXcore engine
,W/m.example.hello( 4959): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10299 path="socket:[9538]" dev="sockfs" ino=9538 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 4959): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10299 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4959): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10299 path="socket:[9642]" dev="sockfs" ino=9642 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 4959): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10299 path="socket:[21927]" dev="sockfs" ino=21927 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4959): Platform android
W/jxcore-log( 4959): 
,W/jxcore-log( 4959): Process ARCH arm
W/jxcore-log( 4959): 
,I/jxcore-log( 4959): JXcore Cordova bridge is ready!
I/jxcore-log( 4959): 
W/jxcore-log( 4959): JXcore engine is started
,E/jxcore-log( 4959): >> motorola-XT1072
E/jxcore-log( 4959): 
,I/jxcore-log( 4959): Total memory 916258816
I/jxcore-log( 4959): 
,I/jxcore-log( 4959): Free memory 35082240
I/jxcore-log( 4959): 
I/jxcore-log( 4959): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4959): 
I/jxcore-log( 4959): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4959): 
I/jxcore-log( 4959): userPath [ 'www' ]
I/jxcore-log( 4959): 
,I/jxcore-log( 4959): Size 720 1184
I/jxcore-log( 4959): 
,I/jxcore-log( 4959): Screen Brightness 82
I/jxcore-log( 4959): 
E/jxcore-log( 4959): Dummy Error Log.
E/jxcore-log( 4959): 
,I/SFPerfTracer(  278):      triggers: (rate: 13:319) (compose: 0:1) (post: 0:1) (render: 0:2) (0:1112 frames) (1:1200)
D/SFPerfTracer(  278):        layers: (3:11) (FocusedStackFrame (0xb7e7c990): 0:17)* (DimLayer (0xb7eadee8): 0:7)* (StatusBar (0xb7eca678): 0:152) (NavigationBar (0xb7ecd718): 0:22) (com.android.systemui.ImageWallpaper (0xb7ed0940): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb7ee1b88): 0:56)- (Starting com.example.hello (0xb7e39af8): 0:40)- (com.example.hello/com.example.hello.MainActivity (0xb7eb09b8): 1:40) 
,I/jxcore-log( 4959): getBuffer is called!!!!
I/jxcore-log( 4959): 
,D/TaskPersister(  880): removeObsoleteFile: deleting file=28_task_thumbnail.png
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:32000 mC
,D/BluetoothManagerService(  880): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  880): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  880): Message: 2
,D/WifiService(  880): New client listening to asynchronous messages
,D/WifiService(  880): setWifiEnabled: false pid=4959, uid=10299
E/WifiService(  880): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 4959): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 4959): 
I/jxcore-log( 4959): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4959): 
,D/AndroidRuntime( 5028): 
D/AndroidRuntime( 5028): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5028): CheckJNI is OFF
,D/AndroidRuntime( 5028): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  880): Force stopping com.example.hello appid=10299 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 4959:com.example.hello/u0a299 (adj 0): stop com.example.hello
,I/WindowState(  880): WIN DEATH: Window{39ede8f7 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  880): Client connection lost with reason: 4
,W/PackageSettings(  880): Skipping PackageSetting{1515f03b com.test.thalitest/10298} due to missing metadata
,W/ActivityManager(  880): Force removing ActivityRecord{2f25ce3b u0 com.example.hello/.MainActivity t29}: app died, no saved state
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  880): Spurious death for ProcessRecord{18f2ffef 4959:com.example.hello/u0a299}, curProc for 4959: null
,I/ActivityManager(  880): Force stopping com.example.hello appid=10299 user=0: pkg removed
,I/art     ( 2872): Explicit concurrent mark sweep GC freed 8746(1486KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 7MB/12MB, paused 795us total 56.876ms
I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
,I/art     ( 1559): Explicit concurrent mark sweep GC freed 3585(238KB) AllocSpace objects, 1(36KB) LOS objects, 24% free, 13MB/17MB, paused 475us total 60.525ms
,I/Decoder ( 1408): createOrResetDecoder
,I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1742): Ignoring removeGeofence because network location is disabled.
,D/OtaApp  ( 2460): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2460): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2460): publish the event [tag = MOT_OTA event name = LOG]
,D/VoicemailCleanupService( 4699): Cleaning up data for package: com.example.hello
,I/art     (  880): Explicit concurrent mark sweep GC freed 8109(699KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 20MB/30MB, paused 1.647ms total 140.899ms
I/art     (  880): WaitForGcToComplete blocked for 41.611ms for cause Explicit
,I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5058 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2460): [debug] > cancelling the previous pending intent set for download later
,I/ConfigService( 1600): onCreate
I/OtaApp  ( 2460): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2460): publish the event [tag = MOT_OTA event name = LOG]
,W/InputMethodManagerService(  880): Got RemoteException sending setActive(false) notification to pid 4959 uid 10299
,I/Keyboard.Facilitator( 1408): onFinishInput()
,W/asset   ( 5058): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5058): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
,W/ResourcesManager( 5058): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5058): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
,D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
,I/art     (  880): Explicit concurrent mark sweep GC freed 5648(295KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.221ms total 189.100ms
,I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5081 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  880): removeObsoleteFile: deleting file=29_task.xml
D/TaskPersister(  880): removeObsoleteFile: deleting file=28_task.xml
,I/ActivityManager(  880): Killing 4778:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,D/AndroidRuntime( 5028): Shutting down VM
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_4778/cgroup.procs: No such file or directory
,I/Launcher( 1559): Deferring update until onResume
,W/ContextImpl( 5081): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5102 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 4814:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_4814/cgroup.procs: No such file or directory
,W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@32ac5cb2 new=com.google.android.velvet.VelvetApplication@32ac5cb2
,D/PackageBroadcastService( 1948): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1948): Clearing selected account for com.example.hello
,I/LocationSettingsChecker( 1948): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1948): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1600): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1600): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/ChimeraCfgMgr( 1948): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1948): Module APK com.google.android.play.games already loaded
,D/gH_CompatibleDatabase( 1948): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1948): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1948): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1948): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5132 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1948): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1948): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1948): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1948): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1948): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1948): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1948): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1948): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1948): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/Icing   ( 1948): doRemovePackageData com.example.hello
,I/PeopleContactsSync( 1948): CP2 sync disabled
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5159 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.036ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 18.944ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 252us total 19.720ms
,I/GAv4    ( 5132): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5132):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5132):   adb logcat -s GAv4
,W/GAv4    ( 5132): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5132): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
E/SharedPreferencesImpl( 5132): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,E/SharedPreferencesImpl( 5132): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/GAv4    ( 5132): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,E/SharedPreferencesImpl( 5132): Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,W/AnalyticsTrackerProxyImpl( 5132): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
