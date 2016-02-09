#### Test 586983493da948e_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6671): 
D/AndroidRuntime( 6671): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6671): CheckJNI is OFF
D/AndroidRuntime( 6671): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  892): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6690 uid=10518 gids={50518, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6671): Shutting down VM
V/ActivityManager(  892): Display changed displayId=0
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6690): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6690): Time to load native libraries: 4 ms (timestamps 7443-7447)
,I/LibraryLoader( 6690): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6690): Binding Chromium to main looper Looper (main, tid 1) {3974fcc}
,I/LibraryLoader( 6690): Expected native library version number "",actual native library version number ""
,I/chromium( 6690): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6690): Initializing chromium process, singleProcess=true
,W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6690): ApplicationContext is null in ApplicationStatus
,W/chromium( 6690): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6690): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6690): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6690): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6690): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6690): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6690): Local Branch: 
I/Adreno-EGL( 6690): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6690): Local Patches: NONE
I/Adreno-EGL( 6690): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  892): Message: 20
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31f8fcd3:true
W/ActivityManager(  892): Activity pause timeout for ActivityRecord{1317690c u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6690): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6690): CordovaWebView is running on device made by: motorola
,W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6690): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6690): Render dirty regions requested: true
,D/Atlas   ( 6690): Validating map...
,W/chromium( 6690): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6690): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6690): Enabling debug mode 0
,I/Keyboard.Facilitator( 1426): onFinishInput()
,I/LaunchCheckinHandler(  892): Displayed com.test.thalitest/.MainActivity,cp,ca,1041
,I/ActivityManager(  892): Displayed com.test.thalitest/.MainActivity: +967ms (total +1s41ms)
,W/IInputConnectionWrapper( 6690): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6690): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6690): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6690): Cannot call determinedVisibility() - never saw a connection for the pid: 6690
,D/JsMessageQueue( 6690): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6690): JniHelper::setJavaVM(0xb733f310), pthread_self() = -1217593232
,I/chromium( 6690): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/art     ( 6690): Suspending all threads took: 16.464ms
,W/jxcore-log( 6690): Initializing JXcore engine
W/jxcore-log( 6690): JXcore engine is ready
,I/art     ( 6690): Background sticky concurrent mark sweep GC freed 3475(292KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 19.187ms total 47.933ms
,W/Thread-807( 6738): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10518 path="socket:[5809]" dev="sockfs" ino=5809 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-807( 6738): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10518 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-807( 6738): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10518 path="socket:[7461]" dev="sockfs" ino=7461 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-807( 6738): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10518 path="socket:[31439]" dev="sockfs" ino=31439 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6690): Starting JXcore engine
,W/jxcore-log( 6690): Platform android
W/jxcore-log( 6690): 
W/jxcore-log( 6690): Process ARCH arm
W/jxcore-log( 6690): 
,I/jxcore-log( 6690): JXcore Cordova bridge is ready!
I/jxcore-log( 6690): 
,W/jxcore-log( 6690): JXcore engine is started
,E/jxcore  ( 6690): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6690): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6690): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  892): Killing 6457:com.google.android.talk/u0a70 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10070/pid_6457/cgroup.procs: No such file or directory
,W/PluginManager( 6690): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 32ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1481): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2603): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2603): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2603): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2603): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2603): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2603): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6690): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1426): onFinishInput()
,D/TaskPersister(  892): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  892): send {1f2d4daf, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  892): send {3f3724b5, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  892): done {3f3724b5, *walarm*:android.content.syncmanager.SYNC_ALARM} [6ms]
,V/AlarmManager(  892): done {1f2d4daf, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1426): run()
I/Keyboard.Facilitator( 1426): flushDynamicLanguageModels()
,I/ConfigService( 1757): onCreate
,I/ConfigService( 1757): onDestroy
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311989, SEQNUM=4423, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-730, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2455): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  892): send {1f2d4daf, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): send {2851e924, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  892): send {2c01853b, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  892): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6764 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
V/AlarmManager(  892): done {2851e924, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [58ms]
,V/AlarmManager(  892): done {1f2d4daf, *alarm*:android.intent.action.TIME_TICK} [98ms]
,I/GAv4    ( 6764): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6764):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6764):   adb logcat -s GAv4
,W/GAv4    ( 6764): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6764): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6764): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  892): done {2c01853b, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [334ms]
,I/ActivityManager(  892): Killing 6495:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  892): failed to open /acct/uid_10007/pid_6495/cgroup.procs: No such file or directory
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  892): send {1f2d4daf, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): send {39dfe458, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  892): done {39dfe458, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [24ms]
,V/AlarmManager(  892): done {1f2d4daf, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  892): User[0] Flushing usage stats to disk
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6812): 
D/AndroidRuntime( 6812): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6812): CheckJNI is OFF
D/AndroidRuntime( 6812): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  892): Force stopping com.test.thalitest appid=10518 user=-1: uninstall pkg
I/ActivityManager(  892): Killing 6690:com.test.thalitest/u0a518 (adj 9): stop com.test.thalitest
W/PackageSettings(  892): Skipping PackageSetting{325b396d com.example.hello/10440} due to missing metadata
I/ActivityManager(  892): Force stopping com.test.thalitest appid=10518 user=0: pkg removed
I/art     ( 3246): Explicit concurrent mark sweep GC freed 10115(2MB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 7MB/12MB, paused 1.010ms total 36.946ms
I/art     ( 1583): Explicit concurrent mark sweep GC freed 4325(275KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 513us total 49.151ms
W/ActivityManager(  892): Spurious death for ProcessRecord{ff739b1 6690:com.test.thalitest/u0a518}, curProc for 6690: null
I/Keyboard.Facilitator( 1426): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1426): run()
I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1565): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/GeofencerStateMachine( 1757): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1426): createOrResetDecoder
I/ActivityManager(  892): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6841 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1964): Explicit concurrent mark sweep GC freed 21028(1218KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 14MB/19MB, paused 1.023ms total 132.705ms
I/ConfigService( 1757): onCreate
I/art     (  892): Explicit concurrent mark sweep GC freed 19577(1372KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 20MB/30MB, paused 1.540ms total 150.503ms
I/art     (  892): WaitForGcToComplete blocked for 119.970ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1426): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1426): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1426): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1426): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1426): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1426): run()
I/StatsUtilsManager( 1426): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1426): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 6841): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6866 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  892): removeObsoleteFile: deleting file=6_task.xml
I/ContactLocale( 6841): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  892): Explicit concurrent mark sweep GC freed 3560(187KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.543ms total 184.140ms
D/AndroidRuntime( 6812): Shutting down VM
W/asset   ( 6866): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6866): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6866): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6866): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/SFPerfTracer(  278):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:251 vsyncs) (2:1015)
I/ActivityManager(  892): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6884 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  892): Killing 6547:com.google.android.apps.plus/u0a90 (adj 15): empty #7
W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_6547/cgroup.procs: No such file or directory
I/Launcher( 1583): Deferring update until onResume
W/ContextImpl( 6884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1964): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1964): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1964): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1964): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1757): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1757): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1964): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1964): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1964): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1964): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1964): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1964): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1964): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1964): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1964): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1964): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1964): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1964): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1964): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1964): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1964): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6913 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/SQLiteLog( 1964): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Icing   ( 1964): doRemovePackageData com.test.thalitest
--------- beginning of crash
E/AndroidRuntime( 1964): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1964): Process: com.google.android.gms, PID: 1964
E/AndroidRuntime( 1964): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1964): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1964): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1964): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 1964): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1964): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1964): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1964): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1964): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1964): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/FileUtils( 1964): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1964): Failed to open Apps corpus file.
E/Icing   ( 1964): Failed to open Apps corpus file.
E/SharedPreferencesImpl( 1964): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
E/DropBoxManagerService(  892): Can't write: system_app_crash
E/DropBoxManagerService(  892): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 1964): Sending signal. PID: 1964 SIG: 9
D/ConnectivityService(  892): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@319d3289)
D/WifiService(  892): Client connection lost with reason: 4
D/ConnectivityService(  892): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  892): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  892): Process com.google.android.gms (pid 1964) has died
W/ActivityManager(  892): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
W/ActivityManager(  892): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  892): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 11000ms
W/ActivityManager(  892): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
W/ActivityManager(  892): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms

```
