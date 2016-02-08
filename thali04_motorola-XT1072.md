#### Test 581356550b07fff_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 6354): 
D/AndroidRuntime( 6354): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6354): CheckJNI is OFF
D/AndroidRuntime( 6354): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  890): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6373 uid=10514 gids={50514, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6354): Shutting down VM
V/ActivityManager(  890): Display changed displayId=0
W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6373): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6373): Time to load native libraries: 3 ms (timestamps 7532-7535)
,I/LibraryLoader( 6373): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6373): Binding Chromium to main looper Looper (main, tid 1) {2f72da22}
,I/LibraryLoader( 6373): Expected native library version number "",actual native library version number ""
,I/chromium( 6373): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6373): Initializing chromium process, singleProcess=true
,W/art     ( 6373): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6373): ApplicationContext is null in ApplicationStatus
,W/chromium( 6373): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6373): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6373): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6373): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6373): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6373): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6373): Local Branch: 
I/Adreno-EGL( 6373): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6373): Local Patches: NONE
I/Adreno-EGL( 6373): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  890): Message: 20
D/BluetoothManagerService(  890): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@271592e6:true
,W/ActivityManager(  890): Activity pause timeout for ActivityRecord{fb3c3d3 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6373): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6373): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6373): CordovaWebView is running on device made by: motorola
,W/art     ( 6373): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6373): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6373): Render dirty regions requested: true
,D/Atlas   ( 6373): Validating map...
,W/chromium( 6373): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,I/OpenGLRenderer( 6373): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6373): Enabling debug mode 0
,I/Keyboard.Facilitator( 1426): onFinishInput()
,I/LaunchCheckinHandler(  890): Displayed com.test.thalitest/.MainActivity,cp,ca,983
,W/IInputConnectionWrapper( 6373): showStatusIcon on inactive InputConnection
I/ActivityManager(  890): Displayed com.test.thalitest/.MainActivity: +912ms (total +983ms)
,E/Adreno-ES20( 6373): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6373): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6373): Cannot call determinedVisibility() - never saw a connection for the pid: 6373
,D/JsMessageQueue( 6373): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6373): JniHelper::setJavaVM(0xb7776310), pthread_self() = -1213171712
,I/chromium( 6373): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6373): Initializing JXcore engine
W/jxcore-log( 6373): JXcore engine is ready
I/art     ( 6373): Background sticky concurrent mark sweep GC freed 2586(190KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 5.472ms total 43.733ms
W/Thread-752( 6422): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10514 path="socket:[7524]" dev="sockfs" ino=7524 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-752( 6422): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10514 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-752( 6422): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10514 path="socket:[9381]" dev="sockfs" ino=9381 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-752( 6422): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10514 path="socket:[26103]" dev="sockfs" ino=26103 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 6373): Starting JXcore engine
W/jxcore-log( 6373): Platform android
W/jxcore-log( 6373): 
W/jxcore-log( 6373): Process ARCH arm
W/jxcore-log( 6373): 
,I/jxcore-log( 6373): JXcore Cordova bridge is ready!
I/jxcore-log( 6373): 
W/jxcore-log( 6373): JXcore engine is started
,E/jxcore  ( 6373): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6373): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6373): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  890): Killing 6099:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  890): failed to open /acct/uid_10057/pid_6099/cgroup.procs: No such file or directory
,W/PluginManager( 6373): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 69ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1485): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2614): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2614): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2614): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2614): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2614): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2614): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1426): onFinishInput()
W/IInputConnectionWrapper( 6373): showStatusIcon on inactive InputConnection
,D/TaskPersister(  890): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  296): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 3
D/MDMCTBK (  296): Event received = CTRL-EVENT-BSS-REMOVED 3
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1426): run()
I/Keyboard.Facilitator( 1426): flushDynamicLanguageModels()
,I/ConfigService( 1745): onCreate
,I/ConfigService( 1745): onDestroy
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  890): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310994, SEQNUM=4439, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-583, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2472): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  890): send {3ddceee0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  890): done {3ddceee0, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  890): send {3ddceee0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  890): send {4ac2d6e, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  890): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6430 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  890): done {3ddceee0, *alarm*:android.intent.action.TIME_TICK} [101ms]
,I/GAv4    ( 6430): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6430):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6430):   adb logcat -s GAv4
,W/GAv4    ( 6430): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6430): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6430): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  890): done {4ac2d6e, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [203ms]
I/ActivityManager(  890): Killing 6131:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  890): failed to open /acct/uid_10090/pid_6131/cgroup.procs: No such file or directory
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  890): send {3ddceee0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  890): send {1c014266, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  890): send {43b0c0f, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  890): done {1c014266, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [22ms]
,V/AlarmManager(  890): done {3ddceee0, *alarm*:android.intent.action.TIME_TICK} [47ms]
,V/AlarmManager(  890): done {43b0c0f, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [59ms]
,I/EventLogService( 6188): Aggregate from 1454950389539 (log), 1454948793024 (data)
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  890): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310256, SEQNUM=4447, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-2194, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2472): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  890): send {3ddceee0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  890): send {58fae88, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  890): done {58fae88, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [26ms]
,V/AlarmManager(  890): done {3ddceee0, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  890): User[0] Flushing usage stats to disk
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  890): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310801, SEQNUM=4454, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-72, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2472): Disconnected process message: 10, size: 0
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  890): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310217, SEQNUM=4455, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-117, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2472): Disconnected process message: 10, size: 0
,V/AlarmManager(  890): send {3ddceee0, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  890): send {2a8af021, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  890): done {2a8af021, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [24ms]
,V/AlarmManager(  890): done {3ddceee0, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6514): 
D/AndroidRuntime( 6514): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6514): CheckJNI is OFF
D/AndroidRuntime( 6514): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  890): Force stopping com.test.thalitest appid=10514 user=-1: uninstall pkg
I/ActivityManager(  890): Killing 6373:com.test.thalitest/u0a514 (adj 11): stop com.test.thalitest
W/PackageSettings(  890): Skipping PackageSetting{c615ecb com.example.hello/10440} due to missing metadata
W/ActivityManager(  890): Spurious death for ProcessRecord{cd87c46 6373:com.test.thalitest/u0a514}, curProc for 6373: null
I/ActivityManager(  890): Force stopping com.test.thalitest appid=10514 user=0: pkg removed
W/GeofencerStateMachine( 1745): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1426): resetDictionaries() : en_US
I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
I/art     ( 3079): Explicit concurrent mark sweep GC freed 5657(1294KB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 477us total 53.884ms
I/ActivityManager(  890): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6543 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1426): run()
D/VoicemailCleanupService( 5953): Cleaning up data for package: com.test.thalitest
I/art     ( 1578): Explicit concurrent mark sweep GC freed 6143(418KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 496us total 129.217ms
I/art     (  890): Explicit concurrent mark sweep GC freed 22079(1575KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 20MB/30MB, paused 1.630ms total 153.785ms
I/art     (  890): WaitForGcToComplete blocked for 63.354ms for cause Explicit
I/Decoder ( 1426): createOrResetDecoder
I/ConfigService( 1745): onCreate
W/asset   ( 6543): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6543): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6543): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6543): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
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
I/ActivityManager(  890): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6568 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  890): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  890): removeObsoleteFile: deleting file=6_task.xml
I/art     (  890): Explicit concurrent mark sweep GC freed 5429(271KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.407ms total 196.655ms
W/ContextImpl( 6568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6188): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6188): Reading stored module config
D/AccountUtils( 6188): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 6188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6188): Loading module APK com.google.android.play.games
I/Launcher( 1578): Deferring update until onResume
I/LocationSettingsChecker( 6188): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6188): App measurement is starting up, version: 8489
I/GMPM-SVC( 6188): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/AndroidRuntime( 6514): Shutting down VM
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6188): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6188): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6188): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6188): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6188): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6188): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6188): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  890): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6597 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 6188): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6188): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6188): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6188): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6188): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6188): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 6188): doRemovePackageData com.test.thalitest
D/ChimeraCfgMgr( 6188): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6188): Module APK com.google.android.play.games already loaded
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
E/BaseAppContext( 6188): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
W/Launcher( 1578): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@2c2ed59c new=com.google.android.velvet.VelvetApplication@2c2ed59c
I/ActivityManager(  890): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6628 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
D/ConnectivityService(  890): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  890): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  890): apparently satisfied.  currentScore=60
D/ConnectivityManager.CallbackHandler( 6188): CM callback handler got msg 524290
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
W/BaseAppContext( 6188): Using Auth Proxy for data requests.
E/SQLiteLog( 6188): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 6188): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6188): Process: com.google.android.gms, PID: 6188
E/AndroidRuntime( 6188): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6188): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6188): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6188): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6188): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6188): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6188): 	at com.google.android.gms.people.c.f.b(SourceFile:3345)
E/AndroidRuntime( 6188): 	at com.google.android.gms.people.c.f.g(SourceFile:3316)
E/AndroidRuntime( 6188): 	at com.google.android.gms.people.service.bg.f.a(SourceFile:273)
E/AndroidRuntime( 6188): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6188): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6188): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6188): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6188): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  890): Can't write: system_app_crash
E/DropBoxManagerService(  890): java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  890): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  890): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  890): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  890): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  890): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  890): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  890): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  890): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  890): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  890): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  890): 	... 5 more
I/Process ( 6188): Sending signal. PID: 6188 SIG: 9
D/ConnectivityService(  890): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@29beb9ab)
D/ConnectivityService(  890): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  890): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
