#### Test 56818254e6f5c3b_thali04_motorola-XT1072 Logs


```
--------- beginning of system
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,--------- beginning of main
D/AndroidRuntime( 5268): 
D/AndroidRuntime( 5268): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5268): CheckJNI is OFF
D/AndroidRuntime( 5268): Calling main entry com.android.commands.am.Am
I/ActivityManager(  885): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  885): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5282 uid=10487 gids={50487, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5268): Shutting down VM
V/ActivityManager(  885): Display changed displayId=0
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5282): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5282): Time to load native libraries: 3 ms (timestamps 8822-8825)
I/LibraryLoader( 5282): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5282): Binding Chromium to main looper Looper (main, tid 1) {1bba55fe}
I/LibraryLoader( 5282): Expected native library version number "",actual native library version number ""
I/chromium( 5282): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5282): Initializing chromium process, singleProcess=true
W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5282): ApplicationContext is null in ApplicationStatus
W/chromium( 5282): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5282): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5282): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5282): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5282): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5282): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5282): Local Branch: 
I/Adreno-EGL( 5282): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5282): Local Patches: NONE
I/Adreno-EGL( 5282): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  885): Message: 20
D/BluetoothManagerService(  885): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ca34c80:true
D/BluetoothAdapter( 5282): 268338299: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  885): Activity pause timeout for ActivityRecord{255c9d05 u0 com.test.thalitest/.MainActivity t6}
W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5282): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5282): CordovaWebView is running on device made by: motorola
W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5282): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5282): Render dirty regions requested: true
D/Atlas   ( 5282): Validating map...
W/chromium( 5282): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5282): Initialized EGL, version 1.4
D/OpenGLRenderer( 5282): Enabling debug mode 0
I/Keyboard.Facilitator( 1407): onFinishInput()
I/LaunchCheckinHandler(  885): Displayed com.test.thalitest/.MainActivity,cp,ca,986
I/ActivityManager(  885): Displayed com.test.thalitest/.MainActivity: +896ms (total +986ms)
W/IInputConnectionWrapper( 5282): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5282): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5282): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5282): Cannot call determinedVisibility() - never saw a connection for the pid: 5282
,D/JsMessageQueue( 5282): Set native->JS mode to OnlineEventsBridgeMode
,V/AlarmManager(  885): send {220101e5, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  885): done {220101e5, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [4ms]
,D/jxcore_app_log( 5282): JniHelper::setJavaVM(0xb7cb1310), pthread_self() = -1207694528
,I/chromium( 5282): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5282): Initializing JXcore engine
W/jxcore-log( 5282): JXcore engine is ready
,W/Thread-608( 5332): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10487 path="socket:[5661]" dev="sockfs" ino=5661 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-608( 5332): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10487 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-608( 5332): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10487 path="socket:[9677]" dev="sockfs" ino=9677 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-608( 5332): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10487 path="socket:[23614]" dev="sockfs" ino=23614 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5282): Starting JXcore engine
,W/jxcore-log( 5282): Platform android
W/jxcore-log( 5282): 
,W/jxcore-log( 5282): Process ARCH arm
W/jxcore-log( 5282): 
,I/jxcore-log( 5282): JXcore Cordova bridge is ready!
I/jxcore-log( 5282): 
W/jxcore-log( 5282): JXcore engine is started
,E/jxcore  ( 5282): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5282): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5282): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  885): Killing 4883:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  885): failed to open /acct/uid_10007/pid_4883/cgroup.procs: No such file or directory
,W/PluginManager( 5282): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1462): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2546): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2546): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2546): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2546): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1407): onFinishInput()
W/IInputConnectionWrapper( 5282): showStatusIcon on inactive InputConnection
,D/TaskPersister(  885): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  885): send {37939477, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {37939477, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [5ms]
,V/AlarmManager(  885): send {251fc4ba, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  885): done {251fc4ba, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,E/global frequency( 2546): no tags to log
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  885): Explicit concurrent mark sweep GC freed 18442(987KB) AllocSpace objects, 6(260KB) LOS objects, 33% free, 19MB/29MB, paused 1.369ms total 119.013ms
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 53659(2MB) AllocSpace objects, 31(1016KB) LOS objects, 40% free, 7MB/12MB, paused 708us total 47.110ms
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1542): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2546): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2546): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2546): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2546): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2546): BcsDSCheckin.events found events 1260
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 2546): Explicit concurrent mark sweep GC freed 20131(940KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/19MB, paused 1.774ms total 63.503ms
,I/BSUtils ( 2546): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:31000 mC
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 3328(132KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 710us total 26.705ms
,D/MMApiWebService( 2546): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2546): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2546): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2546): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2546): unknown error code mapping for: 0
,I/global frequency( 2546): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2546): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2546): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311223, SEQNUM=4360, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=-212, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2546): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2546): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2546): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2546):  Nonce Reponse 
I/MMApiWebService( 2546): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2546): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2546): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2546): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2546): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2546): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2546): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2546): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1698): onCreate
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1698): onDestroy
,V/AlarmManager(  885): send {73c669e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {35c73605, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  885): send {1d96889d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  885): send {37939477, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  885): done {35c73605, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [10ms]
,V/AlarmManager(  885): done {1d96889d, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [25ms]
V/AlarmManager(  885): done {37939477, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [26ms]
,V/AlarmManager(  885): done {73c669e, *alarm*:android.intent.action.TIME_TICK} [55ms]
,I/VacuumService( 1698): Vacuum at: now=1454085810103 tag=VacuumService
,I/ClearcutLoggerApiImpl( 1698): disconnect managed GoogleApiClient
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312304, SEQNUM=4367, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-216, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311989, SEQNUM=4369, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=1008, POWER_SUPPLY_CHARGE_COUNTER=-222, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=264, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311638, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2725, POWER_SUPPLY_CHARGE_COUNTER=29, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/art     (  885): Explicit concurrent mark sweep GC freed 10196(557KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.765ms total 121.410ms
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  885): send {73c669e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): done {73c669e, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2546): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2546): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2546): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2546):  Nonce Reponse 
I/MMApiWebService( 2546): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2546): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2546): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2546): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2546): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2546): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2546): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2546): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311872, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=23, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311267, SEQNUM=4377, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=10, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  885): send {73c669e, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  885): send {2438d7c, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  885): send {3dab93c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,D/Finsky  ( 5070): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  885): send {2c9e647b, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  885): done {2c9e647b, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [21ms]
,V/AlarmManager(  885): done {2438d7c, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [35ms]
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  885): done {73c669e, *alarm*:android.intent.action.TIME_TICK} [66ms]
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  885): done {3dab93c, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [86ms]
,I/EventLogService( 1938): Aggregate from 1454084147845 (log), 1454084147845 (data)
,I/art     ( 1698): Explicit concurrent mark sweep GC freed 39839(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 13MB/21MB, paused 1.202ms total 91.590ms
,E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33dc8c10)
E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2bf4b309)
E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c9eef2f)
E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19e6593c)
,E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36ac76c5)
E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@34fcc81a)
E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@32b54f4b)
E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@345dcd28)
,E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3562ba41)
E/DataBuffer( 1698): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1f0f4be6)
,W/Finsky  ( 5070): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5070): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5070): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 5070): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  885): send {21a41546, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 5070): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/WearableService( 1698): callingUid 10016, callindPid: 1698
,V/AlarmManager(  885): done {21a41546, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [29ms]
,D/DeviceConnectionService( 1698): client connected with version: 8296000
,D/Finsky  ( 5070): [604] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5070): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 5070): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5070): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  885): send {2245b815, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  885): done {2245b815, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
,D/Finsky  ( 5070): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5070): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311561, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311552, SEQNUM=4389, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=4844, POWER_SUPPLY_CHARGE_COUNTER=-15, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311548, SEQNUM=4390, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-38, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311518, SEQNUM=4393, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-148, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2546): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2546): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2546): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2546):  Nonce Reponse 
I/MMApiWebService( 2546): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2546): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2546): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2546): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2546): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2546): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2546): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2546): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2546): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,D/CdsService( 2546): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2546): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2546): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  885): User[0] Flushing usage stats to disk
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1698): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  296): NetlinkHandler, power_supply subsys
I/MDMCTBK (  296): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  296): checkDefaultInst, current pid is = 296
I/MDMCTBK (  296): checkDefaultInst, pid match
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  296): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  296): MdmCutbackHndler,Could not open ''
,D/BatteryService(  885): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311807, SEQNUM=4396, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4807, POWER_SUPPLY_CHARGE_COUNTER=-384, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5486): 
D/AndroidRuntime( 5486): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5486): CheckJNI is OFF
D/AndroidRuntime( 5486): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10487 user=-1: uninstall pkg
I/ActivityManager(  885): Killing 5282:com.test.thalitest/u0a487 (adj 11): stop com.test.thalitest
W/PackageSettings(  885): Skipping PackageSetting{311d1ef7 com.example.hello/10440} due to missing metadata
I/ActivityManager(  885): Force stopping com.test.thalitest appid=10487 user=0: pkg removed
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
I/art     ( 2933): Explicit concurrent mark sweep GC freed 5227(1028KB) AllocSpace objects, 23(368KB) LOS objects, 39% free, 7MB/12MB, paused 502us total 54.782ms
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/InputReader(  885): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1698): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1407): createOrResetDecoder
I/art     ( 1938): Explicit concurrent mark sweep GC freed 3976(231KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 14MB/19MB, paused 899us total 110.912ms
I/ActivityManager(  885): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5514 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
W/ActivityManager(  885): Spurious death for ProcessRecord{1bae9494 5282:com.test.thalitest/u0a487}, curProc for 5282: null
I/art     ( 1561): Explicit concurrent mark sweep GC freed 7350(534KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 461us total 120.825ms
I/art     (  885): Explicit concurrent mark sweep GC freed 19683(1302KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 1.459ms total 208.996ms
I/art     (  885): WaitForGcToComplete blocked for 208.143ms for cause Explicit
I/ConfigService( 1698): onCreate
I/CheckinRequestBuilder( 1698): Classify the device as Phone.
D/VoicemailCleanupService( 5514): Cleaning up data for package: com.test.thalitest
W/FetchTask( 1698): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/BackupManagerService(  885): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  885): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  885): Explicit concurrent mark sweep GC freed 6447(349KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.964ms total 184.597ms
I/ActivityManager(  885): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5547 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  885): removeObsoleteFile: deleting file=6_task.xml
I/ContactLocale( 5514): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/CheckinRequestBuilder( 1698): Classify the device as Phone.
W/FetchTask( 1698): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1698): Classify the device as Phone.
W/asset   ( 5547): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5547): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5547): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5547): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
W/FetchTask( 1698): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Launcher( 1561): Deferring update until onResume
I/ActivityManager(  885): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5567 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  885): Killing 5037:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/CheckinRequestBuilder( 1698): Classify the device as Phone.
W/libprocessgroup(  885): failed to open /acct/uid_10090/pid_5037/cgroup.procs: No such file or directory
D/AndroidRuntime( 5486): Shutting down VM
W/FetchTask( 1698): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ContextImpl( 5567): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1938): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1938): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
I/CheckinRequestBuilder( 1698): Classify the device as Phone.
E/NetworkScheduler.SchedulerReceiver( 1698): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1698): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
W/FetchTask( 1698): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 1938): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1938): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1938): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1938): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): run()
D/gH_CompatibleDatabase( 1938): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1938): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1938): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1938): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1938): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1938): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1938): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1938): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1938): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  885): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5597 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/art     (  320): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 257us total 20.444ms
I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 19.666ms
I/Icing   ( 1938): doRemovePackageData com.test.thalitest
I/art     (  320): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.309ms
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
W/Launcher( 1561): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@dde1298 new=com.google.android.velvet.VelvetApplication@dde1298
I/ActivityManager(  885): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5622 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
