#### Test 579720943a29850_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5342): 
D/AndroidRuntime( 5342): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5342): CheckJNI is OFF
D/AndroidRuntime( 5342): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5361 uid=10491 gids={50491, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5342): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5361): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5361): Time to load native libraries: 4 ms (timestamps 7486-7490)
,I/LibraryLoader( 5361): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5361): Binding Chromium to main looper Looper (main, tid 1) {1c543d5a}
,I/LibraryLoader( 5361): Expected native library version number "",actual native library version number ""
,I/chromium( 5361): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5361): Initializing chromium process, singleProcess=true
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5361): ApplicationContext is null in ApplicationStatus
,W/chromium( 5361): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5361): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5361): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5361): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5361): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5361): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5361): Local Branch: 
I/Adreno-EGL( 5361): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5361): Local Patches: NONE
I/Adreno-EGL( 5361): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79be3b9:true
,D/BluetoothAdapter( 5361): 406871828: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{23c42e5a u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5361): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5361): CordovaWebView is running on device made by: motorola
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5361): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5361): Render dirty regions requested: true
,D/Atlas   ( 5361): Validating map...
,W/chromium( 5361): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5361): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5361): Enabling debug mode 0
,I/Keyboard.Facilitator( 1402): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,968
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +882ms (total +968ms)
,W/IInputConnectionWrapper( 5361): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5361): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5361): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5361): Cannot call determinedVisibility() - never saw a connection for the pid: 5361
,D/JsMessageQueue( 5361): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5361): JniHelper::setJavaVM(0xb77b4310), pthread_self() = -1212933872
,I/chromium( 5361): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5361): Initializing JXcore engine
W/jxcore-log( 5361): JXcore engine is ready
,W/Thread-602( 5409): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10491 path="socket:[5656]" dev="sockfs" ino=5656 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-602( 5409): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10491 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-602( 5409): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10491 path="socket:[7469]" dev="sockfs" ino=7469 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-602( 5409): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10491 path="socket:[23268]" dev="sockfs" ino=23268 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5361): Starting JXcore engine
,W/jxcore-log( 5361): Platform android
W/jxcore-log( 5361): 
,W/jxcore-log( 5361): Process ARCH arm
W/jxcore-log( 5361): 
,I/jxcore-log( 5361): JXcore Cordova bridge is ready!
I/jxcore-log( 5361): 
W/jxcore-log( 5361): JXcore engine is started
,E/jxcore  ( 5361): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5361): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5361): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  880): Killing 5056:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5056/cgroup.procs: No such file or directory
,W/PluginManager( 5361): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2513): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2513): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2513): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2513): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2513): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2513): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5361): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1402): onFinishInput()
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1402): run()
I/Keyboard.Facilitator( 1402): flushDynamicLanguageModels()
,I/ConfigService( 1693): onCreate
,I/ConfigService( 1693): onDestroy
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  880): Explicit concurrent mark sweep GC freed 11398(653KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 19MB/29MB, paused 1.893ms total 114.084ms
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  880): send {3639d7ec, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {3639d7ec, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2513): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2513): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2513): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2513): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2513):  Nonce Reponse 
I/MMApiWebService( 2513): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2513): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2513): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2513): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2513): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2513): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2513): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2513): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2513): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2513): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2513): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2513): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2513): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311347, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-1199, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {3639d7ec, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {26665f11, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {31b7a40d, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): done {26665f11, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [16ms]
,V/AlarmManager(  880): done {3639d7ec, *alarm*:android.intent.action.TIME_TICK} [42ms]
,V/AlarmManager(  880): done {31b7a40d, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [48ms]
,I/EventLogService( 1933): Aggregate from 1454413762371 (log), 1454413762371 (data)
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {3639d7ec, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {264ea8d4, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
,I/PollingManager( 2513): alarm fired!
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2513): alarm fired!
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2513): alarm fired!
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/OtaApp  ( 2513): [info] > PollingManagerService, alarm fired!
,D/Checkin ( 2513): publish the event [tag = MOT_OTA event name = LOG]
,I/Central_PollingManager( 1464): alarm fired!
,V/AlarmManager(  880): done {3639d7ec, *alarm*:android.intent.action.TIME_TICK} [58ms]
,V/AlarmManager(  880): done {264ea8d4, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [73ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2513): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2513): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2513): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2513): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2513):  Nonce Reponse 
I/MMApiWebService( 2513): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2513): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2513): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2513): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2513): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2513): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2513): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2513): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2513): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2513): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2513): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2513): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2513): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2513): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310404, SEQNUM=4394, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-32, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1693): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310685, SEQNUM=4395, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-25, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311005, SEQNUM=4397, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=504, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
D/AndroidRuntime( 5492): 
D/AndroidRuntime( 5492): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5492): CheckJNI is OFF
D/AndroidRuntime( 5492): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10491 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5361:com.test.thalitest/u0a491 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{5ef14a3 com.example.hello/10440} due to missing metadata
W/ActivityManager(  880): Spurious death for ProcessRecord{5919a3b 5361:com.test.thalitest/u0a491}, curProc for 5361: null
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10491 user=0: pkg removed
I/art     ( 2960): Explicit concurrent mark sweep GC freed 4132(813KB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 753us total 44.068ms
I/art     ( 4997): Explicit concurrent mark sweep GC freed 688(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 389us total 93.099ms
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1693): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1402): resetDictionaries() : en_US
I/art     ( 1933): Explicit concurrent mark sweep GC freed 3795(221KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 1.067ms total 124.910ms
I/Keyboard.Facilitator.DecoderInitializer( 1402): run()
I/Decoder ( 1402): createOrResetDecoder
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5521 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7316(532KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 479us total 154.222ms
I/art     (  880): Explicit concurrent mark sweep GC freed 13486(997KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 1.552ms total 153.436ms
I/art     (  880): WaitForGcToComplete blocked for 89.217ms for cause Explicit
I/ConfigService( 1693): onCreate
I/CheckinRequestBuilder( 1693): Classify the device as Phone.
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  880): removeObsoleteFile: deleting file=6_task.xml
D/VoicemailCleanupService( 5521): Cleaning up data for package: com.test.thalitest
W/FetchTask( 1693): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/art     (  880): Explicit concurrent mark sweep GC freed 5675(293KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 3.663ms total 194.386ms
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5552 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5521): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Launcher( 1555): Deferring update until onResume
I/CheckinRequestBuilder( 1693): Classify the device as Phone.
W/FetchTask( 1693): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1693): Classify the device as Phone.
W/asset   ( 5552): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5552): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5552): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/FetchTask( 1693): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/MDMCTBK (  302): NetlinkHandler, power_supply subsys
I/MDMCTBK (  302): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  302): checkDefaultInst, current pid is = 302
I/MDMCTBK (  302): checkDefaultInst, pid match
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  302): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  302): MdmCutbackHndler,Could not open ''
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5572 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2471bb41)
I/art     ( 1693): Explicit concurrent mark sweep GC freed 38105(2MB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 13MB/22MB, paused 881us total 74.790ms
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c0b8e6)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3248fe27)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1fae48d4)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f5dca7d)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@284f7d72)
D/AndroidRuntime( 5492): Shutting down VM
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a3d55c3)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34111e40)
I/ActivityManager(  880): Killing 4997:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8019179)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f93febe)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e958b1f)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f09de6c)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c80cc35)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@370d48ca)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1311ba3b)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@9ec7558)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f7ef6b1)
E/DataBuffer( 1693): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@161f2796)
I/CheckinRequestBuilder( 1693): Classify the device as Phone.
W/ContextImpl( 5572): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_4997/cgroup.procs: No such file or directory
W/FetchTask( 1693): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/PackageBroadcastService( 1933): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1933): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1933): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1933): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1933): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1693): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1693): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/CheckinRequestBuilder( 1693): Classify the device as Phone.
D/gH_CompatibleDatabase( 1933): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1933): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1933): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1933): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1933): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1933): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1933): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1933): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1933): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1933): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1933): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1933): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1933): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5602 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/FetchTask( 1693): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Keyboard.Facilitator.MainLanguageModelLoader( 1402): run()
I/Icing   ( 1933): doRemovePackageData com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1402): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1402): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1402): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1402): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1402): run()
I/StatsUtilsManager( 1402): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1402): shouldRecordStats() = Too Soon
W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@18405f14 new=com.google.android.velvet.VelvetApplication@18405f14
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5629 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  321): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.200ms
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 19.844ms
I/art     (  321): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 20.182ms
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
