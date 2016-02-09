#### Test 584164489c56086_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 6385): 
D/AndroidRuntime( 6385): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6385): CheckJNI is OFF
D/AndroidRuntime( 6385): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  879): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  879): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6404 uid=10519 gids={50519, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6385): Shutting down VM
V/ActivityManager(  879): Display changed displayId=0
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6404): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6404): Time to load native libraries: 1 ms (timestamps 7418-7419)
I/LibraryLoader( 6404): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6404): Binding Chromium to main looper Looper (main, tid 1) {32b4a2dd}
,I/LibraryLoader( 6404): Expected native library version number "",actual native library version number ""
,I/chromium( 6404): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6404): Initializing chromium process, singleProcess=true
W/art     ( 6404): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6404): ApplicationContext is null in ApplicationStatus
,W/chromium( 6404): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6404): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6404): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6404): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6404): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6404): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6404): Local Branch: 
I/Adreno-EGL( 6404): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6404): Local Patches: NONE
I/Adreno-EGL( 6404): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  879): Message: 20
D/BluetoothManagerService(  879): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91b67ba:true
,W/ActivityManager(  879): Activity pause timeout for ActivityRecord{11eb157 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6404): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6404): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6404): CordovaWebView is running on device made by: motorola
,W/art     ( 6404): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6404): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6404): Render dirty regions requested: true
,D/Atlas   ( 6404): Validating map...
,W/chromium( 6404): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6404): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6404): Enabling debug mode 0
,I/Keyboard.Facilitator( 1411): onFinishInput()
,I/LaunchCheckinHandler(  879): Displayed com.test.thalitest/.MainActivity,cp,ca,1046
I/ActivityManager(  879): Displayed com.test.thalitest/.MainActivity: +960ms (total +1s46ms)
,W/IInputConnectionWrapper( 6404): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6404): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6404): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6404): Cannot call determinedVisibility() - never saw a connection for the pid: 6404
,D/JsMessageQueue( 6404): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6404): JniHelper::setJavaVM(0xb801f310), pthread_self() = -1204063016
,I/chromium( 6404): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6404): Initializing JXcore engine
W/jxcore-log( 6404): JXcore engine is ready
,W/Thread-777( 6453): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10519 path="socket:[7478]" dev="sockfs" ino=7478 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-777( 6453): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10519 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-777( 6453): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10519 path="socket:[9691]" dev="sockfs" ino=9691 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-777( 6453): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10519 path="socket:[30884]" dev="sockfs" ino=30884 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6404): Starting JXcore engine
,W/jxcore-log( 6404): Platform android
W/jxcore-log( 6404): 
,W/jxcore-log( 6404): Process ARCH arm
W/jxcore-log( 6404): 
,I/jxcore-log( 6404): JXcore Cordova bridge is ready!
I/jxcore-log( 6404): 
,W/jxcore-log( 6404): JXcore engine is started
,E/jxcore  ( 6404): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6404): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6404): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  879): Killing 5994:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10039/pid_5994/cgroup.procs: No such file or directory
,W/PluginManager( 6404): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 96ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1475): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2572): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2572): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2572): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2572): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2572): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6404): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1411): onFinishInput()
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=279, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311296, SEQNUM=4419, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3734, POWER_SUPPLY_CHARGE_COUNTER=-212, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,D/TaskPersister(  879): removeObsoleteFile: deleting file=5_task.xml
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,D/MDMCTBK (  301): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  301): Event received = CTRL-EVENT-BSS-REMOVED 1
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
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311249, SEQNUM=4421, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-208, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1411): run()
I/Keyboard.Facilitator( 1411): flushDynamicLanguageModels()
,I/art     (  879): Explicit concurrent mark sweep GC freed 12471(775KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.889ms total 128.834ms
,I/ConfigService( 1708): onCreate
,I/ConfigService( 1708): onDestroy
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=273, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311755, SEQNUM=4424, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2725, POWER_SUPPLY_CHARGE_COUNTER=15, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {16ad7134, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): done {16ad7134, *alarm*:android.intent.action.TIME_TICK} [102ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312313, SEQNUM=4426, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4844, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=271, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312014, SEQNUM=4429, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=17, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311997, SEQNUM=4430, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=20, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  879): send {16ad7134, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {1b0cc5c2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  879): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6484 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  879): done {16ad7134, *alarm*:android.intent.action.TIME_TICK} [94ms]
,I/GAv4    ( 6484): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6484):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6484):   adb logcat -s GAv4
,W/GAv4    ( 6484): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6484): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6484): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  879): done {1b0cc5c2, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [377ms]
,I/ActivityManager(  879): Killing 6190:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  879): failed to open /acct/uid_10007/pid_6190/cgroup.procs: No such file or directory
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312291, SEQNUM=4433, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311984, SEQNUM=4436, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-57, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {16ad7134, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {2ac3ebb6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  879): send {1ebd7fd3, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  879): done {2ac3ebb6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [18ms]
,V/AlarmManager(  879): done {16ad7134, *alarm*:android.intent.action.TIME_TICK} [45ms]
,V/AlarmManager(  879): done {1ebd7fd3, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [47ms]
,I/EventLogService( 1956): Aggregate from 1455009622768 (log), 1455008301392 (data)
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311085, SEQNUM=4439, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  879): send {16ad7134, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  879): send {178643c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  879): done {178643c, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [24ms]
,V/AlarmManager(  879): done {16ad7134, *alarm*:android.intent.action.TIME_TICK} [52ms]
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311383, SEQNUM=4442, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-123, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311362, SEQNUM=4443, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-50, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  879): User[0] Flushing usage stats to disk
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311366, SEQNUM=4444, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-127, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312244, SEQNUM=4445, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-96, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2453): Disconnected process message: 10, size: 0
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  301): NetlinkHandler, power_supply subsys
I/MDMCTBK (  301): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  301): checkDefaultInst, current pid is = 301
I/MDMCTBK (  301): checkDefaultInst, pid match
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  301): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  301): MdmCutbackHndler,Could not open ''
,D/BatteryService(  879): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311937, SEQNUM=4446, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-65, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  318): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6532): 
D/AndroidRuntime( 6532): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6532): CheckJNI is OFF
D/AndroidRuntime( 6532): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10519 user=-1: uninstall pkg
I/ActivityManager(  879): Killing 6404:com.test.thalitest/u0a519 (adj 11): stop com.test.thalitest
W/PackageSettings(  879): Skipping PackageSetting{275e6735 com.example.hello/10440} due to missing metadata
W/ActivityManager(  879): Spurious death for ProcessRecord{113525c5 6404:com.test.thalitest/u0a519}, curProc for 6404: null
I/ActivityManager(  879): Force stopping com.test.thalitest appid=10519 user=0: pkg removed
I/InputReader(  879): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1708): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  879): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6552 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator( 1411): resetDictionaries() : en_US
I/art     ( 3008): Explicit concurrent mark sweep GC freed 11788(2MB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 7MB/12MB, paused 817us total 61.161ms
I/Keyboard.Facilitator.DecoderInitializer( 1411): run()
I/Decoder ( 1411): createOrResetDecoder
I/ConfigService( 1708): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): run()
D/BackupManagerService(  879): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  879): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  879): removeObsoleteFile: deleting file=6_task.xml
I/art     ( 1956): Explicit concurrent mark sweep GC freed 22017(1293KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 14MB/19MB, paused 16.569ms total 195.265ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = contacts
I/art     ( 1570): Explicit concurrent mark sweep GC freed 4343(276KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 525us total 84.228ms
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1411): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1411): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1411): run()
I/StatsUtilsManager( 1411): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1411): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 6552): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  879): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6585 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  322): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.132ms
I/ContactLocale( 6552): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  879): Explicit concurrent mark sweep GC freed 15402(1241KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/30MB, paused 5.356ms total 322.033ms
I/art     (  879): WaitForGcToComplete blocked for 151.785ms for cause Explicit
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 251us total 20.253ms
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.289ms
W/asset   ( 6585): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6585): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6585): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6585): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  879): Explicit concurrent mark sweep GC freed 2021(108KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.709ms total 125.186ms
I/ActivityManager(  879): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6606 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  879): Killing 6240:com.google.android.apps.plus/u0a90 (adj 15): empty #7
W/libprocessgroup(  879): failed to open /acct/uid_10090/pid_6240/cgroup.procs: No such file or directory
D/AndroidRuntime( 6532): Shutting down VM
W/ContextImpl( 6606): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1956): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1956): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1956): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1956): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1956): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1956): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1708): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1708): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1956): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1956): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1956): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1956): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1956): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1956): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1956): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  879): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6629 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1956): doRemovePackageData com.test.thalitest
W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3c808d9e new=com.google.android.velvet.VelvetApplication@3c808d9e
I/ActivityManager(  879): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6654 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/Launcher( 1570): Deferring update until onResume
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
