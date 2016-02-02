#### Test 575312431be71d2_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5272): 
D/AndroidRuntime( 5272): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5272): CheckJNI is OFF
D/AndroidRuntime( 5272): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  878): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5291 uid=10493 gids={50493, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5272): Shutting down VM
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5291): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5291): Time to load native libraries: 3 ms (timestamps 7357-7360)
,I/LibraryLoader( 5291): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5291): Binding Chromium to main looper Looper (main, tid 1) {159d164b}
,I/LibraryLoader( 5291): Expected native library version number "",actual native library version number ""
,I/chromium( 5291): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5291): Initializing chromium process, singleProcess=true
,W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5291): ApplicationContext is null in ApplicationStatus
,W/chromium( 5291): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5291): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5291): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5291): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5291): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5291): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5291): Local Branch: 
I/Adreno-EGL( 5291): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5291): Local Patches: NONE
I/Adreno-EGL( 5291): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  878): Message: 20
D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@184fd7d:true
,D/BluetoothAdapter( 5291): 528491378: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  878): Activity pause timeout for ActivityRecord{1dbf5d0e u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5291): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5291): CordovaWebView is running on device made by: motorola
,W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5291): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5291): Render dirty regions requested: true
,D/Atlas   ( 5291): Validating map...
,W/chromium( 5291): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5291): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5291): Enabling debug mode 0
,I/Keyboard.Facilitator( 1401): onFinishInput()
,I/LaunchCheckinHandler(  878): Displayed com.test.thalitest/.MainActivity,cp,ca,1038
,I/ActivityManager(  878): Displayed com.test.thalitest/.MainActivity: +952ms (total +1s38ms)
,W/IInputConnectionWrapper( 5291): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5291): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5291): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5291): Cannot call determinedVisibility() - never saw a connection for the pid: 5291
,D/JsMessageQueue( 5291): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5291): JniHelper::setJavaVM(0xb8875310), pthread_self() = -1195356424
,I/chromium( 5291): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5291): Initializing JXcore engine
W/jxcore-log( 5291): JXcore engine is ready
W/Thread-598( 5340): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10493 path="socket:[7340]" dev="sockfs" ino=7340 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-598( 5340): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10493 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-598( 5340): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10493 path="socket:[6715]" dev="sockfs" ino=6715 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-598( 5340): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10493 path="socket:[24697]" dev="sockfs" ino=24697 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5291): Starting JXcore engine
W/jxcore-log( 5291): Platform android
W/jxcore-log( 5291): 
W/jxcore-log( 5291): Process ARCH arm
W/jxcore-log( 5291): 
,I/jxcore-log( 5291): JXcore Cordova bridge is ready!
I/jxcore-log( 5291): 
W/jxcore-log( 5291): JXcore engine is started
,E/jxcore  ( 5291): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5291): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5291): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  878): Killing 4908:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_4908/cgroup.procs: No such file or directory
,W/PluginManager( 5291): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 86ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1458): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2457): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2457): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2457): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2457): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2457): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2457): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1401): onFinishInput()
W/IInputConnectionWrapper( 5291): showStatusIcon on inactive InputConnection
,D/TaskPersister(  878): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1401): run()
I/Keyboard.Facilitator( 1401): flushDynamicLanguageModels()
,I/ConfigService( 1687): onCreate
,I/ConfigService( 1687): onDestroy
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  878): Explicit concurrent mark sweep GC freed 12014(696KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 19MB/29MB, paused 1.444ms total 189.102ms
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2457): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2457): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2457): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2457): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2457):  Nonce Reponse 
I/MMApiWebService( 2457): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2457): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2457): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2457): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2457): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2457): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 2457): Explicit concurrent mark sweep GC freed 41132(3MB) AllocSpace objects, 6(150KB) LOS objects, 40% free, 11MB/18MB, paused 1.629ms total 69.076ms
,D/MMApiWebService( 2457): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2457): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2457): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2457): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2457): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2457): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2457): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311012, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6911, POWER_SUPPLY_CHARGE_COUNTER=-995, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=265, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311557, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-1287, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {12f0f7ad, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {1a256b55, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  878): done {1a256b55, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [8ms]
,V/AlarmManager(  878): done {12f0f7ad, *alarm*:android.intent.action.TIME_TICK} [51ms]
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311536, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-21, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311241, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {12f0f7ad, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {1bbd06ef, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
,I/PollingManager( 2457): alarm fired!
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2457): alarm fired!
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2457): alarm fired!
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/OtaApp  ( 2457): [info] > PollingManagerService, alarm fired!
,D/Checkin ( 2457): publish the event [tag = MOT_OTA event name = LOG]
,I/Central_PollingManager( 1458): alarm fired!
,V/AlarmManager(  878): done {12f0f7ad, *alarm*:android.intent.action.TIME_TICK} [56ms]
,V/AlarmManager(  878): done {1bbd06ef, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [69ms]
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2457): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2457): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2457): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2457): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2457):  Nonce Reponse 
I/MMApiWebService( 2457): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2457): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2457): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2457): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2457): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2457): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1458): Explicit concurrent mark sweep GC freed 4213(198KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 881us total 31.470ms
,D/MMApiWebService( 2457): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2457): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2457): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2457): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2457): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2457): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2457): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2457): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=263, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311523, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=34, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  878): User[0] Flushing usage stats to disk
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311812, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311510, SEQNUM=4383, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=7, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1687): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311216, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310913, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-55, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  312): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5419): 
D/AndroidRuntime( 5419): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5419): CheckJNI is OFF
D/AndroidRuntime( 5419): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10493 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 5291:com.test.thalitest/u0a493 (adj 9): stop com.test.thalitest
W/PackageSettings(  878): Skipping PackageSetting{19d51f60 com.example.hello/10440} due to missing metadata
W/ActivityManager(  878): Spurious death for ProcessRecord{b42a332 5291:com.test.thalitest/u0a493}, curProc for 5291: null
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10493 user=0: pkg removed
I/art     ( 2896): Explicit concurrent mark sweep GC freed 4597(863KB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 7MB/12MB, paused 669us total 39.908ms
I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1687): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1401): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1401): run()
I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5438 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1553): Explicit concurrent mark sweep GC freed 7352(534KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 515us total 119.807ms
I/Decoder ( 1401): createOrResetDecoder
I/ConfigService( 1687): onCreate
I/art     ( 1926): Explicit concurrent mark sweep GC freed 3966(227KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 14MB/19MB, paused 1.048ms total 184.366ms
I/art     (  878): Explicit concurrent mark sweep GC freed 15413(1152KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 3.585ms total 193.108ms
I/art     (  878): WaitForGcToComplete blocked for 125.754ms for cause Explicit
I/CheckinRequestBuilder( 1687): Classify the device as Phone.
D/VoicemailCleanupService( 5438): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5472 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5438): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
W/FetchTask( 1687): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  878): removeObsoleteFile: deleting file=6_task.xml
I/art     (  878): Explicit concurrent mark sweep GC freed 4068(197KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 3.873ms total 154.281ms
W/asset   ( 5472): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5472): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5472): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5472): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 1687): Classify the device as Phone.
W/FetchTask( 1687): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1687): Classify the device as Phone.
W/FetchTask( 1687): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1687): Classify the device as Phone.
I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5496 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Launcher( 1553): Deferring update until onResume
I/ActivityManager(  878): Killing 5051:com.google.android.apps.plus/u0a90 (adj 15): empty #7
W/FetchTask( 1687): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/AndroidRuntime( 5419): Shutting down VM
I/CheckinRequestBuilder( 1687): Classify the device as Phone.
W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_5051/cgroup.procs: No such file or directory
W/FetchTask( 1687): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Keyboard.Facilitator.MainLanguageModelLoader( 1401): run()
W/ContextImpl( 5496): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/ChimeraCfgMgr( 1926): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1926): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 1926): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1926): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1926): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1926): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1687): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1687): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 1926): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1401): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = user
D/gH_CompatibleDatabase( 1926): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1926): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1401): run() : Loaded (exit)
D/gH_MetricsDatabase( 1926): 0 metrics were deleted when clearing package com.test.thalitest.
I/Keyboard.Facilitator.Delight2FileSweeper( 1401): run()
D/gH_CompatibleDatabase( 1926): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Keyboard.Facilitator.RecurringTaskScheduler( 1401): run()
I/StatsUtilsManager( 1401): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1401): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 1926): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1926): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1926): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1926): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1926): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1926): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1926): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1926): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1926): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5524 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
E/SQLiteLog( 1926): (3850) statement aborts at 16: [DELETE FROM raw_events WHERE app_id=?] disk I/O error
I/Icing   ( 1926): doRemovePackageData com.test.thalitest
E/SQLiteLog( 1926): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 1926): Error deleting application data. appId, error: com.test.thalitest, android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.e(SourceFile:1778)
--------- beginning of crash
E/AndroidRuntime( 1926): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 1926): Process: com.google.android.gms, PID: 1926
E/AndroidRuntime( 1926): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1926): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1926): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1926): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1926): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1926): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 1926): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 1926): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 1926): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3166)
E/AndroidRuntime( 1926): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 1926): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 1926): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 1926): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1926): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 1926): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/FileUtils( 1926): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
E/Icing   ( 1926): Failed to open Apps corpus file.
E/Icing   ( 1926): Failed to open Apps corpus file.
I/Process ( 1926): Sending signal. PID: 1926 SIG: 9
E/DropBoxManagerService(  878): Can't write: system_app_crash
E/DropBoxManagerService(  878): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  878): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  878): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  878): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  878): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  878): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  878): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  878): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  878): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  878): 	... 5 more
D/ConnectivityService(  878): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@f4df011)
D/ConnectivityService(  878): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  878): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
I/ActivityManager(  878): Process com.google.android.gms (pid 1926) has died
W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 1000ms
W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 1000ms
W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 11000ms
W/ActivityManager(  878): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms

```
