#### Test 5038801932cd575_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=285, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311449, SEQNUM=4325, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12520, POWER_SUPPLY_CHARGE_COUNTER=-350, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
--------- beginning of main
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 4847): 
D/AndroidRuntime( 4847): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4847): CheckJNI is OFF
D/AndroidRuntime( 4847): Calling main entry com.android.commands.am.Am
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  878): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4866 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 4847): Shutting down VM
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 4866): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4866): Time to load native libraries: 2 ms (timestamps 3921-3923)
I/LibraryLoader( 4866): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4866): Binding Chromium to main looper Looper (main, tid 1) {2903656e}
,I/LibraryLoader( 4866): Expected native library version number "",actual native library version number ""
,I/chromium( 4866): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4866): Initializing chromium process, singleProcess=true
W/art     ( 4866): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4866): ApplicationContext is null in ApplicationStatus
,W/chromium( 4866): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4866): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4866): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4866): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4866): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4866): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4866): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4866): Local Branch: 
I/Adreno-EGL( 4866): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4866): Local Patches: NONE
I/Adreno-EGL( 4866): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothAdapter( 4866): 1063716897: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  878): Message: 20
D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@50f9286:true
,W/ActivityManager(  878): Activity pause timeout for ActivityRecord{2ee4250a u0 com.example.hello/.MainActivity t3}
,W/art     ( 4866): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4866): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4866): CordovaWebView is running on device made by: motorola
,W/art     ( 4866): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4866): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4866): Render dirty regions requested: true
,D/Atlas   ( 4866): Validating map...
,W/chromium( 4866): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4866): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4866): Enabling debug mode 0
,I/Keyboard.Facilitator( 1404): onFinishInput()
,I/LaunchCheckinHandler(  878): Displayed com.example.hello/.MainActivity,cp,ca,914
I/ActivityManager(  878): Displayed com.example.hello/.MainActivity: +841ms (total +915ms)
,W/IInputConnectionWrapper( 4866): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 4866): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4866): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4866): Cannot call determinedVisibility() - never saw a connection for the pid: 4866
,I/chromium( 4866): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 4866): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4866): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 4866): JniHelper::setJavaVM(0xb84cb310), pthread_self() = -1199198704
D/JX-Cordova( 4866): jxcore cordova android initializing
,W/jxcore-log( 4866): Initializing JXcore engine
W/jxcore-log( 4866): JXcore engine is ready
W/jxcore-log( 4866): Starting JXcore engine
,W/m.example.hello( 4866): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10318 path="socket:[8355]" dev="sockfs" ino=8355 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 4866): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10318 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4866): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10318 path="socket:[6546]" dev="sockfs" ino=6546 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4866): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10318 path="socket:[21449]" dev="sockfs" ino=21449 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4866): Platform android
W/jxcore-log( 4866): 
,W/jxcore-log( 4866): Process ARCH arm
W/jxcore-log( 4866): 
,I/jxcore-log( 4866): JXcore Cordova bridge is ready!
I/jxcore-log( 4866): 
,W/jxcore-log( 4866): JXcore engine is started
,E/jxcore-log( 4866): >> motorola-XT1072
E/jxcore-log( 4866): 
,I/jxcore-log( 4866): Total memory 916258816
I/jxcore-log( 4866): 
,I/jxcore-log( 4866): Free memory 33787904
I/jxcore-log( 4866): 
,I/jxcore-log( 4866): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4866): 
,I/jxcore-log( 4866): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4866): 
,I/jxcore-log( 4866): userPath [ 'www' ]
I/jxcore-log( 4866): 
,I/jxcore-log( 4866): Size 720 1184
I/jxcore-log( 4866): 
,I/jxcore-log( 4866): Screen Brightness 82
I/jxcore-log( 4866): 
,E/jxcore-log( 4866): Dummy Error Log.
E/jxcore-log( 4866): 
,I/jxcore-log( 4866): getBuffer is called!!!!
I/jxcore-log( 4866): 
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,D/BluetoothManagerService(  878): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  878): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  878): Message: 2
,D/WifiService(  878): New client listening to asynchronous messages
,D/WifiService(  878): setWifiEnabled: false pid=4866, uid=10318
E/WifiService(  878): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 4866): ****TEST TOOK:  5053  ms ****
I/jxcore-log( 4866): 
,I/jxcore-log( 4866): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4866): 
,D/AndroidRuntime( 4926): 
D/AndroidRuntime( 4926): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4926): CheckJNI is OFF
,D/AndroidRuntime( 4926): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  878): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 4866:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/WindowState(  878): WIN DEATH: Window{1c3ab199 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  878): Client connection lost with reason: 4
,W/PackageSettings(  878): Skipping PackageSetting{1a7bc819 com.test.thalitest/10315} due to missing metadata
,I/ActivityManager(  878):   Force finishing activity ActivityRecord{2ee4250a u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  878): Spurious death for ProcessRecord{2dd2f06a 4866:com.example.hello/u0a318}, curProc for 4866: null
,I/ActivityManager(  878): Force stopping com.example.hello appid=10318 user=0: pkg removed
,I/ActivityManager(  878):   Force finishing activity ActivityRecord{2ee4250a u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  878): Duplicate finish request for ActivityRecord{2ee4250a u0 com.example.hello/.MainActivity t3 f}
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/art     ( 2870): Explicit concurrent mark sweep GC freed 2907(605KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 7MB/12MB, paused 1.016ms total 32.111ms
,I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1744): Ignoring removeGeofence because network location is disabled.
,I/Keyboard.Facilitator( 1404): resetDictionaries() : en_US
,I/Keyboard.Facilitator.DecoderInitializer( 1404): run()
,D/OtaApp  ( 2480): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2480): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2480): publish the event [tag = MOT_OTA event name = LOG]
,I/Decoder ( 1404): createOrResetDecoder
,D/VoicemailCleanupService( 4530): Cleaning up data for package: com.example.hello
,I/art     ( 1554): Explicit concurrent mark sweep GC freed 7318(532KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 471us total 129.801ms
,I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4957 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2480): [debug] > cancelling the previous pending intent set for download later
,I/art     (  878): Explicit concurrent mark sweep GC freed 21439(1370KB) AllocSpace objects, 6(337KB) LOS objects, 33% free, 19MB/29MB, paused 1.272ms total 161.065ms
,I/art     (  878): WaitForGcToComplete blocked for 95.125ms for cause Explicit
,I/ConfigService( 1603): onCreate
,I/OtaApp  ( 2480): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2480): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  878): send {17b011b2, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
V/AlarmManager(  878): send {632d6df, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,W/InputMethodManagerService(  878): Got RemoteException sending setActive(false) notification to pid 4866 uid 10318
,I/Keyboard.Facilitator( 1404): onFinishInput()
,W/asset   ( 4957): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,W/ResourcesManager( 4957): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 4957): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4957): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1404): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1404): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1404): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1404): run()
,I/Keyboard.Facilitator.RecurringTaskScheduler( 1404): run()
I/StatsUtilsManager( 1404): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1404): shouldRecordStats() = Too Soon
,D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4983 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  878): removeObsoleteFile: deleting file=3_task.xml
,D/TaskPersister(  878): removeObsoleteFile: deleting file=2_task.xml
,I/art     (  878): Explicit concurrent mark sweep GC freed 7019(403KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.636ms total 189.108ms
,I/ActivityManager(  878): Killing 4699:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/Launcher( 1554): Deferring update until onResume
,D/AndroidRuntime( 4926): Shutting down VM
,W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_4699/cgroup.procs: No such file or directory
,W/ContextImpl( 4983): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5001 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/ActivityManager(  878): Killing 4726:com.google.android.gms:car/u0a16 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10016/pid_4726/cgroup.procs: No such file or directory
,W/Launcher( 1554): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@226d2688 new=com.google.android.velvet.VelvetApplication@226d2688
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1943): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1943): Removing dialog suppression flag for package com.example.hello
,E/NetworkScheduler.SchedulerReceiver( 1603): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1603): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1943): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,I/ActivityManager(  878): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5030 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1943): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1943): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1943): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/PeopleContactsSync( 1943): CP2 sync disabled
,I/Icing   ( 1943): doRemovePackageData com.example.hello
,E/global frequency( 2480): no tags to log
,D/Checkin ( 2480): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2480): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1536): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
