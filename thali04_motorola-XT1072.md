#### Test 568182548138a64_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,E/global frequency( 2567): no tags to log
D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
I/art     ( 1474): Explicit concurrent mark sweep GC freed 56791(3MB) AllocSpace objects, 36(1259KB) LOS objects, 39% free, 7MB/12MB, paused 4.079ms total 90.757ms
I/art     (  881): Explicit concurrent mark sweep GC freed 26229(1319KB) AllocSpace objects, 2(221KB) LOS objects, 33% free, 20MB/30MB, paused 1.876ms total 121.268ms
D/AndroidRuntime( 6501): 
D/AndroidRuntime( 6501): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6501): CheckJNI is OFF
D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/AndroidRuntime( 6501): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/art     ( 1474): Explicit concurrent mark sweep GC freed 4155(173KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 711us total 28.449ms
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6525 uid=10474 gids={50474, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 6501): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     ( 2567): Explicit concurrent mark sweep GC freed 27390(1568KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 11MB/18MB, paused 1.527ms total 71.796ms
D/BSUtils ( 2567): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
I/global frequency( 2567): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
E/global frequency( 2567): BcsDSCheckin.logProperties: BL State from property is null or empty
D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
D/Checkin ( 2567): publish the event [tag = DEV_ATTRIBS event name = SW]
D/Checkin ( 2567): publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,I/global frequency( 2567): BcsDSCheckin.events found events 111
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/WebViewFactory( 6525): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6525): Time to load native libraries: 2 ms (timestamps 5356-5358)
,I/LibraryLoader( 6525): Expected native library version number "",actual native library version number ""
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,V/WebViewChromiumFactoryProvider( 6525): Binding Chromium to main looper Looper (main, tid 1) {19f1e4ad}
I/LibraryLoader( 6525): Expected native library version number "",actual native library version number ""
I/chromium( 6525): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,D/MMApiWebService( 2567): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/BrowserStartupController( 6525): Initializing chromium process, singleProcess=true
,W/art     ( 6525): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6525): ApplicationContext is null in ApplicationStatus
,W/chromium( 6525): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6525): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6525): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6525): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6525): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6525): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6525): Local Branch: 
I/Adreno-EGL( 6525): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6525): Local Patches: NONE
I/Adreno-EGL( 6525): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,I/MMApiWSBase( 2567): doRequest(): url: https://argo.svcmot.com:443/v1/cs/checkin.pb/2072049230914535424?appId=6R1TANEX3ZMQ6EU1UH43P34C8B868KTE
D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {24f4e12, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {24f4e12, *walarm*:com.google.android.intent.action.SEND_IDLE} [14ms]
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6bdefe0:true
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [38ms]
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{154891dc u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6525): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6525): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6525): CordovaWebView is running on device made by: motorola
,W/art     ( 6525): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6525): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6525): Render dirty regions requested: true
,D/Atlas   ( 6525): Validating map...
,W/chromium( 6525): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/PhenotypeConfigurator( 1745): Scheduling Phenotype for one-off execution 10324 seconds from now (1453416076873)
,D/GetConfigurationSnapshotOperation( 1745): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     (  881): Explicit concurrent mark sweep GC freed 12256(841KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.485ms total 112.931ms
,I/OpenGLRenderer( 6525): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6525): Enabling debug mode 0
,I/Keyboard.Facilitator( 1416): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1124
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +1s39ms (total +1s124ms)
,W/IInputConnectionWrapper( 6525): showStatusIcon on inactive InputConnection
,I/PhenotypeFlagCommitter( 1745): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1745): Using platform SSLCertificateSocketFactory
,E/Adreno-ES20( 6525): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6525): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6525): Cannot call determinedVisibility() - never saw a connection for the pid: 6525
,D/JsMessageQueue( 6525): Set native->JS mode to OnlineEventsBridgeMode
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:31000 mC
,D/jxcore_app_log( 6525): JniHelper::setJavaVM(0xb7f4a310), pthread_self() = -1204975280
,I/chromium( 6525): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/MMApiWSBase( 2567): doRequest(): v1/cs/checkin resp length: 4
,D/CCE     ( 2567): AppWSProxy - handleResponse(): error=None errorText= statusCode=200 reqId=
,D/CCE     ( 2567): AppWSProxy - sendAIDLWSResponse() sending reponse
I/global frequency( 2567): BcsCore.status() called with error code=ERROR_OK
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/CheckinProvider(  881): 111 events delete 0 left
,I/global frequency( 2567): BcsDSCheckin.events found events 0
,D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2567): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2567): BcsTimer.onReceive checkin completed (0:ERROR_OK)
D/Checkin ( 2567): publish the event [tag = MOT_CHECKIN event name = LOG]
,W/DataUsage( 2567): invalid counter update blocked: 'err' by 0
,D/Checkin ( 2567): publish the event [tag = MOT_CCE event name = LOG]
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/jxcore-log( 6525): Initializing JXcore engine
W/jxcore-log( 6525): JXcore engine is ready
,W/Thread-777( 6592): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10474 path="socket:[6608]" dev="sockfs" ino=6608 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-777( 6592): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10474 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-777( 6592): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10474 path="socket:[7560]" dev="sockfs" ino=7560 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-777( 6592): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10474 path="socket:[27397]" dev="sockfs" ino=27397 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6525): Starting JXcore engine
,W/jxcore-log( 6525): Platform android
W/jxcore-log( 6525): 
,W/jxcore-log( 6525): Process ARCH arm
W/jxcore-log( 6525): 
,I/jxcore-log( 6525): JXcore Cordova bridge is ready!
I/jxcore-log( 6525): 
W/jxcore-log( 6525): JXcore engine is started
,E/jxcore  ( 6525): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6525): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6525): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
,I/ActivityManager(  881): Killing 6285:com.google.android.videos/u0a98 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10098/pid_6285/cgroup.procs: No such file or directory
W/PluginManager( 6525): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2567): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2567): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2567): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2567): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2567): publish the event [tag = MOT_OTA event name = LOG]
,I/Keyboard.Facilitator( 1416): onFinishInput()
,W/IInputConnectionWrapper( 6525): showStatusIcon on inactive InputConnection
,D/TaskPersister(  881): removeObsoleteFile: deleting file=5_task.xml
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:31000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=276, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311901, SEQNUM=4431, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-5909, POWER_SUPPLY_CHARGE_COUNTER=-464, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2419): Disconnected process message: 10, size: 0
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2419): Disconnected process message: 10, size: 0
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {170e4b1f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [83ms]
,V/AlarmManager(  881): done {170e4b1f, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [85ms]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1416): run()
I/Keyboard.Facilitator( 1416): flushDynamicLanguageModels()
,I/ConfigService( 1745): onCreate
,I/ConfigService( 1745): onDestroy
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311776, SEQNUM=4433, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-636, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2419): Disconnected process message: 10, size: 0
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ClearcutLoggerApiImpl( 1745): disconnect managed GoogleApiClient
,D/MDMCTBK (  309): reply_len: 40 reply is = IFNAME=wlan0 <3>CTRL-EVENT-BSS-REMOVED 5
D/MDMCTBK (  309): Event received = CTRL-EVENT-BSS-REMOVED 5
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {a567a3b, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {a567a3b, *walarm*:android.content.syncmanager.SYNC_ALARM} [12ms]
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [41ms]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {4b23558, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,I/ActivityManager(  881): Start proc com.google.android.deskclock for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider: pid=6626 uid=10055 gids={50055, 9997, 3003, 1028} abi=armeabi-v7a
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [96ms]
,I/GAv4    ( 6626): Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6626):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6626):   adb logcat -s GAv4
,W/GAv4    ( 6626): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6626): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6626): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,V/AlarmManager(  881): done {4b23558, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [324ms]
,I/ActivityManager(  881): Killing 5803:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_5803/cgroup.procs: No such file or directory
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {3936a117, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): send {2631b6b1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  881): done {3936a117, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [21ms]
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [42ms]
,V/AlarmManager(  881): done {2631b6b1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [60ms]
,I/EventLogService( 6139): Aggregate from 1453415992418 (log), 1453414850989 (data)
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312226, SEQNUM=4439, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-1776, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2419): Disconnected process message: 10, size: 0
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {335e722, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM}
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [41ms]
,V/AlarmManager(  881): done {335e722, *walarm*:com.google.android.gms.gcm.HEARTBEAT_ALARM} [94ms]
,I/GoogleURLConnFactory( 1745): Using platform SSLCertificateSocketFactory
,I/PhenotypeConfigurator( 1745): Scheduling Phenotype every 14400 seconds, with flex of 1800 seconds
,E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@26bf5391)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3e12f2f6)
,E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@145c96f7)
I/art     ( 1745): Background sticky concurrent mark sweep GC freed 109663(5MB) AllocSpace objects, 20(343KB) LOS objects, 27% free, 16MB/22MB, paused 5.271ms total 103.030ms
,E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1b75b964)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@16f497cd)
,E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18bfe3c9)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@37916ace)
,E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@20c96def)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@b1cd0fc)
E/DataBuffer( 1745): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21d9f385)
,W/PhenotypeConfigurator( 1745): Server returned 404
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {a567a3b, *walarm*:android.content.syncmanager.SYNC_ALARM}
,V/AlarmManager(  881): done {a567a3b, *walarm*:android.content.syncmanager.SYNC_ALARM} [9ms]
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [45ms]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,V/AlarmManager(  881): send {3aebd30d, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {3e1a6246, *walarm*:com.google.android.gms.reminders.REFRESH_NOTIFICATION}
V/AlarmManager(  881): send {3515c07, *alarm*:com.google.android.calendar.APPWIDGET_SCHEDULED_UPDATE}
,V/AlarmManager(  881): done {3aebd30d, *alarm*:android.intent.action.TIME_TICK} [49ms]
,V/AlarmManager(  881): done {3e1a6246, *walarm*:com.google.android.gms.reminders.REFRESH_NOTIFICATION} [52ms]
,I/ActivityManager(  881): Start proc com.google.android.calendar for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider: pid=6700 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SQLiteLog( 6700): (283) recovered 18 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,I/ActivityManager(  881): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6736 uid=10005 gids={50005, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  329): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.578ms
,W/ResourcesManager( 6736): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 19.852ms
,V/AlarmManager(  881): done {3515c07, *alarm*:com.google.android.calendar.APPWIDGET_SCHEDULED_UPDATE} [397ms]
,I/art     (  329): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 259us total 19.845ms
,I/AnalyticsLogBase( 6700): PlayLogger.onLoggerConnected
,I/ActivityManager(  881): Killing 6333:com.android.vending/u0a32 (adj 13): empty #7
,I/ActivityManager(  881): Killing 6400:com.google.android.music:main/u0a80 (adj 15): empty #8
,W/libprocessgroup(  881): failed to open /acct/uid_10032/pid_6333/cgroup.procs: No such file or directory
,W/libprocessgroup(  881): failed to open /acct/uid_10080/pid_6400/cgroup.procs: No such file or directory
,I/CalendarProvider2( 6736): Created com.android.providers.calendar.CalendarAlarmManager@395120d7(com.android.providers.calendar.CalendarProvider2@1cd6adc4)
,I/CalendarProvider2( 6736): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 6736): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  881): Start proc com.motorola.context for broadcast com.motorola.context/.publisher.calendar.CalendarReceiver: pid=6768 uid=10008 gids={50008, 9997, 3001, 3002, 3003} abi=armeabi-v7a
,W/ResourcesManager( 6768): Asset path '/system/framework/com.motorola.motosignature.jar' does not exist or contains no resources.
,V/AlarmManager(  881): send {1165e8f6, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.MidnightAlarmTrigger}
V/AlarmManager(  881): send {19a354f7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR}
,V/AlarmManager(  881): done {1165e8f6, *alarm*:com.motorola.motocare.trigger.AlarmTrigger.MidnightAlarmTrigger} [3ms]
,V/AlarmManager(  881): done {19a354f7, *alarm*:com.android.deskclock.ON_QUARTER_HOUR} [9ms]
,I/ActivityManager(  881): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.MailProvider: pid=6795 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,E/MC_BatteryHealthAction( 2971): Invalid cycle_count 0
E/MC_MmcStatsAction( 2971): Unable to find mmc block stat files.
W/System.err( 2971): java.io.FileNotFoundException: /sys/block/mmcblk1/stat: open failed: ENOENT (No such file or directory)
,W/System.err( 2971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 2971): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 2971): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
W/System.err( 2971): 	at java.io.FileReader.<init>(FileReader.java:66)
W/System.err( 2971): 	at com.motorola.motocare.action.MmcStatsAction.readMmcSectorWrites(MmcStatsAction.java:87)
W/System.err( 2971): 	at com.motorola.motocare.action.MmcStatsAction.appendMmcStatsReport(MmcStatsAction.java:70)
W/System.err( 2971): 	at com.motorola.motocare.action.MmcStatsAction.onReceiveImpl(MmcStatsAction.java:49)
W/System.err( 2971): 	at com.motorola.motocare.util.BackgroundReceiver$1.run(BackgroundReceiver.java:14)
,W/System.err( 2971): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 2971): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2971): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 2971): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2971): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 2971): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 2971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 2971): 	... 11 more
,I/Gmail   ( 6795): getAccountsCursor
,D/ActivityThread( 6795): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,I/ActivityManager(  881): Start proc com.google.android.gm.exchange for service com.google.android.gm.exchange/com.android.exchange.service.EasService: pid=6819 uid=10060 gids={50060, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  881): Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6833 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6795): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/SQLiteLog( 6795): (283) recovered 46 frames from WAL file /data/user/0/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/Exchange( 6819): EasService.onCreate
W/ActivityManager(  881): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6795): getAccountsCursor
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Exchange( 6819): RestartPingTask
,I/Exchange( 6819): RestartPingsTask did not start any pings.
I/Exchange( 6819): PSS stopIfIdle
I/Exchange( 6819): PSS has no active accounts; stopping service.
,I/Exchange( 6819): onDestroy
,I/ActivityManager(  881): Killing 6525:com.test.thalitest/u0a474 (adj 15): empty #7
,I/art     (  881): Explicit concurrent mark sweep GC freed 24130(1303KB) AllocSpace objects, 10(257KB) LOS objects, 33% free, 20MB/30MB, paused 2.488ms total 149.375ms
,I/Gmail   ( 6795): notifyAccountChanged
,I/Gmail   ( 6795): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6795): Observing account changes for notifications
I/Gmail   ( 6795): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6795): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6795): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/libprocessgroup(  881): failed to kill 1 processes for processgroup 6525
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  881): Killing 6139:com.google.android.gms/u0a16 (adj 15): empty #7
,E/ActivityThread( 1474): Failed to find provider info for com.android.email.provider
W/ContextImpl( 1474): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.internal.SmsCallsAction.onReceiveImpl:64 com.motorola.motocare.internal.SmsCallsAction.access$000:21 
,W/libprocessgroup(  881): failed to open /acct/uid_10016/pid_6139/cgroup.procs: No such file or directory
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6795): getAccountsCursor
,I/Gmail   ( 6795): getAccountsCursor
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310876, SEQNUM=4458, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-96, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,D/HeadsetStateMachine( 2419): Disconnected process message: 10, size: 0
,D/HeadsetStateMachine( 2419): Disconnected process message: 10, size: 0
,W/ContextImpl( 6700): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:538 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,I/ActivityManager(  881): Start proc com.google.android.gms for service com.google.android.gms/.analytics.service.AnalyticsService: pid=6902 uid=10016 gids={50016, 9997, 3003, 1028, 1015, 3002, 3001, 1005, 1007, 3007, 2001, 3006} abi=armeabi-v7a
,I/GAV2    ( 6700): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 6902): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6902): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6902): VM with version 2.1.0 has multidex support
I/MultiDex( 6902): install
I/MultiDex( 6902): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6902): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6902): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6902): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b905a1c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6902): Installed default security provider GmsCore_OpenSSL
,I/GAv4-SVC( 6902): Google Analytics 8.4.89 is starting up.
,D/WearableService( 1745): callingUid 10016, callindPid: 1745
,E/MDM     ( 1745): [168] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6902): Restart initialization of location
,D/AuthorizationBluetoothService( 1745): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1745): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 6902): Install completed successfully. count=14 extracted=0
,I/art     ( 6902): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6902): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  881): Start proc android.process.acore for content provider com.android.providers.contacts/.ContactsProvider2: pid=6951 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,W/GCoreFlp( 1745): No location to return for getLastLocation()
,W/FusedLocationProvider( 1745): location=null
,I/ContactLocale( 6951): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,I/ActivityManager(  881): Killing 6768:com.motorola.context/u0a8 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10008/pid_6768/cgroup.procs: No such file or directory
,W/IcingInternalCorpora( 6902): getNumBytesRead when not calculated.
,I/ActivityManager(  881): Killing 6736:com.android.providers.calendar/u0a5 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10005/pid_6736/cgroup.procs: No such file or directory
,I/GAV2    ( 6795): Thread[GAThread,5,main]: No campaign data found.
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  881): Killing 6700:com.google.android.calendar/u0a49 (adj 15): empty #7
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,W/libprocessgroup(  881): failed to open /acct/uid_10049/pid_6700/cgroup.procs: No such file or directory
,D/Checkin (  881): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
D/Checkin (  881): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
D/Checkin (  881): publish the event [tag = MOT_APP_STATS event name = APPLAUNCH]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ActivityManager(  881): Killing 6626:com.google.android.deskclock/u0a55 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10055/pid_6626/cgroup.procs: No such file or directory
,D/Checkin ( 2971): publish the event [tag = DEVICE_AUTH_STATS_L2 event name = DeviceLockStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = CpuFreq]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = BattCap]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L2 event name = DC_SDCARD]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = ChargerTrigger]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengths]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = DataSizesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = RadioTypesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = SignalStrengthsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PhoneTimeStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_CHG event name = PerUidStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = DataSizes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypes]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengths]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = DataSizesSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypesSOn]
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengthsSOn]
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStatsSOn]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = DataSizesSOff]
D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = RadioTypesSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = SignalStrengthsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = PhoneTimeStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = PerUidStatsSOff]
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L1 event name = DC_ACCOUNT]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L1 event name = DC_SIGNALSTRENGTH]
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L1 event name = DC_BATTERY]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = EventLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L2 event name = EventLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L2 event name = DC_PKG]
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,E/MC_Serializer( 2971): Exception in deSerializeObject s=rO0ABXcEAAAAAXNyABFqYXZhLnV0aWwuSGFzaE1hcAUH2sHDFmDRAwABRgAKbG9hZEZhY3RvcnhwP0AAAHcIAAABAAAAAHJ0AAR3bGFuc3IAUWNvbS5tb3Rvcm9sYS5tb3RvY2FyZS5pbnRlcm5hbC53YWtlbG9ja3MuS2VybmVsV2FrZWxvY2tBY3Rpb24kS2VybmVsV2FrZWxvY2tFbnRyeQAAAAAAAAABAgAFSgAObUFjdGl2ZVNpbmNlTXNKAAZtQ291bnRKAAttRHVyYXRpb25Nc0oADW1MYXN0Q2hhbmdlTXNMAAVtTmFtZXQAEkxqYXZhL2xhbmcvU3RyaW5nO3hwAAAAAAAAAAAAAAAAAAAAEwAAAAAAACynAAAAAAACzP5xAH4AAnQAEnN0a19pbnB1dF93YWtlbG9ja3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQHcQB+AAZ0AAlwaWwtbW9kZW1zcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACKHEAfgAIdAAaaXBjMDAwMDAwNTRfTG9jX2hhbF93b3JrZXJzcQB+AAMAAAAAAAAAAAAAAAAAAAAmAAAAAAAAABMAAAAAAALZnHEAfgAKdAAObXNtX2hzdXNiX2hvc3RzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHIXEAfgAMdAALZXZlbnQxMC04ODNzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACNGXEAfgAOdAASc3luYXB0aWNzX2Z3X2ZsYXNoc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA+txAH4AEHQAGmlwYzAwMDAwMDUzX0xvY19oYWxfd29ya2Vyc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAlbNxAH4AEnQABnZpZGVvMXNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAABygAAAAAAAJ1/cQB+ABR0ABVxcG5wLWNoYXJnZXItZTQ5ZTVhMDBzcQB+AAMAAAAAAAAAqAAAAAAAAAACAAAAAAACwuoAAAAAAALZ9nEAfgAWdAAJcGlsLXdjbnNzc3EAfgADAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAF+AAAAAAAAHkRxAH4AGHQAD3FtdXhkX3BvcnRfd2xfN3NxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAQAAAAAAANutcQB+ABp0ABppcGMwMDAwMDAwN190aGVybWFsLWVuZ2luZXNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABjjcQB+ABx0ABppcGMwMDAwMDA1OV9Mb2NfaGFsX3dvcmtlcnNxAH4AAwAAAAAAAAAAAAAAAAAAABAAAAAAAAAAXQAAAAAAAoO7cQB+AB50ABdpcGMwMDAwMDAwYl90aW1lX2RhZW1vbnNxAH4AAwAAAAAAAAAAAAAAAAAAACgAAAAAAAAABgAAAAAAAoO8cQB+ACB0AAttbWMxX2RldGVjdHNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAABNgAAAAAAAAZYcQB+ACJ0ABtpcGMwMDAwMDAyNV9xbWlfbW90ZXh0X2hvb2tzcQB+AAMAAAAAAAAAAAAAAAAAAAAFAAAAAAAAAAAAAAAAAALBb3EAfgAkdAAaaXBjMDAwMDAwMTZfdGhlcm1hbC1lbmdpbmVzcQB+AAMAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAAAAAAAAAKDu3EAfgAmdAASaXBjX3J0cl9zbWRfaXBjcnRyc3EAfgADAAAAAAAAAAAAAAAAAAAAVQAAAAAAAAACAAAAAAAC2ZxxAH4AKHQAF2lwYzAwMDAwMDA2X3JtdF9zdG9yYWdlc3EAfgADAAAAAAAAAAAAAAAAAAAAJgAAAAAAAAOXAAAAAAACg7txAH4AKnQAB0RJQUdfV1NzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADB3EAfgAsdAAKZXZlbnQ5LTg4M3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAI0tcQB+AC50AAYyLTAwNDhzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEB3EAfgAwdAAMZ3Bpb19rZXlzLjc1c3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAByRxAH4AMnQACHNtZGNudGwzc3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAAAAAAAAAAA25BxAH4ANHQAFXFjcmlsX3ByZV9jbGllbnRfaW5pdHNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAAPcAAAAAAAACrScQB+ADZ0ABtTTURfVFRZX0FQUFNfUklWQV9CVF9DTURfUkFzcQB+AAMAAAAAAAAAAAAAAAAAAAA+AAAAAAAAAAEAAAAAAAD0f3EAfgA4dAAKZXZlbnQ3LTg4M3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAI02cQB+ADp0AAxwb3dlci1zdXBwbHlzcQB+AAMAAAAAAAAAAAAAAAAAAAAuAAAAAAAAD9cAAAAAAALadHEAfgA8dAAQaXBjMDAwMDAwMGRfcmlsZHNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABswcQB+AD50AAhzbWRjbnRsNHNxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAQAAAAAAANuWcQB+AEB0ABFxcG5wLWJtcy1lNDllNWMwMHNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAWIcQB+AEJ0AAZ2aWRlbzJzcQB+AAMAAAAAAAAAAAAAAAAAAAABAAAAAAAAAHcAAAAAAACek3EAfgBEdAAIc21kY250bDJzcQB+AAMAAAAAAAAAAAAAAAAAAAALAAAAAAAAAAEAAAAAAADbiXEAfgBGdAAXaXBjMDAwMDAwMGNfdGltZV9kYWVtb25zcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAZFnEAfgBIdAAIc21kY250bDBzcQB+AAMAAAAAAAAAAAAAAAAAAAD7AAAAAAAAAB4AAAAAAADbfHEAfgBKdAAKZXZlbnQ0LTg4M3NxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAsIicQB+AEx0ABppcGMwMDAwMDA1NV9Mb2NfaGFsX3dvcmtlcnNxAH4AAwAAAAAAAAAAAAAAAAAAABAAAAAAAAAAXQAAAAAAAoO7cQB+AE50ABdybXRfc3RvcmFnZV8tMTE5NzgzMjkwNHNxAH4AAwAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAbQAAAAAAAoO4cQB+AFB0ABppcGMwMDAwMDAxNF90aGVybWFsLWVuZ2luZXNxAH4AAwAAAAAAAAAAAAAAAAAAABQAAAAAAAAAAAAAAAAAAoO7cQB+AFJ0AA1zbXNtX3NuYXBzaG90c3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAAGAAAAAAAAOilxAH4AVHQAG1Bvd2VyTWFuYWdlclNlcnZpY2UuRGlzcGxheXNxAH4AAwAAAAAAABlcAAAAAAAAAAIAAAAAAAJmnQAAAAAAAsFBcQB+AFZ0AARxbWkxc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAi9xAH4AWHQADXFwbnBfc29jX3dha2VzcQB+AAMAAAAAAAAAcgAAAAAAAAAXAAAAAAAACqQAAAAAAALaLHEAfgBadAARcXBucC1ydGMtZTRhMzBlMDBzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
,E/MC_Serializer( 2971): Exception in deSerializeObject s=rO0ABXcEAAAAAXNyABFqYXZhLnV0aWwuSGFzaE1hcAUH2sHDFmDRAwABRgAKbG9hZEZhY3RvcnhwP0AAAHcIAAABAAAAAHJ0AAR3bGFuc3IAUWNvbS5tb3Rvcm9sYS5tb3RvY2FyZS5pbnRlcm5hbC53YWtlbG9ja3MuS2VybmVsV2FrZWxvY2tBY3Rpb24kS2VybmVsV2FrZWxvY2tFbnRyeQAAAAAAAAABAgAFSgAObUFjdGl2ZVNpbmNlTXNKAAZtQ291bnRKAAttRHVyYXRpb25Nc0oADW1MYXN0Q2hhbmdlTXNMAAVtTmFtZXQAEkxqYXZhL2xhbmcvU3RyaW5nO3hwAAAAAAAAAAAAAAAAAAAAEwAAAAAAACynAAAAAAACzP5xAH4AAnQAEnN0a19pbnB1dF93YWtlbG9ja3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQHcQB+AAZ0AAlwaWwtbW9kZW1zcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACKHEAfgAIdAAaaXBjMDAwMDAwNTRfTG9jX2hhbF93b3JrZXJzcQB+AAMAAAAAAAAAAAAAAAAAAAAmAAAAAAAAABMAAAAAAALZnHEAfgAKdAAObXNtX2hzdXNiX2hvc3RzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAHIXEAfgAMdAALZXZlbnQxMC04ODNzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACNGXEAfgAOdAASc3luYXB0aWNzX2Z3X2ZsYXNoc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA+txAH4AEHQAGmlwYzAwMDAwMDUzX0xvY19oYWxfd29ya2Vyc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAlbNxAH4AEnQABnZpZGVvMXNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAABygAAAAAAAJ1/cQB+ABR0ABVxcG5wLWNoYXJnZXItZTQ5ZTVhMDBzcQB+AAMAAAAAAAAA+AAAAAAAAAACAAAAAAACwzsAAAAAAALZ9nEAfgAWdAAJcGlsLXdjbnNzc3EAfgADAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAF+AAAAAAAAHkRxAH4AGHQAD3FtdXhkX3BvcnRfd2xfN3NxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAQAAAAAAANutcQB+ABp0ABppcGMwMDAwMDAwN190aGVybWFsLWVuZ2luZXNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABjjcQB+ABx0ABppcGMwMDAwMDA1OV9Mb2NfaGFsX3dvcmtlcnNxAH4AAwAAAAAAAAAAAAAAAAAAABAAAAAAAAAAXQAAAAAAAoO7cQB+AB50ABdpcGMwMDAwMDAwYl90aW1lX2RhZW1vbnNxAH4AAwAAAAAAAAAAAAAAAAAAACgAAAAAAAAABgAAAAAAAoO8cQB+ACB0AAttbWMxX2RldGVjdHNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAABNgAAAAAAAAZYcQB+ACJ0ABtpcGMwMDAwMDAyNV9xbWlfbW90ZXh0X2hvb2tzcQB+AAMAAAAAAAAAAAAAAAAAAAAFAAAAAAAAAAAAAAAAAALBb3EAfgAkdAAaaXBjMDAwMDAwMTZfdGhlcm1hbC1lbmdpbmVzcQB+AAMAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAAAAAAAAAKDu3EAfgAmdAASaXBjX3J0cl9zbWRfaXBjcnRyc3EAfgADAAAAAAAAAAAAAAAAAAAAVQAAAAAAAAACAAAAAAAC2ZxxAH4AKHQAF2lwYzAwMDAwMDA2X3JtdF9zdG9yYWdlc3EAfgADAAAAAAAAAAAAAAAAAAAAJgAAAAAAAAOXAAAAAAACg7txAH4AKnQAB0RJQUdfV1NzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADB3EAfgAsdAAKZXZlbnQ5LTg4M3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAI0tcQB+AC50AAYyLTAwNDhzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAEB3EAfgAwdAAMZ3Bpb19rZXlzLjc1c3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAByRxAH4AMnQACHNtZGNudGwzc3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAAAAAAAAAAA25BxAH4ANHQAFXFjcmlsX3ByZV9jbGllbnRfaW5pdHNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAAPcAAAAAAAACrScQB+ADZ0ABtTTURfVFRZX0FQUFNfUklWQV9CVF9DTURfUkFzcQB+AAMAAAAAAAAAAAAAAAAAAAA+AAAAAAAAAAEAAAAAAAD0f3EAfgA4dAAKZXZlbnQ3LTg4M3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAI02cQB+ADp0AAxwb3dlci1zdXBwbHlzcQB+AAMAAAAAAAAAAAAAAAAAAAAuAAAAAAAAED8AAAAAAALa6XEAfgA8dAAQaXBjMDAwMDAwMGRfcmlsZHNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABswcQB+AD50AAhzbWRjbnRsNHNxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAQAAAAAAANuWcQB+AEB0ABFxcG5wLWJtcy1lNDllNWMwMHNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAWIcQB+AEJ0AAZ2aWRlbzJzcQB+AAMAAAAAAAAAAAAAAAAAAAABAAAAAAAAAHcAAAAAAACek3EAfgBEdAAIc21kY250bDJzcQB+AAMAAAAAAAAAAAAAAAAAAAALAAAAAAAAAAEAAAAAAADbiXEAfgBGdAAXaXBjMDAwMDAwMGNfdGltZV9kYWVtb25zcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAZFnEAfgBIdAAIc21kY250bDBzcQB+AAMAAAAAAAAAAAAAAAAAAAD7AAAAAAAAAB4AAAAAAADbfHEAfgBKdAAKZXZlbnQ0LTg4M3NxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAsIicQB+AEx0ABppcGMwMDAwMDA1NV9Mb2NfaGFsX3dvcmtlcnNxAH4AAwAAAAAAAAAAAAAAAAAAABAAAAAAAAAAXQAAAAAAAoO7cQB+AE50ABdybXRfc3RvcmFnZV8tMTE5NzgzMjkwNHNxAH4AAwAAAAAAAAAAAAAAAAAAAAIAAAAAAAAAbQAAAAAAAoO4cQB+AFB0ABppcGMwMDAwMDAxNF90aGVybWFsLWVuZ2luZXNxAH4AAwAAAAAAAAAAAAAAAAAAABQAAAAAAAAAAAAAAAAAAoO7cQB+AFJ0AA1zbXNtX3NuYXBzaG90c3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAAGAAAAAAAAOilxAH4AVHQAG1Bvd2VyTWFuYWdlclNlcnZpY2UuRGlzcGxheXNxAH4AAwAAAAAAABmtAAAAAAAAAAIAAAAAAAJm7gAAAAAAAsFBcQB+AFZ0AARxbWkxc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAi9xAH4AWHQADXFwbnBfc29jX3dha2VzcQB+AAMAAAAAAAAAwgAAAAAAAAAXAAAAAAAACvQAAAAAAALaLHEAfgBadAARcXBucC1ydGMtZTRhMzBlMDBzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,E/MC_Serializer( 2971): Exception in deSerializeObject s=rO0ABXcEAAAAAXNyABFqYXZhLnV0aWwuSGFzaE1hcAUH2sHDFmDRAwABRgAKbG9hZEZhY3RvcnhwP0AAAHcIAAABAAAAAHJ0AAR3bGFuc3IAUWNvbS5tb3Rvcm9sYS5tb3RvY2FyZS5pbnRlcm5hbC53YWtlbG9ja3MuS2VybmVsV2FrZWxvY2tBY3Rpb24kS2VybmVsV2FrZWxvY2tFbnRyeQAAAAAAAAABAgAFSgAObUFjdGl2ZVNpbmNlTXNKAAZtQ291bnRKAAttRHVyYXRpb25Nc0oADW1MYXN0Q2hhbmdlTXNMAAVtTmFtZXQAEkxqYXZhL2xhbmcvU3RyaW5nO3hwAAAAAAAAAAIAAAAAAAAAEgAAAAAAACeiAAAAAAEPynNxAH4AAnQAEnN0a19pbnB1dF93YWtlbG9ja3NxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQRcQB+AAZ0AApldmVudDQtODgwc3EAfgADAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAAAAAAAAAEPxJZxAH4ACHQACXBpbC1tb2RlbXNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAIycQB+AAp0ABppcGMwMDAwMDA1NF9Mb2NfaGFsX3dvcmtlcnNxAH4AAwAAAAAAAAAAAAAAAAAAACIAAAAAAAAABQAAAAABD8PDcQB+AAx0AA5tc21faHN1c2JfaG9zdHNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAdOcQB+AA50ABppcGMwMDAwMDAxOF90aGVybWFsLWVuZ2luZXNxAH4AAwAAAAAAAAAAAAAAAAAAABQAAAAAAAAAAAAAAAAAAoZccQB+ABB0ABJzeW5hcHRpY3NfZndfZmxhc2hzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAD9XEAfgASdAAaaXBjMDAwMDAwNTNfTG9jX2hhbF93b3JrZXJzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACWznEAfgAUdAAGdmlkZW8xc3EAfgADAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAG+AAAAAAAAnvRxAH4AFnQAFXFwbnAtY2hhcmdlci1lNDllNWEwMHNxAH4AAwAAAAABD8UNAAAAAAAAAAEAAAAAAQ/FDQAAAAAAAAVrcQB+ABh0AAlwaWwtd2Nuc3NzcQB+AAMAAAAAAAAAAAAAAAAAAAABAAAAAAAAAYQAAAAAAAAeaHEAfgAadAAaaXBjMDAwMDAwMTdfdGhlcm1hbC1lbmdpbmVzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAqwHEAfgAcdAAPcW11eGRfcG9ydF93bF83c3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAABAAAAAAAA5VlxAH4AHnQAGmlwYzAwMDAwMDU5X0xvY19oYWxfd29ya2Vyc3EAfgADAAAAAAAAAAAAAAAAAAAAFAAAAAAAAAAEAAAAAAAChl1xAH4AIHQAF2lwYzAwMDAwMDBiX3RpbWVfZGFlbW9uc3EAfgADAAAAAAAAAAAAAAAAAAAAJQAAAAAAAAAMAAAAAAAChl1xAH4AInQAC21tYzFfZGV0ZWN0c3EAfgADAAAAAAAAAAAAAAAAAAAAAQAAAAAAAAE2AAAAAAAABmJxAH4AJHQACmV2ZW50OS04ODBzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACOTXEAfgAmdAAaaXBjMDAwMDAwMTZfdGhlcm1hbC1lbmdpbmVzcQB+AAMAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAAAAAAAAAKGXHEAfgAodAASaXBjX3J0cl9zbWRfaXBjcnRyc3EAfgADAAAAAAAAAAAAAAAAAAAAUQAAAAAAAAACAAAAAAEPw95xAH4AKnQAF2lwYzAwMDAwMDA2X3JtdF9zdG9yYWdlc3EAfgADAAAAAAAAAAAAAAAAAAAAJQAAAAAAAAOXAAAAAAAChl1xAH4ALHQAB0RJQUdfV1NzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADEXEAfgAudAAGMi0wMDQ4c3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABBFxAH4AMHQADGdwaW9fa2V5cy43NXNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAdScQB+ADJ0AAhzbWRjbnRsM3NxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAQAAAAAAAOU5cQB+ADR0ABdpcGMwMDAwMDAwMV9rd29ya2VyLzE6MXNxAH4AAwAAAAAAAAAAAAAAAAAAAAcAAAAAAAAAAAAAAAAAAQJccQB+ADZ0ABVxY3JpbF9wcmVfY2xpZW50X2luaXRzcQB+AAMAAAAAAAAAAAAAAAAAAAABAAAAAAAAD1MAAAAAAAAq8XEAfgA4dAALZXZlbnQxMC04ODBzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACONnEAfgA6dAAbU01EX1RUWV9BUFBTX1JJVkFfQlRfQ01EX1JBc3EAfgADAAAAAAAAAAAAAAAAAAAAPgAAAAAAAAABAAAAAAAA/f5xAH4APHQADHBvd2VyLXN1cHBseXNxAH4AAwAAAAAAAAAAAAAAAAAAALkAAAAAAABAIQAAAAABD8OIcQB+AD50ABBpcGMwMDAwMDAwZF9yaWxkc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAG2NxAH4AQHQACHNtZGNudGw0c3EAfgADAAAAAAAAAAAAAAAAAAAACwAAAAAAAAAAAAAAAAAA5UBxAH4AQnQAEXFwbnAtYm1zLWU0OWU1YzAwc3EAfgADAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABYVxAH4ARHQABnZpZGVvMnNxAH4AAwAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAgwAAAAAAAJ/WcQB+AEZ0AAhzbWRjbnRsMnNxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAAAQAAAAAAAOUxcQB+AEh0ABdpcGMwMDAwMDAwY190aW1lX2RhZW1vbnNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAABmEcQB+AEp0AAhzbWRjbnRsMHNxAH4AAwAAAAAAAAAAAAAAAAAAAPoAAAAAAAAAGgAAAAAAAOUjcQB+AEx0ABtpcGMwMDAwMDAyM19xbWlfbW90ZXh0X2hvb2tzcQB+AAMAAAAAAAAAAAAAAAAAAAAFAAAAAAAAAAAAAAAAAQ/D3nEAfgBOdAAaaXBjMDAwMDAwNTVfTG9jX2hhbF93b3JrZXJzcQB+AAMAAAAAAAAAAAAAAAAAAAAUAAAAAAAAAAMAAAAAAAKGXXEAfgBQdAAaaXBjMDAwMDAwMTRfdGhlcm1hbC1lbmdpbmVzcQB+AAMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAqpnEAfgBSdAANc21zbV9zbmFwc2hvdHNxAH4AAwAAAAAAAAAAAAAAAAAAAAsAAAAAAAAABQAAAAAAADpOcQB+AFR0ABtQb3dlck1hbmFnZXJTZXJ2aWNlLkRpc3BsYXlzcQB+AAMAAAAAAAAGsgAAAAAAAAACAAAAAAACVj8AAAAAAQ/Dw3EAfgBWdAAEcW1pMXNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAI5cQB+AFh0ABFxcG5wLXJ0Yy1lNDlmMGUwMHNxAH4AAwAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAQncQB+AFp0AA1xcG5wX3NvY193YWtlc3EAfgADAAAAAAAAAAA
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,E/MC_Serializer( 2971): Exception in deSerializeObject s=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
E/MC_Serializer( 2971): Exception in deSerializeObject s=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
,D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
D/Checkin ( 2971): publish the event [tag = MOT_CA_STATS_L3 event name = DC_WIFIDRVST]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = MMCStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS event name = MultiUserStats]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_L1 event name = EventLogs]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = DC_MM]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,D/Checkin ( 2971): publish the event [tag = MOT_DEVICE_STATS_MM event name = MediaPlaybackUsage]
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  325): Sensor:xo_therm_pu2:28000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311638, SEQNUM=4466, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-2103, POWER_SUPPLY_CHARGE_COUNTER=-160, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,D/HeadsetStateMachine( 2419): Disconnected process message: 10, size: 0
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6995): 
D/AndroidRuntime( 6995): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6995): CheckJNI is OFF
D/AndroidRuntime( 6995): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10474 user=-1: uninstall pkg
W/PackageSettings(  881): Skipping PackageSetting{3d6e75a com.example.hello/10440} due to missing metadata
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10474 user=0: pkg removed
W/GeofencerStateMachine( 1745): Ignoring removeGeofence because network location is disabled.
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1416): resetDictionaries() : en_US
D/VoicemailCleanupService( 6951): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.DecoderInitializer( 1416): run()
I/Decoder ( 1416): createOrResetDecoder
I/art     ( 2971): Explicit concurrent mark sweep GC freed 73240(3MB) AllocSpace objects, 14(236KB) LOS objects, 39% free, 7MB/12MB, paused 4.346ms total 107.793ms
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=7024 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ConfigService( 1745): onCreate
I/art     ( 1570): Explicit concurrent mark sweep GC freed 4398(279KB) AllocSpace objects, 4(184KB) LOS objects, 24% free, 13MB/17MB, paused 992us total 151.956ms
W/asset   ( 7024): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 7024): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 7024): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7024): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): run()
I/art     (  881): Explicit concurrent mark sweep GC freed 114038(6MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 20MB/30MB, paused 2.146ms total 210.013ms
I/art     (  881): WaitForGcToComplete blocked for 137.151ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1416): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1416): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1416): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1416): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1416): run()
I/StatsUtilsManager( 1416): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1416): shouldRecordStats() = Too Soon
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7050 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 6795:com.google.android.gm/u0a63 (adj 15): empty #7
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     (  881): Explicit concurrent mark sweep GC freed 6952(552KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 1.627ms total 154.199ms
W/libprocessgroup(  881): failed to open /acct/uid_10063/pid_6795/cgroup.procs: No such file or directory
D/TaskPersister(  881): removeObsoleteFile: deleting file=6_task.xml
I/Launcher( 1570): Deferring update until onResume
W/ContextImpl( 7050): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 6902): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 6902): Reading stored module config
D/AccountUtils( 6902): Clearing selected account for com.test.thalitest
D/AndroidRuntime( 6995): Shutting down VM
D/ChimeraCfgMgr( 6902): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 6902): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 6902): Removing dialog suppression flag for package com.test.thalitest
I/GMPM-SVC( 6902): App measurement is starting up, version: 8489
I/GMPM-SVC( 6902): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1745): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/gH_CompatibleDatabase( 6902): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 6902): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 6902): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 6902): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 6902): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 6902): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 6902): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7081 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/gH_CompatibleDatabase( 6902): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 6902): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 6902): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 6902): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 6902): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 6902): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 6902): Using Auth Proxy for data requests.
W/Launcher( 1570): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@ec953cf new=com.google.android.velvet.VelvetApplication@ec953cf
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7102 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
E/SQLiteLog( 6902): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
E/AndroidRuntime( 6902): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 6902): Process: com.google.android.gms, PID: 6902
E/AndroidRuntime( 6902): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6902): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6902): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 6902): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6902): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6902): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 6902): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 6902): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 6902): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 6902): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 6902): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 6902): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6902): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6902): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 6902): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  881): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  881): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  881): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
E/DropBoxManagerService(  881): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  881): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  881): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  881): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  881): 	... 5 more
I/Process ( 6902): Sending signal. PID: 6902 SIG: 9
I/ThermalEngine(  325): Sensor:xo_therm_pu2:29000 mC
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
