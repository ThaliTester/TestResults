#### Test 57132760f6ec045_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 5336): 
D/AndroidRuntime( 5336): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5336): CheckJNI is OFF
D/AndroidRuntime( 5336): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  891): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  891): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5355 uid=10475 gids={50475, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5336): Shutting down VM
V/ActivityManager(  891): Display changed displayId=0
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5355): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5355): Time to load native libraries: 3 ms (timestamps 7574-7577)
I/LibraryLoader( 5355): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5355): Binding Chromium to main looper Looper (main, tid 1) {be583e9}
I/LibraryLoader( 5355): Expected native library version number "",actual native library version number ""
,I/chromium( 5355): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5355): Initializing chromium process, singleProcess=true
W/art     ( 5355): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5355): ApplicationContext is null in ApplicationStatus
,W/chromium( 5355): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5355): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5355): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5355): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5355): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5355): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5355): Local Branch: 
I/Adreno-EGL( 5355): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5355): Local Patches: NONE
I/Adreno-EGL( 5355): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  891): Message: 20
D/BluetoothManagerService(  891): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38ea93e4:true
,D/BluetoothAdapter( 5355): 150834554: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  891): Activity pause timeout for ActivityRecord{809a2d9 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5355): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5355): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5355): CordovaWebView is running on device made by: motorola
,W/art     ( 5355): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5355): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5355): Render dirty regions requested: true
,D/Atlas   ( 5355): Validating map...
,W/chromium( 5355): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5355): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5355): Enabling debug mode 0
,I/Keyboard.Facilitator( 1419): onFinishInput()
,I/LaunchCheckinHandler(  891): Displayed com.test.thalitest/.MainActivity,cp,ca,993
I/ActivityManager(  891): Displayed com.test.thalitest/.MainActivity: +913ms (total +993ms)
,W/IInputConnectionWrapper( 5355): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5355): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5355): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5355): Cannot call determinedVisibility() - never saw a connection for the pid: 5355
,D/JsMessageQueue( 5355): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5355): JniHelper::setJavaVM(0xb76de310), pthread_self() = -1213795496
,I/chromium( 5355): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5355): Initializing JXcore engine
W/jxcore-log( 5355): JXcore engine is ready
,W/Thread-543( 5404): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10475 path="socket:[6852]" dev="sockfs" ino=6852 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-543( 5404): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10475 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-543( 5404): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10475 path="socket:[7503]" dev="sockfs" ino=7503 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-543( 5404): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10475 path="socket:[22413]" dev="sockfs" ino=22413 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5355): Starting JXcore engine
,W/jxcore-log( 5355): Platform android
W/jxcore-log( 5355): 
,W/jxcore-log( 5355): Process ARCH arm
W/jxcore-log( 5355): 
,I/jxcore-log( 5355): JXcore Cordova bridge is ready!
I/jxcore-log( 5355): 
W/jxcore-log( 5355): JXcore engine is started
,E/jxcore  ( 5355): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5355): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5355): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  891): Killing 5113:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  891): failed to open /acct/uid_10057/pid_5113/cgroup.procs: No such file or directory
,W/PluginManager( 5355): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1476): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2692): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2692): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2692): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2692): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2692): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2692): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1419): onFinishInput()
,W/IInputConnectionWrapper( 5355): showStatusIcon on inactive InputConnection
,D/TaskPersister(  891): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1419): run()
I/Keyboard.Facilitator( 1419): flushDynamicLanguageModels()
,I/ConfigService( 1726): onCreate
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ConfigService( 1726): onDestroy
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2692): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2692): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2692): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1476): Explicit concurrent mark sweep GC freed 4778(230KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 7MB/12MB, paused 916us total 38.141ms
,D/MMApiWebService( 2692): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2692):  Nonce Reponse 
I/MMApiWebService( 2692): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2692): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2692): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2692): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2692): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2692): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2692): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2692): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2692): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2692): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2692): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2692): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2692): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  304): NetlinkHandler, power_supply subsys
I/MDMCTBK (  304): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  304): checkDefaultInst, current pid is = 304
I/MDMCTBK (  304): checkDefaultInst, pid match
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  304): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  304): NetlinkHandler, power_supply subsys
I/MDMCTBK (  304): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  304): checkDefaultInst, current pid is = 304
I/MDMCTBK (  304): checkDefaultInst, pid match
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  304): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311973, SEQNUM=4452, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11919, POWER_SUPPLY_CHARGE_COUNTER=-1338, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  891): send {7f2829d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  891): send {13e41d16, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  891): done {13e41d16, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [6ms]
,V/AlarmManager(  891): done {7f2829d, *alarm*:android.intent.action.TIME_TICK} [50ms]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2692): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2692): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2692): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2692): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2692):  Nonce Reponse 
,I/MMApiWebService( 2692): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2692): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2692): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2692): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2692): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2692): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2692): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2692): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2692): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2692): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2692): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,D/CdsService( 2692): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2692): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2692): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  891): User[0] Flushing usage stats to disk
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  891): Explicit concurrent mark sweep GC freed 15129(841KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 20MB/30MB, paused 1.518ms total 136.594ms
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  304): NetlinkHandler, power_supply subsys
I/MDMCTBK (  304): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  304): checkDefaultInst, current pid is = 304
I/MDMCTBK (  304): checkDefaultInst, pid match
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  304): MdmCutbackHndler,Could not open ''
,D/BatteryService(  891): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311325, SEQNUM=4461, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1614, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  304): NetlinkHandler, power_supply subsys
I/MDMCTBK (  304): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  304): checkDefaultInst, current pid is = 304
I/MDMCTBK (  304): checkDefaultInst, pid match
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  304): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  304): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  317): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5477): 
D/AndroidRuntime( 5477): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5477): CheckJNI is OFF
D/AndroidRuntime( 5477): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10475 user=-1: uninstall pkg
I/ActivityManager(  891): Killing 5355:com.test.thalitest/u0a475 (adj 9): stop com.test.thalitest
W/ActivityManager(  891): Spurious death for ProcessRecord{20c8c4a4 5355:com.test.thalitest/u0a475}, curProc for 5355: null
W/PackageSettings(  891): Skipping PackageSetting{c356366 com.example.hello/10440} due to missing metadata
I/ActivityManager(  891): Force stopping com.test.thalitest appid=10475 user=0: pkg removed
I/InputReader(  891): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1726): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1419): resetDictionaries() : en_US
I/art     ( 3136): Explicit concurrent mark sweep GC freed 4661(896KB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 7MB/12MB, paused 554us total 52.253ms
I/Keyboard.Facilitator.DecoderInitializer( 1419): run()
I/Decoder ( 1419): createOrResetDecoder
D/VoicemailCleanupService( 1625): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  891): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5507 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  891): Explicit concurrent mark sweep GC freed 7605(664KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 19MB/29MB, paused 2.316ms total 150.474ms
I/art     (  891): WaitForGcToComplete blocked for 151.880ms for cause Explicit
I/art     ( 1567): Explicit concurrent mark sweep GC freed 3676(245KB) AllocSpace objects, 1(36KB) LOS objects, 24% free, 13MB/17MB, paused 519us total 59.380ms
I/art     ( 1945): Explicit concurrent mark sweep GC freed 1995(76KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 1.272ms total 95.422ms
I/ConfigService( 1726): onCreate
W/asset   ( 5507): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5507): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): run()
D/BackupManagerService(  891): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  891): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     ( 1726): Explicit concurrent mark sweep GC freed 36687(2MB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 13MB/22MB, paused 964us total 79.304ms
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f5f82d2)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@35f2dfa3)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@139f12a0)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a27de59)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a8efa1e)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3049d2ff)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3df2b8cc)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@e6f0715)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8ac9a2a)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ef2a01b)
I/ActivityManager(  891): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5532 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19f895b8)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@10c5ff91)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33522ef6)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c9122f7)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@347d5564)
D/TaskPersister(  891): removeObsoleteFile: deleting file=6_task.xml
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@38ba03cd)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@11ea4482)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2af793)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@386c63d0)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f700fc9)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1419): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = contacts
I/art     (  891): Explicit concurrent mark sweep GC freed 4859(247KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 3.930ms total 192.022ms
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1419): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1419): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1419): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1419): run()
I/StatsUtilsManager( 1419): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1419): shouldRecordStats() = Too Soon
W/ContextImpl( 5532): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1945): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1945): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1945): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1945): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1945): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5562 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  891): send {7f2829d, *alarm*:android.intent.action.TIME_TICK}
D/AndroidRuntime( 5477): Shutting down VM
V/AlarmManager(  891): send {13e41d16, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  891): send {396d8be2, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
I/Launcher( 1567): Deferring update until onResume
I/Icing   ( 1945): doRemovePackageData com.test.thalitest
V/AlarmManager(  891): done {7f2829d, *alarm*:android.intent.action.TIME_TICK} [47ms]
W/Launcher( 1567): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@3b6c992b new=com.google.android.velvet.VelvetApplication@3b6c992b
I/ActivityManager(  891): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5585 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  891): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5613 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  891): Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=5630 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/SharedPreferencesImpl( 5562): Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
--------- beginning of crash
E/AndroidRuntime( 5562): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5562): Process: com.google.android.googlequicksearchbox:search, PID: 5562
E/AndroidRuntime( 5562): java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
E/AndroidRuntime( 5562): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
E/AndroidRuntime( 5562): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
E/AndroidRuntime( 5562): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5562): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5562): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 5562): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 5562): Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5562): 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
E/AndroidRuntime( 5562): 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
E/AndroidRuntime( 5562): 	... 7 more
E/AndroidRuntime( 5562): Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
E/AndroidRuntime( 5562): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
E/AndroidRuntime( 5562): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 5562): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 5562): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 5562): 	at java.lang.Thread.run(Thread.java:818)
E/AndroidRuntime( 5562): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
E/AndroidRuntime( 5562): Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5562): 	at java.io.File.createNewFile(File.java:941)
E/AndroidRuntime( 5562): 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
E/AndroidRuntime( 5562): 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
E/AndroidRuntime( 5562): 	... 9 more
E/AndroidRuntime( 5562): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/AndroidRuntime( 5562): 	at libcore.io.Posix.open(Native Method)
E/AndroidRuntime( 5562): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/AndroidRuntime( 5562): 	at java.io.File.createNewFile(File.java:934)
E/AndroidRuntime( 5562): 	... 11 more
I/art     (  321): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.538ms
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
