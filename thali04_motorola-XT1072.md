#### Test 5065027865f659b_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2781): no tags to log
D/Checkin ( 2781): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2781): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     (  892): Explicit concurrent mark sweep GC freed 18028(948KB) AllocSpace objects, 2(190KB) LOS objects, 33% free, 19MB/29MB, paused 1.983ms total 158.936ms
D/BSUtils ( 2781): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2781): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2781): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 5016): 
D/AndroidRuntime( 5016): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5016): CheckJNI is OFF
I/art     ( 1472): Explicit concurrent mark sweep GC freed 37556(2025KB) AllocSpace objects, 17(580KB) LOS objects, 39% free, 7MB/12MB, paused 712us total 35.824ms
D/BSUtils ( 2781): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2781): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2781): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1550): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 5016): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  892): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/BSUtils ( 2781): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2781): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/ActivityManager(  892): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5040 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5016): Shutting down VM
I/BSUtils ( 2781): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2781): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2781): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2781): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2781): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2781): publish the event [tag = DEV_ATTRIBS event name = SW]
V/ActivityManager(  892): Display changed displayId=0
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/global frequency( 2781): BcsDSCheckin.events found events 668
D/Checkin ( 2781): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/WebViewFactory( 5040): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/BSUtils ( 2781): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,V/AlarmManager(  892): send {2bd4ef0a, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  892): done {2bd4ef0a, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/LibraryLoader( 5040): Time to load native libraries: 4 ms (timestamps 5242-5246)
I/LibraryLoader( 5040): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5040): Binding Chromium to main looper Looper (main, tid 1) {187f9877}
,I/LibraryLoader( 5040): Expected native library version number "",actual native library version number ""
I/chromium( 5040): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5040): Initializing chromium process, singleProcess=true
,W/art     ( 5040): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5040): ApplicationContext is null in ApplicationStatus
,W/chromium( 5040): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5040): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5040): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5040): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/MMApiWebService( 2781): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
I/Adreno-EGL( 5040): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5040): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5040): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5040): Local Branch: 
I/Adreno-EGL( 5040): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5040): Local Patches: NONE
I/Adreno-EGL( 5040): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  892): Message: 20
D/BluetoothManagerService(  892): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28f066f3:true
,D/BluetoothAdapter( 5040): 650797904: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 2781): Explicit concurrent mark sweep GC freed 17202(1152KB) AllocSpace objects, 4(52KB) LOS objects, 39% free, 11MB/19MB, paused 868us total 70.626ms
,D/MMApiWebService( 2781): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2781): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2781): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2781): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2781): unknown error code mapping for: 0
I/global frequency( 2781): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2781): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2781): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2781): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/ActivityManager(  892): Activity pause timeout for ActivityRecord{2a20c05f u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 5040): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5040): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5040): CordovaWebView is running on device made by: motorola
,W/art     ( 5040): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5040): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5040): Render dirty regions requested: true
,D/Atlas   ( 5040): Validating map...
,W/chromium( 5040): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5040): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5040): Enabling debug mode 0
,I/Keyboard.Facilitator( 1417): onFinishInput()
,I/LaunchCheckinHandler(  892): Displayed com.test.thalitest/.MainActivity,cp,ca,935
I/ActivityManager(  892): Displayed com.test.thalitest/.MainActivity: +853ms (total +935ms)
,W/IInputConnectionWrapper( 5040): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5040): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,E/Adreno-ES20( 5040): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5040): Cannot call determinedVisibility() - never saw a connection for the pid: 5040
,D/JsMessageQueue( 5040): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5040): JniHelper::setJavaVM(0xb7a9d310), pthread_self() = -1209868704
,D/JX-Cordova( 5040): jxcore cordova android initializing
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,W/jxcore-log( 5040): Initializing JXcore engine
W/jxcore-log( 5040): JXcore engine is ready
,W/jxcore-log( 5040): Starting JXcore engine
,W/.test.thalitest( 5040): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10366 path="socket:[7284]" dev="sockfs" ino=7284 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5040): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10366 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5040): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10366 path="socket:[7030]" dev="sockfs" ino=7030 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5040): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10366 path="socket:[20375]" dev="sockfs" ino=20375 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5040): Platform android
W/jxcore-log( 5040): 
,W/jxcore-log( 5040): Process ARCH arm
W/jxcore-log( 5040): 
,I/jxcore-log( 5040): JXcore Cordova bridge is ready!
I/jxcore-log( 5040): 
W/jxcore-log( 5040): JXcore engine is started
I/Choreographer( 5040): Skipped 178 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5040): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5040): Error!: missing ) after argument list
E/jxcore  ( 5040): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5040): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  892): Killing 4872:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/PluginManager( 5040): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 22ms. Plugin should use CordovaInterface.getThreadPool().
,W/libprocessgroup(  892): failed to open /acct/uid_10039/pid_4872/cgroup.procs: No such file or directory
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1472): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2781): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2781): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2781): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2781): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2781): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2781): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  892): send {10d4d380, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  892): send {28700a7c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  892): done {28700a7c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,W/IInputConnectionWrapper( 5040): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1417): onFinishInput()
,V/AlarmManager(  892): done {10d4d380, *alarm*:android.intent.action.TIME_TICK} [51ms]
,D/TaskPersister(  892): removeObsoleteFile: deleting file=2_task.xml
,I/MMApiBackOffService( 2781): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2781): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2781): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  892): Explicit concurrent mark sweep GC freed 8273(491KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 19MB/29MB, paused 1.756ms total 118.607ms
,D/MMApiWebService( 2781): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2781):  Nonce Reponse 
I/MMApiWebService( 2781): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2781): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2781): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2781): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2781): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2781): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1472): Explicit concurrent mark sweep GC freed 3872(173KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 744us total 35.464ms
,D/MMApiWebService( 2781): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2781): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2781): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2781): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311376, SEQNUM=4437, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=9890, POWER_SUPPLY_CHARGE_COUNTER=-188, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1717): disconnect managed GoogleApiClient
,V/AlarmManager(  892): send {26f52ed2, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  892): send {3f774f0c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  892): done {26f52ed2, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  892): done {3f774f0c, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [8ms]
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@229de989)
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@35a5d8e)
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fcf49af)
E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@200fe1bc)
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@10f29545)
,I/Keyboard.Facilitator.LanguageModelFlusher( 1417): run()
I/Keyboard.Facilitator( 1417): flushDynamicLanguageModels()
,I/ConfigService( 1629): onCreate
,I/CheckinRequestBuilder( 1629): Classify the device as Phone.
,W/FetchTask( 1629): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1629): Classify the device as Phone.
,W/FetchTask( 1629): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1629): Classify the device as Phone.
,W/FetchTask( 1629): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1629): Classify the device as Phone.
,W/FetchTask( 1629): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/CheckinRequestBuilder( 1629): Classify the device as Phone.
,W/FetchTask( 1629): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigService( 1629): onDestroy
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311545, SEQNUM=4440, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-92, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1ce9d284)
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@23cb0a6d)
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@17eed6a2)
,E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1962ef33)
E/DataBuffer( 1629): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@287392f0)
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311220, SEQNUM=4441, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-192, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311229, SEQNUM=4443, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-205, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  892): send {10d4d380, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): done {10d4d380, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=267, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311203, SEQNUM=4444, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-284, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2781): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2781): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2781): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2781): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2781):  Nonce Reponse 
I/MMApiWebService( 2781): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2781): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2781): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2781): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2781): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2781): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2781): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2781): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2781): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2781): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311151, SEQNUM=4445, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-702, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  892): send {10d4d380, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): send {ee99ec3, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
,I/PollingManager( 2781): alarm fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2781): alarm fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2781): alarm fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  892): done {10d4d380, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/OtaApp  ( 2781): [info] > PollingManagerService, alarm fired!
D/Checkin ( 2781): publish the event [tag = MOT_OTA event name = LOG]
,I/Central_PollingManager( 1472): alarm fired!
,V/AlarmManager(  892): done {ee99ec3, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [119ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  892): send {10d4d380, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): send {3eefe55d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/Finsky  ( 4566): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  892): send {14841cb0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  892): done {14841cb0, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [20ms]
,V/AlarmManager(  892): done {3eefe55d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [27ms]
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  892): done {10d4d380, *alarm*:android.intent.action.TIME_TICK} [65ms]
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4566): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4566): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4566): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4566): [1] WearSupportService.startHygiene: disabled
,D/Finsky  ( 4566): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  892): send {30173291, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 4566): [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,D/DeviceConnectionService( 1717): client connected with version: 8296000
,V/AlarmManager(  892): done {30173291, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [12ms]
,D/Finsky  ( 4566): [480] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  892): send {1d8bdbfc, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  892): done {1d8bdbfc, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [8ms]
,D/Finsky  ( 4566): [465] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4566): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311415, SEQNUM=4454, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-335, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2781): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2781): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2781): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2781): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2781):  Nonce Reponse 
I/MMApiWebService( 2781): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2781): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2781): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2781): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2781): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2781): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/art     (  892): Explicit concurrent mark sweep GC freed 14648(724KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.784ms total 117.506ms
,D/MMApiWebService( 2781): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2781): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2781): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2781): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2781): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  892): User[0] Flushing usage stats to disk
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311402, SEQNUM=4457, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-572, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  892): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311100, SEQNUM=4465, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-359, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  892): send {10d4d380, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  892): send {3eefe55d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  892): send {1e325811, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  892): send {101d085c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  892): send {810c765, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
,I/ProcessStatsService(  892): Prepared write state in 13ms
,V/AlarmManager(  892): done {3eefe55d, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [48ms]
,I/ProcessStatsService(  892): Prepared write state in 15ms
,V/AlarmManager(  892): done {1e325811, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [71ms]
,V/AlarmManager(  892): done {10d4d380, *alarm*:android.intent.action.TIME_TICK} [83ms]
,I/ProcessStatsService(  892): Prepared write state in 9ms
,V/AlarmManager(  892): done {101d085c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [101ms]
,V/AlarmManager(  892): done {810c765, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [115ms]
,I/EventLogService( 1953): Aggregate from 1449597588269 (log), 1449597588269 (data)
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  892): Pruning old procstats: /data/system/procstats/state-2015-12-07-19-17-35.bin
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1629): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5261): 
D/AndroidRuntime( 5261): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5261): CheckJNI is OFF
D/AndroidRuntime( 5261): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  892): Force stopping com.test.thalitest appid=10366 user=-1: uninstall pkg
I/ActivityManager(  892): Killing 5040:com.test.thalitest/u0a366 (adj 11): stop com.test.thalitest
W/PackageSettings(  892): Skipping PackageSetting{1059b99c com.example.hello/10359} due to missing metadata
I/ActivityManager(  892): Killing 4895:com.google.android.apps.docs/u0a57 (adj 15): empty for 1876s
I/ActivityManager(  892): Force stopping com.test.thalitest appid=10366 user=0: pkg removed
I/art     ( 3151): Explicit concurrent mark sweep GC freed 4578(869KB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 7MB/12MB, paused 564us total 30.457ms
W/libprocessgroup(  892): failed to open /acct/uid_10057/pid_4895/cgroup.procs: No such file or directory
W/ActivityManager(  892): Spurious death for ProcessRecord{1027e88e 5040:com.test.thalitest/u0a366}, curProc for 5040: null
W/GeofencerStateMachine( 1717): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1417): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1417): run()
I/Decoder ( 1417): createOrResetDecoder
I/InputReader(  892): Reconfiguring input devices.  changes=0x00000010
D/VoicemailCleanupService( 4802): Cleaning up data for package: com.test.thalitest
I/art     ( 1567): Explicit concurrent mark sweep GC freed 7318(532KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 490us total 118.138ms
I/ActivityManager(  892): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5290 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  315): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.791ms
I/ConfigService( 1629): onCreate
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 19.522ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.240ms
W/asset   ( 5290): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5290): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
I/art     (  892): Explicit concurrent mark sweep GC freed 15145(1103KB) AllocSpace objects, 10(228KB) LOS objects, 33% free, 19MB/29MB, paused 2.104ms total 163.804ms
W/ResourcesManager( 5290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5290): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  892): WaitForGcToComplete blocked for 133.521ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1417): run()
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
I/ActivityManager(  892): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5317 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/BackupManagerService(  892): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  892): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  892): removeObsoleteFile: deleting file=3_task.xml
I/ActivityManager(  892): Killing 4939:com.google.android.apps.plus/u0a90 (adj 15): empty for 1875s
I/art     (  892): Explicit concurrent mark sweep GC freed 5498(294KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 4.570ms total 207.831ms
W/libprocessgroup(  892): failed to open /acct/uid_10090/pid_4939/cgroup.procs: No such file or directory
W/ContextImpl( 5317): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/Launcher( 1567): Deferring update until onResume
I/ActivityManager(  892): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5335 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/AndroidRuntime( 5261): Shutting down VM
W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@e4ed949 new=com.google.android.velvet.VelvetApplication@e4ed949
D/PackageBroadcastService( 1953): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1953): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1953): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1953): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1953): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1953): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1629): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1629): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1953): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 1953): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1953): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1953): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1953): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1953): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1953): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1953): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1953): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1953): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1953): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1953): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1953): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1953): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  892): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5360 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/PeopleContactsSync( 1953): CP2 sync disabled
I/Icing   ( 1953): doRemovePackageData com.test.thalitest
I/ActivityManager(  892): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5390 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 5335): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteDatabase( 5335): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 5335): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5335): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5335): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5335): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5335): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/SQLiteDatabase( 5335): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/SQLiteDatabase( 5335): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/SQLiteDatabase( 5335): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/SQLiteDatabase( 5335): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/SQLiteDatabase( 5335): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/SQLiteDatabase( 5335): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/SQLiteDatabase( 5335): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/SQLiteDatabase( 5335): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/SQLiteDatabase( 5335): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5335): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5335): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5335): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
