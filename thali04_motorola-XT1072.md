#### Test 5024228542a63d7_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/AndroidRuntime( 6444): 
D/AndroidRuntime( 6444): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6444): CheckJNI is OFF
E/global frequency( 2575): no tags to log
D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1536): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6444): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6464 uid=10426 gids={50426, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6444): Shutting down VM
I/art     ( 1468): Explicit concurrent mark sweep GC freed 56786(3MB) AllocSpace objects, 37(1262KB) LOS objects, 39% free, 7MB/12MB, paused 964us total 46.111ms
D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1536): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/WebViewFactory( 6464): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6464): Time to load native libraries: 1 ms (timestamps 4130-4131)
I/LibraryLoader( 6464): Expected native library version number "",actual native library version number ""
,I/art     (  881): Explicit concurrent mark sweep GC freed 34995(1725KB) AllocSpace objects, 2(218KB) LOS objects, 33% free, 20MB/30MB, paused 1.768ms total 137.601ms
,V/WebViewChromiumFactoryProvider( 6464): Binding Chromium to main looper Looper (main, tid 1) {23e096f5}
,I/LibraryLoader( 6464): Expected native library version number "",actual native library version number ""
,I/chromium( 6464): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6464): Initializing chromium process, singleProcess=true
,W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6464): ApplicationContext is null in ApplicationStatus
,W/chromium( 6464): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6464): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6464): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6464): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6464): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6464): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6464): Local Branch: 
I/Adreno-EGL( 6464): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6464): Local Patches: NONE
I/Adreno-EGL( 6464): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1536): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BluetoothManagerService(  881): Message: 20
,D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19b6869a:true
,I/art     ( 1468): Explicit concurrent mark sweep GC freed 4184(185KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 518us total 26.696ms
,I/art     ( 2575): Explicit concurrent mark sweep GC freed 32247(1784KB) AllocSpace objects, 4(110KB) LOS objects, 40% free, 11MB/18MB, paused 1.212ms total 81.080ms
,D/BSUtils ( 2575): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2575): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2575): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2575): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2575): publish the event [tag = DEV_ATTRIBS event name = SW]
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{57c74b7 u0 com.example.hello/.MainActivity t3}
,D/Checkin ( 2575): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6464): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6464): CordovaWebView is running on device made by: motorola
,I/global frequency( 2575): BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6464): Attempt to remove local handle scope entry from IRT, ignoring
D/Checkin ( 2575): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/OpenGLRenderer( 6464): Render dirty regions requested: true
,D/Atlas   ( 6464): Validating map...
,W/chromium( 6464): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6464): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6464): Enabling debug mode 0
,I/Keyboard.Facilitator( 1414): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.example.hello/.MainActivity,cp,ca,826
,I/ActivityManager(  881): Displayed com.example.hello/.MainActivity: +728ms (total +826ms)
,W/IInputConnectionWrapper( 6464): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6464): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6464): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6464): Cannot call determinedVisibility() - never saw a connection for the pid: 6464
,I/chromium( 6464): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 6464): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 6464): Unable to open asset URL: file:///android_asset/www/jxcore.js
,V/AlarmManager(  881): send {36e29a97, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {36e29a97, *walarm*:com.google.android.intent.action.SEND_IDLE} [9ms]
,D/jxcore_app_log( 6464): JniHelper::setJavaVM(0xb7109310), pthread_self() = -1219908864
,D/JX-Cordova( 6464): jxcore cordova android initializing
,W/jxcore-log( 6464): Initializing JXcore engine
W/jxcore-log( 6464): JXcore engine is ready
,I/PhenotypeConfigurator( 1684): Scheduling Phenotype for one-off execution 11110 seconds from now (1452276756630)
,W/Thread-802( 6524): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10426 path="socket:[6801]" dev="sockfs" ino=6801 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-802( 6524): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10426 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-802( 6524): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10426 path="socket:[7462]" dev="sockfs" ino=7462 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-802( 6524): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10426 path="socket:[27964]" dev="sockfs" ino=27964 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6464): Starting JXcore engine
,D/GetConfigurationSnapshotOperation( 1684): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1684): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1684): Using platform SSLCertificateSocketFactory
,W/jxcore-log( 6464): Platform android
W/jxcore-log( 6464): 
W/jxcore-log( 6464): Process ARCH arm
W/jxcore-log( 6464): 
,I/jxcore-log( 6464): JXcore Cordova bridge is ready!
I/jxcore-log( 6464): 
,W/jxcore-log( 6464): JXcore engine is started
,E/jxcore  ( 6464): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 6464): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:267:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ClearcutLoggerApiImpl( 1684): disconnect managed GoogleApiClient
,V/AlarmManager(  881): send {34f0e2ec, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {384632dd, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  881): done {384632dd, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [6ms]
,V/AlarmManager(  881): done {34f0e2ec, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1414): run()
I/Keyboard.Facilitator( 1414): flushDynamicLanguageModels()
,I/ConfigService( 1684): onCreate
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ConfigService( 1684): onDestroy
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312524, SEQNUM=4415, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-417, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2447): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2447): Disconnected process message: 10, size: 0
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,D/MDMCTBK (  293): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 1
D/MDMCTBK (  293): Event received = CTRL-EVENT-BSS-REMOVED 1
,V/AlarmManager(  881): send {34f0e2ec, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {d781fd9, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6555 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  881): done {34f0e2ec, *alarm*:android.intent.action.TIME_TICK} [85ms]
,I/GAv4    ( 6555): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6555):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6555):   adb logcat -s GAv4
,W/GAv4    ( 6555): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6555): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6555): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {d781fd9, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [185ms]
,I/ActivityManager(  881): Killing 6173:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_6173/cgroup.procs: No such file or directory
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=253, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312460, SEQNUM=4420, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-478, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2447): Disconnected process message: 10, size: 0
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 6592): 
D/AndroidRuntime( 6592): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6592): CheckJNI is OFF
D/AndroidRuntime( 6592): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.example.hello appid=10426 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6464:com.example.hello/u0a426 (adj 0): stop com.example.hello
I/WindowState(  881): WIN DEATH: Window{8dca4a u0 com.example.hello/com.example.hello.MainActivity}
I/WindowState(  881): WIN DEATH: Window{1666a425 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  881): Skipping PackageSetting{2d4f511c com.test.thalitest/10425} due to missing metadata
I/ActivityManager(  881):   Force finishing activity ActivityRecord{57c74b7 u0 com.example.hello/.MainActivity t3}
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  881): Spurious death for ProcessRecord{10afdd9e 6464:com.example.hello/u0a426}, curProc for 6464: null
I/ActivityManager(  881): Force stopping com.example.hello appid=10426 user=0: pkg removed
I/ActivityManager(  881):   Force finishing activity ActivityRecord{57c74b7 u0 com.example.hello/.MainActivity t3 f}
W/ActivityManager(  881): Duplicate finish request for ActivityRecord{57c74b7 u0 com.example.hello/.MainActivity t3 f}
I/art     ( 2989): Explicit concurrent mark sweep GC freed 9576(2MB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 7MB/12MB, paused 816us total 36.344ms
I/Keyboard.Facilitator( 1414): resetDictionaries() : en_US
W/ContextImpl( 1468): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/GeofencerStateMachine( 1684): Ignoring removeGeofence because network location is disabled.
I/art     ( 1559): Explicit concurrent mark sweep GC freed 4375(278KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 502us total 43.936ms
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1414): run()
D/OtaApp  ( 2575): [debug] > DownloadActivity, FormattedText
I/Decoder ( 1414): createOrResetDecoder
I/OtaApp  ( 2575): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2575): publish the event [tag = MOT_OTA event name = LOG]
D/VoicemailCleanupService( 6252): Cleaning up data for package: com.example.hello
I/art     ( 1938): Explicit concurrent mark sweep GC freed 20935(1267KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/19MB, paused 1.110ms total 135.058ms
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6623 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/OtaApp  ( 2575): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2575): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
I/ConfigService( 1684): onCreate
D/Checkin ( 2575): publish the event [tag = MOT_OTA event name = LOG]
I/art     (  881): Explicit concurrent mark sweep GC freed 21078(1287KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 1.453ms total 134.736ms
I/art     (  881): WaitForGcToComplete blocked for 76.003ms for cause Explicit
W/InputMethodManagerService(  881): Got RemoteException sending setActive(false) notification to pid 6464 uid 10426
I/Keyboard.Facilitator( 1414): onFinishInput()
W/asset   ( 6623): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6623): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6623): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6623): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1414): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = history
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1414): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1414): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1414): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1414): run()
I/StatsUtilsManager( 1414): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1414): shouldRecordStats() = Too Soon
I/art     (  881): Explicit concurrent mark sweep GC freed 5147(254KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 5.006ms total 166.478ms
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6649 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6306:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 6592): Shutting down VM
W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6306/cgroup.procs: No such file or directory
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
I/Launcher( 1559): Deferring update until onResume
W/ContextImpl( 6649): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1938): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1938): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1684): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1684): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1938): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1938): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1938): 0 metrics were deleted when clearing package com.example.hello.
D/gH_CompatibleDatabase( 1938): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1938): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1938): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1938): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1938): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1938): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1938): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1938): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1938): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1938): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6671 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/Icing   ( 1938): doRemovePackageData com.example.hello
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@246b33d7 new=com.google.android.velvet.VelvetApplication@246b33d7
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6697 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
