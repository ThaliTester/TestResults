#### Test 5813565532fb33b_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,D/AndroidRuntime( 6646): 
D/AndroidRuntime( 6646): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6646): CheckJNI is OFF
D/AndroidRuntime( 6646): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6665 uid=10501 gids={50501, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6646): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6665): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6665): Time to load native libraries: 2 ms (timestamps 7370-7372)
,I/LibraryLoader( 6665): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6665): Binding Chromium to main looper Looper (main, tid 1) {3a99e1f8}
I/LibraryLoader( 6665): Expected native library version number "",actual native library version number ""
,I/chromium( 6665): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6665): Initializing chromium process, singleProcess=true
,W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6665): ApplicationContext is null in ApplicationStatus
,W/chromium( 6665): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6665): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6665): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6665): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6665): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6665): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6665): Local Branch: 
I/Adreno-EGL( 6665): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6665): Local Patches: NONE
I/Adreno-EGL( 6665): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f3ca744:true
,W/ActivityManager(  885): Activity pause timeout for ActivityRecord{161608b9 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6665): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6665): CordovaWebView is running on device made by: motorola
,W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6665): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6665): Render dirty regions requested: true
,D/Atlas   ( 6665): Validating map...
,W/chromium( 6665): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6665): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6665): Enabling debug mode 0
,I/Keyboard.Facilitator( 1424): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,913
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +829ms (total +913ms)
,W/IInputConnectionWrapper( 6665): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6665): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6665): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6665): Cannot call determinedVisibility() - never saw a connection for the pid: 6665
,D/JsMessageQueue( 6665): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6665): JniHelper::setJavaVM(0xb8a79310), pthread_self() = -1193236656
,I/chromium( 6665): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6665): Initializing JXcore engine
W/jxcore-log( 6665): JXcore engine is ready
,W/Thread-787( 6713): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10501 path="socket:[7345]" dev="sockfs" ino=7345 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-787( 6713): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10501 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-787( 6713): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10501 path="socket:[8924]" dev="sockfs" ino=8924 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-787( 6713): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10501 path="socket:[32337]" dev="sockfs" ino=32337 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6665): Starting JXcore engine
,W/jxcore-log( 6665): Platform android
W/jxcore-log( 6665): 
,W/jxcore-log( 6665): Process ARCH arm
W/jxcore-log( 6665): 
,I/jxcore-log( 6665): JXcore Cordova bridge is ready!
I/jxcore-log( 6665): 
W/jxcore-log( 6665): JXcore engine is started
,E/jxcore  ( 6665): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6665): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6665): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  885): Killing 6097:android.process.acore/u0a7 (adj 15): empty #7
,W/PluginManager( 6665): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 27ms. Plugin should use CordovaInterface.getThreadPool().
W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_6097/cgroup.procs: No such file or directory
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2627): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2627): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2627): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2627): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2627): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2627): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6665): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1424): onFinishInput()
,D/TaskPersister(  885): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  295): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  295): Event received = CTRL-EVENT-BSS-REMOVED 4
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1424): run()
I/Keyboard.Facilitator( 1424): flushDynamicLanguageModels()
,I/ConfigService( 1719): onCreate
,I/ConfigService( 1719): onDestroy
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311686, SEQNUM=4442, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=9, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1719): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311660, SEQNUM=4444, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311954, SEQNUM=4446, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312227, SEQNUM=4447, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,D/ConnectivityService(  885): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10016
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): ValidatedState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): DefaultState{ when=-3ms what=532488 arg1=10016 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Checking http://clients3.google.com/generate_204 on "NG700"
,I/ActivityManager(  885): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6755 uid=10070 gids={50070, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 52.440ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 42.200ms
,W/ResourcesManager( 6755): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.445ms
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 19:38:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454528317286], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454528317256]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  885): Validated
,D/ConnectivityService(  885): Validated NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  885): rematching NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  885): Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
D/ConnectivityService(  885): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityManager.CallbackHandler( 1294): CM callback handler got msg 524290
,I/art     (  885): Explicit concurrent mark sweep GC freed 19289(1055KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.452ms total 113.436ms
,I/Babel_SMS( 6755): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6755): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6755): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
I/Babel_SMS( 6755): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6755): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6755): MmsConfig.loadFromResources
,E/Babel_SMS( 6755): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6755): MmsConfig.loadMmsSettings: mUserAgent=MOT-XT1072/Mms-5.0, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/motoxt1072/Profile/motoxt1072-row.rdf
,W/Settings( 6755): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6755): startup - clean
,I/Babel   ( 6755): deleted: false for 0
,W/VideoCapabilities( 6755): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6755): Unsupported mime audio/amr-wb-plus
,W/VideoCapabilities( 6755): Unsupported mime video/mpeg2
,I/VideoCapabilities( 6755): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6755): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6755): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6755): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6755): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  885): Killing 6281:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10057/pid_6281/cgroup.procs: No such file or directory
,I/vclib   ( 6755): onServiceConnected
W/Babel   ( 6755): Attempted to change video mute state without an active call.
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {2f639518, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {2575a353, *walarm*:com.google.android.intent.action.GCM_RECONNECT}
,V/AlarmManager(  885): done {2575a353, *walarm*:com.google.android.intent.action.GCM_RECONNECT} [10ms]
,V/AlarmManager(  885): done {2f639518, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311894, SEQNUM=4458, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311621, SEQNUM=4460, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {2f639518, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {2919f4b3, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): done {2919f4b3, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [9ms]
,V/AlarmManager(  885): done {2f639518, *alarm*:android.intent.action.TIME_TICK} [46ms]
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
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311591, SEQNUM=4461, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-85, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {2f639518, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {5401740, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  885): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6829 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  885): done {2f639518, *alarm*:android.intent.action.TIME_TICK} [96ms]
,I/GAv4    ( 6829): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6829):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6829):   adb logcat -s GAv4
,W/GAv4    ( 6829): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6829): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6829): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  885): done {5401740, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [188ms]
,I/ActivityManager(  885): Killing 6480:com.google.android.apps.docs.editors.sheets/u0a105 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10105/pid_6480/cgroup.procs: No such file or directory
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311574, SEQNUM=4472, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-90, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
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
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311552, SEQNUM=4473, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4844, POWER_SUPPLY_CHARGE_COUNTER=-92, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311846, SEQNUM=4475, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-108, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311548, SEQNUM=4476, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-113, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311846, SEQNUM=4477, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-135, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2473): Disconnected process message: 10, size: 0
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  307): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6878): 
D/AndroidRuntime( 6878): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6878): CheckJNI is OFF
D/AndroidRuntime( 6878): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10501 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 6665:com.test.thalitest/u0a501 (adj 11): stop com.test.thalitest
W/PackageSettings(  885): Skipping PackageSetting{1568a3a9 com.example.hello/10440} due to missing metadata
W/ActivityManager(  885): Spurious death for ProcessRecord{3edf9679 6665:com.test.thalitest/u0a501}, curProc for 6665: null
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10501 user=0: pkg removed
W/GeofencerStateMachine( 1719): Ignoring removeGeofence because network location is disabled.
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 1557): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6898 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator( 1424): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1424): run()
I/art     ( 3023): Explicit concurrent mark sweep GC freed 11373(2MB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 7MB/12MB, paused 711us total 85.444ms
I/Decoder ( 1424): createOrResetDecoder
I/ConfigService( 1719): onCreate
I/art     ( 1574): Explicit concurrent mark sweep GC freed 4464(283KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 495us total 89.979ms
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  885): removeObsoleteFile: deleting file=6_task.xml
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): run()
D/VoicemailCleanupService( 6898): Cleaning up data for package: com.test.thalitest
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
I/art     (  885): Explicit concurrent mark sweep GC freed 15398(1157KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 20MB/30MB, paused 2.225ms total 170.289ms
I/art     (  885): WaitForGcToComplete blocked for 116.240ms for cause Explicit
I/ContactLocale( 6898): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6931 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
W/asset   ( 6931): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6931): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6931): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6931): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/AndroidRuntime( 6878): Shutting down VM
I/art     (  885): Explicit concurrent mark sweep GC freed 2126(114KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.743ms total 134.699ms
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6952 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6379:com.google.android.gms/u0a16 (adj 15): empty #7
W/libprocessgroup(  885): failed to open /acct/uid_10016/pid_6379/cgroup.procs: No such file or directory
W/ContextImpl( 6952): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  885): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=6970 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
I/ActivityManager(  885): Killing 6178:com.android.vending/u0a32 (adj 15): empty #7
W/libprocessgroup(  885): failed to open /acct/uid_10032/pid_6178/cgroup.procs: No such file or directory
W/ResourcesManager( 6970): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6970): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6970): VM with version 2.1.0 has multidex support
I/MultiDex( 6970): install
I/MultiDex( 6970): VM has multidex support, MultiDex support library is disabled.
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
