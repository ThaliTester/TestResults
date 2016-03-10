#### Test 61703351ed386f4_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,V/AlarmManager(  885): send {1faa91c7, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
V/AlarmManager(  885): done {1faa91c7, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [8ms]
--------- beginning of main
D/AndroidRuntime( 5178): 
D/AndroidRuntime( 5178): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5178): CheckJNI is OFF
D/AndroidRuntime( 5178): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5197 uid=10568 gids={50568, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 5178): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5197): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5197): Time to load native libraries: 1 ms (timestamps 641-642)
I/LibraryLoader( 5197): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5197): Binding Chromium to main looper Looper (main, tid 1) {2712cc92}
,I/LibraryLoader( 5197): Expected native library version number "",actual native library version number ""
I/chromium( 5197): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5197): Initializing chromium process, singleProcess=true
,W/art     ( 5197): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5197): ApplicationContext is null in ApplicationStatus
,W/chromium( 5197): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5197): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5197): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5197): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5197): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5197): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5197): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5197): Local Branch: 
I/Adreno-EGL( 5197): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5197): Local Patches: NONE
I/Adreno-EGL( 5197): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothAdapter( 5197): 343958975: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@374cfbdb:true
,I/ActivityManager(  885): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5232 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/art     (  885): Explicit concurrent mark sweep GC freed 22559(1214KB) AllocSpace objects, 4(305KB) LOS objects, 33% free, 19MB/29MB, paused 1.181ms total 133.669ms
,I/GservicesProvider( 5232): Gservices pushing to system: true; secure/global: true
,W/ActivityManager(  885): Activity pause timeout for ActivityRecord{3af4e3f4 u0 com.example.hello/.MainActivity t9}
,I/GoogleHttpClient( 5232): GMS http client unavailable, use old client
,W/art     ( 5197): Attempt to remove local handle scope entry from IRT, ignoring
,I/GoogleHttpClient( 5232): GMS http client unavailable, use old client
,W/AwContents( 5197): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5197): CordovaWebView is running on device made by: motorola
,W/art     ( 5197): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5197): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5197): Render dirty regions requested: true
,D/Atlas   ( 5197): Validating map...
,W/chromium( 5197): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  885): Killing 4720:com.android.defcontainer/u0a10 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10010/pid_4720/cgroup.procs: No such file or directory
,I/OpenGLRenderer( 5197): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5197): Enabling debug mode 0
,I/Keyboard.Facilitator( 1411): onFinishInput()
,I/LaunchCheckinHandler(  885): Displayed com.example.hello/.MainActivity,cp,ca,908
I/ActivityManager(  885): Displayed com.example.hello/.MainActivity: +834ms (total +908ms)
,W/IInputConnectionWrapper( 5197): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5197): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5197): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5197): Cannot call determinedVisibility() - never saw a connection for the pid: 5197
,I/chromium( 5197): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 5197): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 5197): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/jxcore_app_log( 5197): JniHelper::setJavaVM(0xb7618310), pthread_self() = -1214602424
,W/jxcore-log( 5197): Initializing JXcore engine
W/jxcore-log( 5197): JXcore engine is ready
,W/Thread-587( 5283): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10568 path="socket:[5902]" dev="sockfs" ino=5902 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-587( 5283): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10568 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2220 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-587( 5283): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10568 path="socket:[9458]" dev="sockfs" ino=9458 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-587( 5283): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10568 path="socket:[23871]" dev="sockfs" ino=23871 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5197): Starting JXcore engine
,W/jxcore-log( 5197): Platform android
W/jxcore-log( 5197): 
,W/jxcore-log( 5197): Process ARCH arm
W/jxcore-log( 5197): 
,I/jxcore-log( 5197): JXcore Cordova bridge is ready!
I/jxcore-log( 5197): 
,W/jxcore-log( 5197): JXcore engine is started
,E/jxcore  ( 5197): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 5197): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  885): send {12f82187, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {117455c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {117455c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [14ms]
,V/AlarmManager(  885): done {12f82187, *alarm*:android.intent.action.TIME_TICK} [50ms]
,E/global frequency( 2473): no tags to log
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 53386(2MB) AllocSpace objects, 32(1028KB) LOS objects, 40% free, 7MB/12MB, paused 867us total 48.315ms
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1537): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2473): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2473): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2473): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2473): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/art     (  885): Explicit concurrent mark sweep GC freed 6948(380KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 19MB/29MB, paused 1.327ms total 103.965ms
,V/AlarmManager(  885): send {1765f1ec, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  885): done {1765f1ec, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/global frequency( 2473): BcsDSCheckin.events found events 2000
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2473): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 2473): Explicit concurrent mark sweep GC freed 32248(2MB) AllocSpace objects, 6(148KB) LOS objects, 39% free, 12MB/20MB, paused 1.516ms total 62.170ms
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 4207(175KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 930us total 29.562ms
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2473): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2473): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2473): unknown error code mapping for: 0
I/global frequency( 2473): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2473): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2473): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1691): disconnect managed GoogleApiClient
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2473):  Nonce Reponse 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2473): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2473): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2473): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2473): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2473): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2473): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2473): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  885): send {ea619b5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  885): send {224b81c4, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  885): send {117455c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {ea619b5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,V/AlarmManager(  885): done {224b81c4, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [14ms]
V/AlarmManager(  885): done {117455c, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [14ms]
,I/VacuumService( 1691): Vacuum at: now=1457596596400 tag=VacuumService
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  291): NetlinkHandler, power_supply subsys
I/MDMCTBK (  291): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  291): checkDefaultInst, current pid is = 291
I/MDMCTBK (  291): checkDefaultInst, pid match
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  291): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  291): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311324, SEQNUM=4355, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-363, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/CdsService( 2473): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2473): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2473): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1411): run()
I/Keyboard.Facilitator( 1411): flushDynamicLanguageModels()
,I/ConfigService( 1691): onCreate
,I/ConfigService( 1691): onDestroy
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  301): Sensor:xo_therm_pu2:31000 mC
,TIME-OUT KILL (timeout was 150000ms),D/AndroidRuntime( 5320): 
D/AndroidRuntime( 5320): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5320): CheckJNI is OFF
D/AndroidRuntime( 5320): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.example.hello appid=10568 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 5197:com.example.hello/u0a568 (adj 0): stop com.example.hello
I/WindowState(  885): WIN DEATH: Window{315b5066 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowState(  885): WIN DEATH: Window{35eaf9c0 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  885): Skipping PackageSetting{62c8e4d com.test.thalitest/10566} due to missing metadata
I/ActivityManager(  885):   Force finishing activity ActivityRecord{3af4e3f4 u0 com.example.hello/.MainActivity t9}
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ActivityManager(  885): Spurious death for ProcessRecord{3af6a097 5197:com.example.hello/u0a568}, curProc for 5197: null
I/ActivityManager(  885): Force stopping com.example.hello appid=10568 user=0: pkg removed
I/ActivityManager(  885):   Force finishing activity ActivityRecord{3af4e3f4 u0 com.example.hello/.MainActivity t9 f}
W/ActivityManager(  885): Duplicate finish request for ActivityRecord{3af4e3f4 u0 com.example.hello/.MainActivity t9 f}
I/art     ( 2907): Explicit concurrent mark sweep GC freed 3022(622KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 7MB/12MB, paused 508us total 36.818ms
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1411): resetDictionaries() : en_US
W/GeofencerStateMachine( 1691): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5344 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1562): Explicit concurrent mark sweep GC freed 7280(529KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 455us total 104.617ms
I/Keyboard.Facilitator.DecoderInitializer( 1411): run()
D/OtaApp  ( 2473): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2473): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2473): publish the event [tag = MOT_OTA event name = LOG]
I/Decoder ( 1411): createOrResetDecoder
I/OtaApp  ( 2473): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2473): publish the event [tag = MOT_OTA event name = LOG]
I/art     (  885): Explicit concurrent mark sweep GC freed 10152(724KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 19MB/29MB, paused 1.886ms total 140.771ms
I/art     (  885): WaitForGcToComplete blocked for 130.374ms for cause Explicit
D/OtaApp  ( 2473): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2473): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2473): publish the event [tag = MOT_OTA event name = LOG]
I/art     ( 1946): Explicit concurrent mark sweep GC freed 623(28KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/18MB, paused 928us total 197.895ms
I/ConfigService( 1691): onCreate
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1411): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1411): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1411): run()
I/StatsUtilsManager( 1411): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1411): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5344): Cleaning up data for package: com.example.hello
W/InputMethodManagerService(  885): Got RemoteException sending setActive(false) notification to pid 5197 uid 10568
I/Keyboard.Facilitator( 1411): onFinishInput()
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5373 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  885): removeObsoleteFile: deleting file=9_task.xml
I/ContactLocale( 5344): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/TaskPersister(  885): removeObsoleteFile: deleting file=8_task.xml
I/ActivityManager(  885): Killing 4983:com.motorola.context/u0a8 (adj 15): empty #7
I/art     (  885): Explicit concurrent mark sweep GC freed 5186(284KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 19MB/29MB, paused 2.416ms total 211.998ms
D/AndroidRuntime( 5320): Shutting down VM
W/libprocessgroup(  885): failed to open /acct/uid_10008/pid_4983/cgroup.procs: No such file or directory
I/Launcher( 1562): Deferring update until onResume
W/asset   ( 5373): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5373): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5373): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5397 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  885): Killing 2966:com.google.android.calendar/u0a49 (adj 15): empty #7
W/libprocessgroup(  885): failed to open /acct/uid_10049/pid_2966/cgroup.procs: No such file or directory
W/ContextImpl( 5397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1946): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1946): Clearing selected account for com.example.hello
I/LocationSettingsChecker( 1946): Removing dialog suppression flag for package com.example.hello
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 5397): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5397): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 5397): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 5397): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 5397): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 5397): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/SQLiteDatabase( 5397): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/SQLiteDatabase( 5397): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5397): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 5397): 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
E/AndroidRuntime( 5397): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5397): Process: com.android.keychain, PID: 5397
E/AndroidRuntime( 5397): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/AndroidRuntime( 5397): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/AndroidRuntime( 5397): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 5397): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 5397): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
E/AndroidRuntime( 5397): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
E/AndroidRuntime( 5397): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5397): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5397): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1946): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 1946): disk I/O error (code 3850)
E/DriveAsyncService( 1946): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 1946): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 1946): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 1946): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 1946): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 1946): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 1946): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 1946): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteLog( 1691): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/ChimeraCfgMgr( 1946): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1946): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 1691): Shutting down VM
E/AndroidRuntime( 1691): FATAL EXCEPTION: main
E/AndroidRuntime( 1691): Process: com.google.android.gms.persistent, PID: 1691
E/AndroidRuntime( 1691): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1691): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2618)
E/AndroidRuntime( 1691): 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
E/AndroidRuntime( 1691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1369)
E/AndroidRuntime( 1691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1691): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1691): 	at android.app.ActivityThread.main(ActivityThread.java:5312)
E/AndroidRuntime( 1691): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 1691): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 1691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:901)
E/AndroidRuntime( 1691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:696)
E/AndroidRuntime( 1691): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1691): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1691): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 1691): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1691): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1691): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 1691): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1691): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1691): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1691): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2611)
E/AndroidRuntime( 1691): 	... 9 more
E/SQLiteDatabase( 1946): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 1946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1946): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 1946): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1946): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1946): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 1946): Could not unregister android package com.example.hello
E/PhenotypeInitializer( 1946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/PhenotypeInitializer( 1946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/PhenotypeInitializer( 1946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/PhenotypeInitializer( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/PhenotypeInitializer( 1946): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 1946): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 1946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 1946): 	at android.os.Looper.loop(Looper.java:135)
E/PhenotypeInitializer( 1946): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 5397): Sending signal. PID: 5397 SIG: 9
I/Process ( 1691): Sending signal. PID: 1691 SIG: 9
E/DropBoxManagerService(  885): Can't write: system_app_crash
E/DropBoxManagerService(  885): java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteLog( 1946): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDatabase( 1946): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 1946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 1946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 1946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 1946): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 1946): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 1946): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 1946): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 1946): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1946): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 1946): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 1946): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 1946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteOpenHelper( 1946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteOpenHelper( 1946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 1946): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 1946): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 1946): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 1946): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 1946): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 1946): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 1946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 1946): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteOpenHelper( 1946): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1946): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/SQLiteOpenHelper( 1946): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 1946): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1946): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 1946): (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.example.hello"] attempt to write a readonly database
D/gH_CompatibleDatabase( 1946): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Process ( 1946): Sending signal. PID: 1946 SIG: 9
D/GpsStatusListenerHelper(  885): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@12b4450d
D/WifiService(  885): Client connection lost with reason: 4
V/BackupManagerService(  885): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  885): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
I/qdhwcomposer(  277): handle_blank_event: dpy:0 panel power state: 0
D/ConnectivityService(  885): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@18d98cc2)
D/ConnectivityService(  885): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  885): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]

```
