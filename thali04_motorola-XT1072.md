#### Test 52383621d5a0cb8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 6406): 
D/AndroidRuntime( 6406): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6406): CheckJNI is OFF
D/AndroidRuntime( 6406): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6425 uid=10339 gids={50339, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6406): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 6425): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6425): Time to load native libraries: 1 ms (timestamps 7770-7771)
I/LibraryLoader( 6425): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6425): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 6425): Expected native library version number "",actual native library version number ""
I/chromium( 6425): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6425): Initializing chromium process, singleProcess=true
W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6425): ApplicationContext is null in ApplicationStatus
W/chromium( 6425): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6425): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6425): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6425): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6425): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6425): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6425): Local Branch: 
I/Adreno-EGL( 6425): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6425): Local Patches: NONE
I/Adreno-EGL( 6425): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a855cb3:true
W/ActivityManager(  881): Activity pause timeout for ActivityRecord{2f70696c u0 com.test.thalitest/.MainActivity t3}
W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6425): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6425): CordovaWebView is running on device made by: motorola
W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6425): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6425): Render dirty regions requested: true
D/Atlas   ( 6425): Validating map...
W/chromium( 6425): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6425): Initialized EGL, version 1.4
D/OpenGLRenderer( 6425): Enabling debug mode 0
I/Keyboard.Facilitator( 1417): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,932
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +845ms (total +932ms)
W/IInputConnectionWrapper( 6425): showStatusIcon on inactive InputConnection
E/Adreno-ES20( 6425): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6425): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
W/BindingManager( 6425): Cannot call determinedVisibility() - never saw a connection for the pid: 6425
D/JsMessageQueue( 6425): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 6425): JniHelper::setJavaVM(0xb6ffa310), pthread_self() = -1221022360
D/JX-Cordova( 6425): jxcore cordova android initializing
,W/jxcore-log( 6425): Initializing JXcore engine
W/jxcore-log( 6425): JXcore engine is ready
,W/jxcore-log( 6425): Starting JXcore engine
,W/.test.thalitest( 6425): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10339 path="socket:[5798]" dev="sockfs" ino=5798 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6425): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10339 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/.test.thalitest( 6425): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10339 path="socket:[9602]" dev="sockfs" ino=9602 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 6425): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10339 path="socket:[27371]" dev="sockfs" ino=27371 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6425): Platform android
W/jxcore-log( 6425): 
,W/jxcore-log( 6425): Process ARCH arm
W/jxcore-log( 6425): 
,I/jxcore-log( 6425): JXcore Cordova bridge is ready!
I/jxcore-log( 6425): 
,W/jxcore-log( 6425): JXcore engine is started
,I/chromium( 6425): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 6425): Error!: Cannot find module '../server-address.js'
E/jxcore  ( 6425): Stack: [{"_fileName":"module.js","_functionName":"Module._oldRes","_lineNumber":"776","_columnNumber":"15","_msg":"    at Module._oldRes@module.js:776:15"},{"_fileName":"module.js","_functionName":"Module._resolveFilename","_lineNumber":"1608","_columnNumber":"1","_msg":"    at Module._resolveFilename@module.js:1608:1"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"337","_columnNumber":"18","_msg":"    at Module._load@module.js:337:18"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"11","_columnNumber":"21","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21"},{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"597","_columnNumber":"10","_msg":"    at Module.prototype._compile@module.js:597:10"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"}]
,I/chromium( 6425): [INFO:CONSOLE(37)] "App.js file failed to load : "Cannot find module '../server-address.js'\nError: Cannot find module '../server-address.js'\n    at Module._oldRes@module.js:776:15\n    at Module._resolveFilename@module.js:1608:1\n    at Module._load@module.js:337:18\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:11:21\n    at Module.prototype._compile@module.js:597:10\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  881): Killing 6137:com.motorola.MotGallery2/u0a27 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10027/pid_6137/cgroup.procs: No such file or directory
,W/PluginManager( 6425): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2631): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2631): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2631): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2631): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2631): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2631): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6425): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1417): onFinishInput()
,E/global frequency( 2631): no tags to log
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 57587(3MB) AllocSpace objects, 37(1254KB) LOS objects, 39% free, 7MB/12MB, paused 888us total 61.073ms
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1551): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2631): Explicit concurrent mark sweep GC freed 40789(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 11MB/18MB, paused 1.271ms total 88.337ms
,I/art     (  881): Explicit concurrent mark sweep GC freed 23727(1246KB) AllocSpace objects, 3(231KB) LOS objects, 33% free, 20MB/30MB, paused 1.469ms total 119.435ms
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 4344(181KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 570us total 34.289ms
,D/BSUtils ( 2631): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2631): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2631): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2631): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2631): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2631): BcsDSCheckin.events found events 103
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2631): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/MMApiWSBase( 2631): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWSBase( 2631): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2631): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2631): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 2631): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  881): 103 events delete 0 left
,I/global frequency( 2631): BcsDSCheckin.events found events 0
,D/Checkin ( 2631): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2631): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/DataUsage( 2631): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2631): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  881): send {2984b91b, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {2984b91b, *walarm*:com.google.android.intent.action.SEND_IDLE} [8ms]
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312216, SEQNUM=4466, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14122, POWER_SUPPLY_CHARGE_COUNTER=-470, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1609): disconnect managed GoogleApiClient
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311207, SEQNUM=4468, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13020, POWER_SUPPLY_CHARGE_COUNTER=-622, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,I/ClearcutLoggerApiImpl( 1722): disconnect managed GoogleApiClient
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  881): send {1e340626, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {23cb3ab8, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  881): done {23cb3ab8, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [9ms]
,V/AlarmManager(  881): done {1e340626, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1417): run()
I/Keyboard.Facilitator( 1417): flushDynamicLanguageModels()
,I/ConfigService( 1609): onCreate
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3abda3bb)
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2843e0d8)
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1278bc31)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@25a53f16)
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@198c097)
,E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4823284)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2cebea6d)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f2e36a2)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e9ecf33)
E/DataBuffer( 1609): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2131f2f0)
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1609): onDestroy
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:30000 mC
,D/MDMCTBK (  289): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 7
D/MDMCTBK (  289): Event received = CTRL-EVENT-BSS-REMOVED 7
,V/AlarmManager(  881): send {1e340626, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {39554a64, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6503 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  881): done {1e340626, *alarm*:android.intent.action.TIME_TICK} [83ms]
,I/GAv4    ( 6503): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6503):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6503):   adb logcat -s GAv4
,W/GAv4    ( 6503): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6503): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6503): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {39554a64, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [329ms]
,I/ActivityManager(  881): Killing 6256:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_6256/cgroup.procs: No such file or directory
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
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312238, SEQNUM=4474, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-1201, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
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
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311897, SEQNUM=4475, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-1591, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
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
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {1e340626, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {10dd8c87, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {10dd8c87, *walarm*:android.content.syncmanager.SYNC_ALARM} [10ms]
,V/AlarmManager(  881): done {1e340626, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {136f04c6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): send {1e340626, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {135354cd, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT}
,V/AlarmManager(  881): done {136f04c6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [11ms]
,V/AlarmManager(  881): done {1e340626, *alarm*:android.intent.action.TIME_TICK} [44ms]
,V/AlarmManager(  881): done {135354cd, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT} [53ms]
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
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {1e340626, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {1dfc182, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  881): done {1dfc182, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [24ms]
,V/AlarmManager(  881): done {1e340626, *alarm*:android.intent.action.TIME_TICK} [41ms]
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311854, SEQNUM=4480, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-2564, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
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
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311542, SEQNUM=4481, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-2557, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311235, SEQNUM=4482, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311235, SEQNUM=4484, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310659, SEQNUM=4486, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-11, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311823, SEQNUM=4487, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-61, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  289): NetlinkHandler, power_supply subsys
I/MDMCTBK (  289): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  289): checkDefaultInst, current pid is = 289
I/MDMCTBK (  289): checkDefaultInst, pid match
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  289): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  289): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2513): Disconnected process message: 10, size: 0
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
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {1e340626, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {136f04c6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): send {17f5c5f4, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  881): send {2b4ea8d0, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  881): send {8cd70c9, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  881): send {135354cd, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT}
V/AlarmManager(  881): send {1c4c73ce, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.WeeklyAlarmTrigger}
,I/ActivityManager(  881): Killing 6025:com.google.android.googlequicksearchbox:search/u0a39 (adj 13): empty for 1804s
,I/ActivityManager(  881): Killing 6214:com.google.android.apps.plus/u0a90 (adj 13): empty for 1805s
,V/AlarmManager(  881): done {136f04c6, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [104ms]
,W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_6214/cgroup.procs: No such file or directory
,I/ProcessStatsService(  881): Prepared write state in 78ms
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_6025/cgroup.procs: No such file or directory
,V/AlarmManager(  881): done {17f5c5f4, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [198ms]
,I/ProcessStatsService(  881): Prepared write state in 13ms
,I/ProcessStatsService(  881): Prepared write state in 7ms
,V/AlarmManager(  881): done {1e340626, *alarm*:android.intent.action.TIME_TICK} [238ms]
,V/AlarmManager(  881): done {2b4ea8d0, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [244ms]
,V/AlarmManager(  881): done {8cd70c9, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [255ms]
,V/AlarmManager(  881): done {135354cd, *walarm*:com.google.android.intent.action.MCS_HEARTBEAT} [271ms]
,V/AlarmManager(  881): done {1c4c73ce, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.WeeklyAlarmTrigger} [273ms]
,I/EventLogService( 1958): Aggregate from 1449056465215 (log), 1449055852449 (data)
,V/GLSActivity( 1609): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1609): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Checkin ( 3059): publish the event [tag = MOT_DEVICE_STATS_L3 event name = SystemLocale]
,I/ProcessStatsService(  881): Pruning old procstats: /data/system/procstats/state-2015-12-01-12-15-53.bin
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  302): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 6589): 
D/AndroidRuntime( 6589): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6589): CheckJNI is OFF
D/AndroidRuntime( 6589): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10339 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 6425:com.test.thalitest/u0a339 (adj 13): stop com.test.thalitest
W/ActivityManager(  881): Spurious death for ProcessRecord{11c264f5 6425:com.test.thalitest/u0a339}, curProc for 6425: null
W/PackageSettings(  881): Skipping PackageSetting{f36067b com.example.hello/10333} due to missing metadata
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10339 user=0: pkg removed
I/art     ( 3059): Explicit concurrent mark sweep GC freed 11192(2MB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 7MB/12MB, paused 722us total 34.209ms
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1722): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6612 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 22.029ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 24.797ms
I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 256us total 20.577ms
I/Decoder ( 1417): createOrResetDecoder
I/ConfigService( 1609): onCreate
I/art     ( 1570): Explicit concurrent mark sweep GC freed 4416(280KB) AllocSpace objects, 4(184KB) LOS objects, 25% free, 13MB/17MB, paused 508us total 182.911ms
I/art     (  881): Explicit concurrent mark sweep GC freed 25136(1771KB) AllocSpace objects, 14(306KB) LOS objects, 33% free, 20MB/30MB, paused 4.784ms total 219.741ms
I/art     (  881): WaitForGcToComplete blocked for 126.241ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
D/VoicemailCleanupService( 6612): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1417): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1417): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1417): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1417): run()
I/StatsUtilsManager( 1417): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1417): shouldRecordStats() = Too Soon
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6641 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 6612): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
W/asset   ( 6641): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6641): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6641): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6641): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Launcher( 1570): Deferring update until onResume
I/art     (  881): Explicit concurrent mark sweep GC freed 5638(288KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.008ms total 181.410ms
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6659 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6163:com.android.vending/u0a32 (adj 15): empty for 1856s
D/AndroidRuntime( 6589): Shutting down VM
W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6163/cgroup.procs: No such file or directory
W/ContextImpl( 6659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  881): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6680 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Finsky  ( 6680): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 6680): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6680): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6680): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 6680): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 6680): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6680): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6680): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6680): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/SQLiteDatabase( 6680): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/SQLiteDatabase( 6680): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6680): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6680): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6680): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Finsky.CrashDetector( 6680): Failed to write crash file cnt=0, ts=0.
W/Finsky.CrashDetector( 6680): java.io.FileNotFoundException: /data/data/com.android.vending/cache/crash804300: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 6680): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/Finsky.CrashDetector( 6680): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/Finsky.CrashDetector( 6680): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/Finsky.CrashDetector( 6680): 	at com.google.android.finsky.CrashDetector.safeWriteCrashFile(CrashDetector.java:169)
W/Finsky.CrashDetector( 6680): 	at com.google.android.finsky.CrashDetector.uncaughtException(CrashDetector.java:97)
W/Finsky.CrashDetector( 6680): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
W/Finsky.CrashDetector( 6680): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
W/Finsky.CrashDetector( 6680): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/Finsky.CrashDetector( 6680): 	at libcore.io.Posix.open(Native Method)
W/Finsky.CrashDetector( 6680): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/Finsky.CrashDetector( 6680): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/Finsky.CrashDetector( 6680): 	... 6 more
--------- beginning of crash
E/AndroidRuntime( 6680): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 6680): Process: com.android.vending, PID: 6680
E/AndroidRuntime( 6680): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 6680): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 6680): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6680): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6680): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:282)
E/AndroidRuntime( 6680): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:1075)
E/AndroidRuntime( 6680): 	at android.os.Handler.handleCallback(Handler.java:739)
E/AndroidRuntime( 6680): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 6680): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6680): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 6680): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 6680): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6680): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6680): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6680): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6680): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 6680): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:370)
E/SQLiteDatabase( 6680): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 6680): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:3082)
E/SQLiteDatabase( 6680): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 6680): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6680): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 6680): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6680): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6680): 	at java.lang.Thread.run(Thread.java:818)
E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  881): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  881): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  881): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  881): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  881): 	... 5 more
I/Process ( 6680): Sending signal. PID: 6680 SIG: 9
I/qdhwcomposer(  277): handle_blank_event: dpy:0 panel power state: 0

```
