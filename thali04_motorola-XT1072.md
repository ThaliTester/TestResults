#### Test 57659382b63fd0b_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 5361): 
D/AndroidRuntime( 5361): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5361): CheckJNI is OFF
D/AndroidRuntime( 5361): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5380 uid=10486 gids={50486, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5361): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5380): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5380): Time to load native libraries: 3 ms (timestamps 7369-7372)
,I/LibraryLoader( 5380): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5380): Binding Chromium to main looper Looper (main, tid 1) {fa830ad}
,I/LibraryLoader( 5380): Expected native library version number "",actual native library version number ""
,I/chromium( 5380): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5380): Initializing chromium process, singleProcess=true
,W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5380): ApplicationContext is null in ApplicationStatus
,W/chromium( 5380): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5380): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5380): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5380): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5380): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5380): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5380): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5380): Local Branch: 
I/Adreno-EGL( 5380): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5380): Local Patches: NONE
I/Adreno-EGL( 5380): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5960f3e:true
D/BluetoothAdapter( 5380): 37476398: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{97376cb u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5380): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5380): CordovaWebView is running on device made by: motorola
,W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5380): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5380): Render dirty regions requested: true
,D/Atlas   ( 5380): Validating map...
,W/chromium( 5380): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5380): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5380): Enabling debug mode 0
,I/Keyboard.Facilitator( 1408): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,998
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +912ms (total +998ms)
,W/IInputConnectionWrapper( 5380): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5380): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5380): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5380): Cannot call determinedVisibility() - never saw a connection for the pid: 5380
,D/JsMessageQueue( 5380): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 5380): JniHelper::setJavaVM(0xb897d310), pthread_self() = -1194278328
I/chromium( 5380): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5380): Initializing JXcore engine
W/jxcore-log( 5380): JXcore engine is ready
,W/Thread-603( 5436): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10486 path="socket:[6543]" dev="sockfs" ino=6543 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-603( 5436): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10486 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-603( 5436): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10486 path="socket:[9777]" dev="sockfs" ino=9777 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-603( 5436): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10486 path="socket:[23172]" dev="sockfs" ino=23172 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5380): Starting JXcore engine
,W/jxcore-log( 5380): Platform android
W/jxcore-log( 5380): 
,W/jxcore-log( 5380): Process ARCH arm
W/jxcore-log( 5380): 
,I/jxcore-log( 5380): JXcore Cordova bridge is ready!
I/jxcore-log( 5380): 
W/jxcore-log( 5380): JXcore engine is started
,E/jxcore  ( 5380): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5380): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5380): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  880): Killing 5113:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_5113/cgroup.procs: No such file or directory
W/PluginManager( 5380): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 76ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2541): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2541): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2541): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2541): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2541): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2541): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1408): onFinishInput()
W/IInputConnectionWrapper( 5380): showStatusIcon on inactive InputConnection
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1408): run()
I/Keyboard.Facilitator( 1408): flushDynamicLanguageModels()
,I/ConfigService( 1691): onCreate
,I/ConfigService( 1691): onDestroy
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {10310b8c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {10310b8c, *alarm*:android.intent.action.TIME_TICK} [38ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310292, SEQNUM=4369, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=6560, POWER_SUPPLY_CHARGE_COUNTER=12, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2541): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2541): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2541): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2541): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2541):  Nonce Reponse 
I/MMApiWebService( 2541): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2541): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2541): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2541): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2541): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2541): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2541): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2541): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2541): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2541): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2541): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2541): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2541): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:29000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310547, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310833, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-19, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310547, SEQNUM=4374, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-62, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  880): send {10310b8c, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {10aec2d5, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {10aec2d5, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  880): done {10310b8c, *alarm*:android.intent.action.TIME_TICK} [47ms]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2541): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2541): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2541): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2541): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2541):  Nonce Reponse 
I/MMApiWebService( 2541): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2541): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2541): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2541): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2541): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2541): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2541): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2541): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2541): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2541): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2541): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,D/CdsService( 2541): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2541): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2541): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1691): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=255, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310496, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-1307, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  304): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5493): 
D/AndroidRuntime( 5493): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5493): CheckJNI is OFF
D/AndroidRuntime( 5493): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10486 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 5380:com.test.thalitest/u0a486 (adj 9): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{21e6c35a com.example.hello/10440} due to missing metadata
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10486 user=0: pkg removed
I/art     ( 2936): Explicit concurrent mark sweep GC freed 4668(916KB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 7MB/12MB, paused 623us total 33.232ms
I/art     ( 4978): Explicit concurrent mark sweep GC freed 1392(71KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 706us total 86.028ms
W/ActivityManager(  880): Spurious death for ProcessRecord{3f0c29fe 5380:com.test.thalitest/u0a486}, curProc for 5380: null
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1691): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1408): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1408): run()
I/Decoder ( 1408): createOrResetDecoder
I/art     ( 1559): Explicit concurrent mark sweep GC freed 7350(535KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 493us total 59.347ms
I/art     ( 5029): Explicit concurrent mark sweep GC freed 706(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 398us total 100.356ms
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5522 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ConfigService( 1691): onCreate
I/art     (  880): Explicit concurrent mark sweep GC freed 16827(1223KB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 19MB/29MB, paused 1.389ms total 152.764ms
I/art     (  880): WaitForGcToComplete blocked for 44.378ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): run()
D/VoicemailCleanupService( 5522): Cleaning up data for package: com.test.thalitest
I/art     ( 1691): Explicit concurrent mark sweep GC freed 36879(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 13MB/22MB, paused 1.258ms total 74.400ms
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e638552)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@326af023)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2ac51920)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1253a2d9)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1610a49e)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27726b7f)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@bb2a74c)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1ad29395)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@ede6caa)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f4c409b)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1208ec38)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1115d411)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@30ea976)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@c244b77)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@f7c93e4)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1372a04d)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3d33e702)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d082813)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1a610a50)
E/DataBuffer( 1691): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1655f449)
I/Keyboard.Facilitator.MainLanguageModelLoader( 1408): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5544 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = contacts
D/TaskPersister(  880): removeObsoleteFile: deleting file=6_task.xml
I/ContactLocale( 5522): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  880): Explicit concurrent mark sweep GC freed 4653(254KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.523ms total 200.345ms
D/AndroidRuntime( 5493): Shutting down VM
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1408): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1408): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1408): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1408): run()
I/StatsUtilsManager( 1408): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1408): shouldRecordStats() = Too Soon
W/asset   ( 5544): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5544): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5544): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5544): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5568 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/Launcher( 1559): Deferring update until onResume
I/ActivityManager(  880): Killing 5029:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
W/ContextImpl( 5568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_5029/cgroup.procs: No such file or directory
D/ChimeraCfgMgr( 4978): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4978): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 4978): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4978): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4978): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4978): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1691): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1691): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5590 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 4978): Removing dialog suppression flag for package com.test.thalitest
W/BaseAppContext( 4978): Using Auth Proxy for data requests.
W/BaseAppContext( 4978): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 4978): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4978): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4978): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4978): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4978): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4978): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4978): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/GMPM-SVC( 4978): App measurement is starting up, version: 8489
I/GMPM-SVC( 4978): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/gH_CompatibleDatabase( 4978): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4978): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4978): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4978): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4978): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4978): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/Icing   ( 4978): doRemovePackageData com.test.thalitest
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@10ed3fcf new=com.google.android.velvet.VelvetApplication@10ed3fcf
I/ActivityManager(  880): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5618 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.716ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 19.017ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.515ms
E/SQLiteLog( 4978): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 4978): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
D/ConnectivityService(  880): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/SharedPreferencesImpl( 4978): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
W/DriveInitializer( 4978): Awaiting to be initialized
W/DriveInitializer( 4978): Background init thread started
E/SQLiteLog( 4978): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error

```
