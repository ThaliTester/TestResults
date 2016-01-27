#### Test 564496604206eac_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 5225): 
D/AndroidRuntime( 5225): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5225): CheckJNI is OFF
D/AndroidRuntime( 5225): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5244 uid=10480 gids={50480, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5225): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5244): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5244): Time to load native libraries: 2 ms (timestamps 7286-7288)
,I/LibraryLoader( 5244): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5244): Binding Chromium to main looper Looper (main, tid 1) {430ea56}
,I/LibraryLoader( 5244): Expected native library version number "",actual native library version number ""
,I/chromium( 5244): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5244): Initializing chromium process, singleProcess=true
,W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5244): ApplicationContext is null in ApplicationStatus
,W/chromium( 5244): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5244): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5244): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5244): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5244): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5244): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5244): Local Branch: 
I/Adreno-EGL( 5244): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5244): Local Patches: NONE
I/Adreno-EGL( 5244): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1493c6fb:true
,D/BluetoothAdapter( 5244): 90822825: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{2ba76294 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5244): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5244): CordovaWebView is running on device made by: motorola
,W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5244): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5244): Render dirty regions requested: true
,D/Atlas   ( 5244): Validating map...
,W/chromium( 5244): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5244): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5244): Enabling debug mode 0
,I/Keyboard.Facilitator( 1411): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,940
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +869ms (total +941ms)
,W/IInputConnectionWrapper( 5244): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5244): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5244): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5244): Cannot call determinedVisibility() - never saw a connection for the pid: 5244
,D/JsMessageQueue( 5244): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5244): JniHelper::setJavaVM(0xb8c0c310), pthread_self() = -1191595952
,I/chromium( 5244): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5244): Initializing JXcore engine
W/jxcore-log( 5244): JXcore engine is ready
,W/Thread-612( 5292): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10480 path="socket:[9856]" dev="sockfs" ino=9856 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-612( 5292): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10480 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-612( 5292): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10480 path="socket:[6550]" dev="sockfs" ino=6550 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-612( 5292): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10480 path="socket:[23026]" dev="sockfs" ino=23026 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5244): Starting JXcore engine
,W/jxcore-log( 5244): Platform android
W/jxcore-log( 5244): 
,W/jxcore-log( 5244): Process ARCH arm
W/jxcore-log( 5244): 
,I/jxcore-log( 5244): JXcore Cordova bridge is ready!
I/jxcore-log( 5244): 
W/jxcore-log( 5244): JXcore engine is started
,E/jxcore  ( 5244): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5244): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5244): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  883): Killing 4883:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_4883/cgroup.procs: No such file or directory
W/PluginManager( 5244): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 43ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1469): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2510): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2510): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2510): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2510): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2510): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2510): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  883): send {19df86c9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): done {19df86c9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [3ms]
,W/IInputConnectionWrapper( 5244): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1411): onFinishInput()
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task.xml
,V/AlarmManager(  883): send {9cfbaf4, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {9cfbaf4, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,E/global frequency( 2510): no tags to log
,D/Checkin ( 2510): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 2510): Explicit concurrent mark sweep GC freed 20994(1306KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 1.414ms total 67.780ms
,D/BSUtils ( 2510): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  883): Explicit concurrent mark sweep GC freed 16014(822KB) AllocSpace objects, 5(242KB) LOS objects, 33% free, 19MB/29MB, paused 1.374ms total 114.800ms
,D/BSUtils ( 2510): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2510): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2510): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 37768(2029KB) AllocSpace objects, 17(582KB) LOS objects, 40% free, 7MB/12MB, paused 620us total 38.541ms
,D/BSUtils ( 2510): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2510): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2510): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2510): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2510): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2510): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2510): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2510): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2510): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2510): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2510): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2510): BcsDSCheckin.events found events 699
,D/Checkin ( 2510): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2510): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2510): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2510): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2510): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2510): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2510): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2510): unknown error code mapping for: 0
I/global frequency( 2510): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2510): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2510): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
D/Checkin ( 2510): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2510): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2510): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2510): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1469): Explicit concurrent mark sweep GC freed 3650(144KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 734us total 30.780ms
,D/MMApiWebService( 2510): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2510):  Nonce Reponse 
I/MMApiWebService( 2510): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2510): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2510): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2510): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2510): Explicit concurrent mark sweep GC freed 22722(1696KB) AllocSpace objects, 2(31KB) LOS objects, 40% free, 11MB/18MB, paused 1.072ms total 72.112ms
,D/MMApiWebService( 2510): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2510): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2510): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {f20de5c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {2f796b83, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  883): send {19df86c9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): done {2f796b83, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [23ms]
V/AlarmManager(  883): done {19df86c9, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [23ms]
,V/AlarmManager(  883): done {f20de5c, *alarm*:android.intent.action.TIME_TICK} [54ms]
,I/VacuumService( 1706): Vacuum at: now=1453885623412 tag=VacuumService
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311549, SEQNUM=4351, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-529, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {2b64dfde, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  883): done {2b64dfde, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/ClearcutLoggerApiImpl( 1706): disconnect managed GoogleApiClient
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1411): run()
I/Keyboard.Facilitator( 1411): flushDynamicLanguageModels()
,I/ConfigService( 1706): onCreate
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311787, SEQNUM=4352, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-523, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ConfigService( 1706): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310852, SEQNUM=4354, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-552, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311429, SEQNUM=4355, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-568, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  883): Explicit concurrent mark sweep GC freed 10655(595KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 1.846ms total 128.676ms
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {f20de5c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {f20de5c, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2510): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2510): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2510): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2510): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2510):  Nonce Reponse 
I/MMApiWebService( 2510): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2510): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2510): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2510): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2510): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2510): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2510): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311031, SEQNUM=4362, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-135, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2510): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2510): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2510): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2510): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2510):  Nonce Reponse 
I/MMApiWebService( 2510): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2510): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2510): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2510): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2510): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2510): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2510): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2510): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2510): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {f20de5c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {28bb5232, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  883): send {58c28ec, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  883): done {28bb5232, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [23ms]
,V/AlarmManager(  883): done {58c28ec, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [35ms]
,V/AlarmManager(  883): done {f20de5c, *alarm*:android.intent.action.TIME_TICK} [48ms]
,I/EventLogService( 1929): Aggregate from 1453884721926 (log), 1453884721926 (data)
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1706): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311001, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-46, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5410): 
D/AndroidRuntime( 5410): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5410): CheckJNI is OFF
D/AndroidRuntime( 5410): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10480 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 5244:com.test.thalitest/u0a480 (adj 11): stop com.test.thalitest
W/ActivityManager(  883): Spurious death for ProcessRecord{3bca7e8f 5244:com.test.thalitest/u0a480}, curProc for 5244: null
W/PackageSettings(  883): Skipping PackageSetting{35d2a36f com.example.hello/10440} due to missing metadata
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10480 user=0: pkg removed
I/Keyboard.Facilitator( 1411): resetDictionaries() : en_US
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1706): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5430 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 2914): Explicit concurrent mark sweep GC freed 3922(747KB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 731us total 99.197ms
I/Keyboard.Facilitator.DecoderInitializer( 1411): run()
I/Decoder ( 1411): createOrResetDecoder
I/ConfigService( 1706): onCreate
I/art     ( 1560): Explicit concurrent mark sweep GC freed 7316(532KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 533us total 167.309ms
I/art     (  883): Explicit concurrent mark sweep GC freed 12327(902KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 1.799ms total 182.503ms
I/art     (  883): WaitForGcToComplete blocked for 76.002ms for cause Explicit
I/art     ( 1929): Explicit concurrent mark sweep GC freed 3880(224KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 944us total 195.361ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): run()
D/VoicemailCleanupService( 5430): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5462 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = contacts
I/ContactLocale( 5430): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = user
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  883): removeObsoleteFile: deleting file=6_task.xml
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1411): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1411): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1411): run()
I/StatsUtilsManager( 1411): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1411): shouldRecordStats() = Too Soon
I/Launcher( 1560): Deferring update until onResume
W/asset   ( 5462): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5462): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5462): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  883): Explicit concurrent mark sweep GC freed 5494(296KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.043ms total 205.813ms
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5483 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 20.692ms
I/ActivityManager(  883): Killing 5025:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 5410): Shutting down VM
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 246us total 21.872ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.687ms
W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_5025/cgroup.procs: No such file or directory
W/ContextImpl( 5483): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1929): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1929): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1929): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1929): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1929): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1929): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1929): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1706): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1706): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1929): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1929): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1929): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1929): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1929): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1929): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1929): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1929): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1929): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1929): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1929): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1929): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1929): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5513 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/Launcher( 1560): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@393e4430 new=com.google.android.velvet.VelvetApplication@393e4430
I/Icing   ( 1929): doRemovePackageData com.test.thalitest
I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5543 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
