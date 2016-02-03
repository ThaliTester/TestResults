#### Test 58135655e794d2c_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6778): 
D/AndroidRuntime( 6778): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6778): CheckJNI is OFF
D/AndroidRuntime( 6778): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  888): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  888): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6797 uid=10503 gids={50503, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6778): Shutting down VM
V/ActivityManager(  888): Display changed displayId=0
W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6797): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6797): Time to load native libraries: 12 ms (timestamps 7502-7514)
I/LibraryLoader( 6797): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6797): Binding Chromium to main looper Looper (main, tid 1) {36cab246}
I/LibraryLoader( 6797): Expected native library version number "",actual native library version number ""
,I/chromium( 6797): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6797): Initializing chromium process, singleProcess=true
,W/art     ( 6797): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6797): ApplicationContext is null in ApplicationStatus
,W/chromium( 6797): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6797): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6797): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6797): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6797): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6797): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6797): Local Branch: 
I/Adreno-EGL( 6797): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6797): Local Patches: NONE
I/Adreno-EGL( 6797): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  888): Activity pause timeout for ActivityRecord{3f1f1fcd u0 com.test.thalitest/.MainActivity t6}
,D/BluetoothManagerService(  888): Message: 20
D/BluetoothManagerService(  888): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@df328e8:true
,W/art     ( 6797): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6797): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6797): CordovaWebView is running on device made by: motorola
,W/art     ( 6797): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6797): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6797): Render dirty regions requested: true
,D/Atlas   ( 6797): Validating map...
,W/chromium( 6797): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  888): Explicit concurrent mark sweep GC freed 9031(504KB) AllocSpace objects, 2(224KB) LOS objects, 33% free, 20MB/30MB, paused 1.478ms total 126.488ms
,I/OpenGLRenderer( 6797): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6797): Enabling debug mode 0
,I/Keyboard.Facilitator( 1424): onFinishInput()
,I/LaunchCheckinHandler(  888): Displayed com.test.thalitest/.MainActivity,cp,ca,1129
I/ActivityManager(  888): Displayed com.test.thalitest/.MainActivity: +1s38ms (total +1s129ms)
,W/IInputConnectionWrapper( 6797): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6797): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6797): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6797): Cannot call determinedVisibility() - never saw a connection for the pid: 6797
,D/JsMessageQueue( 6797): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6797): JniHelper::setJavaVM(0xb74cf310), pthread_self() = -1215965688
,I/chromium( 6797): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6797): Initializing JXcore engine
W/jxcore-log( 6797): JXcore engine is ready
,W/Thread-818( 6846): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10503 path="socket:[5594]" dev="sockfs" ino=5594 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-818( 6846): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10503 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-818( 6846): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10503 path="socket:[6918]" dev="sockfs" ino=6918 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-818( 6846): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10503 path="socket:[31204]" dev="sockfs" ino=31204 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6797): Starting JXcore engine
,W/jxcore-log( 6797): Platform android
W/jxcore-log( 6797): 
,W/jxcore-log( 6797): Process ARCH arm
W/jxcore-log( 6797): 
,I/jxcore-log( 6797): JXcore Cordova bridge is ready!
I/jxcore-log( 6797): 
,W/jxcore-log( 6797): JXcore engine is started
,E/jxcore  ( 6797): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6797): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6797): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  888): Killing 6577:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  888): failed to open /acct/uid_10057/pid_6577/cgroup.procs: No such file or directory
W/PluginManager( 6797): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2610): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2610): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2610): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1424): onFinishInput()
W/IInputConnectionWrapper( 6797): showStatusIcon on inactive InputConnection
,D/TaskPersister(  888): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  300): Event received = CTRL-EVENT-BSS-REMOVED 1
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  300): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 2
D/MDMCTBK (  300): Event received = CTRL-EVENT-BSS-REMOVED 2
,I/Keyboard.Facilitator.LanguageModelFlusher( 1424): run()
I/Keyboard.Facilitator( 1424): flushDynamicLanguageModels()
,I/ConfigService( 1731): onCreate
,I/ConfigService( 1731): onDestroy
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  888): send {121901e1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): done {121901e1, *alarm*:android.intent.action.TIME_TICK} [38ms]
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311564, SEQNUM=4413, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-1068, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2432): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310664, SEQNUM=4415, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1141, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2432): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  888): send {121901e1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): send {3319855a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  888): send {a58d630, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  888): done {3319855a, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [25ms]
,V/AlarmManager(  888): done {a58d630, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [35ms]
,V/AlarmManager(  888): done {121901e1, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/EventLogService( 1962): Aggregate from 1454534074652 (log), 1454533005098 (data)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  888): send {121901e1, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  888): send {5432065, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  888): done {121901e1, *alarm*:android.intent.action.TIME_TICK} [53ms]
,V/AlarmManager(  888): done {5432065, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [84ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  888): send {121901e1, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  888): send {2491c13a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  888): done {2491c13a, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [16ms]
,V/AlarmManager(  888): done {121901e1, *alarm*:android.intent.action.TIME_TICK} [38ms]
,V/AlarmManager(  888): send {27cb21eb, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
,I/PollingManager( 2610): alarm fired!
,D/Checkin ( 2610): publish the event [tag = MOT_CCE event name = LOG]
,D/PollingManager( 2610): now: 1041277 ,futureTime: 9223372036854775807
,I/PollingManager( 2610): alarm fired!
,D/Checkin ( 2610): publish the event [tag = MOT_CCE event name = LOG]
,D/PollingManager( 2610): now: 1041289 ,futureTime: 9223372036854775807
,I/PollingManager( 2610): alarm fired!
,D/Checkin ( 2610): publish the event [tag = MOT_CCE event name = LOG]
,D/PollingManager( 2610): now: 1041303 ,futureTime: 9223372036854775807
,I/OtaApp  ( 2610): [info] > PollingManagerService, alarm fired!
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > PollingManagerService, now: 1041317 ,futureTime: 2026317
D/OtaApp  ( 2610): [debug] > PollingManagerService, wake lock acquired
,D/OtaApp  ( 2610): [debug] > PollingManagerService, decideWhoNeedsPolling(): polling cUsPollingService
,D/OtaApp  ( 2610): [debug] > Polling alarm set to expire at: 2026317 Current Time: 1041331
,I/Central_PollingManager( 1483): alarm fired!
D/Central_PollingManager( 1483): now: 1041336 ,futureTime: 86477387
D/Central_PollingManager( 1483): Polling alarm set to expire at: 86477387 Current Time: 1041336
,V/AlarmManager(  888): done {27cb21eb, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [159ms]
,D/OtaApp  ( 2610): [debug] > AndroidClientUpgradeService.handleIntent: com.motorola.blur.service.blur.cUsPollingService.pollingManagerIntent
I/OtaApp  ( 2610): [info] > CusPollingService interval expired, doing check for upgrade
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > CusSM.onPollingExpiryNotification
,D/OtaApp  ( 2610): [debug] > PollingManagerService, wake lock released
,E/CdsService( 2610): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2610): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2610): [d] > Check Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072
,I/CdsService( 2610): [i] > Starting webservice android service
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2610): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2610): [d] > appending web service request to serviceHandler
,W/ActivityThread( 2610): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/CdsService( 2610): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/0IKQ2q9lsvcjoJkpA0tikHb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTQdBxckdFB%2BCxth5z9vV9sAdTUVi6yiomz3MFujLszM8CEEDkYt5gjMgKTUEwWO7DtOX9D5OiTsHBqMh5NvQbzGBXo6V6vmPHsjJ%2B1wTXLr4WBkayQhPeuks7euPsMOyW%2BILsMUmY4RMddW%2BbN86f8IW%2BF1xX7eeCfBFhvuui%2Bl50dadQFAU3Yg9SSHg7OqTG9fhoDPIeBvr6SuDg504qbk9WH88tVzaLsiRPdk8X92BlZurvnrz%2BgRmD4roihJOJZY7j2YjQBdpB5Mq1rptDPNb0cyoOAuR4HpoUNessKUc%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/V7YybYnqErILhlD4NCc%2BEXb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fu
,D/CdsService( 2610): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/0IKQ2q9lsvcjoJkpA0tikHb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTQdBxckdFB%2BCxth5z9vV9sAdTUVi6yiomz3MFujLszM8CEEDkYt5gjMgKTUEwWO7DtOX9D5OiTsHBqMh5NvQbzGBXo6V6vmPHsjJ%2B1wTXLr4WBkayQhPeuks7euPsMOyW%2BILsMUmY4RMddW%2BbN86f8IW%2BF1xX7eeCfBFhvuui%2Bl50dadQFAU3Yg9SSHg7OqTG9fhoDPIeBvr6SuDg504qbk9WH88tVzaLsiRPdk8X92BlZurvnrz%2BgRmD4roihJOJZY7j2YjQBdpB5Mq1rptDPNb0cyoOAuR4HpoUNessKUc%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/V7YybYnqErILhlD4NCc%2B
I/OtaApp  ,( 2610): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update : 200 : {"proceed":true,"context":"ota","contextKey":"XT1072","content":{"serviceControlEnabled":"true","preInstallNotes":"","optionalUpdateCancelReminderDays":14,"serviceTimeoutSeconds":60,"wifionly":"true","upgradeNotification":"<br>\n<br><a href=https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374>Information<\/a>. <br>\n<br> Android&#153; 5.0, Lollipop&#174;","showDownloadOptions":"false","preInstallNotificationExpiryMins":1440,"lowDataStorageReminder":86400,"showPreDownloadDialog":"true","size":263329787,"forced":"false","showPreInstallScreen":"true","md5_checksum":"1c15cb429a15d27979de836903ee927a","forceUpgradeTime":-1,"version":"Blur_Version.22.46.12.thea_reteu.reteuall.en.EU","packageID":"delta-ota-Blur_Version.22.21.28-22.46.12.thea_reteu.reteuall.en.EU.zip.79f4ac4c-f0e7-4447-9691-9a752588436b","lowDataStorageDeferCount":-1,"postInstallNotes":"","showDownloadProgress":"true","releaseNotes":"https:\/\/motorola-global-en-uk.custhelp.com\/app\/answers\/prod_answer_detail\/a_id\/107374","showPostInstallScreen":"true","preDownloadNotificationExpiryMins":1440,"optionalUpdateDeferCount":-1,"uiWorkflowControl":{"notification":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"setup":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"user":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true},"polling":{"forced":false,"showPreInstallScreen":true,"wifionly":true,"preDownloadNotificationExpiryMins":1440,"showDownloadOptions":false,"showDownloadProgress":true,"preInstallNotificationExpiryMins":1440,"rebootRequired":true,"showPreDownloadDialog":true,"showPostInstallScreen":true}},"fingerprint":"motorola\/thea_reteu\/thea:5.0.2\/LXB22.46-28\/27:user\/release-keys","rebootRequired":"true","annoy":"60","flavour":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","installTime":10,"policyBundle":false,"postInstallFailureMessage":"","downloadUrl":"","minBatteryRequiredForInstall":25,"continueOnServiceError":"true","reserveSpaceInMb":0,"d2denabled":"false","criticalUpdateDeferCount":-1,"minVersion":"Blur_Version.22.21.28.thea_reteu.reteuall.en.EU","trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"TRIGGER-POLLING,POLL_1446466325942"},"contentTimestamp":1445419042000,"contentResources":[{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/0IKQ2q9lsvcjoJkpA0tikHb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B050WFYMNrGLsDB14%2BSIjX2%2BffVYrcksDn8LfDD7fuDEjZZbOLQ2IYRZH0OBs89rbCjKvM2bLJff981eAxqnurhZIefs5d31igWCgFpEuL2jYd8Ga%2FHG5YIZGvMz2BhBljCMhdXEZlkONQinyzoHzLwdezR7oVTOKlSK4fC4cPXD2n%2B4IbjTU7KbOBmqsWK2oolPBKwNkGVq8Kzx3u49cZ3FsJZcWBmhrdNWoppRi8zVaYeqrXyqNMMkv7BIgpB8j33%2Ff0eQjE6fto949gFMbVZvGan%2F14zdzS5j5Un9GoG9EmBnXmOHjp%2BhhZ9bI2eVuM%2FPw%2B3PZkRedrbf8mTQdBxckdFB%2BCxth5z9vV9sAdTUVi6yiomz3MFujLszM8CEEDkYt5gjMgKTUEwWO7DtOX9D5OiTsHBqMh5NvQbzGBXo6V6vmPHsjJ%2B1wTXLr4WBkayQhPeuks7euPsMOyW%2BILsMUmY4RMddW%2BbN86f8IW%2BF1xX7eeCfBFhvuui%2Bl50dadQFAU3Yg9SSHg7OqTG9fhoDPIeBvr6SuDg504qbk9WH88tVzaLsiRPdk8X92BlZurvnrz%2BgRmD4roihJOJZY7j2YjQBdpB5Mq1rptDPNb0cyoOAuR4HpoUNessKUc%3D","headers":{},"tags":["WIFI","URL_GCS_SIGNED","DLMGR_AGENT"],"urlTtlSeconds":600},{"url":"https:\/\/dlmgr.gtm.svcmot.com\/dl\/dlws\/1\/download\/V7YybYnqErILhlD4NCc%2BEXb98SYvcz3La8G7Q%2FzZfF%2Fx2%2B
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > AndroidPollingManager.handleIntent: com.motorola.blur.service.blur.upgrade_poll
,I/OtaApp  ( 2610): [info] > Next Polling is scheduled at 1439 mins from now
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > PollingManagerService, registerApp(): cUsPollingService
,D/OtaApp  ( 2610): [debug] > PollingManagerService, registerApp(): cUsPollingService already registered.
,D/OtaApp  ( 2610): [debug] > PollingManagerService, modifyApp(): cUsPollingService
D/OtaApp  ( 2610): [debug] > calculateShortestInterval(): shortest interval is 985000
,I/OtaApp  ( 2610): [info] > CusSM.handleNewVersion: was notified of a new version : src Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: dest Blur_Version.22.46.12.thea_reteu.reteuall.en.EU: current Blur_Version.22.21.28.thea_reteu.reteuall.en.EU: size 263329787: contentTimeStamp 1445419042000
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2610): [info] > Device is NOT rooted. persist.qe=qe 0/0
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2610): [error] > UpgradeSource.isUpgradeAcceptable succeeded 
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > prevDestVersion = Blur_Version.22.46.12.thea_reteu.reteuall.en.EU
,W/OtaApp  ( 2610): [warn] > CusSM.handleNewVersion: already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,E/OtaApp  ( 2610): [error] > CusSM.failNotify: notification failed from repository upgrade for reason already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; additional information: polling initiated upgrade
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1454535006763, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2610): [debug] > exec insert into status (_id, time, dev, src, dest, state, status, info, Repository, reportingTag, trackingId) values (NULL, 1454535006776, ?, ?, ?, ?, ?, ?, ?, ?, ?) data
,D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2610): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  NotifiedBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EURepository: upgrade; Location: null; AddOnInfo: polling initiated upgradehttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741454535006786true
,D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; Repository: upgrade; Location: null; AddOnInfo: polling initiated upgrade; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1454535006
,E/CdsService( 2610): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2610): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2610): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,I/CdsService( 2610): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2610): [d] > appending web service request to serviceHandler
,I/OtaApp  ( 2610): [info] > OTAUpgradeSource.handleCheckWSResponse: check_for_update handle new version returned false
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > BotaFotaResolver.parse got the following check order (bota); assuming only bota is enabled
D/OtaApp  ( 2610): [debug] > OTAUpgradeSource.handleCheckWSResponse: authoritative response from BOTA ERR_NOTFOUND
,D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: already sending status
,D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2610): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: server told to :wait
,D/CdsService( 2610): [d] > appending web service response to serviceHandler
D/CdsService( 2610): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/check/ctx/ota/key/XT1072 from queue
,D/CdsService( 2610): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/CdsService( 2610): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
,D/OtaApp  ( 2610): [debug] > Inside handleStateResponse
,D/OtaApp  ( 2610): [debug] > exec delete from status where _id=1
,D/OtaApp  ( 2610): [debug] > stopTimer, cancel()
,D/OtaApp  ( 2610): [debug] > handleStateResponse server told to : continue
D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: send status to MDPM
D/OtaApp  ( 2610): [debug] > sendUpgradeStatus: sending sticky intent  ACTION_UPGRADE_UPDATE_STATUS  ResultBlur_Version.22.21.28.thea_reteu.reteuall.en.EUBlur_Version.22.46.12.thea_reteu.reteuall.en.EUalready working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OKhttps://motorola-global-en-uk.custhelp.com/app/answers/prod_answer_detail/a_id/1073741454535007989true
,D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: cur: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; src: Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; dest: Blur_Version.22.46.12.thea_reteu.reteuall.en.EU; upgradeSource:upgrade; already working on version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU with status RS_TEMP_OK; reportingTag: ; trackingId: 1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E; metaDataVersion: null; ro.carrier: reteu. time: 1454535006
,E/CdsService( 2610): [e] > Failed to parse int value from string null exception :java.lang.NumberFormatException: Invalid int: "null"
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2610): [d] > Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,D/CdsService( 2610): [d] > State Request getUrl(): url is https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,I/CdsService( 2610): [i] > Received web service call for request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2610): [d] > appending web service request to serviceHandler
,D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2610): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2610): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2610): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2610): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  888): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: already sending status
D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: already sending status
D/CdsService( 2610): [d] > appending web service response to serviceHandler
,D/CdsService( 2610): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Notified/ctx/ota/key/XT1072 from queue
,W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2610): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2610): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2610): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2610): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2610): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2610): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/CdsService( 2610): [d] > success response : {"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}
,D/CdsService( 2610): [d] > InternalResponseHandler:onTransact() response string from WebService{"statusCode":200,"payload":{"proceed":true,"context":"ota","contextKey":"XT1072","content":null,"contentTimestamp":1445419042000,"contentResources":null,"trackingId":"1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E","reportingTags":"","pollAfterSeconds":86400}}
D/OtaApp  ( 2610): [debug] > Inside handleStateResponse
D/OtaApp  ( 2610): [debug] > exec delete from status where _id=2
,D/OtaApp  ( 2610): [debug] > stopTimer, have stoped, do nothing
D/OtaApp  ( 2610): [debug] > handleStateResponse server told to : continue
D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: getVersions's version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU; getDescription's versionBlur_Version.22.21.28.thea_reteu.reteuall.en.EU
I/OtaApp  ( 2610): [info] > CusSM.runStateMachine: found version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU in database with state (RequestPermission)
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: server told to :continue
D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: user is being notified for version Blur_Version.22.21.28.thea_reteu.reteuall.en.EU
D/OtaApp  ( 2610): [debug] > CusSM.runStateMachine: getDownloadOptStartStopTime text null
,D/OtaApp  ( 2610): [debug] > Receive intent: com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION
,D/OtaApp  ( 2610): [debug] > UpdateReceiver: Received true from doSanityCheck.
D/OtaApp  ( 2610): [debug] > In cancelAnyPendingIntentSetPreviously
,I/ActivityManager(  888): START u0 {act=com.motorola.blur.service.blur.Actions.UPGRADE_UPDATE_NOTIFICATION flg=0x30000000 cmp=com.motorola.ccc.ota/.ui.DownloadActivity (has extras)} from uid 10000 on display 0
,W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
,W/ContextImpl( 1483): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2610): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2610): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2610): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2610): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > CusSM.sendUpgradeStatus: no unlogged events.
D/CdsService( 2610): [d] > appending web service response to serviceHandler
,D/CdsService( 2610): [d] > Removing request :https://moto-cds.appspot.com/cds/upgrade/1/state/t/1-E8890B803207D12A83FF198BF0316EFD4D0B66443BA86BE9FA351F0D85CB43DCEFBB84CA5ABB6B5C8125EBD5EFB36D5E/s/Result/ctx/ota/key/XT1072 from queue
D/CdsService( 2610): [d] > No pending web request. shutdown webservice
,D/OtaApp  ( 2610): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2610): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2610): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2610): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,I/CdsService( 2610): [i] > Stopping webservice android service
,D/Checkin ( 2610): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  300): NetlinkHandler, power_supply subsys
I/MDMCTBK (  300): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  300): checkDefaultInst, current pid is = 300
I/MDMCTBK (  300): checkDefaultInst, pid match
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  300): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  300): MdmCutbackHndler,Could not open ''
,D/BatteryService(  888): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311158, SEQNUM=4432, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-2323, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2432): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  888): User[0] Flushing usage stats to disk
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6954): 
D/AndroidRuntime( 6954): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6954): CheckJNI is OFF
D/AndroidRuntime( 6954): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  888): Force stopping com.test.thalitest appid=10503 user=-1: uninstall pkg
I/ActivityManager(  888): Killing 6797:com.test.thalitest/u0a503 (adj 11): stop com.test.thalitest
W/PackageSettings(  888): Skipping PackageSetting{387ee29f com.example.hello/10440} due to missing metadata
W/ActivityManager(  888): Spurious death for ProcessRecord{637f1c7 6797:com.test.thalitest/u0a503}, curProc for 6797: null
I/ActivityManager(  888): Force stopping com.test.thalitest appid=10503 user=0: pkg removed
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
I/InputReader(  888): Reconfiguring input devices.  changes=0x00000010
I/LaunchCheckinHandler(  888): cleanup(): cleared. Last call was 444184 ms ago
I/ActivityManager(  888): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6973 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator( 1424): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1424): run()
I/art     ( 3230): Explicit concurrent mark sweep GC freed 10574(2MB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 7MB/12MB, paused 19.303ms total 79.899ms
I/art     ( 1575): Explicit concurrent mark sweep GC freed 4406(279KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 485us total 45.905ms
I/Decoder ( 1424): createOrResetDecoder
I/ConfigService( 1731): onCreate
D/BackupManagerService(  888): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  888): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  888): removeObsoleteFile: deleting file=6_task.xml
I/art     ( 1962): Explicit concurrent mark sweep GC freed 21173(1233KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 14MB/19MB, paused 1.515ms total 185.223ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1424): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1424): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1424): run()
I/StatsUtilsManager( 1424): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1424): shouldRecordStats() = Too Soon
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24058d3f)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@520860c)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@10f8eb55)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a6e496a)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1d4fbe5b)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1c55f6f8)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3da9e7d1)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@229f9236)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2841e537)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@376f8aa4)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3594300d)
D/VoicemailCleanupService( 6973): Cleaning up data for package: com.test.thalitest
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2dca9bc2)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34c59dd3)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@126cad10)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f60c009)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@26aab20e)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3dc2442f)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27d78a3c)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@94c53c5)
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@663e11a)
I/ActivityManager(  888): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7007 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  888): Explicit concurrent mark sweep GC freed 19017(1342KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 20MB/30MB, paused 2.346ms total 269.890ms
I/art     (  888): WaitForGcToComplete blocked for 144.549ms for cause Explicit
I/ContactLocale( 6973): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
E/DataBuffer( 1731): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b38f44b)
W/asset   ( 7007): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7007): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7007): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7007): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  888): Explicit concurrent mark sweep GC freed 2353(124KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.794ms total 130.688ms
I/ActivityManager(  888): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7030 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  888): Killing 6555:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
W/libprocessgroup(  888): failed to open /acct/uid_10105/pid_6555/cgroup.procs: No such file or directory
W/ContextImpl( 7030): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/AndroidRuntime( 6954): Shutting down VM
D/PackageBroadcastService( 1962): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1962): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1962): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1962): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1962): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1731): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1731): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1962): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
I/ActivityManager(  888): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7055 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1962): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1962): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1962): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1962): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1962): doRemovePackageData com.test.thalitest
W/Launcher( 1575): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@16044ca0 new=com.google.android.velvet.VelvetApplication@16044ca0
I/Launcher( 1575): Deferring update until onResume
I/ActivityManager(  888): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7079 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
E/MP-Decision( 2171): Error(-22) changing core 3 status to offline
E/MP-Decision( 2171): Error(-22) changing core 2 status to offline
E/MP-Decision( 2171): Error(-22) changing core 1 status to offline

```
