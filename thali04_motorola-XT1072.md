#### Test 50242285feafdeb_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312059, SEQNUM=4361, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-270, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
--------- beginning of main
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 5479): 
D/AndroidRuntime( 5479): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5479): CheckJNI is OFF
D/AndroidRuntime( 5479): Calling main entry com.android.commands.am.Am
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  892): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5498 uid=10440 gids={50440, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5479): Shutting down VM
V/ActivityManager(  892): Display changed displayId=0
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5498): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5498): Time to load native libraries: 2 ms (timestamps 3942-3944)
I/LibraryLoader( 5498): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5498): Binding Chromium to main looper Looper (main, tid 1) {57656ff}
,I/LibraryLoader( 5498): Expected native library version number "",actual native library version number ""
I/chromium( 5498): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5498): Initializing chromium process, singleProcess=true
,W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5498): ApplicationContext is null in ApplicationStatus
,W/chromium( 5498): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5498): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5498): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5498): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5498): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5498): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5498): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5498): Local Branch: 
I/Adreno-EGL( 5498): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5498): Local Patches: NONE
I/Adreno-EGL( 5498): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  892): Message: 20
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f1f4e8c:true
,D/BluetoothAdapter( 5498): 536658678: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  892): Activity pause timeout for ActivityRecord{29634ae1 u0 com.example.hello/.MainActivity t3}
,W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5498): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5498): CordovaWebView is running on device made by: motorola
,W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5498): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5498): Render dirty regions requested: true
,D/Atlas   ( 5498): Validating map...
,W/chromium( 5498): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5498): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5498): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,I/LaunchCheckinHandler(  892): Displayed com.example.hello/.MainActivity,cp,ca,905
I/ActivityManager(  892): Displayed com.example.hello/.MainActivity: +826ms (total +905ms)
,W/IInputConnectionWrapper( 5498): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5498): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5498): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5498): Cannot call determinedVisibility() - never saw a connection for the pid: 5498
,I/chromium( 5498): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5498): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5498): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5498): JniHelper::setJavaVM(0xb84b8310), pthread_self() = -1199268496
,W/jxcore-log( 5498): Initializing JXcore engine
W/jxcore-log( 5498): JXcore engine is ready
,W/Thread-632( 5547): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10440 path="socket:[5573]" dev="sockfs" ino=5573 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-632( 5547): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10440 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-632( 5547): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10440 path="socket:[6821]" dev="sockfs" ino=6821 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-632( 5547): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10440 path="socket:[24921]" dev="sockfs" ino=24921 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5498): Starting JXcore engine
,W/jxcore-log( 5498): Platform android
W/jxcore-log( 5498): 
W/jxcore-log( 5498): Process ARCH arm
W/jxcore-log( 5498): 
,I/jxcore-log( 5498): JXcore Cordova bridge is ready!
I/jxcore-log( 5498): 
,W/jxcore-log( 5498): JXcore engine is started
,E/jxcore  ( 5498): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5498): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311752, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-307, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ClearcutLoggerApiImpl( 1726): disconnect managed GoogleApiClient
,V/AlarmManager(  892): send {284dfc8c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): send {3f34cc81, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  892): send {168b94a7, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  892): done {3f34cc81, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [16ms]
,V/AlarmManager(  892): done {168b94a7, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [30ms]
,V/AlarmManager(  892): done {284dfc8c, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/EventLogService( 1941): Aggregate from 1452550897518 (log), 1452550897518 (data)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1726): onCreate
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ConfigService( 1726): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 5571): 
D/AndroidRuntime( 5571): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5571): CheckJNI is OFF
D/AndroidRuntime( 5571): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  892): Force stopping com.example.hello appid=10440 user=-1: uninstall pkg
I/ActivityManager(  892): Killing 5498:com.example.hello/u0a440 (adj 0): stop com.example.hello
I/WindowState(  892): WIN DEATH: Window{d5972bc u0 com.example.hello/com.example.hello.MainActivity}
I/WindowState(  892): WIN DEATH: Window{31ad9966 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  892): Skipping PackageSetting{2539658e com.test.thalitest/10437} due to missing metadata
I/ActivityManager(  892):   Force finishing activity ActivityRecord{29634ae1 u0 com.example.hello/.MainActivity t3}
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  892): Spurious death for ProcessRecord{28c4719f 5498:com.example.hello/u0a440}, curProc for 5498: null
I/ActivityManager(  892): Force stopping com.example.hello appid=10440 user=0: pkg removed
I/ActivityManager(  892):   Force finishing activity ActivityRecord{29634ae1 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  892): Duplicate finish request for ActivityRecord{29634ae1 u0 com.example.hello/.MainActivity t3 f}
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/GeofencerStateMachine( 1726): Ignoring removeGeofence because network location is disabled.
I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
D/OtaApp  ( 2604): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2604): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2604): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2604): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2604): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2604): publish the event [tag = MOT_OTA event name = LOG]
I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
I/art     ( 3185): Explicit concurrent mark sweep GC freed 3652(740KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 7MB/12MB, paused 493us total 84.263ms
I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5599 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/VoicemailCleanupService( 5211): Cleaning up data for package: com.example.hello
I/art     ( 1568): Explicit concurrent mark sweep GC freed 7328(533KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 466us total 70.026ms
I/art     (  892): Explicit concurrent mark sweep GC freed 14434(1061KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 19MB/29MB, paused 1.389ms total 181.251ms
I/art     (  892): WaitForGcToComplete blocked for 180.255ms for cause Explicit
I/art     ( 1941): Explicit concurrent mark sweep GC freed 17362(1080KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/19MB, paused 984us total 91.510ms
I/Decoder ( 1416): createOrResetDecoder
W/asset   ( 5599): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5599): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5599): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5599): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ConfigService( 1726): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
I/ActivityManager(  892): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5624 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  892): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  892): removeObsoleteFile: deleting file=2_task.xml
I/art     (  892): Explicit concurrent mark sweep GC freed 4961(271KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.531ms total 196.715ms
W/InputMethodManagerService(  892): Got RemoteException sending setActive(false) notification to pid 5498 uid 10440
I/ActivityManager(  892): Killing 5317:com.google.android.apps.docs/u0a57 (adj 15): empty #7
I/Keyboard.Facilitator( 1416): onFinishInput()
D/AndroidRuntime( 5571): Shutting down VM
I/Launcher( 1568): Deferring update until onResume
W/libprocessgroup(  892): failed to open /acct/uid_10057/pid_5317/cgroup.procs: No such file or directory
W/ContextImpl( 5624): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1941): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1941): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1941): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1941): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1941): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1941): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1941): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1941): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1941): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1941): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1941): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1941): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1941): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1941): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1941): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1941): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1941): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1941): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5651 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1941): doRemovePackageData com.example.hello
W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@39ee6391 new=com.google.android.velvet.VelvetApplication@39ee6391
I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5677 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
