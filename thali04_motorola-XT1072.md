#### Test 575312430087a60_thali04_motorola-XT1072 Logs


```
--------- beginning of system
V/AlarmManager(  884): send {3bf86af0, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
V/AlarmManager(  884): done {3bf86af0, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [9ms]
,--------- beginning of main
D/AndroidRuntime( 5218): 
D/AndroidRuntime( 5218): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5218): CheckJNI is OFF
D/AndroidRuntime( 5218): Calling main entry com.android.commands.am.Am
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5237 uid=10489 gids={50489, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5218): Shutting down VM
V/ActivityManager(  884): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5237): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5237): Time to load native libraries: 3 ms (timestamps 1088-1091)
,I/LibraryLoader( 5237): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5237): Binding Chromium to main looper Looper (main, tid 1) {30b84eb0}
,I/LibraryLoader( 5237): Expected native library version number "",actual native library version number ""
I/chromium( 5237): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5237): Initializing chromium process, singleProcess=true
,W/art     ( 5237): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5237): ApplicationContext is null in ApplicationStatus
,W/chromium( 5237): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5237): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5237): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5237): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5237): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5237): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5237): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5237): Local Branch: 
I/Adreno-EGL( 5237): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5237): Local Patches: NONE
I/Adreno-EGL( 5237): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6163cb4:true
,D/BluetoothAdapter( 5237): 238681195: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  884): Activity pause timeout for ActivityRecord{1efad869 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5237): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5237): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5237): CordovaWebView is running on device made by: motorola
,W/art     ( 5237): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5237): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     (  884): Explicit concurrent mark sweep GC freed 17033(836KB) AllocSpace objects, 2(196KB) LOS objects, 33% free, 19MB/29MB, paused 1.600ms total 123.070ms
,D/OpenGLRenderer( 5237): Render dirty regions requested: true
,D/Atlas   ( 5237): Validating map...
,W/chromium( 5237): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5237): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5237): Enabling debug mode 0
,I/Keyboard.Facilitator( 1407): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.test.thalitest/.MainActivity,cp,ca,1114
I/ActivityManager(  884): Displayed com.test.thalitest/.MainActivity: +1s23ms (total +1s114ms)
,W/IInputConnectionWrapper( 5237): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5237): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5237): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5237): Cannot call determinedVisibility() - never saw a connection for the pid: 5237
,D/JsMessageQueue( 5237): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5237): JniHelper::setJavaVM(0xb7641310), pthread_self() = -1215550096
,I/chromium( 5237): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5237): Initializing JXcore engine
W/jxcore-log( 5237): JXcore engine is ready
,W/Thread-592( 5286): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10489 path="socket:[7699]" dev="sockfs" ino=7699 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-592( 5286): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10489 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2212 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-592( 5286): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10489 path="socket:[8944]" dev="sockfs" ino=8944 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-592( 5286): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10489 path="socket:[23887]" dev="sockfs" ino=23887 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5237): Starting JXcore engine
,W/jxcore-log( 5237): Platform android
W/jxcore-log( 5237): 
,W/jxcore-log( 5237): Process ARCH arm
W/jxcore-log( 5237): 
,I/jxcore-log( 5237): JXcore Cordova bridge is ready!
I/jxcore-log( 5237): 
,W/jxcore-log( 5237): JXcore engine is started
,E/jxcore  ( 5237): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5237): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5237): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  884): Killing 4815:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_4815/cgroup.procs: No such file or directory
,W/PluginManager( 5237): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2511): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2511): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2511): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2511): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2511): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2511): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5237): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1407): onFinishInput()
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:32000 mC
,D/TaskPersister(  884): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  884): send {132fed97, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  884): send {3ffbbb, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {3ffbbb, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,V/AlarmManager(  884): done {132fed97, *alarm*:android.intent.action.TIME_TICK} [41ms]
,E/global frequency( 2511): no tags to log
,D/Checkin ( 2511): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2511): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2511): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2511): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2511): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 38378(2MB) AllocSpace objects, 16(573KB) LOS objects, 39% free, 7MB/12MB, paused 718us total 33.648ms
,D/BSUtils ( 2511): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2511): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2511): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2511): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2511): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2511): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2511): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2511): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2511): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2511): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2511): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/art     ( 2511): Explicit concurrent mark sweep GC freed 17530(898KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 11MB/18MB, paused 1.421ms total 64.062ms
,I/global frequency( 2511): BcsDSCheckin.events found events 1392
,D/Checkin ( 2511): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2511): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,V/AlarmManager(  884): send {3e2027c, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  884): done {3e2027c, *walarm*:com.google.android.intent.action.SEND_IDLE} [3ms]
,D/MMApiWebService( 2511): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     (  884): Explicit concurrent mark sweep GC freed 7747(459KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 19MB/29MB, paused 1.429ms total 106.476ms
,D/MMApiWebService( 2511): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2511): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2511): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
,D/CCE     ( 2511): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2511): unknown error code mapping for: 0
I/global frequency( 2511): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2511): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2511): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2511): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311182, SEQNUM=4354, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-442, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2511): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2511): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2511): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3188(126KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 826us total 37.252ms
,D/MMApiWebService( 2511): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2511):  Nonce Reponse 
I/MMApiWebService( 2511): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2511): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2511): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2511): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2511): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2511): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2511): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311117, SEQNUM=4356, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-479, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/CdsService( 2511): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2511): [i] > Retry handler returned true; Retry web request after backoff time: 300000
,D/Checkin ( 2511): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1733): onCreate
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,I/ConfigService( 1733): onDestroy
,V/AlarmManager(  884): send {1ed6784, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
V/AlarmManager(  884): send {132fed97, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  884): send {e8aca68, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  884): send {3ffbbb, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {1ed6784, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [5ms]
,V/AlarmManager(  884): done {e8aca68, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [22ms]
V/AlarmManager(  884): done {3ffbbb, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [22ms]
,V/AlarmManager(  884): done {132fed97, *alarm*:android.intent.action.TIME_TICK} [52ms]
,I/VacuumService( 1733): Vacuum at: now=1454092084619 tag=VacuumService
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310966, SEQNUM=4360, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-614, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  884): send {132fed97, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {3091a367, *walarm*:com.motorola.blur.service.blur.pm.alarmintent}
,I/PollingManager( 2511): alarm fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2511): alarm fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/PollingManager( 2511): alarm fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/OtaApp  ( 2511): [info] > PollingManagerService, alarm fired!
,D/Checkin ( 2511): publish the event [tag = MOT_OTA event name = LOG]
,I/Central_PollingManager( 1465): alarm fired!
,V/AlarmManager(  884): done {132fed97, *alarm*:android.intent.action.TIME_TICK} [47ms]
,V/AlarmManager(  884): done {3091a367, *walarm*:com.motorola.blur.service.blur.pm.alarmintent} [63ms]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311253, SEQNUM=4363, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-626, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2511): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2511): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2511): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2511): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2511):  Nonce Reponse 
I/MMApiWebService( 2511): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2511): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2511): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2511): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2511): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2511): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2511): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=266, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311223, SEQNUM=4364, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-672, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 2511): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2511): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2511): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  884): send {132fed97, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  884): send {338ba997, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  884): done {338ba997, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [7ms]
,V/AlarmManager(  884): done {132fed97, *alarm*:android.intent.action.TIME_TICK} [44ms]
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=261, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310573, SEQNUM=4365, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-154, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309951, SEQNUM=4368, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-214, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310556, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310547, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310539, SEQNUM=4373, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=503, POWER_SUPPLY_CHARGE_COUNTER=3, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2511): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2511): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2511): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2511): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2511):  Nonce Reponse 
I/MMApiWebService( 2511): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2511): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2511): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2511): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2511): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2511): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2511): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2511): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2511): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310539, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-4, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/CdsService( 2511): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2511): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2511): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310837, SEQNUM=4377, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=6561, POWER_SUPPLY_CHARGE_COUNTER=5, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310833, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=0, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  884): User[0] Flushing usage stats to disk
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4309942, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3205, POWER_SUPPLY_CHARGE_COUNTER=-39, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  316): NetlinkHandler, power_supply subsys
I/MDMCTBK (  316): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  316): checkDefaultInst, current pid is = 316
I/MDMCTBK (  316): checkDefaultInst, pid match
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  316): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  316): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=257, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310820, SEQNUM=4383, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-27, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  326): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5376): 
D/AndroidRuntime( 5376): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5376): CheckJNI is OFF
D/AndroidRuntime( 5376): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10489 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 5237:com.test.thalitest/u0a489 (adj 11): stop com.test.thalitest
W/PackageSettings(  884): Skipping PackageSetting{16299501 com.example.hello/10440} due to missing metadata
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10489 user=0: pkg removed
I/art     ( 2947): Explicit concurrent mark sweep GC freed 5476(1008KB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 7MB/12MB, paused 614us total 50.846ms
W/ActivityManager(  884): Spurious death for ProcessRecord{36b3470c 5237:com.test.thalitest/u0a489}, curProc for 5237: null
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/Decoder ( 1407): createOrResetDecoder
I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5404 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 4886): Explicit concurrent mark sweep GC freed 1982(97KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 697us total 128.772ms
I/art     ( 1559): Explicit concurrent mark sweep GC freed 7396(537KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 474us total 122.604ms
I/ConfigService( 1733): onCreate
I/art     ( 4940): Explicit concurrent mark sweep GC freed 688(38KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 354us total 158.257ms
I/art     (  884): Explicit concurrent mark sweep GC freed 22765(1582KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 3.081ms total 178.031ms
I/art     (  884): WaitForGcToComplete blocked for 96.895ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): run()
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
D/VoicemailCleanupService( 5404): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5428 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5404): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  884): removeObsoleteFile: deleting file=6_task.xml
I/Launcher( 1559): Deferring update until onResume
W/asset   ( 5428): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5428): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5428): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5428): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  884): Explicit concurrent mark sweep GC freed 5004(262KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 4.559ms total 221.999ms
I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5449 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  884): Killing 4940:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5376): Shutting down VM
W/libprocessgroup(  884): failed to open /acct/uid_10039/pid_4940/cgroup.procs: No such file or directory
W/ContextImpl( 5449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4886): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4886): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4886): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4886): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4886): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4886): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 4886): Removing dialog suppression flag for package com.test.thalitest
E/NetworkScheduler.SchedulerReceiver( 1733): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1733): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 4886): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4886): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4886): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4886): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4886): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4886): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4886): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4886): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4886): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4886): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4886): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4886): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4886): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5475 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/BaseAppContext( 4886): Using Auth Proxy for data requests.
W/BaseAppContext( 4886): Using Auth Proxy for data requests.
I/GMPM-SVC( 4886): App measurement is starting up, version: 8489
I/GMPM-SVC( 4886): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
D/ConnectivityService(  884): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/Icing   ( 4886): doRemovePackageData com.test.thalitest
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@376175ba new=com.google.android.velvet.VelvetApplication@376175ba
I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5510 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/SQLiteLog( 4886): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 4886): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SharedPreferencesImpl( 4886): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
W/DriveInitializer( 4886): Awaiting to be initialized
W/DriveInitializer( 4886): Background init thread started
E/SQLiteLog( 4886): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 4886): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 4886): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4886): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 4886): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4886): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4886): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 4886): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 4886): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 4886): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 4886): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 4886): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4886): Process: com.google.android.gms, PID: 4886
E/AndroidRuntime( 4886): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4886): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4886): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 4886): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 4886): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 4886): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 4886): disk I/O error (code 3850)
E/DriveAsyncService( 4886): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4886): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4886): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 4886): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4886): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4886): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 4886): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 4886): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4886): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4886): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4886): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4886): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4886): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4886): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4886): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4886): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 4886): Sending signal. PID: 4886 SIG: 9
E/DropBoxManagerService(  884): Can't write: system_app_crash
E/DropBoxManagerService(  884): java.io.FileNotFoundException: /data/system/dropbox/drop95.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  884): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  884): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  884): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  884): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  884): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  884): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  884): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  884): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  884): 	... 5 more
D/ConnectivityService(  884): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3a94fef4)
D/ConnectivityService(  884): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  884): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
