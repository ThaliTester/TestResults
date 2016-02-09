#### Test 583805004f2b042_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 6474): 
D/AndroidRuntime( 6474): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6474): CheckJNI is OFF
D/AndroidRuntime( 6474): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6493 uid=10526 gids={50526, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6474): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6493): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6493): Time to load native libraries: 3 ms (timestamps 8131-8134)
,I/LibraryLoader( 6493): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6493): Binding Chromium to main looper Looper (main, tid 1) {37487900}
I/LibraryLoader( 6493): Expected native library version number "",actual native library version number ""
,I/chromium( 6493): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6493): Initializing chromium process, singleProcess=true
,W/art     ( 6493): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6493): ApplicationContext is null in ApplicationStatus
,W/chromium( 6493): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6493): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6493): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6493): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6493): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6493): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6493): Local Branch: 
I/Adreno-EGL( 6493): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6493): Local Patches: NONE
I/Adreno-EGL( 6493): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@71066aa:true
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{335fc487 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6493): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6493): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6493): CordovaWebView is running on device made by: motorola
,W/art     ( 6493): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6493): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6493): Render dirty regions requested: true
,D/Atlas   ( 6493): Validating map...
,W/chromium( 6493): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (1:214 vsyncs) (3:1126)
,I/OpenGLRenderer( 6493): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6493): Enabling debug mode 0
,I/Keyboard.Facilitator( 1414): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1041
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +952ms (total +1s41ms)
,W/IInputConnectionWrapper( 6493): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6493): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 6493): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6493): Cannot call determinedVisibility() - never saw a connection for the pid: 6493
,D/JsMessageQueue( 6493): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6493): JniHelper::setJavaVM(0xb7a77310), pthread_self() = -1210022568
,I/chromium( 6493): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6493): Initializing JXcore engine
W/jxcore-log( 6493): JXcore engine is ready
,W/Thread-783( 6542): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10526 path="socket:[5842]" dev="sockfs" ino=5842 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-783( 6542): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10526 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-783( 6542): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10526 path="socket:[9422]" dev="sockfs" ino=9422 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-783( 6542): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10526 path="socket:[31075]" dev="sockfs" ino=31075 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6493): Starting JXcore engine
,W/jxcore-log( 6493): Platform android
W/jxcore-log( 6493): 
,W/jxcore-log( 6493): Process ARCH arm
W/jxcore-log( 6493): 
,I/jxcore-log( 6493): JXcore Cordova bridge is ready!
I/jxcore-log( 6493): 
,W/jxcore-log( 6493): JXcore engine is started
,E/jxcore  ( 6493): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6493): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6493): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  880): Killing 6190:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_6190/cgroup.procs: No such file or directory
,W/PluginManager( 6493): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 37ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2573): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2573): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2573): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2573): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2573): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2573): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1414): onFinishInput()
,W/IInputConnectionWrapper( 6493): showStatusIcon on inactive InputConnection
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  301): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  301): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/Keyboard.Facilitator.LanguageModelFlusher( 1414): run()
I/Keyboard.Facilitator( 1414): flushDynamicLanguageModels()
,I/ConfigService( 1717): onCreate
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311298, SEQNUM=4427, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-850, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2454): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2454): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1717): onDestroy
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {2f117a74, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {2f117a74, *alarm*:android.intent.action.TIME_TICK} [37ms]
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
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {2f117a74, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2ff1ceb2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  880): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6565 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  880): done {2f117a74, *alarm*:android.intent.action.TIME_TICK} [81ms]
,I/GAv4    ( 6565): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6565):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6565):   adb logcat -s GAv4
,W/GAv4    ( 6565): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6565): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6565): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  880): done {2ff1ceb2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [244ms]
,I/ActivityManager(  880): Killing 6080:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_6080/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311744, SEQNUM=4433, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-1982, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2454): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {2f117a74, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  880): send {1c0cf41b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {1c0cf41b, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [7ms]
,V/AlarmManager(  880): done {2f117a74, *alarm*:android.intent.action.TIME_TICK} [49ms]
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
,V/AlarmManager(  880): send {2f117a74, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {269b6e03, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): done {2f117a74, *alarm*:android.intent.action.TIME_TICK} [48ms]
,V/AlarmManager(  880): done {269b6e03, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [88ms]
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
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {2f117a74, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {2f4d8def, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {2f4d8def, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  880): done {2f117a74, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ActivityManager(  880): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=6619 uid=10090 gids={50090, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 26.116ms
,W/ResourcesManager( 6619): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.029ms
,I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 19.786ms
,I/ActivityManager(  880): Killing 6304:com.google.android.gms/u0a16 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10016/pid_6304/cgroup.procs: No such file or directory
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311969, SEQNUM=4442, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-460, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2454): Disconnected process message: 10, size: 0
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {2f4d8def, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  880): done {2f4d8def, *walarm*:android.content.syncmanager.SYNC_ALARM} [3ms]
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
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6670): 
D/AndroidRuntime( 6670): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6670): CheckJNI is OFF
D/AndroidRuntime( 6670): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10526 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 6493:com.test.thalitest/u0a526 (adj 13): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{36f4311 com.example.hello/10440} due to missing metadata
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10526 user=0: pkg removed
W/GeofencerStateMachine( 1717): Ignoring removeGeofence because network location is disabled.
W/ActivityManager(  880): Spurious death for ProcessRecord{31c170f1 6493:com.test.thalitest/u0a526}, curProc for 6493: null
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
I/art     ( 3028): Explicit concurrent mark sweep GC freed 10845(2MB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 7MB/12MB, paused 795us total 70.755ms
D/VoicemailCleanupService( 5943): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6700 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1571): Explicit concurrent mark sweep GC freed 4436(281KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 469us total 90.052ms
I/Decoder ( 1414): createOrResetDecoder
I/ConfigService( 1717): onCreate
W/asset   ( 6700): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6700): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6700): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6700): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  880): Explicit concurrent mark sweep GC freed 23277(1501KB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 20MB/30MB, paused 3.091ms total 252.979ms
I/art     (  880): WaitForGcToComplete blocked for 252.935ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6724 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
I/art     ( 1717): Background sticky concurrent mark sweep GC freed 104854(5MB) AllocSpace objects, 20(343KB) LOS objects, 27% free, 16MB/22MB, paused 1.034ms total 101.823ms
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3d9fb2ca)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@37b4dc3b)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23bdef58)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@cdbe8b1)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@246e3196)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@60b0117)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1bcea904)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b955eed)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@9d3d122)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b3497b3)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@230f5170)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4f5fce9)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1501dd6e)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3456fc0f)
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
I/art     (  880): Explicit concurrent mark sweep GC freed 3324(163KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.773ms total 131.800ms
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c70149c)
D/AndroidRuntime( 6670): Shutting down VM
W/ContextImpl( 6724): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  880): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=6744 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
I/ActivityManager(  880): Killing 6107:com.android.vending/u0a32 (adj 15): empty #7
I/Launcher( 1571): Deferring update until onResume
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_6107/cgroup.procs: No such file or directory
D/TaskPersister(  880): removeObsoleteFile: deleting file=6_task.xml
W/ResourcesManager( 6744): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6744): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6744): VM with version 2.1.0 has multidex support
I/MultiDex( 6744): install
I/MultiDex( 6744): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6744): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6744): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6744): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b465fbb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6744): Installed default security provider GmsCore_OpenSSL
D/ChimeraCfgMgr( 6744): Reading stored module config
D/PackageBroadcastService( 6744): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6744): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6744): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6744): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6744): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteDatabase( 6744): Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
E/SQLiteDatabase( 6744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 6744): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:422)
E/SQLiteDatabase( 6744): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteDatabase( 6744): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteDatabase( 6744): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteDatabase( 6744): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteDatabase( 6744): 	at com.google.android.gms.reminders.a.a.a(SourceFile:66)
E/SQLiteDatabase( 6744): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteDatabase( 6744): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6744): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6744): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6744): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6744): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6744): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6744): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 6744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6744): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 6744): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6744): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6744): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6744): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 6744): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 6744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 6744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/PhenotypeInitializer( 6744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 6744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 6744): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 6744): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 6744): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 6744): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 6744): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 6744): Couldn't open reminders.db for writing (will try read-only):
E/SQLiteOpenHelper( 6744): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 6744): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 6744): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 6744): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 6744): 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:422)
E/SQLiteOpenHelper( 6744): 	at android.content.ContentProvider.query(ContentProvider.java:950)
E/SQLiteOpenHelper( 6744): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:210)
E/SQLiteOpenHelper( 6744): 	at android.content.ContentResolver.query(ContentResolver.java:478)
E/SQLiteOpenHelper( 6744): 	at android.content.ContentResolver.query(ContentResolver.java:422)
E/SQLiteOpenHelper( 6744): 	at com.google.android.gms.reminders.a.a.a(SourceFile:66)
E/SQLiteOpenHelper( 6744): 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:45)
E/SQLiteOpenHelper( 6744): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteOpenHelper( 6744): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 6744): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteOpenHelper( 6744): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 6744): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 6744): 	at java.lang.Thread.run(Thread.java:818)
W/SQLiteOpenHelper( 6744): Opened reminders.db in read-only mode
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/GMPM-SVC( 6744): App measurement is starting up, version: 8489
I/GMPM-SVC( 6744): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE

```
