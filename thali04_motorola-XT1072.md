#### Test 50650278b1aec71_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,D/AndroidRuntime( 4731): 
D/AndroidRuntime( 4731): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4731): CheckJNI is OFF
D/AndroidRuntime( 4731): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  886): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  886): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4750 uid=10365 gids={50365, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 4731): Shutting down VM
V/ActivityManager(  886): Display changed displayId=0
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 4750): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4750): Time to load native libraries: 3 ms (timestamps 7686-7689)
I/LibraryLoader( 4750): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4750): Binding Chromium to main looper Looper (main, tid 1) {1059773b}
,I/LibraryLoader( 4750): Expected native library version number "",actual native library version number ""
,I/chromium( 4750): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4750): Initializing chromium process, singleProcess=true
,W/art     ( 4750): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4750): ApplicationContext is null in ApplicationStatus
,W/chromium( 4750): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4750): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4750): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4750): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4750): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4750): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4750): Local Branch: 
I/Adreno-EGL( 4750): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4750): Local Patches: NONE
I/Adreno-EGL( 4750): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  886): Message: 20
,D/BluetoothManagerService(  886): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24fe08cd:true
,D/BluetoothAdapter( 4750): 27236356: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  886): Activity pause timeout for ActivityRecord{230deb1e u0 com.test.thalitest/.MainActivity t3}
,I/art     (  886): Explicit concurrent mark sweep GC freed 17650(949KB) AllocSpace objects, 2(191KB) LOS objects, 33% free, 19MB/29MB, paused 2.038ms total 166.941ms
,W/art     ( 4750): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4750): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4750): CordovaWebView is running on device made by: motorola
,W/art     ( 4750): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4750): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4750): Render dirty regions requested: true
,D/Atlas   ( 4750): Validating map...
,W/chromium( 4750): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4750): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4750): Enabling debug mode 0
,I/Keyboard.Facilitator( 1412): onFinishInput()
,I/LaunchCheckinHandler(  886): Displayed com.test.thalitest/.MainActivity,cp,ca,946
I/ActivityManager(  886): Displayed com.test.thalitest/.MainActivity: +854ms (total +946ms)
W/IInputConnectionWrapper( 4750): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 4750): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4750): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4750): Cannot call determinedVisibility() - never saw a connection for the pid: 4750
,D/JsMessageQueue( 4750): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4750): JniHelper::setJavaVM(0xb8b94310), pthread_self() = -1192084568
,D/JX-Cordova( 4750): jxcore cordova android initializing
,W/jxcore-log( 4750): Initializing JXcore engine
W/jxcore-log( 4750): JXcore engine is ready
,W/jxcore-log( 4750): Starting JXcore engine
,W/.test.thalitest( 4750): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10365 path="socket:[5668]" dev="sockfs" ino=5668 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 4750): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10365 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 4750): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10365 path="socket:[9495]" dev="sockfs" ino=9495 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 4750): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10365 path="socket:[21302]" dev="sockfs" ino=21302 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4750): Platform android
W/jxcore-log( 4750): 
,W/jxcore-log( 4750): Process ARCH arm
W/jxcore-log( 4750): 
,I/jxcore-log( 4750): JXcore Cordova bridge is ready!
I/jxcore-log( 4750): 
W/jxcore-log( 4750): JXcore engine is started
,I/chromium( 4750): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 4750): Error!: missing ) after argument list
E/jxcore  ( 4750): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 4750): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  886): Killing 4568:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  886): failed to open /acct/uid_10039/pid_4568/cgroup.procs: No such file or directory
,W/PluginManager( 4750): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1470): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2458): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2458): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2458): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2458): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2458): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2458): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  886): send {173a5f7a, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  886): done {173a5f7a, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [4ms]
,W/IInputConnectionWrapper( 4750): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1412): onFinishInput()
,E/global frequency( 2458): no tags to log
,D/Checkin ( 2458): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2458): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1545): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2458): Explicit concurrent mark sweep GC freed 21198(1264KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/18MB, paused 1.539ms total 64.688ms
,D/BSUtils ( 2458): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2458): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 53940(2MB) AllocSpace objects, 33(1039KB) LOS objects, 39% free, 7MB/12MB, paused 985us total 48.608ms
,D/BSUtils ( 2458): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1545): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2458): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2458): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2458): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1545): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2458): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2458): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2458): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2458): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2458): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2458): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2458): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2458): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2458): BcsDSCheckin.events found events 627
,D/Checkin ( 2458): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2458): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2458): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 4195(174KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 646us total 35.956ms
,I/art     (  886): Explicit concurrent mark sweep GC freed 7028(375KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.367ms total 109.122ms
,D/MMApiWebService( 2458): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2458): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2458): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2458): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2458): unknown error code mapping for: 0
I/global frequency( 2458): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2458): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2458): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2458): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  886): send {274498f5, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  886): done {274498f5, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,D/TaskPersister(  886): removeObsoleteFile: deleting file=2_task.xml
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/MMApiBackOffService( 2458): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2458): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2458): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2458): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2458):  Nonce Reponse 
I/MMApiWebService( 2458): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2458): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2458): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2458): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2458): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2458): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2458): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1635): disconnect managed GoogleApiClient
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  886): send {2ded29fd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {217e8143, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  886): send {214df68a, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  886): done {217e8143, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [17ms]
,V/AlarmManager(  886): done {2ded29fd, *alarm*:android.intent.action.TIME_TICK} [45ms]
,V/AlarmManager(  886): done {214df68a, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [50ms]
,I/EventLogService( 1947): Aggregate from 1449594555255 (log), 1449593923199 (data)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ClearcutLoggerApiImpl( 1753): disconnect managed GoogleApiClient
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=284, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311910, SEQNUM=4360, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-480, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  886): send {255f25d7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  886): done {255f25d7, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [67ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@16b39b0)
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@145b6029)
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@aea9fae)
E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1121314f)
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a4240dc)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1412): run()
I/Keyboard.Facilitator( 1412): flushDynamicLanguageModels()
,I/ConfigService( 1635): onCreate
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1635): onDestroy
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311249, SEQNUM=4366, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-628, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c94505e)
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2570c3f)
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c85990c)
E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24cc0255)
,E/DataBuffer( 1635): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3651146a)
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  886): send {2ded29fd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): done {2ded29fd, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  886): send {1ae576e1, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
,I/PollingManager( 2458): alarm fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2458): alarm fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2458): alarm fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/OtaApp  ( 2458): [info] > PollingManagerService, alarm fired!
D/Checkin ( 2458): publish the event [tag = MOT_OTA event name = LOG]
,I/Central_PollingManager( 1470): alarm fired!
,V/AlarmManager(  886): done {1ae576e1, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [106ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2458): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2458): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2458): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2458): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2458):  Nonce Reponse 
I/MMApiWebService( 2458): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2458): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2458): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2458): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2458): Explicit concurrent mark sweep GC freed 21793(1645KB) AllocSpace objects, 1(15KB) LOS objects, 40% free, 11MB/18MB, paused 1.271ms total 139.447ms
,D/MMApiWebService( 2458): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2458): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2458): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
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
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311984, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1268, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312283, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1307, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,V/AlarmManager(  886): send {2ded29fd, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  886): send {77426f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  886): done {77426f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,V/AlarmManager(  886): done {2ded29fd, *alarm*:android.intent.action.TIME_TICK} [51ms]
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
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311638, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1758, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/MMApiBackOffService( 2458): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2458): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2458): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2458): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2458):  Nonce Reponse 
I/MMApiWebService( 2458): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2458): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2458): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2458): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1470): Explicit concurrent mark sweep GC freed 3287(143KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 856us total 35.679ms
,D/MMApiWebService( 2458): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2458): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2458): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2458): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2458): publish the event [tag = MOT_CCE event name = LOG]
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
,I/UsageStatsService(  886): User[0] Flushing usage stats to disk
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311595, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-2129, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311608, SEQNUM=4378, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-2239, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311885, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-2549, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/ClearcutLoggerApiImpl( 1635): disconnect managed GoogleApiClient
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311565, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-2661, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  886): Prepared write state in 8ms
,I/art     (  886): Explicit concurrent mark sweep GC freed 15244(1000KB) AllocSpace objects, 10(204KB) LOS objects, 33% free, 19MB/29MB, paused 1.663ms total 170.512ms
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1635): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  886): Pruning old procstats: /data/system/procstats/state-2015-12-07-16-13-40.bin
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312728, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311565, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2722, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311846, SEQNUM=4391, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3227, POWER_SUPPLY_CHARGE_COUNTER=8, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311561, SEQNUM=4393, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=13, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  886): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311859, SEQNUM=4395, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=25, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 4916): 
D/AndroidRuntime( 4916): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4916): CheckJNI is OFF
D/AndroidRuntime( 4916): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10365 user=-1: uninstall pkg
I/ActivityManager(  886): Killing 4750:com.test.thalitest/u0a365 (adj 9): stop com.test.thalitest
W/PackageSettings(  886): Skipping PackageSetting{1c4da390 com.example.hello/10359} due to missing metadata
I/ActivityManager(  886): Killing 4594:com.google.android.apps.docs/u0a57 (adj 15): empty for 1876s
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10365 user=0: pkg removed
I/art     ( 2875): Explicit concurrent mark sweep GC freed 5602(1026KB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 7MB/12MB, paused 620us total 43.750ms
W/libprocessgroup(  886): failed to open /acct/uid_10057/pid_4594/cgroup.procs: No such file or directory
W/ActivityManager(  886): Spurious death for ProcessRecord{24466ff0 4750:com.test.thalitest/u0a365}, curProc for 4750: null
I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1412): resetDictionaries() : en_US
W/GeofencerStateMachine( 1753): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1412): run()
I/art     ( 1562): Explicit concurrent mark sweep GC freed 7337(533KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 476us total 121.223ms
I/Decoder ( 1412): createOrResetDecoder
D/VoicemailCleanupService( 4501): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  886): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=4946 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  886): Explicit concurrent mark sweep GC freed 8040(710KB) AllocSpace objects, 3(72KB) LOS objects, 33% free, 19MB/29MB, paused 2.227ms total 152.513ms
I/art     (  886): WaitForGcToComplete blocked for 83.454ms for cause Explicit
I/ConfigService( 1635): onCreate
W/asset   ( 4946): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 4946): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 4946): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4946): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1412): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1412): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1412): run()
I/StatsUtilsManager( 1412): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1412): shouldRecordStats() = Too Soon
D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  886): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  886): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4968 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  886): removeObsoleteFile: deleting file=3_task.xml
I/art     (  886): Explicit concurrent mark sweep GC freed 4519(237KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.444ms total 180.253ms
I/art     (  324): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 20.782ms
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 19.175ms
I/ActivityManager(  886): Killing 4642:com.google.android.apps.plus/u0a90 (adj 15): empty for 1875s
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.547ms
D/AndroidRuntime( 4916): Shutting down VM
W/libprocessgroup(  886): failed to open /acct/uid_10090/pid_4642/cgroup.procs: No such file or directory
I/Launcher( 1562): Deferring update until onResume
W/ContextImpl( 4968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  886): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=4989 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/Launcher( 1562): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@285d21ed new=com.google.android.velvet.VelvetApplication@285d21ed
D/PackageBroadcastService( 1947): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1947): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1947): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1947): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1947): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1947): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1635): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1635): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  886): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5015 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
V/AlarmManager(  886): send {2ded29fd, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  886): send {77426f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  886): send {d234958, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  886): send {235d9337, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  886): send {253ca0a4, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
D/gH_CompatibleDatabase( 1947): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1947): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1947): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1947): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1947): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1947): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1947): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/PeopleContactsSync( 1947): CP2 sync disabled
V/AlarmManager(  886): done {2ded29fd, *alarm*:android.intent.action.TIME_TICK} [44ms]
D/gH_CompatibleDatabase( 1947): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1947): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1947): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1947): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1947): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1947): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 1947): doRemovePackageData com.test.thalitest
I/ActivityManager(  886): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5052 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
