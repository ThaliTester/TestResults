#### Test 564496605d11e75_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
--------- beginning of system
D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311755, SEQNUM=4344, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-564, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
D/AndroidRuntime( 5249): 
D/AndroidRuntime( 5249): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5249): CheckJNI is OFF
D/AndroidRuntime( 5249): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5275 uid=10476 gids={50476, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5249): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5275): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5275): Time to load native libraries: 3 ms (timestamps 3072-3075)
I/LibraryLoader( 5275): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5275): Binding Chromium to main looper Looper (main, tid 1) {25c2cf66}
I/LibraryLoader( 5275): Expected native library version number "",actual native library version number ""
I/chromium( 5275): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5275): Initializing chromium process, singleProcess=true
W/art     ( 5275): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5275): ApplicationContext is null in ApplicationStatus
W/chromium( 5275): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5275): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5275): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5275): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5275): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5275): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5275): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5275): Local Branch: 
I/Adreno-EGL( 5275): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5275): Local Patches: NONE
I/Adreno-EGL( 5275): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fdf79c0:true
D/BluetoothAdapter( 5275): 680571459: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  885): Activity pause timeout for ActivityRecord{328ed545 u0 com.test.thalitest/.MainActivity t6}
W/art     ( 5275): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5275): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5275): CordovaWebView is running on device made by: motorola
W/art     ( 5275): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5275): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5275): Render dirty regions requested: true
D/Atlas   ( 5275): Validating map...
,W/chromium( 5275): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5275): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5275): Enabling debug mode 0
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,979
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +910ms (total +979ms)
,W/IInputConnectionWrapper( 5275): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5275): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5275): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5275): Cannot call determinedVisibility() - never saw a connection for the pid: 5275
,D/JsMessageQueue( 5275): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5275): JniHelper::setJavaVM(0xb86ea310), pthread_self() = -1196980728
I/chromium( 5275): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5275): Initializing JXcore engine
W/jxcore-log( 5275): JXcore engine is ready
,W/Thread-602( 5330): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10476 path="socket:[5596]" dev="sockfs" ino=5596 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-602( 5330): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10476 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-602( 5330): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10476 path="socket:[6912]" dev="sockfs" ino=6912 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-602( 5330): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10476 path="socket:[21448]" dev="sockfs" ino=21448 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5275): Starting JXcore engine
,W/jxcore-log( 5275): Platform android
W/jxcore-log( 5275): 
,W/jxcore-log( 5275): Process ARCH arm
W/jxcore-log( 5275): 
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 5275): JXcore Cordova bridge is ready!
I/jxcore-log( 5275): 
,W/jxcore-log( 5275): JXcore engine is started
,E/jxcore  ( 5275): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5275): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5275): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  885): Killing 4848:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_4848/cgroup.procs: No such file or directory
,W/PluginManager( 5275): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1467): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2489): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2489): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2489): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2489): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2489): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5275): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1407): onFinishInput()
,V/AlarmManager(  885): send {37ee8db6, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {37ee8db6, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [9ms]
,D/TaskPersister(  885): removeObsoleteFile: deleting file=5_task.xml
,E/global frequency( 2489): no tags to log
,D/Checkin ( 2489): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2489): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  885): Explicit concurrent mark sweep GC freed 18808(997KB) AllocSpace objects, 6(260KB) LOS objects, 33% free, 19MB/29MB, paused 1.479ms total 122.795ms
,D/BSUtils ( 2489): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2489): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2489): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1467): Explicit concurrent mark sweep GC freed 38562(2MB) AllocSpace objects, 17(590KB) LOS objects, 39% free, 7MB/12MB, paused 695us total 43.559ms
,D/BSUtils ( 2489): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2489): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2489): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2489): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2489): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2489): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2489): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2489): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2489): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2489): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2489): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2489): BcsDSCheckin.events found events 426
,D/Checkin ( 2489): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2489): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2489): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2489): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2489): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2489): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2489): unknown error code mapping for: 0
,I/global frequency( 2489): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2489): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  885): send {124c1008, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  885): done {124c1008, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2489): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2489): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2489): Explicit concurrent mark sweep GC freed 19762(1380KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.149ms total 64.893ms
,D/MMApiWebService( 2489): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2489):  Nonce Reponse 
I/MMApiWebService( 2489): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2489): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2489): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1467): Explicit concurrent mark sweep GC freed 3256(129KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 760us total 33.270ms
,I/art     (  885): Explicit concurrent mark sweep GC freed 6260(320KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.440ms total 110.208ms
,D/MMApiWebService( 2489): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2489): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2489): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  885): send {4705990, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  885): send {8f1728e, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  885): send {37ee8db6, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {8f1728e, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [22ms]
V/AlarmManager(  885): done {37ee8db6, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [22ms]
,V/AlarmManager(  885): done {4705990, *alarm*:android.intent.action.TIME_TICK} [56ms]
,I/VacuumService( 1696): Vacuum at: now=1453807685747 tag=VacuumService
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1696): disconnect managed GoogleApiClient
,V/AlarmManager(  885): send {6795d87, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  885): done {6795d87, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [68ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1696): onCreate
,I/ConfigService( 1696): onDestroy
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311319, SEQNUM=4364, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-788, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {4705990, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {4705990, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2489): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2489): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2489): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2489):  Nonce Reponse 
I/MMApiWebService( 2489): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2489): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2489): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2489): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2489): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2489): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
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
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311471, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-1463, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/ClearcutLoggerApiImpl( 1696): disconnect managed GoogleApiClient
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311462, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-21, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311748, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-42, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2489): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2489): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2489): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2489):  Nonce Reponse 
I/MMApiWebService( 2489): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2489): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2489): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2489): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2489): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2489): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2489): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2489): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2489): publish the event [tag = MOT_CCE event name = LOG]
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
,I/MDMCTBK (  298): NetlinkHandler, power_supply subsys
I/MDMCTBK (  298): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  298): checkDefaultInst, current pid is = 298
I/MDMCTBK (  298): checkDefaultInst, pid match
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  298): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  298): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311436, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-60, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  885): send {4705990, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {34803289, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  885): send {1204e680, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  885): done {34803289, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [25ms]
,V/AlarmManager(  885): done {4705990, *alarm*:android.intent.action.TIME_TICK} [49ms]
,V/AlarmManager(  885): done {1204e680, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [56ms]
,I/EventLogService( 4918): Aggregate from 1453806901244 (log), 1453806901244 (data)
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3147820)
E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@151115d9)
E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2bc49b9e)
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@454967f)
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@318f64c)
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@37743695)
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@115ad3aa)
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2fa61b9b)
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b052b38)
,I/art     ( 1696): Explicit concurrent mark sweep GC freed 39280(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 13MB/21MB, paused 1.137ms total 82.809ms
,E/DataBuffer( 1696): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@39aea711)
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1696): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5468): 
D/AndroidRuntime( 5468): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5468): CheckJNI is OFF
D/AndroidRuntime( 5468): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10476 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 5275:com.test.thalitest/u0a476 (adj 11): stop com.test.thalitest
W/PackageSettings(  885): Skipping PackageSetting{268aad3f com.example.hello/10440} due to missing metadata
W/ActivityManager(  885): Spurious death for ProcessRecord{122c6f3 5275:com.test.thalitest/u0a476}, curProc for 5275: null
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10476 user=0: pkg removed
I/art     ( 2911): Explicit concurrent mark sweep GC freed 4229(827KB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 7MB/12MB, paused 565us total 41.047ms
I/art     ( 4975): Explicit concurrent mark sweep GC freed 697(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 384us total 43.015ms
W/GeofencerStateMachine( 1696): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/art     ( 4918): Explicit concurrent mark sweep GC freed 3109(234KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 12MB/17MB, paused 748us total 126.242ms
I/art     ( 1559): Explicit concurrent mark sweep GC freed 7417(540KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 489us total 82.687ms
I/Decoder ( 1407): createOrResetDecoder
I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5498 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  885): Explicit concurrent mark sweep GC freed 17733(1209KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 1.346ms total 122.200ms
I/art     (  885): WaitForGcToComplete blocked for 59.856ms for cause Explicit
I/ConfigService( 1696): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1407): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1407): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1407): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1407): run()
I/StatsUtilsManager( 1407): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1407): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5498): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5522 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5498): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/TaskPersister(  885): removeObsoleteFile: deleting file=6_task.xml
I/art     (  885): Explicit concurrent mark sweep GC freed 6480(339KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.266ms total 186.120ms
I/Launcher( 1559): Deferring update until onResume
W/asset   ( 5522): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5522): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5522): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5522): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5544 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  885): Killing 4975:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5468): Shutting down VM
W/ContextImpl( 5544): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  885): failed to open /acct/uid_10039/pid_4975/cgroup.procs: No such file or directory
D/PackageBroadcastService( 4918): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4918): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4918): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4918): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4918): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4918): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1696): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1696): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5569 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 4918): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 4918): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4918): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4918): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4918): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4918): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4918): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4918): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4918): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4918): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4918): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4918): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4918): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4918): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 4918): Using Auth Proxy for data requests.
W/BaseAppContext( 4918): Using Auth Proxy for data requests.
I/GMPM-SVC( 4918): App measurement is starting up, version: 8489
I/GMPM-SVC( 4918): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 4918): doRemovePackageData com.test.thalitest
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3ebe80c0 new=com.google.android.velvet.VelvetApplication@3ebe80c0
I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5605 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  315): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 23.273ms
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 20.567ms
D/ConnectivityService(  885): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/art     (  315): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.392ms
I/ThermalEngine(  310): Sensor:xo_therm_pu2:28000 mC
W/DriveInitializer( 4918): Awaiting to be initialized
W/DriveInitializer( 4918): Background init thread started
E/SQLiteLog( 4918): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 4918): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 4918): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4918): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 4918): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4918): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4918): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 4918): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 4918): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 4918): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 4918): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 4918): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 4918): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4918): Process: com.google.android.gms, PID: 4918
E/AndroidRuntime( 4918): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4918): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4918): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 4918): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 4918): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DriveAsyncService( 4918): disk I/O error (code 3850)
E/DriveAsyncService( 4918): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4918): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4918): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 4918): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4918): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4918): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 4918): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 4918): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4918): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4918): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4918): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4918): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4918): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4918): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4918): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4918): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 4918): Sending signal. PID: 4918 SIG: 9
E/DropBoxManagerService(  885): Can't write: system_app_crash
E/DropBoxManagerService(  885): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  885): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  885): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  885): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  885): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  885): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  885): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  885): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  885): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  885): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  885): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  885): 	... 5 more
D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@39baad71)
D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  283): handle_blank_event: dpy:0 panel power state: 0

```
