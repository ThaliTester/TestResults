#### Test 57531243c766d4e_thali04_motorola-XT1072 Logs


```
--------- beginning of system
V/AlarmManager(  982): send {2ce342b3, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  982): send {3c279eda, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
V/AlarmManager(  982): done {3c279eda, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [17ms]
V/AlarmManager(  982): done {2ce342b3, *alarm*:android.intent.action.TIME_TICK} [41ms]
,--------- beginning of main
D/AndroidRuntime( 5476): 
D/AndroidRuntime( 5476): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5476): CheckJNI is OFF
D/AndroidRuntime( 5476): Calling main entry com.android.commands.am.Am
I/ActivityManager(  982): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  982): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5495 uid=10488 gids={50488, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5476): Shutting down VM
V/ActivityManager(  982): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5495): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5495): Time to load native libraries: 3 ms (timestamps 1024-1027)
I/LibraryLoader( 5495): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5495): Binding Chromium to main looper Looper (main, tid 1) {3db6fd8c}
,I/LibraryLoader( 5495): Expected native library version number "",actual native library version number ""
I/chromium( 5495): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5495): Initializing chromium process, singleProcess=true
,W/art     ( 5495): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5495): ApplicationContext is null in ApplicationStatus
,W/chromium( 5495): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5495): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5495): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5495): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5495): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5495): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5495): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5495): Local Branch: 
I/Adreno-EGL( 5495): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5495): Local Patches: NONE
I/Adreno-EGL( 5495): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  982): Message: 20
D/BluetoothManagerService(  982): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10790c7e:true
,D/BluetoothAdapter( 5495): 158382775: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  982): Activity pause timeout for ActivityRecord{25e13f0b u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5495): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5495): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5495): CordovaWebView is running on device made by: motorola
,W/art     ( 5495): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5495): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5495): Render dirty regions requested: true
,D/Atlas   ( 5495): Validating map...
,W/chromium( 5495): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  982): Explicit concurrent mark sweep GC freed 17502(869KB) AllocSpace objects, 2(193KB) LOS objects, 33% free, 19MB/29MB, paused 1.483ms total 119.516ms
,I/OpenGLRenderer( 5495): Initialized EGL, version 1.4
D/OpenGLRenderer( 5495): Enabling debug mode 0
,I/Keyboard.Facilitator( 1405): onFinishInput()
,I/LaunchCheckinHandler(  982): Displayed com.test.thalitest/.MainActivity,cp,ca,1046
,I/ActivityManager(  982): Displayed com.test.thalitest/.MainActivity: +966ms (total +1s46ms)
,W/IInputConnectionWrapper( 5495): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5495): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5495): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5495): Cannot call determinedVisibility() - never saw a connection for the pid: 5495
,D/JsMessageQueue( 5495): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5495): JniHelper::setJavaVM(0xb70be310), pthread_self() = -1220228880
,I/chromium( 5495): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/art     ( 5495): Suspending all threads took: 11.558ms
,W/jxcore-log( 5495): Initializing JXcore engine
W/jxcore-log( 5495): JXcore engine is ready
,I/art     ( 5495): Background sticky concurrent mark sweep GC freed 4168(353KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 12.684ms total 46.822ms
,W/Thread-582( 5551): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10488 path="socket:[6125]" dev="sockfs" ino=6125 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-582( 5551): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10488 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3091 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-582( 5551): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10488 path="socket:[8800]" dev="sockfs" ino=8800 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-582( 5551): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10488 path="socket:[22288]" dev="sockfs" ino=22288 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5495): Starting JXcore engine
,W/jxcore-log( 5495): Platform android
W/jxcore-log( 5495): 
W/jxcore-log( 5495): Process ARCH arm
W/jxcore-log( 5495): 
,I/jxcore-log( 5495): JXcore Cordova bridge is ready!
I/jxcore-log( 5495): 
W/jxcore-log( 5495): JXcore engine is started
,E/jxcore  ( 5495): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5495): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5495): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  982): Killing 5079:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  982): failed to open /acct/uid_10007/pid_5079/cgroup.procs: No such file or directory
,W/PluginManager( 5495): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 34ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2843): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2843): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2843): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2843): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2843): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2843): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5495): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1405): onFinishInput()
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
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,D/TaskPersister(  982): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  982): send {67174cd, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  982): done {67174cd, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,E/global frequency( 2843): no tags to log
,D/Checkin ( 2843): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2843): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2843): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2843): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2843): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 51591(2MB) AllocSpace objects, 31(1012KB) LOS objects, 40% free, 7MB/12MB, paused 650us total 41.331ms
,D/BSUtils ( 2843): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2843): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2843): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1538): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2843): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2843): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2843): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2843): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2843): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2843): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2843): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2843): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2843): BcsDSCheckin.events found events 1328
,D/Checkin ( 2843): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/art     ( 2843): Explicit concurrent mark sweep GC freed 21772(1015KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/19MB, paused 1.337ms total 55.264ms
,I/BSUtils ( 2843): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2843): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3313(131KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 805us total 32.780ms
,D/MMApiWebService( 2843): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2843): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2843): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2843): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2843): unknown error code mapping for: 0
,I/global frequency( 2843): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2843): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2843): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2843): publish the event [tag = MOT_CHECKIN event name = LOG]
,V/AlarmManager(  982): send {127c9806, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  982): done {127c9806, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/BatteryService(  982): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311328, SEQNUM=4440, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-733, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2843): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2843): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2843): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  982): Explicit concurrent mark sweep GC freed 8328(501KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 19MB/29MB, paused 1.754ms total 112.264ms
,D/MMApiWebService( 2843): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2843):  Nonce Reponse 
I/MMApiWebService( 2843): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2843): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2843): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2843): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2843): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2843): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2843): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
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
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  982): send {67174cd, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  982): done {67174cd, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,I/VacuumService( 1690): Vacuum at: now=1454090330904 tag=VacuumService
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
,D/CdsService( 2843): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2843): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2843): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  982): send {187ad5d0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  982): send {2ce342b3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  982): done {187ad5d0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [6ms]
,V/AlarmManager(  982): done {2ce342b3, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
,I/ConfigService( 1690): onCreate
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1690): disconnect managed GoogleApiClient
,I/ConfigService( 1690): onDestroy
,V/AlarmManager(  982): send {2c210460, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  982): done {2c210460, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [6ms]
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
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
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
,D/BatteryService(  982): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311229, SEQNUM=4448, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-934, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2843): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2843): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2843): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2843): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2843):  Nonce Reponse 
I/MMApiWebService( 2843): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2843): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2843): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2843): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2843): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2843): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2843): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2843): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2843): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2843): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
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
,D/BatteryService(  982): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311394, SEQNUM=4450, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-1832, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  982): send {2ce342b3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  982): send {a83f193, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  982): done {a83f193, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [9ms]
,V/AlarmManager(  982): done {2ce342b3, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2843): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2843): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2843): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2843): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2843):  Nonce Reponse 
I/MMApiWebService( 2843): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2843): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2843): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2843): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2843): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2843): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2843): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2843): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2843): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,D/CdsService( 2843): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2843): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2843): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  982): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1690): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5645): 
D/AndroidRuntime( 5645): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5645): CheckJNI is OFF
D/AndroidRuntime( 5645): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  982): Force stopping com.test.thalitest appid=10488 user=-1: uninstall pkg
I/ActivityManager(  982): Killing 5495:com.test.thalitest/u0a488 (adj 11): stop com.test.thalitest
W/PackageSettings(  982): Skipping PackageSetting{4b66c2d com.example.hello/10440} due to missing metadata
I/ActivityManager(  982): Force stopping com.test.thalitest appid=10488 user=0: pkg removed
I/art     ( 3271): Explicit concurrent mark sweep GC freed 3799(766KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 7MB/12MB, paused 574us total 41.645ms
I/art     ( 1556): Explicit concurrent mark sweep GC freed 7369(536KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 580us total 91.390ms
W/ActivityManager(  982): Spurious death for ProcessRecord{7048131 5495:com.test.thalitest/u0a488}, curProc for 5495: null
I/Keyboard.Facilitator( 1405): resetDictionaries() : en_US
I/art     ( 5153): Explicit concurrent mark sweep GC freed 10819(654KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/16MB, paused 701us total 110.661ms
I/Keyboard.Facilitator.DecoderInitializer( 1405): run()
I/InputReader(  982): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1690): Ignoring removeGeofence because network location is disabled.
I/Decoder ( 1405): createOrResetDecoder
I/art     ( 5217): Explicit concurrent mark sweep GC freed 697(39KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 374us total 146.297ms
I/ActivityManager(  982): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5673 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  982): Explicit concurrent mark sweep GC freed 17181(1101KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 1.460ms total 136.948ms
I/art     (  982): WaitForGcToComplete blocked for 32.435ms for cause Explicit
I/ConfigService( 1690): onCreate
I/CheckinRequestBuilder( 1690): Classify the device as Phone.
W/FetchTask( 1690): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/VoicemailCleanupService( 5673): Cleaning up data for package: com.test.thalitest
D/BackupManagerService(  982): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  982): Receieved: android.intent.action.PACKAGE_REMOVED
I/CheckinRequestBuilder( 1690): Classify the device as Phone.
I/ContactLocale( 5673): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  982): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5707 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/TaskPersister(  982): removeObsoleteFile: deleting file=6_task.xml
I/art     (  982): Explicit concurrent mark sweep GC freed 4373(225KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 3.162ms total 183.529ms
W/FetchTask( 1690): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/asset   ( 5707): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5707): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5707): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5707): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 1690): Classify the device as Phone.
W/FetchTask( 1690): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1690): Classify the device as Phone.
W/FetchTask( 1690): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Launcher( 1556): Deferring update until onResume
I/CheckinRequestBuilder( 1690): Classify the device as Phone.
I/ActivityManager(  982): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5731 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/FetchTask( 1690): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ActivityManager(  982): Killing 5217:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
W/libprocessgroup(  982): failed to open /acct/uid_10039/pid_5217/cgroup.procs: No such file or directory
W/ContextImpl( 5731): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 5153): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 5153): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 5153): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5153): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 5645): Shutting down VM
D/ChimeraCfgMgr( 5153): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5153): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1690): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1405): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = contacts
I/ActivityManager(  982): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5754 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 5153): Removing dialog suppression flag for package com.test.thalitest
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Loading LM = user
D/gH_CompatibleDatabase( 5153): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 5153): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 5153): 0 metrics were deleted when clearing package com.test.thalitest.
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1405): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1405): run() : Loaded (exit)
D/gH_CompatibleDatabase( 5153): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
I/Keyboard.Facilitator.Delight2FileSweeper( 1405): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1405): run()
I/StatsUtilsManager( 1405): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1405): shouldRecordStats() = Too Soon
D/gH_CompatibleDatabase( 5153): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 5153): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 5153): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 5153): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 5153): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 5153): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 5153): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 5153): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 5153): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 5153): Using Auth Proxy for data requests.
W/BaseAppContext( 5153): Using Auth Proxy for data requests.
I/GMPM-SVC( 5153): App measurement is starting up, version: 8489
I/GMPM-SVC( 5153): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/ConnectivityService(  982): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Launcher( 1556): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1964db6 new=com.google.android.velvet.VelvetApplication@1964db6
I/Icing   ( 5153): doRemovePackageData com.test.thalitest
I/ActivityManager(  982): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5783 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/DriveInitializer( 5153): Awaiting to be initialized
W/DriveInitializer( 5153): Background init thread started
E/SQLiteLog( 5153): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 5153): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 5153): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 5153): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 5153): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 5153): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 5153): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 5153): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 5153): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 5153): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 5153): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 5153): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 5153): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 5153): Process: com.google.android.gms, PID: 5153
E/AndroidRuntime( 5153): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5153): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 5153): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 5153): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 5153): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 5153): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 5153): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 5153): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 5153): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 5153): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 5153): disk I/O error (code 3850)
E/DriveAsyncService( 5153): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 5153): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 5153): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 5153): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 5153): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 5153): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 5153): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 5153): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 5153): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 5153): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 5153): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 5153): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 5153): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 5153): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 5153): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 5153): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 5153): Sending signal. PID: 5153 SIG: 9
E/DropBoxManagerService(  982): Can't write: system_app_crash
E/DropBoxManagerService(  982): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  982): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  982): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  982): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  982): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  982): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  982): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  982): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  982): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  982): 	... 5 more
D/ConnectivityService(  982): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@17e35cbe)
D/ConnectivityService(  982): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  982): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
