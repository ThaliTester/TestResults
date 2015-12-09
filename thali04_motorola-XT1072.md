#### Test 50650278eab32a5_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 5093): 
D/AndroidRuntime( 5093): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5093): CheckJNI is OFF
D/AndroidRuntime( 5093): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5112 uid=10368 gids={50368, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5093): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5112): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5112): Time to load native libraries: 3 ms (timestamps 7297-7300)
I/LibraryLoader( 5112): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5112): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 5112): Expected native library version number "",actual native library version number ""
I/chromium( 5112): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5112): Initializing chromium process, singleProcess=true
W/art     ( 5112): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5112): ApplicationContext is null in ApplicationStatus
W/chromium( 5112): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5112): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5112): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5112): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5112): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5112): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5112): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5112): Local Branch: 
I/Adreno-EGL( 5112): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5112): Local Patches: NONE
I/Adreno-EGL( 5112): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12958819:true
D/BluetoothAdapter( 5112): 343958975: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  881): Activity pause timeout for ActivityRecord{2258e13a u0 com.test.thalitest/.MainActivity t3}
W/art     ( 5112): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5112): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5112): CordovaWebView is running on device made by: motorola
I/art     (  881): Explicit concurrent mark sweep GC freed 17162(906KB) AllocSpace objects, 2(193KB) LOS objects, 33% free, 19MB/29MB, paused 1.402ms total 115.721ms
W/art     ( 5112): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5112): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5112): Render dirty regions requested: true
D/Atlas   ( 5112): Validating map...
W/chromium( 5112): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5112): Initialized EGL, version 1.4
D/OpenGLRenderer( 5112): Enabling debug mode 0
I/Keyboard.Facilitator( 1406): onFinishInput()
I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1098
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +1s20ms (total +1s98ms)
W/IInputConnectionWrapper( 5112): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5112): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5112): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5112): Cannot call determinedVisibility() - never saw a connection for the pid: 5112
,D/JsMessageQueue( 5112): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5112): JniHelper::setJavaVM(0xb8ee3310), pthread_self() = -1188617224
,D/JX-Cordova( 5112): jxcore cordova android initializing
,W/jxcore-log( 5112): Initializing JXcore engine
W/jxcore-log( 5112): JXcore engine is ready
,W/jxcore-log( 5112): Starting JXcore engine
,W/.test.thalitest( 5112): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10368 path="socket:[7522]" dev="sockfs" ino=7522 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5112): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10368 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 5112): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10368 path="socket:[7650]" dev="sockfs" ino=7650 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/.test.thalitest( 5112): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10368 path="socket:[21478]" dev="sockfs" ino=21478 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5112): Platform android
W/jxcore-log( 5112): 
,W/jxcore-log( 5112): Process ARCH arm
W/jxcore-log( 5112): 
,I/jxcore-log( 5112): JXcore Cordova bridge is ready!
I/jxcore-log( 5112): 
,W/jxcore-log( 5112): JXcore engine is started
,I/Choreographer( 5112): Skipped 177 frames!  The application may be doing too much work on its main thread.
,I/chromium( 5112): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 5112): Error!: missing ) after argument list
E/jxcore  ( 5112): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 5112): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  881): Killing 4939:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_4939/cgroup.procs: No such file or directory
W/PluginManager( 5112): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1463): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2632): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2632): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2632): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2632): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2632): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2632): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  881): send {61092c8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {224b81c4, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  881): done {224b81c4, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [4ms]
,W/IInputConnectionWrapper( 5112): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1406): onFinishInput()
,V/AlarmManager(  881): done {61092c8, *alarm*:android.intent.action.TIME_TICK} [38ms]
,E/global frequency( 2632): no tags to log
,D/Checkin ( 2632): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 2632): Explicit concurrent mark sweep GC freed 33772(1905KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.565ms total 79.380ms
,D/BSUtils ( 2632): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1536): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2632): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2632): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2632): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1536): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 37879(2015KB) AllocSpace objects, 16(566KB) LOS objects, 39% free, 7MB/12MB, paused 553us total 35.613ms
,D/BSUtils ( 2632): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2632): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2632): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1536): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2632): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2632): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2632): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2632): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2632): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2632): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2632): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2632): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2632): BcsDSCheckin.events found events 831
,D/Checkin ( 2632): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2632): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2632): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     (  881): Explicit concurrent mark sweep GC freed 6989(377KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 19MB/29MB, paused 1.331ms total 118.100ms
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
,I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/MMApiWebService( 2632): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2632): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2632): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2632): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2632): unknown error code mapping for: 0
,I/global frequency( 2632): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2632): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  881): send {360200c1, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {360200c1, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,D/TaskPersister(  881): removeObsoleteFile: deleting file=2_task.xml
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2632): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2632): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2632): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2632): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2632):  Nonce Reponse 
I/MMApiWebService( 2632): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2632): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2632): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2632): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1463): Explicit concurrent mark sweep GC freed 3564(140KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 782us total 35.628ms
,I/art     ( 2632): Explicit concurrent mark sweep GC freed 21737(1706KB) AllocSpace objects, 5(75KB) LOS objects, 40% free, 11MB/18MB, paused 1.565ms total 67.060ms
,D/MMApiWebService( 2632): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2632): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2632): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310409, SEQNUM=4395, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-561, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/CdsService( 2632): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2632): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2632): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {147add4e, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  881): send {61092c8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): done {147add4e, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [5ms]
,V/AlarmManager(  881): done {61092c8, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1711): disconnect managed GoogleApiClient
,V/AlarmManager(  881): send {315b5066, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  881): done {315b5066, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [65ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1406): run()
I/Keyboard.Facilitator( 1406): flushDynamicLanguageModels()
,I/ConfigService( 1600): onCreate
,E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2255628b)
,E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24e37f68)
,E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@381f1f81)
E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f9fe826)
,E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3359c67)
,E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@12252a14)
,E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c1d32bd)
E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@291260b2)
,E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11f59803)
E/DataBuffer( 1600): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f34d380)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1600): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310595, SEQNUM=4397, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-839, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2632): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2632): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2632): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2632): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2632):  Nonce Reponse 
I/MMApiWebService( 2632): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2632): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2632): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2632): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2632): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2632): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2632): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2632): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2632): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2632): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310807, SEQNUM=4398, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1405, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310781, SEQNUM=4399, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-1644, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {61092c8, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {b759049, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): done {b759049, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [7ms]
,V/AlarmManager(  881): done {61092c8, *alarm*:android.intent.action.TIME_TICK} [43ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310777, SEQNUM=4400, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-1815, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2632): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2632): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2632): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2632): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2632):  Nonce Reponse 
I/MMApiWebService( 2632): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2632): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2632): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2632): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2632): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2632): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2632): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2632): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2632): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2632): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2632): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2632): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310176, SEQNUM=4406, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-2530, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310756, SEQNUM=4407, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-2861, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310155, SEQNUM=4408, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-2938, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311037, SEQNUM=4409, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-3047, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310436, SEQNUM=4410, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-3303, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  881): send {61092c8, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {b759049, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): send {17f5c5f4, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
V/AlarmManager(  881): send {363a8749, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  881): send {179a084e, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  881): send {35717d6f, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
,I/ProcessStatsService(  881): Prepared write state in 10ms
,V/AlarmManager(  881): done {b759049, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [36ms]
,I/ProcessStatsService(  881): Prepared write state in 8ms
,V/AlarmManager(  881): done {17f5c5f4, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [64ms]
,V/AlarmManager(  881): done {61092c8, *alarm*:android.intent.action.TIME_TICK} [76ms]
,V/AlarmManager(  881): done {363a8749, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [87ms]
,V/AlarmManager(  881): done {179a084e, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [99ms]
,V/AlarmManager(  881): done {35717d6f, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver} [117ms]
,I/EventLogService( 1938): Aggregate from 1449668423828 (log), 1449668423828 (data)
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  881): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-10-56.bin
,I/art     (  881): Explicit concurrent mark sweep GC freed 16713(1101KB) AllocSpace objects, 11(245KB) LOS objects, 33% free, 19MB/29MB, paused 1.480ms total 112.290ms
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1600): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5299): 
D/AndroidRuntime( 5299): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5299): CheckJNI is OFF
D/AndroidRuntime( 5299): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10368 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5112:com.test.thalitest/u0a368 (adj 9): stop com.test.thalitest
W/PackageSettings(  881): Skipping PackageSetting{f36067b com.example.hello/10359} due to missing metadata
I/ActivityManager(  881): Killing 4969:com.google.android.apps.docs/u0a57 (adj 15): empty for 1875s
W/ActivityManager(  881): Spurious death for ProcessRecord{3c595e29 5112:com.test.thalitest/u0a368}, curProc for 5112: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10368 user=0: pkg removed
I/art     ( 3021): Explicit concurrent mark sweep GC freed 4748(942KB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 7MB/12MB, paused 1.213ms total 31.650ms
W/libprocessgroup(  881): failed to open /acct/uid_10057/pid_4969/cgroup.procs: No such file or directory
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1711): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1406): resetDictionaries() : en_US
D/VoicemailCleanupService( 4891): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1406): run()
I/Decoder ( 1406): createOrResetDecoder
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5328 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7378(536KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 459us total 126.531ms
I/art     (  881): Explicit concurrent mark sweep GC freed 7593(595KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 19MB/29MB, paused 1.398ms total 146.611ms
I/art     (  881): WaitForGcToComplete blocked for 62.625ms for cause Explicit
I/ConfigService( 1600): onCreate
W/asset   ( 5328): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5328): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5328): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5328): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1406): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1406): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1406): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1406): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1406): run()
I/StatsUtilsManager( 1406): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1406): shouldRecordStats() = Too Soon
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5354 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  881): removeObsoleteFile: deleting file=3_task.xml
I/art     (  881): Explicit concurrent mark sweep GC freed 3305(164KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.541ms total 175.219ms
I/ActivityManager(  881): Killing 5009:com.google.android.apps.plus/u0a90 (adj 15): empty for 1875s
D/AndroidRuntime( 5299): Shutting down VM
W/libprocessgroup(  881): failed to open /acct/uid_10090/pid_5009/cgroup.procs: No such file or directory
I/Launcher( 1555): Deferring update until onResume
W/ContextImpl( 5354): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5372 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1938): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1938): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1600): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1600): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5403 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
D/gH_CompatibleDatabase( 1938): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1938): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1938): 0 metrics were deleted when clearing package com.test.thalitest.
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
I/PeopleContactsSync( 1938): CP2 sync disabled
I/Icing   ( 1938): doRemovePackageData com.test.thalitest
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  881): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5441 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a

```
