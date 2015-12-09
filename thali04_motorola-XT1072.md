#### Test 5065027873d6a28_thali04_motorola-XT1072 Logs


```
--------- beginning of main,
I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
D/AndroidRuntime( 4859): 
D/AndroidRuntime( 4859): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4859): CheckJNI is OFF
D/AndroidRuntime( 4859): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4878 uid=10367 gids={50367, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 4859): Shutting down VM
I/art     (  880): Explicit concurrent mark sweep GC freed 8330(459KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.447ms total 110.984ms
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 4878): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4878): Time to load native libraries: 3 ms (timestamps 7570-7573)
I/LibraryLoader( 4878): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4878): Binding Chromium to main looper Looper (main, tid 1) {3ec41279}
,I/LibraryLoader( 4878): Expected native library version number "",actual native library version number ""
,I/chromium( 4878): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4878): Initializing chromium process, singleProcess=true
W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4878): ApplicationContext is null in ApplicationStatus
,W/chromium( 4878): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4878): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4878): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4878): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4878): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 4878): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 4878): Build Date: 10/28/14 Tue
I/Adreno-EGL( 4878): Local Branch: 
I/Adreno-EGL( 4878): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 4878): Local Patches: NONE
I/Adreno-EGL( 4878): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
,D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2def7063:true
,D/BluetoothAdapter( 4878): 546044504: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{37497e5c u0 com.test.thalitest/.MainActivity t3}
,W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4878): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4878): CordovaWebView is running on device made by: motorola
,W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4878): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 4878): Render dirty regions requested: true
,D/Atlas   ( 4878): Validating map...
,W/chromium( 4878): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 4878): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4878): Enabling debug mode 0
,I/Keyboard.Facilitator( 1401): onFinishInput()
W/IInputConnectionWrapper( 4878): showStatusIcon on inactive InputConnection
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1036
,I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +828ms (total +1s36ms)
,E/Adreno-ES20( 4878): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 4878): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 4878): Cannot call determinedVisibility() - never saw a connection for the pid: 4878
,D/JsMessageQueue( 4878): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4878): JniHelper::setJavaVM(0xb6fbb310), pthread_self() = -1221287160
D/JX-Cordova( 4878): jxcore cordova android initializing
,I/art     ( 4878): Background sticky concurrent mark sweep GC freed 23462(2MB) AllocSpace objects, 0(0B) LOS objects, 13% free, 16MB/19MB, paused 5.208ms total 32.880ms
,W/jxcore-log( 4878): Initializing JXcore engine
W/jxcore-log( 4878): JXcore engine is ready
,W/jxcore-log( 4878): Starting JXcore engine
,W/.test.thalitest( 4878): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10367 path="socket:[6521]" dev="sockfs" ino=6521 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 4878): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10367 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/.test.thalitest( 4878): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10367 path="socket:[5979]" dev="sockfs" ino=5979 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/.test.thalitest( 4878): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10367 path="socket:[20420]" dev="sockfs" ino=20420 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 4878): Platform android
W/jxcore-log( 4878): 
W/jxcore-log( 4878): Process ARCH arm
W/jxcore-log( 4878): 
,I/jxcore-log( 4878): JXcore Cordova bridge is ready!
I/jxcore-log( 4878): 
,W/jxcore-log( 4878): JXcore engine is started
,I/Choreographer( 4878): Skipped 171 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4878): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/jxcore  ( 4878): Error!: missing ) after argument list
E/jxcore  ( 4878): Stack: [{"_fileName":"module.js","_functionName":"Module.prototype._compile","_lineNumber":"567","_columnNumber":"25","_msg":"    at Module.prototype._compile@module.js:567:25"},{"_fileName":"module.js","_functionName":"Module._extensions[\".js\"]","_lineNumber":"627","_columnNumber":"1","_msg":"    at Module._extensions[\".js\"]@module.js:627:1"},{"_fileName":"module.js","_functionName":"Module.prototype.load","_lineNumber":"418","_columnNumber":"7","_msg":"    at Module.prototype.load@module.js:418:7"},{"_fileName":"module.js","_functionName":"Module._load","_lineNumber":"382","_columnNumber":"5","_msg":"    at Module._load@module.js:382:5"},{"_fileName":"module.js","_functionName":"Module.prototype.require","_lineNumber":"453","_columnNumber":"10","_msg":"    at Module.prototype.require@module.js:453:10"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"471","_columnNumber":"12","_msg":"    at require@module.js:471:12"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"267","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:267:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"287","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:287:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,I/chromium( 4878): [INFO:CONSOLE(37)] "App.js file failed to load : "missing ) after argument list\nSyntaxError: missing ) after argument list\n    at Module.prototype._compile@module.js:567:25\n    at Module._extensions[\".js\"]@module.js:627:1\n    at Module.prototype.load@module.js:418:7\n    at Module._load@module.js:382:5\n    at Module.prototype.require@module.js:453:10\n    at require@module.js:471:12\n    at internal_methods.loadMainFile@main.js:267:5\n    at JXMobile.executeJSON@main.js:287:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  880): Killing 4696:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10039/pid_4696/cgroup.procs: No such file or directory
,W/PluginManager( 4878): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 30ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2560): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2560): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2560): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2560): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2560): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1401): onFinishInput()
,W/IInputConnectionWrapper( 4878): showStatusIcon on inactive InputConnection
,D/TaskPersister(  880): removeObsoleteFile: deleting file=2_task.xml
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310965, SEQNUM=4377, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-832, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310935, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-869, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1401): run()
I/Keyboard.Facilitator( 1401): flushDynamicLanguageModels()
,I/ConfigService( 1605): onCreate
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ConfigService( 1605): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  880): send {1145c511, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): done {1145c511, *alarm*:android.intent.action.TIME_TICK} [38ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2560): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2560): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2560):  Nonce Reponse 
I/MMApiWebService( 2560): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2560): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2560): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2560): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2560): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2560): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
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
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/DataBuffer( 1605): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3c5ddc34)
,E/DataBuffer( 1605): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1146ca5d)
,E/DataBuffer( 1605): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@dbaafd2)
E/DataBuffer( 1605): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@87b08a3)
E/DataBuffer( 1605): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a1687a0)
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
,V/AlarmManager(  880): send {1145c511, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {18e64676, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {a07d97, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  880): done {18e64676, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [16ms]
,V/AlarmManager(  880): done {a07d97, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [46ms]
,V/AlarmManager(  880): done {1145c511, *alarm*:android.intent.action.TIME_TICK} [58ms]
,I/EventLogService( 1946): Aggregate from 1449625492752 (log), 1449625492752 (data)
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311411, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1824, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/MMApiBackOffService( 2560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2560): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2560): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2560):  Nonce Reponse 
I/MMApiWebService( 2560): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2560): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2560): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2560): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 4431(204KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 785us total 31.066ms
,D/MMApiWebService( 2560): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2560): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2560): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2560): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2560): publish the event [tag = MOT_CCE event name = LOG]
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
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311078, SEQNUM=4388, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-2976, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager(  880): send {1145c511, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {18e64676, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  880): send {267db5c3, *alarm*:com.android.server.action.NETWORK_STATS_POLL}
,I/ProcessStatsService(  880): Prepared write state in 9ms
,V/AlarmManager(  880): send {2a2a3250, *walarm*:com.google.android.gms.icing.INDEX_RECURRING_MAINTENANCE}
,V/AlarmManager(  880): send {92bfc49, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS}
V/AlarmManager(  880): send {380ed94e, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver}
,V/AlarmManager(  880): done {2a2a3250, *walarm*:com.google.android.gms.icing.INDEX_RECURRING_MAINTENANCE} [54ms]
V/AlarmManager(  880): done {18e64676, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [54ms]
,V/AlarmManager(  880): done {267db5c3, *alarm*:com.android.server.action.NETWORK_STATS_POLL} [80ms]
,V/AlarmManager(  880): done {1145c511, *alarm*:android.intent.action.TIME_TICK} [96ms]
,V/AlarmManager(  880): done {92bfc49, *alarm*:com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS} [103ms]
,I/Icing   ( 1946): Performing maintenance.
,V/AlarmManager(  880): done {380ed94e, *alarm*:com.google.android.gms/.common.download.DownloadAlarmReceiver} [121ms]
,W/Icing   ( 1946): Received bad json for section weights override -- ignoring.
W/Icing   ( 1946): Received bad json for corpus context scoring override -- ignoring.
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ProcessStatsService(  880): Pruning old procstats: /data/system/procstats/state-2015-12-08-08-50-04.bin
,W/Icing   ( 1946): Failed to get auth token for account:<redacted>, error:NetworkError
,W/Icing   ( 1946): Failed to get auth token for account:<redacted>, error:NetworkError
,I/art     (  880): Explicit concurrent mark sweep GC freed 17252(1046KB) AllocSpace objects, 13(277KB) LOS objects, 33% free, 19MB/29MB, paused 2.227ms total 123.700ms
,I/ActivityManager(  880): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.UdcSettingBroadcastReceiver: pid=5000 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,I/Icing   ( 1946): updateResources: need to parse f{com.google.android.gms}
,I/art     (  314): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.645ms
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 19.333ms
,I/Icing   ( 1946): Performing maintenance usage 1764959 budget 1150306095 free 99.847% index free 99.973% purge? false target 805214266
,I/art     (  314): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 19.990ms
,I/ActivityManager(  880): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5025 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  880): Killing 4723:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_4723/cgroup.procs: No such file or directory
,I/ActivityManager(  880): Killing 4621:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10007/pid_4621/cgroup.procs: No such file or directory
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1605): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime( 5053): 
D/AndroidRuntime( 5053): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5053): CheckJNI is OFF
D/AndroidRuntime( 5053): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10367 user=-1: uninstall pkg
I/ActivityManager(  880): Killing 4878:com.test.thalitest/u0a367 (adj 11): stop com.test.thalitest
W/PackageSettings(  880): Skipping PackageSetting{b7bc8b6 com.example.hello/10359} due to missing metadata
I/ActivityManager(  880): Killing 4762:com.google.android.apps.plus/u0a90 (adj 15): empty for 2035s
W/ActivityManager(  880): Spurious death for ProcessRecord{5585f9d 4878:com.test.thalitest/u0a367}, curProc for 4878: null
W/libprocessgroup(  880): failed to open /acct/uid_10090/pid_4762/cgroup.procs: No such file or directory
I/ActivityManager(  880): Force stopping com.test.thalitest appid=10367 user=0: pkg removed
I/art     ( 2983): Explicit concurrent mark sweep GC freed 4786(1000KB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 7MB/12MB, paused 962us total 33.194ms
I/InputReader(  880): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1401): resetDictionaries() : en_US
W/GeofencerStateMachine( 1708): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  880): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5073 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1401): run()
I/Decoder ( 1401): createOrResetDecoder
I/art     ( 1553): Explicit concurrent mark sweep GC freed 7336(534KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 446us total 117.543ms
I/ConfigService( 1605): onCreate
I/art     (  880): Explicit concurrent mark sweep GC freed 8760(653KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 19MB/29MB, paused 2.407ms total 138.300ms
I/art     (  880): WaitForGcToComplete blocked for 74.652ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1401): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1401): loadStaticLm() : Loading File = /data/app/com.google.android.inputmethod.latin-1/base.apk (offset=5005604, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1401): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1401): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1401): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1401): run()
I/StatsUtilsManager( 1401): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1401): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5073): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  880): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  880): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  880): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5105 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  880): removeObsoleteFile: deleting file=3_task.xml
I/ContactLocale( 5073): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/art     (  880): Explicit concurrent mark sweep GC freed 4423(236KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.802ms total 178.454ms
I/ActivityManager(  880): Killing 4389:com.android.vending/u0a32 (adj 15): empty for 2022s
D/AndroidRuntime( 5053): Shutting down VM
W/libprocessgroup(  880): failed to open /acct/uid_10032/pid_4389/cgroup.procs: No such file or directory
I/Launcher( 1553): Deferring update until onResume
W/asset   ( 5105): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5105): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5105): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5105): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  880): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5129 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl( 5129): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
I/ActivityManager(  880): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5148 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
