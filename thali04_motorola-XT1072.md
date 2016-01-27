#### Test 568182540458528_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311061, SEQNUM=4341, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-248, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
--------- beginning of main
I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
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
D/AndroidRuntime( 5291): 
D/AndroidRuntime( 5291): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5291): CheckJNI is OFF
D/AndroidRuntime( 5291): Calling main entry com.android.commands.am.Am
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  883): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5310 uid=10478 gids={50478, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5291): Shutting down VM
V/ActivityManager(  883): Display changed displayId=0
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5310): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5310): Time to load native libraries: 4 ms (timestamps 3065-3069)
,I/LibraryLoader( 5310): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5310): Binding Chromium to main looper Looper (main, tid 1) {39e50ef}
,I/LibraryLoader( 5310): Expected native library version number "",actual native library version number ""
I/chromium( 5310): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5310): Initializing chromium process, singleProcess=true
,W/art     ( 5310): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5310): ApplicationContext is null in ApplicationStatus
W/chromium( 5310): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5310): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5310): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5310): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5310): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5310): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5310): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5310): Local Branch: 
I/Adreno-EGL( 5310): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5310): Local Patches: NONE
I/Adreno-EGL( 5310): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  883): Message: 20
D/BluetoothManagerService(  883): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b9959c7:true
,D/BluetoothAdapter( 5310): 520162817: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  883): Activity pause timeout for ActivityRecord{274c9e30 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5310): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5310): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5310): CordovaWebView is running on device made by: motorola
,W/art     ( 5310): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5310): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5310): Render dirty regions requested: true
,D/Atlas   ( 5310): Validating map...
,W/chromium( 5310): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5310): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5310): Enabling debug mode 0
,I/Keyboard.Facilitator( 1412): onFinishInput()
,I/LaunchCheckinHandler(  883): Displayed com.test.thalitest/.MainActivity,cp,ca,1039
I/ActivityManager(  883): Displayed com.test.thalitest/.MainActivity: +966ms (total +1s39ms)
,W/IInputConnectionWrapper( 5310): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5310): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5310): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5310): Cannot call determinedVisibility() - never saw a connection for the pid: 5310
,D/JsMessageQueue( 5310): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5310): JniHelper::setJavaVM(0xb8afd310), pthread_self() = -1192702608
,I/chromium( 5310): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5310): Initializing JXcore engine
W/jxcore-log( 5310): JXcore engine is ready
,W/Thread-607( 5358): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10478 path="socket:[8367]" dev="sockfs" ino=8367 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-607( 5358): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10478 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-607( 5358): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10478 path="socket:[7604]" dev="sockfs" ino=7604 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-607( 5358): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10478 path="socket:[23313]" dev="sockfs" ino=23313 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5310): Starting JXcore engine
,W/jxcore-log( 5310): Platform android
W/jxcore-log( 5310): 
,W/jxcore-log( 5310): Process ARCH arm
W/jxcore-log( 5310): 
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/jxcore-log( 5310): JXcore Cordova bridge is ready!
I/jxcore-log( 5310): 
,W/jxcore-log( 5310): JXcore engine is started
,E/jxcore  ( 5310): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5310): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5310): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  883): Killing 4932:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  883): failed to open /acct/uid_10007/pid_4932/cgroup.procs: No such file or directory
W/PluginManager( 5310): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 24ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2491): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2491): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2491): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2491): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2491): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2491): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5310): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1412): onFinishInput()
,V/AlarmManager(  883): send {2219f7f5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): done {2219f7f5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,D/TaskPersister(  883): removeObsoleteFile: deleting file=5_task.xml
,E/global frequency( 2491): no tags to log
,D/Checkin ( 2491): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2491): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 2491): Explicit concurrent mark sweep GC freed 32154(1840KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 11MB/18MB, paused 1.736ms total 84.853ms
,I/art     (  883): Explicit concurrent mark sweep GC freed 17131(921KB) AllocSpace objects, 6(258KB) LOS objects, 33% free, 19MB/29MB, paused 1.380ms total 117.898ms
,D/BSUtils ( 2491): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2491): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2491): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 37738(2028KB) AllocSpace objects, 17(583KB) LOS objects, 39% free, 7MB/12MB, paused 513us total 33.147ms
,D/BSUtils ( 2491): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,V/AlarmManager(  883): send {38c4d1af, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  883): done {38c4d1af, *walarm*:com.google.android.intent.action.SEND_IDLE} [2ms]
,I/BSUtils ( 2491): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2491): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1543): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2491): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2491): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2491): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2491): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2491): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2491): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2491): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2491): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2491): BcsDSCheckin.events found events 566
,D/Checkin ( 2491): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2491): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2491): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,D/MMApiWebService( 2491): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2491): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2491): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2491): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2491): unknown error code mapping for: 0
,I/global frequency( 2491): BcsCore.status() called with error code=ERROR_FAIL
D/Checkin ( 2491): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2491): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2491): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2491): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 3667(144KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 891us total 31.333ms
,D/MMApiWebService( 2491): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2491):  Nonce Reponse 
I/MMApiWebService( 2491): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2491): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2491): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2491): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2491): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2491): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2491): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  883): send {1daef73d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {325aab30, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  883): send {2219f7f5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  883): done {325aab30, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [22ms]
V/AlarmManager(  883): done {2219f7f5, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [22ms]
,V/AlarmManager(  883): done {1daef73d, *alarm*:android.intent.action.TIME_TICK} [49ms]
,I/VacuumService( 1728): Vacuum at: now=1453857079210 tag=VacuumService
,D/CdsService( 2491): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2491): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2491): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1728): disconnect managed GoogleApiClient
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310975, SEQNUM=4354, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-330, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  883): send {369bec9a, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  883): done {369bec9a, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [3ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1412): run()
I/Keyboard.Facilitator( 1412): flushDynamicLanguageModels()
,I/ConfigService( 1728): onCreate
,I/ConfigService( 1728): onDestroy
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
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  883): send {1daef73d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): done {1daef73d, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2491): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2491): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/art     (  883): Explicit concurrent mark sweep GC freed 10341(508KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.830ms total 123.647ms
,D/MMApiWebService( 2491): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2491): Explicit concurrent mark sweep GC freed 22025(1574KB) AllocSpace objects, 2(31KB) LOS objects, 39% free, 11MB/18MB, paused 1.355ms total 130.188ms
,D/MMApiWebService( 2491): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
,I/ Nonce  ( 2491):  Nonce Reponse 
I/MMApiWebService( 2491): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2491): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2491): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2491): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2491): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2491): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2491): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2491): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2491): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2491): publish the event [tag = MOT_OTA event name = LOG]
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310824, SEQNUM=4357, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-197, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310824, SEQNUM=4359, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=2, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310824, SEQNUM=4361, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-39, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310521, SEQNUM=4364, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-181, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager(  883): send {1daef73d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  883): send {2b124073, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  883): done {2b124073, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [6ms]
,V/AlarmManager(  883): done {1daef73d, *alarm*:android.intent.action.TIME_TICK} [42ms]
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
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=255, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310785, SEQNUM=4367, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-729, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/MMApiBackOffService( 2491): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2491): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2491): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2491): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2491):  Nonce Reponse 
I/MMApiWebService( 2491): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2491): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2491): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2491): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2491): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2491): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2491): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2491): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2491): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,D/CdsService( 2491): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2491): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2491): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310474, SEQNUM=4368, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-843, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  883): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  883): uevent={POWER_SUPPLY_TEMP=254, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309877, SEQNUM=4369, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-897, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1728): Explicit concurrent mark sweep GC freed 39610(2MB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 13MB/21MB, paused 1.114ms total 97.710ms
,E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19b163db)
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13566e78)
,E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3a45c951)
E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18b395b6)
,V/GLSActivity( 1728): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3cd862b7)
,E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@19cca98d)
E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@7db5742)
E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c067353)
E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3b149490)
E/DataBuffer( 1728): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24675189)
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5483): 
D/AndroidRuntime( 5483): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5483): CheckJNI is OFF
D/AndroidRuntime( 5483): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10478 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 5310:com.test.thalitest/u0a478 (adj 11): stop com.test.thalitest
W/PackageSettings(  883): Skipping PackageSetting{3710e3b4 com.example.hello/10440} due to missing metadata
W/ActivityManager(  883): Spurious death for ProcessRecord{3073639e 5310:com.test.thalitest/u0a478}, curProc for 5310: null
I/ActivityManager(  883): Force stopping com.test.thalitest appid=10478 user=0: pkg removed
I/art     ( 2917): Explicit concurrent mark sweep GC freed 4451(841KB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 7MB/12MB, paused 743us total 39.321ms
I/Keyboard.Facilitator( 1412): resetDictionaries() : en_US
W/GeofencerStateMachine( 1728): Ignoring removeGeofence because network location is disabled.
I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  883): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5506 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1412): run()
I/art     ( 1560): Explicit concurrent mark sweep GC freed 7285(529KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 486us total 100.192ms
I/art     ( 1943): Explicit concurrent mark sweep GC freed 2167(87KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/18MB, paused 907us total 156.287ms
I/Decoder ( 1412): createOrResetDecoder
I/ConfigService( 1728): onCreate
I/art     (  883): Explicit concurrent mark sweep GC freed 13509(1037KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 5.510ms total 170.213ms
I/art     (  883): WaitForGcToComplete blocked for 79.926ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1412): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1412): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1412): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1412): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1412): run()
I/StatsUtilsManager( 1412): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1412): shouldRecordStats() = Too Soon
D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  883): removeObsoleteFile: deleting file=6_task.xml
D/VoicemailCleanupService( 5506): Cleaning up data for package: com.test.thalitest
I/art     (  883): Explicit concurrent mark sweep GC freed 5574(291KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.027ms total 153.488ms
I/ActivityManager(  883): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5535 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5506): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/Launcher( 1560): Deferring update until onResume
W/asset   ( 5535): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5535): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5535): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5535): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
D/AndroidRuntime( 5483): Shutting down VM
I/ActivityManager(  883): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5558 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/ContextImpl( 5558): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1943): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1943): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1943): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1943): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1943): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1728): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1728): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1943): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1943): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1943): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1943): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1943): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1943): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1943): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  883): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5583 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager(  883): Killing 5074:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.602ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 23.897ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 19.616ms
W/libprocessgroup(  883): failed to open /acct/uid_10090/pid_5074/cgroup.procs: No such file or directory
I/Icing   ( 1943): doRemovePackageData com.test.thalitest
W/Launcher( 1560): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1f010e01 new=com.google.android.velvet.VelvetApplication@1f010e01
I/ActivityManager(  883): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5608 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
