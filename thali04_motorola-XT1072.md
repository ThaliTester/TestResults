#### Test 56672827b6f75d5_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  321): Sensor:xo_therm_pu2:31000 mC
,D/AndroidRuntime( 6232): 
D/AndroidRuntime( 6232): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6232): CheckJNI is OFF
D/AndroidRuntime( 6232): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  884): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  884): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6251 uid=10472 gids={50472, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6232): Shutting down VM
V/ActivityManager(  884): Display changed displayId=0
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6251): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 6251): Time to load native libraries: 2 ms (timestamps 7775-7777)
I/LibraryLoader( 6251): Expected native library version number "",actual native library version number ""
I/art     (  884): Explicit concurrent mark sweep GC freed 35055(1728KB) AllocSpace objects, 2(216KB) LOS objects, 33% free, 20MB/30MB, paused 1.439ms total 127.583ms
V/WebViewChromiumFactoryProvider( 6251): Binding Chromium to main looper Looper (main, tid 1) {32b157c4}
I/LibraryLoader( 6251): Expected native library version number "",actual native library version number ""
I/chromium( 6251): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6251): Initializing chromium process, singleProcess=true
W/art     ( 6251): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6251): ApplicationContext is null in ApplicationStatus
W/chromium( 6251): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6251): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6251): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6251): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6251): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6251): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6251): Local Branch: 
I/Adreno-EGL( 6251): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6251): Local Patches: NONE
I/Adreno-EGL( 6251): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
W/ActivityManager(  884): Activity pause timeout for ActivityRecord{b566b50 u0 com.test.thalitest/.MainActivity t6}
D/BluetoothManagerService(  884): Message: 20
D/BluetoothManagerService(  884): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32403567:true
W/art     ( 6251): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6251): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 6251): CordovaWebView is running on device made by: motorola
W/art     ( 6251): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6251): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6251): Render dirty regions requested: true
D/Atlas   ( 6251): Validating map...
W/chromium( 6251): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/OpenGLRenderer( 6251): Initialized EGL, version 1.4
D/OpenGLRenderer( 6251): Enabling debug mode 0
,I/Keyboard.Facilitator( 1418): onFinishInput()
,I/LaunchCheckinHandler(  884): Displayed com.test.thalitest/.MainActivity,cp,ca,1090
I/ActivityManager(  884): Displayed com.test.thalitest/.MainActivity: +1s19ms (total +1s90ms)
,W/IInputConnectionWrapper( 6251): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 6251): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6251): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,V/AlarmManager(  884): send {1379d1b0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  884): done {1379d1b0, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [6ms]
,W/BindingManager( 6251): Cannot call determinedVisibility() - never saw a connection for the pid: 6251
,D/JsMessageQueue( 6251): Set native->JS mode to OnlineEventsBridgeMode
,I/PhenotypeConfigurator( 1712): Scheduling Phenotype for one-off execution 891 seconds from now (1453394740904)
,D/GetConfigurationSnapshotOperation( 1712): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1712): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1712): Using platform SSLCertificateSocketFactory
,D/jxcore_app_log( 6251): JniHelper::setJavaVM(0xb8ad0310), pthread_self() = -1192887472
,I/chromium( 6251): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/global frequency( 2582): no tags to log
,D/Checkin ( 2582): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2582): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 57535(3MB) AllocSpace objects, 35(1196KB) LOS objects, 39% free, 7MB/12MB, paused 705us total 53.960ms
,D/BSUtils ( 2582): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2582): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2582): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2582): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1554): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1464): Explicit concurrent mark sweep GC freed 3920(165KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 666us total 27.227ms
,W/jxcore-log( 6251): Initializing JXcore engine
W/jxcore-log( 6251): JXcore engine is ready
,I/art     (  884): Explicit concurrent mark sweep GC freed 12889(638KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.442ms total 114.583ms
,W/Thread-763( 6313): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10472 path="socket:[7335]" dev="sockfs" ino=7335 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-763( 6313): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10472 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-763( 6313): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10472 path="socket:[9662]" dev="sockfs" ino=9662 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-763( 6313): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10472 path="socket:[25941]" dev="sockfs" ino=25941 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6251): Starting JXcore engine
,V/GLSActivity( 1712): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1712): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 2582): Explicit concurrent mark sweep GC freed 27791(1588KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 11MB/18MB, paused 1.264ms total 66.401ms
,D/BSUtils ( 2582): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2582): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2582): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2582): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2582): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2582): publish the event [tag = DEV_ATTRIBS event name = SW]
,D/Checkin ( 2582): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,W/jxcore-log( 6251): Platform android
W/jxcore-log( 6251): 
W/jxcore-log( 6251): Process ARCH arm
W/jxcore-log( 6251): 
,I/global frequency( 2582): BcsDSCheckin.events found events 48
,D/Checkin ( 2582): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2582): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/MMApiWSBase( 2582): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
,D/Checkin ( 2582): publish the event [tag = MOT_CCE event name = LOG]
,I/jxcore-log( 6251): JXcore Cordova bridge is ready!
I/jxcore-log( 6251): 
,W/jxcore-log( 6251): JXcore engine is started
,E/jxcore  ( 6251): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6251): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6251): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  884): Killing 5911:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  884): failed to open /acct/uid_10007/pid_5911/cgroup.procs: No such file or directory
,W/PluginManager( 6251): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 28ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1464): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2582): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2582): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2582): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2582): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2582): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2582): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1418): onFinishInput()
W/IInputConnectionWrapper( 6251): showStatusIcon on inactive InputConnection
,D/MMApiWSBase( 2582): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2582): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2582): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/global frequency( 2582): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2582): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  884): 48 events delete 2 left
,I/global frequency( 2582): BcsDSCheckin.events found events 0
,D/Checkin ( 2582): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2582): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,W/DataUsage( 2582): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2582): publish the event [tag = MOT_CCE event name = LOG]
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/TaskPersister(  884): removeObsoleteFile: deleting file=5_task.xml
,V/AlarmManager(  884): send {11bb10c, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  884): done {11bb10c, *walarm*:com.google.android.intent.action.SEND_IDLE} [8ms]
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:30000 mC
,I/ClearcutLoggerApiImpl( 1712): disconnect managed GoogleApiClient
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  884): send {34714a49, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {24043a55, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  884): done {24043a55, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [6ms]
,V/AlarmManager(  884): done {34714a49, *alarm*:android.intent.action.TIME_TICK} [42ms]
,I/Keyboard.Facilitator.LanguageModelFlusher( 1418): run()
I/Keyboard.Facilitator( 1418): flushDynamicLanguageModels()
,I/ConfigService( 1712): onCreate
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1712): onDestroy
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312684, SEQNUM=4423, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2704, POWER_SUPPLY_CHARGE_COUNTER=-424, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2458): Disconnected process message: 10, size: 0
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,D/MDMCTBK (  303): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 4
D/MDMCTBK (  303): Event received = CTRL-EVENT-BSS-REMOVED 4
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  884): send {34714a49, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {379b26d1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  884): done {379b26d1, *walarm*:android.content.syncmanager.SYNC_ALARM} [6ms]
,V/AlarmManager(  884): done {34714a49, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  303): NetlinkHandler, power_supply subsys
I/MDMCTBK (  303): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  303): checkDefaultInst, current pid is = 303
I/MDMCTBK (  303): checkDefaultInst, pid match
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  303): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  303): MdmCutbackHndler,Could not open ''
,D/BatteryService(  884): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312243, SEQNUM=4425, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8613, POWER_SUPPLY_CHARGE_COUNTER=-886, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2458): Disconnected process message: 10, size: 0
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  884): send {34714a49, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {379b26d1, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  884): done {379b26d1, *walarm*:android.content.syncmanager.SYNC_ALARM} [6ms]
,V/AlarmManager(  884): done {34714a49, *alarm*:android.intent.action.TIME_TICK} [40ms]
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  884): send {34714a49, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {258d4240, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  884): done {258d4240, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [10ms]
,V/AlarmManager(  884): done {34714a49, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  884): send {34714a49, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {9896536, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  884): done {34714a49, *alarm*:android.intent.action.TIME_TICK} [40ms]
,V/AlarmManager(  884): done {9896536, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [89ms]
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  884): send {34714a49, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  884): send {2a1abc37, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  884): done {2a1abc37, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [18ms]
,V/AlarmManager(  884): done {34714a49, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  884): User[0] Flushing usage stats to disk
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  321): Sensor:xo_therm_pu2:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6377): 
D/AndroidRuntime( 6377): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6377): CheckJNI is OFF
D/AndroidRuntime( 6377): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10472 user=-1: uninstall pkg
I/ActivityManager(  884): Killing 6251:com.test.thalitest/u0a472 (adj 9): stop com.test.thalitest
W/PackageSettings(  884): Skipping PackageSetting{37262d05 com.example.hello/10440} due to missing metadata
I/ActivityManager(  884): Force stopping com.test.thalitest appid=10472 user=0: pkg removed
I/art     ( 3024): Explicit concurrent mark sweep GC freed 10483(2MB) AllocSpace objects, 18(288KB) LOS objects, 39% free, 7MB/12MB, paused 750us total 38.605ms
W/ActivityManager(  884): Spurious death for ProcessRecord{1c4515a4 6251:com.test.thalitest/u0a472}, curProc for 6251: null
I/Keyboard.Facilitator( 1418): resetDictionaries() : en_US
I/InputReader(  884): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1712): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  884): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=6405 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/Keyboard.Facilitator.DecoderInitializer( 1418): run()
I/art     ( 1573): Explicit concurrent mark sweep GC freed 4076(265KB) AllocSpace objects, 3(128KB) LOS objects, 25% free, 13MB/17MB, paused 490us total 105.694ms
I/Decoder ( 1418): createOrResetDecoder
I/ConfigService( 1712): onCreate
I/art     ( 1954): Explicit concurrent mark sweep GC freed 13330(789KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 14MB/19MB, paused 1.010ms total 164.863ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): run()
I/art     (  884): Explicit concurrent mark sweep GC freed 16437(1116KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 20MB/30MB, paused 1.597ms total 169.366ms
I/art     (  884): WaitForGcToComplete blocked for 121.353ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1418): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1418): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1418): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1418): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1418): run()
I/StatsUtilsManager( 1418): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1418): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 6405): Cleaning up data for package: com.test.thalitest
I/ContactLocale( 6405): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  884): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6428 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/BackupManagerService(  884): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  884): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  884): removeObsoleteFile: deleting file=6_task.xml
I/art     (  884): Explicit concurrent mark sweep GC freed 3488(180KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.542ms total 190.013ms
W/asset   ( 6428): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6428): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6428): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6428): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  884): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6449 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  884): Killing 6059:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/Launcher( 1573): Deferring update until onResume
D/AndroidRuntime( 6377): Shutting down VM
W/libprocessgroup(  884): failed to open /acct/uid_10090/pid_6059/cgroup.procs: No such file or directory
W/ContextImpl( 6449): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1954): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1954): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1954): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1954): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1954): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1954): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1954): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/NetworkScheduler.SchedulerReceiver( 1712): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1712): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_MetricsDatabase( 1954): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1954): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1954): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1954): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1954): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1954): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1954): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1954): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1954): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1954): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1954): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  884): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6474 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/ChimeraCfgMgr( 1954): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1954): Module APK com.google.android.play.games already loaded
I/Icing   ( 1954): doRemovePackageData com.test.thalitest
W/Launcher( 1573): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@de1162e new=com.google.android.velvet.VelvetApplication@de1162e
I/ActivityManager(  884): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6499 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  884): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6527 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
I/art     (  330): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 333us total 28.830ms

```
