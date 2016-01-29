#### Test 5761781115ba656_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  896): send {d4f48e8, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
V/AlarmManager(  896): done {d4f48e8, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [9ms]
--------- beginning of main
D/AndroidRuntime( 5160): 
D/AndroidRuntime( 5160): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5160): CheckJNI is OFF
D/AndroidRuntime( 5160): Calling main entry com.android.commands.am.Am
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  896): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5179 uid=10484 gids={50484, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5160): Shutting down VM
V/ActivityManager(  896): Display changed displayId=0
W/ContextImpl( 1484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5179): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5179): Time to load native libraries: 1 ms (timestamps 1094-1095)
I/LibraryLoader( 5179): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5179): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
I/LibraryLoader( 5179): Expected native library version number "",actual native library version number ""
I/chromium( 5179): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5179): Initializing chromium process, singleProcess=true
W/art     ( 5179): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5179): ApplicationContext is null in ApplicationStatus
W/chromium( 5179): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5179): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5179): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5179): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5179): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5179): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5179): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5179): Local Branch: 
I/Adreno-EGL( 5179): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5179): Local Patches: NONE
I/Adreno-EGL( 5179): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  896): Message: 20
D/BluetoothManagerService(  896): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19bd392c:true
D/BluetoothAdapter( 5179): 446216149: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  896): Activity pause timeout for ActivityRecord{1e68eb01 u0 com.test.thalitest/.MainActivity t6}
W/art     ( 5179): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5179): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5179): CordovaWebView is running on device made by: motorola
W/art     ( 5179): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5179): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5179): Render dirty regions requested: true
D/Atlas   ( 5179): Validating map...
W/chromium( 5179): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5179): Initialized EGL, version 1.4
D/OpenGLRenderer( 5179): Enabling debug mode 0
I/Keyboard.Facilitator( 1425): onFinishInput()
I/LaunchCheckinHandler(  896): Displayed com.test.thalitest/.MainActivity,cp,ca,958
I/ActivityManager(  896): Displayed com.test.thalitest/.MainActivity: +878ms (total +958ms)
W/IInputConnectionWrapper( 5179): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5179): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5179): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5179): Cannot call determinedVisibility() - never saw a connection for the pid: 5179
,D/JsMessageQueue( 5179): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5179): JniHelper::setJavaVM(0xb8578310), pthread_self() = -1198489824
,I/chromium( 5179): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5179): Initializing JXcore engine
W/jxcore-log( 5179): JXcore engine is ready
,W/Thread-598( 5235): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10484 path="socket:[9566]" dev="sockfs" ino=9566 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-598( 5235): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10484 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-598( 5235): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10484 path="socket:[9745]" dev="sockfs" ino=9745 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-598( 5235): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10484 path="socket:[23161]" dev="sockfs" ino=23161 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5179): Starting JXcore engine
,W/jxcore-log( 5179): Platform android
W/jxcore-log( 5179): 
,W/jxcore-log( 5179): Process ARCH arm
W/jxcore-log( 5179): 
,I/jxcore-log( 5179): JXcore Cordova bridge is ready!
I/jxcore-log( 5179): 
,W/jxcore-log( 5179): JXcore engine is started
,E/jxcore  ( 5179): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5179): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5179): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  896): Killing 4814:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  896): failed to open /acct/uid_10007/pid_4814/cgroup.procs: No such file or directory
,W/PluginManager( 5179): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 23ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1484): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2514): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2514): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2514): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2514): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2514): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2514): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5179): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1425): onFinishInput()
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,D/TaskPersister(  896): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  896): send {36f95b09, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  896): send {1df25082, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  896): done {1df25082, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,V/AlarmManager(  896): done {36f95b09, *alarm*:android.intent.action.TIME_TICK} [41ms]
,V/AlarmManager(  896): send {2e93fde1, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  896): done {2e93fde1, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,E/global frequency( 2514): no tags to log
,D/Checkin ( 2514): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2514): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  896): Explicit concurrent mark sweep GC freed 16952(900KB) AllocSpace objects, 6(261KB) LOS objects, 33% free, 19MB/29MB, paused 1.490ms total 120.275ms
,D/BSUtils ( 2514): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1484): Explicit concurrent mark sweep GC freed 55689(3MB) AllocSpace objects, 32(1036KB) LOS objects, 39% free, 7MB/12MB, paused 745us total 42.653ms
,I/BSUtils ( 2514): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2514): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2514): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/BSUtils ( 2514): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2514): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2514): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1484): Explicit concurrent mark sweep GC freed 4180(174KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 634us total 34.616ms
,I/BSUtils ( 2514): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2514): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2514): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2514): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2514): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2514): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2514): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/art     ( 2514): Explicit concurrent mark sweep GC freed 10336(558KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 10MB/18MB, paused 838us total 53.395ms
,I/global frequency( 2514): BcsDSCheckin.events found events 1078
,D/Checkin ( 2514): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2514): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2514): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2514): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2514): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2514): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2514): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2514): unknown error code mapping for: 0
I/global frequency( 2514): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2514): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2514): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2514): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2514): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2514): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2514):  Nonce Reponse 
I/MMApiWebService( 2514): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2514): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2514): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2514): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2514): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2514): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2514): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2514): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2514): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2514): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1425): run()
I/Keyboard.Facilitator( 1425): flushDynamicLanguageModels()
,I/ConfigService( 1727): onCreate
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ClearcutLoggerApiImpl( 1727): disconnect managed GoogleApiClient
,I/ConfigService( 1727): onDestroy
,V/AlarmManager(  896): send {49902a6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  896): send {36f95b09, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  896): send {2d764b60, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  896): send {1df25082, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  896): done {49902a6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [5ms]
,V/AlarmManager(  896): done {2d764b60, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [22ms]
V/AlarmManager(  896): done {1df25082, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [22ms]
,V/AlarmManager(  896): done {36f95b09, *alarm*:android.intent.action.TIME_TICK} [53ms]
,I/VacuumService( 1727): Vacuum at: now=1454056265294 tag=VacuumService
,D/BatteryService(  896): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310865, SEQNUM=4353, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-780, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
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
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  896): Explicit concurrent mark sweep GC freed 9601(475KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.408ms total 134.268ms
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2514): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2514): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2514): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2514): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2514):  Nonce Reponse 
I/MMApiWebService( 2514): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2514): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2514): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2514): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2514): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2514): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2514): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2514): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2514): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2514): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  896): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310997, SEQNUM=4363, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-1428, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  896): send {36f95b09, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  896): send {3a1401, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  896): send {37a506f9, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  896): done {3a1401, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [17ms]
,V/AlarmManager(  896): done {36f95b09, *alarm*:android.intent.action.TIME_TICK} [42ms]
,V/AlarmManager(  896): done {37a506f9, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [110ms]
,I/EventLogService( 1956): Aggregate from 1454055295406 (log), 1454055295406 (data)
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2514): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2514): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2514): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2514): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2514):  Nonce Reponse 
I/MMApiWebService( 2514): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2514): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2514): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2514): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2514): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2514): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1484): Explicit concurrent mark sweep GC freed 3283(143KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 838us total 37.229ms
,D/MMApiWebService( 2514): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2514): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2514): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2514): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2514): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  896): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  896): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310936, SEQNUM=4368, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-6, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1727): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  896): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310347, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=3732, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5332): 
D/AndroidRuntime( 5332): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5332): CheckJNI is OFF
D/AndroidRuntime( 5332): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10484 user=-1: uninstall pkg
I/ActivityManager(  896): Killing 5179:com.test.thalitest/u0a484 (adj 11): stop com.test.thalitest
W/PackageSettings(  896): Skipping PackageSetting{f36067b com.example.hello/10440} due to missing metadata
W/ActivityManager(  896): Spurious death for ProcessRecord{139052f0 5179:com.test.thalitest/u0a484}, curProc for 5179: null
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10484 user=0: pkg removed
I/art     ( 2922): Explicit concurrent mark sweep GC freed 4025(785KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 7MB/12MB, paused 560us total 39.492ms
W/GeofencerStateMachine( 1727): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1425): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1425): run()
I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1559): Explicit concurrent mark sweep GC freed 7303(530KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 468us total 85.727ms
I/ActivityManager(  896): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5351 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Decoder ( 1425): createOrResetDecoder
I/ConfigService( 1727): onCreate
I/art     ( 1956): Explicit concurrent mark sweep GC freed 3815(222KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 2.697ms total 210.204ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1425): run()
I/art     (  896): Explicit concurrent mark sweep GC freed 14308(1039KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 2.042ms total 209.549ms
I/art     (  896): WaitForGcToComplete blocked for 119.328ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1425): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1425): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1425): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1425): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1425): run()
I/StatsUtilsManager( 1425): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1425): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5351): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  896): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5383 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5351): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  896): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  896): removeObsoleteFile: deleting file=6_task.xml
I/Launcher( 1559): Deferring update until onResume
W/asset   ( 5383): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5383): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5383): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5383): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  896): Explicit concurrent mark sweep GC freed 4262(212KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.600ms total 179.543ms
I/ActivityManager(  896): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5402 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 4957:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 5332): Shutting down VM
W/libprocessgroup(  896): failed to open /acct/uid_10090/pid_4957/cgroup.procs: No such file or directory
W/ContextImpl( 5402): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1956): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1956): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1956): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1956): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1956): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1727): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1727): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
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
I/ActivityManager(  896): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5431 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/ChimeraCfgMgr( 1956): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1956): Module APK com.google.android.play.games already loaded
I/Icing   ( 1956): doRemovePackageData com.test.thalitest
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  896): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5457 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
