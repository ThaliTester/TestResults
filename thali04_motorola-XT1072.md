#### Test 58259810381ca4f_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6662): 
D/AndroidRuntime( 6662): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6662): CheckJNI is OFF
D/AndroidRuntime( 6662): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6681 uid=10504 gids={50504, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6662): Shutting down VM
V/ActivityManager(  879): Display changed displayId=0
W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6681): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6681): Time to load native libraries: 1 ms (timestamps 7429-7430)
I/LibraryLoader( 6681): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6681): Binding Chromium to main looper Looper (main, tid 1) {e1092f0}
,I/LibraryLoader( 6681): Expected native library version number "",actual native library version number ""
,I/chromium( 6681): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6681): Initializing chromium process, singleProcess=true
,W/art     ( 6681): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6681): ApplicationContext is null in ApplicationStatus
,W/chromium( 6681): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6681): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6681): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6681): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6681): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6681): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6681): Local Branch: 
I/Adreno-EGL( 6681): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6681): Local Patches: NONE
I/Adreno-EGL( 6681): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  879): Message: 20
,D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2431a585:true
,I/art     (  879): Explicit concurrent mark sweep GC freed 15870(738KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.585ms total 121.760ms
,W/ActivityManager(  879): Activity pause timeout for ActivityRecord{479dcf6 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6681): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6681): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6681): CordovaWebView is running on device made by: motorola
,W/art     ( 6681): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6681): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6681): Render dirty regions requested: true
,D/Atlas   ( 6681): Validating map...
,W/chromium( 6681): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6681): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6681): Enabling debug mode 0
,I/Keyboard.Facilitator( 1409): onFinishInput()
I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,897
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +825ms (total +897ms)
W/IInputConnectionWrapper( 6681): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6681): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6681): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6681): Cannot call determinedVisibility() - never saw a connection for the pid: 6681
D/JsMessageQueue( 6681): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6681): JniHelper::setJavaVM(0xb8551310), pthread_self() = -1198650344
I/chromium( 6681): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6681): Initializing JXcore engine
W/jxcore-log( 6681): JXcore engine is ready
,W/Thread-812( 6729): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10504 path="socket:[7342]" dev="sockfs" ino=7342 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-812( 6729): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10504 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-812( 6729): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10504 path="socket:[9475]" dev="sockfs" ino=9475 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-812( 6729): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10504 path="socket:[27536]" dev="sockfs" ino=27536 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6681): Starting JXcore engine
,W/jxcore-log( 6681): Platform android
W/jxcore-log( 6681): 
W/jxcore-log( 6681): Process ARCH arm
W/jxcore-log( 6681): 
,I/jxcore-log( 6681): JXcore Cordova bridge is ready!
I/jxcore-log( 6681): 
W/jxcore-log( 6681): JXcore engine is started
,E/jxcore  ( 6681): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6681): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6681): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  879): Killing 6426:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6426/cgroup.procs: No such file or directory
W/PluginManager( 6681): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2592): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2592): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2592): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2592): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2592): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2592): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6681): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1409): onFinishInput()
,D/TaskPersister(  879): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 5
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1409): run()
I/Keyboard.Facilitator( 1409): flushDynamicLanguageModels()
,I/ConfigService( 1687): onCreate
,I/ConfigService( 1687): onDestroy
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311560, SEQNUM=4436, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=9790, POWER_SUPPLY_CHARGE_COUNTER=-637, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2483): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310927, SEQNUM=4437, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-483, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2483): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {232701a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {63dfc5f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  879): send {325a72ad, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  879): done {63dfc5f, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [24ms]
,V/AlarmManager(  879): done {325a72ad, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [34ms]
,V/AlarmManager(  879): done {232701a, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/EventLogService( 1939): Aggregate from 1454578931973 (log), 1454577658388 (data)
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {232701a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {8f51857, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {8f51857, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,V/AlarmManager(  879): done {232701a, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {8f51857, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  879): done {8f51857, *walarm*:android.content.syncmanager.SYNC_ALARM} [4ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {232701a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {285fcbc7, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  879): done {285fcbc7, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [20ms]
,V/AlarmManager(  879): done {232701a, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310586, SEQNUM=4442, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1655, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2483): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {232701a, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {3ca95f4, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  879): done {3ca95f4, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [19ms]
,V/AlarmManager(  879): done {232701a, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311452, SEQNUM=4445, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-21, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2483): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310279, SEQNUM=4446, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-211, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2483): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6780): 
D/AndroidRuntime( 6780): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6780): CheckJNI is OFF
D/AndroidRuntime( 6780): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10504 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 6681:com.test.thalitest/u0a504 (adj 13): stop com.test.thalitest
W/PackageSettings(  879): Skipping PackageSetting{8daac41 com.example.hello/10440} due to missing metadata
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10504 user=0: pkg removed
I/art     ( 3029): Explicit concurrent mark sweep GC freed 10554(2MB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 7MB/12MB, paused 927us total 36.749ms
W/ActivityManager(  879): Spurious death for ProcessRecord{5aa611d 6681:com.test.thalitest/u0a504}, curProc for 6681: null
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1687): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6808 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
I/art     ( 1571): Explicit concurrent mark sweep GC freed 4293(273KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 490us total 124.601ms
I/Decoder ( 1409): createOrResetDecoder
I/ConfigService( 1687): onCreate
I/art     ( 1939): Explicit concurrent mark sweep GC freed 20462(1185KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 14MB/19MB, paused 1.041ms total 189.138ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
I/art     (  879): Explicit concurrent mark sweep GC freed 21245(1449KB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 20MB/30MB, paused 1.719ms total 179.466ms
I/art     (  879): WaitForGcToComplete blocked for 179.732ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 6808): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6832 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 6808): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  879): removeObsoleteFile: deleting file=6_task.xml
W/asset   ( 6832): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6832): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6832): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6832): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  879): Explicit concurrent mark sweep GC freed 5080(267KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.447ms total 227.231ms
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6854 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6310:com.android.vending/u0a32 (adj 15): empty #7
I/Launcher( 1571): Deferring update until onResume
D/AndroidRuntime( 6780): Shutting down VM
W/libprocessgroup(  879): failed to open /acct/uid_10032/pid_6310/cgroup.procs: No such file or directory
W/ContextImpl( 6854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1939): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
E/NetworkScheduler.SchedulerReceiver( 1687): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1687): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6879 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1939): doRemovePackageData com.test.thalitest
W/Launcher( 1571): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@286d97fa new=com.google.android.velvet.VelvetApplication@286d97fa
I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6903 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
