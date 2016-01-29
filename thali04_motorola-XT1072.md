#### Test 57617811ecc172f_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,--------- beginning of system
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
D/AndroidRuntime( 5276): 
D/AndroidRuntime( 5276): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5276): CheckJNI is OFF
D/AndroidRuntime( 5276): Calling main entry com.android.commands.am.Am
I/ActivityManager(  894): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  894): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5307 uid=10485 gids={50485, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5276): Shutting down VM
V/ActivityManager(  894): Display changed displayId=0
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 5307): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5307): Time to load native libraries: 3 ms (timestamps 7884-7887)
,I/LibraryLoader( 5307): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5307): Binding Chromium to main looper Looper (main, tid 1) {38222161}
,I/LibraryLoader( 5307): Expected native library version number "",actual native library version number ""
I/chromium( 5307): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5307): Initializing chromium process, singleProcess=true
,W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5307): ApplicationContext is null in ApplicationStatus
,W/chromium( 5307): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5307): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5307): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5307): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5307): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5307): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5307): Local Branch: 
I/Adreno-EGL( 5307): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5307): Local Patches: NONE
I/Adreno-EGL( 5307): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  894): Message: 20
D/BluetoothManagerService(  894): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2a0849d1:true
,D/BluetoothAdapter( 5307): 386239203: getState() :  mService = null. Returning STATE_OFF
,I/art     ( 2930): Background partial concurrent mark sweep GC freed 8411(2040KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 8.777ms total 24.175ms
,W/ActivityManager(  894): Activity pause timeout for ActivityRecord{1f326412 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5307): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5307): CordovaWebView is running on device made by: motorola
,W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5307): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5307): Render dirty regions requested: true
,D/Atlas   ( 5307): Validating map...
,W/chromium( 5307): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  894): Explicit concurrent mark sweep GC freed 17080(852KB) AllocSpace objects, 2(195KB) LOS objects, 33% free, 19MB/29MB, paused 1.569ms total 120.855ms
,I/OpenGLRenderer( 5307): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5307): Enabling debug mode 0
,I/Keyboard.Facilitator( 1420): onFinishInput()
,I/LaunchCheckinHandler(  894): Displayed com.test.thalitest/.MainActivity,cp,ca,1056
I/ActivityManager(  894): Displayed com.test.thalitest/.MainActivity: +973ms (total +1s56ms)
,W/IInputConnectionWrapper( 5307): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5307): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5307): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5307): Cannot call determinedVisibility() - never saw a connection for the pid: 5307
,D/JsMessageQueue( 5307): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5307): JniHelper::setJavaVM(0xb8503310), pthread_self() = -1198971144
,I/chromium( 5307): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,V/AlarmManager(  894): send {d9d5372, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  894): done {d9d5372, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [2ms]
,W/art     ( 5307): Suspending all threads took: 15.189ms
,I/art     ( 5307): Background sticky concurrent mark sweep GC freed 3286(268KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 16.292ms total 50.446ms
,W/jxcore-log( 5307): Initializing JXcore engine
,W/jxcore-log( 5307): JXcore engine is ready
,W/Thread-603( 5363): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10485 path="socket:[9637]" dev="sockfs" ino=9637 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-603( 5363): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10485 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-603( 5363): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10485 path="socket:[6426]" dev="sockfs" ino=6426 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-603( 5363): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10485 path="socket:[19401]" dev="sockfs" ino=19401 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5307): Starting JXcore engine
,W/jxcore-log( 5307): Platform android
W/jxcore-log( 5307): 
W/jxcore-log( 5307): Process ARCH arm
W/jxcore-log( 5307): 
,I/jxcore-log( 5307): JXcore Cordova bridge is ready!
I/jxcore-log( 5307): 
W/jxcore-log( 5307): JXcore engine is started
,E/jxcore  ( 5307): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5307): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5307): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  894): Killing 5013:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  894): failed to open /acct/uid_10039/pid_5013/cgroup.procs: No such file or directory
,W/PluginManager( 5307): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2494): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2494): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2494): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2494): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2494): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2494): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1420): onFinishInput()
W/IInputConnectionWrapper( 5307): showStatusIcon on inactive InputConnection
,D/TaskPersister(  894): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  894): send {189d77dc, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  894): done {189d77dc, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [5ms]
,E/global frequency( 2494): no tags to log
,D/Checkin ( 2494): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2494): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2494): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2494): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2494): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 53778(2MB) AllocSpace objects, 32(1026KB) LOS objects, 39% free, 7MB/12MB, paused 952us total 42.040ms
,D/BSUtils ( 2494): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2494): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2494): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1541): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,V/AlarmManager(  894): send {3ae934be, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  894): done {3ae934be, *walarm*:com.google.android.intent.action.SEND_IDLE} [4ms]
,D/BSUtils ( 2494): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2494): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2494): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2494): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2494): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2494): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2494): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2494): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/global frequency( 2494): BcsDSCheckin.events found events 1125
,D/Checkin ( 2494): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2494): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 2494): Explicit concurrent mark sweep GC freed 22668(1520KB) AllocSpace objects, 7(129KB) LOS objects, 39% free, 11MB/19MB, paused 877us total 71.893ms
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 3520(138KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 565us total 25.967ms
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2494): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2494): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2494): unknown error code mapping for: 0
I/global frequency( 2494): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2494): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2494): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2494): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=275, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312241, SEQNUM=4363, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-434, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2494): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2494): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  894): Explicit concurrent mark sweep GC freed 8544(511KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 19MB/29MB, paused 1.852ms total 114.336ms
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2494):  Nonce Reponse 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2494): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2494): MMApiWebService told us not to continue at the moment with this request: nonce.json
D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2494): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2494): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1420): run()
I/Keyboard.Facilitator( 1420): flushDynamicLanguageModels()
,I/ConfigService( 1729): onCreate
,I/ClearcutLoggerApiImpl( 1729): disconnect managed GoogleApiClient
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1729): onDestroy
,V/AlarmManager(  894): send {28d1a362, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {192f42e0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  894): send {117fdeca, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  894): send {189d77dc, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  894): done {192f42e0, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [9ms]
,V/AlarmManager(  894): done {117fdeca, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [25ms]
V/AlarmManager(  894): done {189d77dc, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [25ms]
,V/AlarmManager(  894): done {28d1a362, *alarm*:android.intent.action.TIME_TICK} [58ms]
,I/VacuumService( 1729): Vacuum at: now=1454063500157 tag=VacuumService,
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312435, SEQNUM=4369, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-568, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  894): send {28d1a362, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): done {28d1a362, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=262, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312332, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-858, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2494): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2494): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2494):  Nonce Reponse 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2494): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2494): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2494): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=260, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312592, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5408, POWER_SUPPLY_CHARGE_COUNTER=-1108, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311982, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-1252, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311990, SEQNUM=4374, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-1295, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  894): send {28d1a362, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  894): send {2260a8e3, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  894): send {252cb95d, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  894): done {2260a8e3, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [19ms]
,V/AlarmManager(  894): done {28d1a362, *alarm*:android.intent.action.TIME_TICK} [50ms]
,V/AlarmManager(  894): done {252cb95d, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [59ms]
,I/EventLogService( 4959): Aggregate from 1454061836879 (log), 1454061836879 (data)
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311705, SEQNUM=4378, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-1355, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312570, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7011, POWER_SUPPLY_CHARGE_COUNTER=-1389, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311688, SEQNUM=4381, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1405, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311969, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-1536, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MMApiBackOffService( 2494): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2494): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2494):  Nonce Reponse 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2494): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2494): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 3534(152KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 771us total 30.175ms
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2494): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  894): User[0] Flushing usage stats to disk
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  308): NetlinkHandler, power_supply subsys
I/MDMCTBK (  308): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  308): checkDefaultInst, current pid is = 308
I/MDMCTBK (  308): checkDefaultInst, pid match
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  308): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  308): MdmCutbackHndler,Could not open ''
,D/BatteryService(  894): uevent={POWER_SUPPLY_TEMP=256, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312544, SEQNUM=4385, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-2382, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  320): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5448): 
D/AndroidRuntime( 5448): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5448): CheckJNI is OFF
D/AndroidRuntime( 5448): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  894): Force stopping com.test.thalitest appid=10485 user=-1: uninstall pkg
I/ActivityManager(  894): Killing 5307:com.test.thalitest/u0a485 (adj 11): stop com.test.thalitest
W/PackageSettings(  894): Skipping PackageSetting{3c9ae7e com.example.hello/10440} due to missing metadata
W/ActivityManager(  894): Spurious death for ProcessRecord{3535d1da 5307:com.test.thalitest/u0a485}, curProc for 5307: null
I/ActivityManager(  894): Force stopping com.test.thalitest appid=10485 user=0: pkg removed
I/art     ( 2930): Explicit concurrent mark sweep GC freed 4162(825KB) AllocSpace objects, 19(304KB) LOS objects, 39% free, 7MB/12MB, paused 578us total 34.997ms
I/Keyboard.Facilitator( 1420): resetDictionaries() : en_US
W/GeofencerStateMachine( 1729): Ignoring removeGeofence because network location is disabled.
I/InputReader(  894): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1420): run()
I/Decoder ( 1420): createOrResetDecoder
D/VoicemailCleanupService( 4884): Cleaning up data for package: com.test.thalitest
I/art     ( 1568): Explicit concurrent mark sweep GC freed 7296(530KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 497us total 135.273ms
I/ActivityManager(  894): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5479 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 4959): Explicit concurrent mark sweep GC freed 3494(248KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 12MB/17MB, paused 773us total 175.104ms
I/art     (  894): Explicit concurrent mark sweep GC freed 18152(1304KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 19MB/29MB, paused 2.304ms total 135.942ms
I/art     (  894): WaitForGcToComplete blocked for 136.323ms for cause Explicit
I/ConfigService( 1729): onCreate
W/asset   ( 5479): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5479): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5479): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5479): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.MainLanguageModelLoader( 1420): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1420): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1420): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1420): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1420): run()
I/StatsUtilsManager( 1420): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1420): shouldRecordStats() = Too Soon
D/BackupManagerService(  894): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  894): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  894): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5506 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  894): removeObsoleteFile: deleting file=6_task.xml
I/art     (  894): Explicit concurrent mark sweep GC freed 5579(285KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.899ms total 175.721ms
I/Launcher( 1568): Deferring update until onResume
W/ContextImpl( 5506): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4959): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4959): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4959): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4959): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4959): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4959): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1729): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1729): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/AndroidRuntime( 5448): Shutting down VM
I/ActivityManager(  894): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5528 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 4959): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 4959): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4959): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4959): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4959): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4959): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4959): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4959): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4959): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4959): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4959): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4959): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4959): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4959): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 4959): Using Auth Proxy for data requests.
W/BaseAppContext( 4959): Using Auth Proxy for data requests.
I/GMPM-SVC( 4959): App measurement is starting up, version: 8489
I/GMPM-SVC( 4959): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 4959): doRemovePackageData com.test.thalitest
D/ConnectivityService(  894): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Launcher( 1568): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@17058ae3 new=com.google.android.velvet.VelvetApplication@17058ae3
I/ActivityManager(  894): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5559 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
W/DriveInitializer( 4959): Awaiting to be initialized
W/DriveInitializer( 4959): Background init thread started
E/Vold    (  280): Failed to find mounted volume for /storage/sdcard1/Android/data/com.google.android.gms/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4959): Failed to ensure directory: /storage/sdcard1/Android/data/com.google.android.gms/files
I/ActivityManager(  894): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=5586 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/art     (  324): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.308ms
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 19.439ms
E/SQLiteLog( 4959): (3850) statement aborts at 151: [DELETE FROM FileContent163 WHERE hash IN WipeoutFileContentHashView AND hash NOT IN ()] disk I/O error
E/DocListDatabase( 4959): Failed to delete from FileContent163 table
E/DocListDatabase( 4959): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4959): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 4959): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 4959): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/DocListDatabase( 4959): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/DocListDatabase( 4959): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/DocListDatabase( 4959): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DocListDatabase( 4959): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DocListDatabase( 4959): 	at java.lang.Thread.run(Thread.java:818)
--------- beginning of crash
E/AndroidRuntime( 4959): FATAL EXCEPTION: pool-10-thread-1
E/AndroidRuntime( 4959): Process: com.google.android.gms, PID: 4959
E/AndroidRuntime( 4959): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4959): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4959): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 4959): 	at com.google.android.gms.drive.database.f.a(SourceFile:987)
E/AndroidRuntime( 4959): 	at com.google.android.gms.drive.b.e.run(SourceFile:74)
E/AndroidRuntime( 4959): 	at com.google.android.gms.drive.j.ah.run(SourceFile:51)
E/AndroidRuntime( 4959): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4959): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4959): 	at java.lang.Thread.run(Thread.java:818)
I/art     (  324): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.449ms
I/Process ( 4959): Sending signal. PID: 4959 SIG: 9
E/DropBoxManagerService(  894): Can't write: system_app_crash
E/DropBoxManagerService(  894): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  894): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  894): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  894): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  894): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  894): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  894): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  894): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  894): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  894): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  894): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  894): 	... 5 more
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
