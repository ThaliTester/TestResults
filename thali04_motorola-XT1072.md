#### Test 50388019831b9e1_thali04_motorola-XT1072 Logs


```
--------- beginning of system
D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=237, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2366000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310456, SEQNUM=4359, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-22836, POWER_SUPPLY_CHARGE_COUNTER=-1576, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
--------- beginning of main
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/AndroidRuntime( 5342): 
D/AndroidRuntime( 5342): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5342): CheckJNI is OFF
D/AndroidRuntime( 5342): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5361 uid=10406 gids={50406, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5342): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5361): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5361): Time to load native libraries: 2 ms (timestamps 4495-4497)
I/LibraryLoader( 5361): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5361): Binding Chromium to main looper Looper (main, tid 1) {1dd8dff7}
I/LibraryLoader( 5361): Expected native library version number "",actual native library version number ""
I/chromium( 5361): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5361): Initializing chromium process, singleProcess=true
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5361): ApplicationContext is null in ApplicationStatus
,W/chromium( 5361): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5361): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5361): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5361): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5361): Local Branch: 
I/Adreno-EGL( 5361): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5361): Local Patches: NONE
I/Adreno-EGL( 5361): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a182608:true
,D/BluetoothAdapter( 5361): 11300048: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{225086d u0 com.example.hello/.MainActivity t3}
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5361): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5361): CordovaWebView is running on device made by: motorola
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5361): Render dirty regions requested: true
D/Atlas   ( 5361): Validating map...
,W/chromium( 5361): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5361): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5361): Enabling debug mode 0
,W/IInputConnectionWrapper( 5361): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.example.hello/.MainActivity,cp,ca,841
I/ActivityManager(  883): Displayed com.example.hello/.MainActivity: +764ms (total +842ms)
,E/Adreno-ES20( 5361): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5361): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5361): Cannot call determinedVisibility() - never saw a connection for the pid: 5361
,I/chromium( 5361): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5361): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5361): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5361): JniHelper::setJavaVM(0xb7f3e310), pthread_self() = -1205016856
,D/JX-Cordova( 5361): jxcore cordova android initializing
,W/jxcore-log( 5361): Initializing JXcore engine
W/jxcore-log( 5361): JXcore engine is ready
,W/jxcore-log( 5361): Starting JXcore engine
,W/m.example.hello( 5361): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10406 path="socket:[5810]" dev="sockfs" ino=5810 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5361): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10406 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 5361): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10406 path="socket:[7463]" dev="sockfs" ino=7463 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 5361): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10406 path="socket:[24107]" dev="sockfs" ino=24107 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5361): Platform android
W/jxcore-log( 5361): 
,W/jxcore-log( 5361): Process ARCH arm
W/jxcore-log( 5361): 
,I/jxcore-log( 5361): JXcore Cordova bridge is ready!
I/jxcore-log( 5361): 
W/jxcore-log( 5361): JXcore engine is started
,E/jxcore-log( 5361): >> motorola-XT1072
E/jxcore-log( 5361): 
I/jxcore-log( 5361): Total memory 916258816
I/jxcore-log( 5361): 
I/jxcore-log( 5361): Free memory 35065856
I/jxcore-log( 5361): 
I/jxcore-log( 5361): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5361): 
I/jxcore-log( 5361): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5361): 
,I/jxcore-log( 5361): userPath [ 'www' ]
I/jxcore-log( 5361): 
,I/jxcore-log( 5361): Size 720 1184
I/jxcore-log( 5361): 
,I/jxcore-log( 5361): Screen Brightness 82
I/jxcore-log( 5361): 
,E/jxcore-log( 5361): Dummy Error Log.
E/jxcore-log( 5361): 
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:27000 mC
,I/jxcore-log( 5361): getBuffer is called!!!!
I/jxcore-log( 5361): 
,D/BluetoothManagerService(  883): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  883): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService(  883): Message: 2
,D/WifiService(  883): New client listening to asynchronous messages
,D/WifiService(  883): setWifiEnabled: false pid=5361, uid=10406
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,I/jxcore-log( 5361): ****TEST TOOK:  5056  ms ****
I/jxcore-log( 5361): 
I/jxcore-log( 5361): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5361): 
,D/AndroidRuntime( 5420): 
D/AndroidRuntime( 5420): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 5420): CheckJNI is OFF
,D/AndroidRuntime( 5420): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  883): Force stopping com.example.hello appid=10406 user=-1: uninstall pkg
,I/ActivityManager(  883): Killing 5361:com.example.hello/u0a406 (adj 0): stop com.example.hello
,I/WindowState(  883): WIN DEATH: Window{2c252138 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  883): Client connection lost with reason: 4
,W/PackageSettings(  883): Skipping PackageSetting{25b0d566 com.test.thalitest/10404} due to missing metadata
,I/ActivityManager(  883):   Force finishing activity ActivityRecord{225086d u0 com.example.hello/.MainActivity t3}
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ActivityManager(  883): Spurious death for ProcessRecord{1013414d 5361:com.example.hello/u0a406}, curProc for 5361: null
,I/ActivityManager(  883): Force stopping com.example.hello appid=10406 user=0: pkg removed
I/ActivityManager(  883):   Force finishing activity ActivityRecord{225086d u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  883): Duplicate finish request for ActivityRecord{225086d u0 com.example.hello/.MainActivity t3 f}
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/art     ( 2925): Explicit concurrent mark sweep GC freed 3802(765KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 7MB/12MB, paused 792us total 41.559ms
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1692): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
,D/OtaApp  ( 2503): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2503): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2503): publish the event [tag = MOT_OTA event name = LOG]
,I/art     ( 1558): Explicit concurrent mark sweep GC freed 7323(532KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 510us total 99.381ms
,D/VoicemailCleanupService( 5018): Cleaning up data for package: com.example.hello
I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
,I/art     ( 1940): Explicit concurrent mark sweep GC freed 2119(85KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 967us total 127.878ms
,I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5451 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,D/OtaApp  ( 2503): [debug] > cancelling the previous pending intent set for download later
,I/art     (  883): Explicit concurrent mark sweep GC freed 18067(1066KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 19MB/29MB, paused 1.535ms total 134.984ms
,I/art     (  883): WaitForGcToComplete blocked for 56.492ms for cause Explicit
,I/OtaApp  ( 2503): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2503): publish the event [tag = MOT_OTA event name = LOG]
,I/Decoder ( 1409): createOrResetDecoder
,W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 5361 uid 10406
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/ConfigService( 1692): onCreate
,W/asset   ( 5451): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5451): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5451): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5451): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5473 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,D/TaskPersister(  883): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=2_task.xml
,I/art     ( 1692): Explicit concurrent mark sweep GC freed 38166(2MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 13MB/21MB, paused 1.456ms total 85.695ms
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34c1ada7)
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f8a0254)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2b70c5fd)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a0592f2)
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@517d43)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1baeefc0)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@508c4f9)
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2255ec3e)
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@284aa9f)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@147347ec)
E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2187b7b5)
,E/DataBuffer( 1692): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2bc08e4a)
,I/Launcher( 1558): Deferring update until onResume
,I/ActivityManager(  883): Killing 5173:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,I/art     (  883): Explicit concurrent mark sweep GC freed 6919(395KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 2.003ms total 203.742ms
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
,I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
,I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
,I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
,D/AndroidRuntime( 5420): Shutting down VM
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_5173/cgroup.procs: No such file or directory
,W/ContextImpl( 5473): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,D/PackageBroadcastService( 1940): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1940): Clearing selected account for com.example.hello
,D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1940): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 1940): Removing dialog suppression flag for package com.example.hello
,D/ChimeraCfgMgr( 1940): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1940): Module APK com.google.android.play.games already loaded
,E/NetworkScheduler.SchedulerReceiver( 1692): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1692): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,D/gH_CompatibleDatabase( 1940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,D/gH_MetricsDatabase( 1940): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,D/gH_CompatibleDatabase( 1940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/gH_CompatibleDatabase( 1940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,D/gH_CompatibleDatabase( 1940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/gH_CompatibleDatabase( 1940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,D/gH_CompatibleDatabase( 1940): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1940): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/gH_CompatibleDatabase( 1940): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5502 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 1940): doRemovePackageData com.example.hello
,W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@b71e4c9 new=com.google.android.velvet.VelvetApplication@b71e4c9
,I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5535 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
