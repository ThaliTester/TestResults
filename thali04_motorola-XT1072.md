#### Test 573480789efee08_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5467): 
D/AndroidRuntime( 5467): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5467): CheckJNI is OFF
D/AndroidRuntime( 5467): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  878): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  878): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5486 uid=10482 gids={50482, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5467): Shutting down VM
V/ActivityManager(  878): Display changed displayId=0
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5486): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5486): Time to load native libraries: 2 ms (timestamps 7434-7436)
I/LibraryLoader( 5486): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5486): Binding Chromium to main looper Looper (main, tid 1) {1328d2db}
I/LibraryLoader( 5486): Expected native library version number "",actual native library version number ""
I/chromium( 5486): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5486): Initializing chromium process, singleProcess=true
W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5486): ApplicationContext is null in ApplicationStatus
W/chromium( 5486): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5486): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5486): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5486): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5486): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5486): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5486): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5486): Local Branch: 
I/Adreno-EGL( 5486): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5486): Local Patches: NONE
I/Adreno-EGL( 5486): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  878): Message: 20
D/BluetoothManagerService(  878): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33e0b7bb:true
D/BluetoothAdapter( 5486): 455967298: getState() :  mService = null. Returning STATE_OFF
W/ActivityManager(  878): Activity pause timeout for ActivityRecord{159bd054 u0 com.test.thalitest/.MainActivity t6}
W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5486): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5486): CordovaWebView is running on device made by: motorola
W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5486): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 5486): Render dirty regions requested: true
D/Atlas   ( 5486): Validating map...
W/chromium( 5486): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 5486): Initialized EGL, version 1.4
D/OpenGLRenderer( 5486): Enabling debug mode 0
I/Keyboard.Facilitator( 1405): onFinishInput()
I/LaunchCheckinHandler(  878): Displayed com.test.thalitest/.MainActivity,cp,ca,962
I/ActivityManager(  878): Displayed com.test.thalitest/.MainActivity: +890ms (total +962ms)
W/IInputConnectionWrapper( 5486): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5486): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5486): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5486): Cannot call determinedVisibility() - never saw a connection for the pid: 5486
,D/JsMessageQueue( 5486): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5486): JniHelper::setJavaVM(0xb862c310), pthread_self() = -1197748256
,I/chromium( 5486): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5486): Initializing JXcore engine
W/jxcore-log( 5486): JXcore engine is ready
,W/Thread-603( 5535): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10482 path="socket:[5852]" dev="sockfs" ino=5852 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-603( 5535): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10482 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-603( 5535): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10482 path="socket:[9452]" dev="sockfs" ino=9452 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-603( 5535): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10482 path="socket:[22407]" dev="sockfs" ino=22407 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5486): Starting JXcore engine
,W/jxcore-log( 5486): Platform android
W/jxcore-log( 5486): 
W/jxcore-log( 5486): Process ARCH arm
W/jxcore-log( 5486): 
,I/jxcore-log( 5486): JXcore Cordova bridge is ready!
I/jxcore-log( 5486): 
W/jxcore-log( 5486): JXcore engine is started
,E/jxcore  ( 5486): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5486): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5486): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  878): Killing 5094:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  878): failed to open /acct/uid_10007/pid_5094/cgroup.procs: No such file or directory
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5486): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1459): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/art     ( 2670): Explicit concurrent mark sweep GC freed 31177(1798KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.579ms total 73.338ms
,D/OtaApp  ( 2670): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2670): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2670): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2670): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  878): send {1d307d89, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  878): done {1d307d89, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [4ms]
,W/IInputConnectionWrapper( 5486): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1405): onFinishInput()
,I/VacuumService( 1689): Vacuum at: now=1453981670695 tag=VacuumService
,E/global frequency( 2670): no tags to log
,D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1531): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  878): Explicit concurrent mark sweep GC freed 18440(922KB) AllocSpace objects, 3(211KB) LOS objects, 33% free, 19MB/29MB, paused 1.784ms total 113.171ms
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 54123(2MB) AllocSpace objects, 33(1052KB) LOS objects, 39% free, 7MB/12MB, paused 674us total 42.458ms
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1531): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1531): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2670): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2670): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2670): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2670): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2670): BcsDSCheckin.events found events 883
,D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2670): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/TaskPersister(  878): removeObsoleteFile: deleting file=5_task.xml
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 4273(178KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 785us total 27.880ms
,D/MMApiWebService( 2670): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2670): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2670): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2670): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2670): unknown error code mapping for: 0
I/global frequency( 2670): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2670): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  878): send {3ba949d9, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  878): done {3ba949d9, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2670): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2670): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2670): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2670):  Nonce Reponse 
I/MMApiWebService( 2670): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2670): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2670): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/art     ( 2670): Explicit concurrent mark sweep GC freed 25765(1908KB) AllocSpace objects, 6(86KB) LOS objects, 40% free, 11MB/18MB, paused 2.146ms total 75.281ms
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2670): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2670): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2670): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2670): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2670): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  878): send {2b1e5324, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {1cbc5f3e, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  878): send {326abf9e, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  878): done {1cbc5f3e, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [17ms]
,V/AlarmManager(  878): done {326abf9e, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [33ms]
,V/AlarmManager(  878): done {2b1e5324, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/EventLogService( 1933): Aggregate from 1453979911392 (log), 1453979911392 (data)
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1689): disconnect managed GoogleApiClient
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  878): send {235caf9b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  878): done {235caf9b, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [4ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
,I/ConfigService( 1689): onCreate
,I/ConfigService( 1689): onDestroy
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311179, SEQNUM=4410, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-419, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/art     (  878): Explicit concurrent mark sweep GC freed 8315(504KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 19MB/29MB, paused 1.834ms total 123.645ms
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  878): send {2b1e5324, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): done {2b1e5324, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2670): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2670): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2670): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2670):  Nonce Reponse 
I/MMApiWebService( 2670): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2670): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2670): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2670): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2670): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2670): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2670): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2670): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309873, SEQNUM=4414, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=2119, POWER_SUPPLY_CHARGE_COUNTER=-1330, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310440, SEQNUM=4419, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-1341, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  878): send {2b1e5324, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  878): send {28dad5f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  878): done {28dad5f2, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [6ms]
,V/AlarmManager(  878): done {2b1e5324, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310431, SEQNUM=4420, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-47, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2670): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2670): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2670): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2670):  Nonce Reponse 
I/MMApiWebService( 2670): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2670): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2670): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2670): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1459): Explicit concurrent mark sweep GC freed 3271(130KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.063ms total 31.323ms
,D/MMApiWebService( 2670): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2670): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2670): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2670): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2670): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310137, SEQNUM=4423, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-66, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,D/CdsService( 2670): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2670): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2670): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  878): User[0] Flushing usage stats to disk
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=255, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310406, SEQNUM=4424, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-139, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  292): NetlinkHandler, power_supply subsys
I/MDMCTBK (  292): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  292): checkDefaultInst, current pid is = 292
I/MDMCTBK (  292): checkDefaultInst, pid match
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  292): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  292): MdmCutbackHndler,Could not open ''
,D/BatteryService(  878): uevent={POWER_SUPPLY_TEMP=255, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310401, SEQNUM=4425, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-43, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1689): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  303): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5655): 
D/AndroidRuntime( 5655): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5655): CheckJNI is OFF
D/AndroidRuntime( 5655): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10482 user=-1: uninstall pkg
I/ActivityManager(  878): Killing 5486:com.test.thalitest/u0a482 (adj 11): stop com.test.thalitest
W/PackageSettings(  878): Skipping PackageSetting{3641dab0 com.example.hello/10440} due to missing metadata
W/ActivityManager(  878): Spurious death for ProcessRecord{336b534f 5486:com.test.thalitest/u0a482}, curProc for 5486: null
I/ActivityManager(  878): Force stopping com.test.thalitest appid=10482 user=0: pkg removed
I/art     ( 3077): Explicit concurrent mark sweep GC freed 4681(912KB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 7MB/12MB, paused 799us total 36.477ms
W/GeofencerStateMachine( 1689): Ignoring removeGeofence because network location is disabled.
I/InputReader(  878): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1405): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1405): run()
I/Decoder ( 1405): createOrResetDecoder
I/art     ( 1555): Explicit concurrent mark sweep GC freed 7356(535KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 497us total 60.013ms
I/ActivityManager(  878): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5680 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ConfigService( 1689): onCreate
I/art     ( 1933): Explicit concurrent mark sweep GC freed 3785(221KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 1.035ms total 146.103ms
I/art     (  878): Explicit concurrent mark sweep GC freed 15386(1096KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 2.350ms total 188.266ms
I/art     (  878): WaitForGcToComplete blocked for 127.080ms for cause Explicit
I/art     ( 1689): Explicit concurrent mark sweep GC freed 35839(2MB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 13MB/21MB, paused 882us total 76.328ms
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@287b3497)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a459684)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1957e6d)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e7a3aa2)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3348333)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@9c796f0)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@27989469)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b655eee)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@172a1f8f)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2a27321c)
E/DataBuffer( 1689): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19d0e25)
D/VoicemailCleanupService( 5680): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): run()
I/ActivityManager(  878): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5705 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5680): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  878): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  878): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  878): removeObsoleteFile: deleting file=6_task.xml
I/Launcher( 1555): Deferring update until onResume
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1405): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1405): run()
W/asset   ( 5705): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
I/Keyboard.Facilitator.RecurringTaskScheduler( 1405): run()
I/StatsUtilsManager( 1405): startPeriodStatsRecorder() : Success
W/ResourcesManager( 5705): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
I/PeriodicStatsRecorder( 1405): shouldRecordStats() = Too Soon
W/ResourcesManager( 5705): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5705): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  878): Explicit concurrent mark sweep GC freed 4478(235KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.356ms total 207.568ms
I/ActivityManager(  878): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5728 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  878): Killing 5236:com.google.android.apps.plus/u0a90 (adj 15): empty #7
D/AndroidRuntime( 5655): Shutting down VM
W/libprocessgroup(  878): failed to open /acct/uid_10090/pid_5236/cgroup.procs: No such file or directory
W/ContextImpl( 5728): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1933): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1933): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1933): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1933): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1689): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1689): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
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
I/ActivityManager(  878): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5757 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/ChimeraCfgMgr( 1933): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1933): Module APK com.google.android.play.games already loaded
I/Icing   ( 1933): doRemovePackageData com.test.thalitest
W/Launcher( 1555): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@39b0a08d new=com.google.android.velvet.VelvetApplication@39b0a08d
I/ActivityManager(  878): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5788 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 20.501ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 19.920ms
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 23.723ms

```
