#### Test 58135655e9e7eb8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 6298): 
D/AndroidRuntime( 6298): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6298): CheckJNI is OFF
D/AndroidRuntime( 6298): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6317 uid=10521 gids={50521, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6298): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6317): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6317): Time to load native libraries: 3 ms (timestamps 7490-7493)
I/LibraryLoader( 6317): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6317): Binding Chromium to main looper Looper (main, tid 1) {417ec5f}
,I/LibraryLoader( 6317): Expected native library version number "",actual native library version number ""
,I/chromium( 6317): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6317): Initializing chromium process, singleProcess=true
,W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6317): ApplicationContext is null in ApplicationStatus
,W/chromium( 6317): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6317): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6317): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6317): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6317): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6317): Local Branch: 
I/Adreno-EGL( 6317): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6317): Local Patches: NONE
I/Adreno-EGL( 6317): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@384f074:true
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{3ff6fd29 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6317): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6317): CordovaWebView is running on device made by: motorola
,W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6317): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6317): Render dirty regions requested: true
,D/Atlas   ( 6317): Validating map...
,W/chromium( 6317): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6317): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6317): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1009
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +936ms (total +1s9ms)
,W/IInputConnectionWrapper( 6317): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6317): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6317): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6317): Cannot call determinedVisibility() - never saw a connection for the pid: 6317
,D/JsMessageQueue( 6317): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6317): JniHelper::setJavaVM(0xb8789310), pthread_self() = -1196322856
I/chromium( 6317): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6317): Initializing JXcore engine
W/jxcore-log( 6317): JXcore engine is ready
W/Thread-768( 6366): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10521 path="socket:[5850]" dev="sockfs" ino=5850 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-768( 6366): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10521 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-768( 6366): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10521 path="socket:[6009]" dev="sockfs" ino=6009 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-768( 6366): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10521 path="socket:[30814]" dev="sockfs" ino=30814 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6317): Starting JXcore engine
,W/jxcore-log( 6317): Platform android
W/jxcore-log( 6317): 
W/jxcore-log( 6317): Process ARCH arm
W/jxcore-log( 6317): 
,I/jxcore-log( 6317): JXcore Cordova bridge is ready!
I/jxcore-log( 6317): 
,W/jxcore-log( 6317): JXcore engine is started
,E/jxcore  ( 6317): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6317): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6317): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  883): Killing 6001:android.process.acore/u0a7 (adj 15): empty #7
,W/PluginManager( 6317): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 19ms. Plugin should use CordovaInterface.getThreadPool().
W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_6001/cgroup.procs: No such file or directory
,W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2564): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2564): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2564): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2564): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2564): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2564): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6317): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1416): onFinishInput()
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1745): onCreate
,I/ConfigService( 1745): onDestroy
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  308): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  308): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311199, SEQNUM=4408, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10817, POWER_SUPPLY_CHARGE_COUNTER=-1406, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2458): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {1fbd10e8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {1fbd10e8, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {1fbd10e8, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  883): send {2c8dde3c, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  883): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6376 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  883): done {1fbd10e8, *alarm*:android.intent.action.TIME_TICK} [84ms]
,I/GAv4    ( 6376): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6376):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6376):   adb logcat -s GAv4
,W/GAv4    ( 6376): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6376): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6376): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/AlarmManager(  883): done {2c8dde3c, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [176ms]
,I/ActivityManager(  883): Killing 6178:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_6178/cgroup.procs: No such file or directory
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {1fbd10e8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {16720e3e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  883): send {108617c5, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  883): done {16720e3e, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [21ms]
,V/AlarmManager(  883): done {1fbd10e8, *alarm*:android.intent.action.TIME_TICK} [47ms]
,V/AlarmManager(  883): done {108617c5, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [49ms]
,I/EventLogService( 1963): Aggregate from 1455021498485 (log), 1455020508395 (data)
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {1fbd10e8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {3e32a8e6, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  883): done {1fbd10e8, *alarm*:android.intent.action.TIME_TICK} [49ms]
,V/AlarmManager(  883): done {3e32a8e6, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [91ms]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311056, SEQNUM=4418, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-2976, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2458): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {1fbd10e8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {247139ec, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  883): done {247139ec, *walarm*:android.content.syncmanager.SYNC_ALARM} [11ms]
,V/AlarmManager(  883): done {1fbd10e8, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {1fbd10e8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {32ec2e27, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  883): done {32ec2e27, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [24ms]
,V/AlarmManager(  883): done {1fbd10e8, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311009, SEQNUM=4421, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-3606, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2458): Disconnected process message: 10, size: 0
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  322): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6443): 
D/AndroidRuntime( 6443): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6443): CheckJNI is OFF
D/AndroidRuntime( 6443): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10521 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 6317:com.test.thalitest/u0a521 (adj 11): stop com.test.thalitest
W/PackageSettings(  883): Skipping PackageSetting{3765a064 com.example.hello/10440} due to missing metadata
W/ActivityManager(  883): Spurious death for ProcessRecord{3dc9b8d4 6317:com.test.thalitest/u0a521}, curProc for 6317: null
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10521 user=0: pkg removed
I/art     ( 3012): Explicit concurrent mark sweep GC freed 10994(2MB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 7MB/12MB, paused 2.347ms total 31.533ms
W/GeofencerStateMachine( 1745): Ignoring removeGeofence because network location is disabled.
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1555): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6462 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
I/art     ( 5920): Explicit concurrent mark sweep GC freed 762(42KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 387us total 130.583ms
I/art     ( 1573): Explicit concurrent mark sweep GC freed 4319(274KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 502us total 132.600ms
I/Decoder ( 1416): createOrResetDecoder
I/art     ( 1963): Explicit concurrent mark sweep GC freed 36109(2MB) AllocSpace objects, 8(128KB) LOS objects, 24% free, 14MB/19MB, paused 1.096ms total 193.364ms
I/ConfigService( 1745): onCreate
I/art     (  883): Explicit concurrent mark sweep GC freed 24092(1629KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 20MB/30MB, paused 3.606ms total 179.702ms
I/art     (  883): WaitForGcToComplete blocked for 181.053ms for cause Explicit
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
D/VoicemailCleanupService( 6462): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
I/ContactLocale( 6462): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6495 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  883): removeObsoleteFile: deleting file=6_task.xml
I/art     (  883): Explicit concurrent mark sweep GC freed 4798(239KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.916ms total 188.433ms
I/Launcher( 1573): Deferring update until onResume
W/asset   ( 6495): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6495): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6495): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6518 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  883): Killing 5920:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 6443): Shutting down VM
W/ContextImpl( 6518): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  883): failed to open /acct/uid_10039/pid_5920/cgroup.procs: No such file or directory
D/PackageBroadcastService( 1963): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1963): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1963): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1963): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1963): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1963): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1963): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1963): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1963): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1963): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1963): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1963): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1963): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1963): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1963): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1963): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1963): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1963): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6543 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/art     (  331): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 22.415ms
I/Icing   ( 1963): doRemovePackageData com.test.thalitest
I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.090ms
I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.171ms
W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@d5c4df1 new=com.google.android.velvet.VelvetApplication@d5c4df1
I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6567 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
