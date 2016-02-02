#### Test 575312435db8e90_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5384): 
D/AndroidRuntime( 5384): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5384): CheckJNI is OFF
D/AndroidRuntime( 5384): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5403 uid=10490 gids={50490, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5384): Shutting down VM
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5403): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5403): Time to load native libraries: 1 ms (timestamps 7643-7644)
I/LibraryLoader( 5403): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5403): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 5403): Expected native library version number "",actual native library version number ""
,I/chromium( 5403): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5403): Initializing chromium process, singleProcess=true
,W/art     ( 5403): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5403): ApplicationContext is null in ApplicationStatus
,W/chromium( 5403): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5403): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5403): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5403): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5403): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5403): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5403): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5403): Local Branch: 
I/Adreno-EGL( 5403): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5403): Local Patches: NONE
I/Adreno-EGL( 5403): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1af9849a:true
,D/BluetoothAdapter( 5403): 343958975: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{34957ab7 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5403): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5403): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5403): CordovaWebView is running on device made by: motorola
,W/art     ( 5403): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5403): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5403): Render dirty regions requested: true
,D/Atlas   ( 5403): Validating map...
,W/chromium( 5403): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5403): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5403): Enabling debug mode 0
,I/Keyboard.Facilitator( 1408): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,997
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +909ms (total +997ms)
,W/IInputConnectionWrapper( 5403): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5403): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5403): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5403): Cannot call determinedVisibility() - never saw a connection for the pid: 5403
,D/JsMessageQueue( 5403): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5403): JniHelper::setJavaVM(0xb8793310), pthread_self() = -1196281080
,I/chromium( 5403): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5403): Initializing JXcore engine
W/jxcore-log( 5403): JXcore engine is ready
W/Thread-598( 5452): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10490 path="socket:[7590]" dev="sockfs" ino=7590 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-598( 5452): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10490 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-598( 5452): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10490 path="socket:[7752]" dev="sockfs" ino=7752 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-598( 5452): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10490 path="socket:[24836]" dev="sockfs" ino=24836 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5403): Starting JXcore engine
W/jxcore-log( 5403): Platform android
W/jxcore-log( 5403): 
W/jxcore-log( 5403): Process ARCH arm
W/jxcore-log( 5403): 
,I/jxcore-log( 5403): JXcore Cordova bridge is ready!
I/jxcore-log( 5403): 
W/jxcore-log( 5403): JXcore engine is started
,E/jxcore  ( 5403): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5403): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5403): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  882): Killing 5056:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10039/pid_5056/cgroup.procs: No such file or directory
,W/PluginManager( 5403): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2461): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2461): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2461): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2461): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2461): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2461): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5403): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1408): onFinishInput()
,D/TaskPersister(  882): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312036, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1408): run()
I/Keyboard.Facilitator( 1408): flushDynamicLanguageModels()
,I/ConfigService( 1690): onCreate
,I/ConfigService( 1690): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312296, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311984, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=10, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312265, SEQNUM=4378, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4339, POWER_SUPPLY_CHARGE_COUNTER=-6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311375, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-18, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2461): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2461): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2461): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2461): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2461):  Nonce Reponse 
I/MMApiWebService( 2461): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2461): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2461): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2461): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2461): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2461): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2461): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2461): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2461): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2461): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2461): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2461): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2461): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312231, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-46, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {3a7077c7, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {247cd01d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {247cd01d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,V/AlarmManager(  882): done {3a7077c7, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312789, SEQNUM=4381, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-95, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312512, SEQNUM=4384, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-8, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311907, SEQNUM=4385, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-60, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312776, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-16, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312188, SEQNUM=4389, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-45, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2461): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2461): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2461): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2461): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2461):  Nonce Reponse 
I/MMApiWebService( 2461): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2461): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2461): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2461): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2461): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2461): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2461): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2461): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2461): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2461): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2461): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2461): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2461): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2461): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  882): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1690): Explicit concurrent mark sweep GC freed 39106(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 13MB/21MB, paused 6.396ms total 158.746ms
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c14fd87)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@79944b4)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@66948dd)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@6f58c52)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20b9eb23)
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@14dff820)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@29b695d9)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b36167f)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@261c764c)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@30f1b695)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8ca53aa)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@31f9b9b)
,E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ac0ab38)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d842711)
E/DataBuffer( 1690): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d520076)
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311608, SEQNUM=4396, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-205, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311582, SEQNUM=4397, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-384, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311578, SEQNUM=4398, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-465, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5526): 
D/AndroidRuntime( 5526): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5526): CheckJNI is OFF
D/AndroidRuntime( 5526): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10490 user=-1: uninstall pkg
I/ActivityManager(  882): Killing 5403:com.test.thalitest/u0a490 (adj 9): stop com.test.thalitest
W/PackageSettings(  882): Skipping PackageSetting{f36067b com.example.hello/10440} due to missing metadata
W/ActivityManager(  882): Spurious death for ProcessRecord{7925b5a 5403:com.test.thalitest/u0a490}, curProc for 5403: null
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10490 user=0: pkg removed
I/art     ( 2889): Explicit concurrent mark sweep GC freed 5460(1062KB) AllocSpace objects, 26(416KB) LOS objects, 39% free, 7MB/12MB, paused 653us total 37.136ms
I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
W/GeofencerStateMachine( 1690): Ignoring removeGeofence because network location is disabled.
I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
D/VoicemailCleanupService( 4933): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1408): createOrResetDecoder
I/art     ( 1557): Explicit concurrent mark sweep GC freed 7376(537KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 495us total 130.344ms
I/art     ( 5006): Explicit concurrent mark sweep GC freed 11418(676KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/16MB, paused 981us total 153.711ms
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5557 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ConfigService( 1690): onCreate
I/art     (  882): Explicit concurrent mark sweep GC freed 18603(1455KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 19MB/29MB, paused 3.880ms total 152.340ms
I/art     (  882): WaitForGcToComplete blocked for 32.639ms for cause Explicit
W/asset   ( 5557): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5557): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5557): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5557): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5580 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  882): removeObsoleteFile: deleting file=6_task.xml
I/art     (  882): Explicit concurrent mark sweep GC freed 5902(330KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.854ms total 146.992ms
W/ContextImpl( 5580): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 5006): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 5006): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 5006): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5006): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5006): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5006): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/AndroidRuntime( 5526): Shutting down VM
I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5602 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Launcher( 1557): Deferring update until onResume
I/LocationSettingsChecker( 5006): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 5006): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 5006): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
W/BaseAppContext( 5006): Using Auth Proxy for data requests.
D/gH_MetricsDatabase( 5006): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 5006): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/BaseAppContext( 5006): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 5006): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 5006): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 5006): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 5006): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 5006): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 5006): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 5006): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 5006): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 5006): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/GMPM-SVC( 5006): App measurement is starting up, version: 8489
I/GMPM-SVC( 5006): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/Launcher( 1557): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5625 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/Icing   ( 5006): doRemovePackageData com.test.thalitest
D/ConnectivityService(  882): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/DriveInitializer( 5006): Awaiting to be initialized
W/DriveInitializer( 5006): Background init thread started
I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5658 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
E/Vold    (  278): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
I/UpdateIcingCorporaServi( 5602): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ContextImpl( 5006): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
E/SQLiteLog( 5006): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 5006): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 5006): Background init thread ended
E/DriveAsyncService( 5006): disk I/O error (code 3850)
E/DriveAsyncService( 5006): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 5006): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 5006): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 5006): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 5006): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 5006): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 5006): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 5006): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 5006): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 5006): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 5006): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 5006): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 5006): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 5006): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 5006): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 5006): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 5006): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 5006): Process: com.google.android.gms, PID: 5006
E/AndroidRuntime( 5006): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 5006): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 5006): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/AndroidRuntime( 5006): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/AndroidRuntime( 5006): 	at com.google.android.gms.drive.database.f.e(SourceFile:858)
E/AndroidRuntime( 5006): 	at com.google.android.gms.drive.events.av.b(SourceFile:192)
E/AndroidRuntime( 5006): 	at com.google.android.gms.drive.events.av.a(SourceFile:158)
E/AndroidRuntime( 5006): 	at com.google.android.gms.drive.t.run(SourceFile:65)
I/Process ( 5006): Sending signal. PID: 5006 SIG: 9
E/DropBoxManagerService(  882): Can't write: system_app_crash
E/DropBoxManagerService(  882): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  882): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  882): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  882): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  882): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  882): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  882): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  882): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  882): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  882): 	... 5 more
E/SQLiteDatabase( 5602): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 5602): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5602): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5602): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5602): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5602): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/SQLiteDatabase( 5602): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/SQLiteDatabase( 5602): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/SQLiteDatabase( 5602): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/SQLiteDatabase( 5602): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/SQLiteDatabase( 5602): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/SQLiteDatabase( 5602): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/SQLiteDatabase( 5602): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/SQLiteDatabase( 5602): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/SQLiteDatabase( 5602): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5602): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5602): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ConnectivityService(  882): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@28faedf7)
D/ConnectivityService(  882): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  882): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5677 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/SharedPreferencesImpl( 5602): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
E/AndroidRuntime( 5602): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5602): Process: com.google.android.googlequicksearchbox:search, PID: 5602
E/AndroidRuntime( 5602): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5602): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 5602): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5602): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5602): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/AndroidRuntime( 5602): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/AndroidRuntime( 5602): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/AndroidRuntime( 5602): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/AndroidRuntime( 5602): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/AndroidRuntime( 5602): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/AndroidRuntime( 5602): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/AndroidRuntime( 5602): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/AndroidRuntime( 5602): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/AndroidRuntime( 5602): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5602): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5602): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5602): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 20.513ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 21.433ms

```
