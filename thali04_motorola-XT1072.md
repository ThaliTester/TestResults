#### Test 6122644500803c8_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,D/AndroidRuntime( 5115): 
D/AndroidRuntime( 5115): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5115): CheckJNI is OFF
D/AndroidRuntime( 5115): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  880): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  880): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5134 uid=10534 gids={50534, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5115): Shutting down VM
V/ActivityManager(  880): Display changed displayId=0
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5134): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5134): Time to load native libraries: 3 ms (timestamps 7451-7454)
I/LibraryLoader( 5134): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5134): Binding Chromium to main looper Looper (main, tid 1) {bbae7f3}
,I/LibraryLoader( 5134): Expected native library version number "",actual native library version number ""
,I/chromium( 5134): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5134): Initializing chromium process, singleProcess=true
,W/art     ( 5134): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5134): ApplicationContext is null in ApplicationStatus
,W/chromium( 5134): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5134): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5134): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5134): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5134): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5134): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5134): Local Branch: 
I/Adreno-EGL( 5134): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5134): Local Patches: NONE
I/Adreno-EGL( 5134): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  880): Message: 20
D/BluetoothManagerService(  880): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7179feb:true
,D/BluetoothAdapter( 5134): 457389020: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  880): Activity pause timeout for ActivityRecord{1101e7c4 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 5134): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5134): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5134): CordovaWebView is running on device made by: motorola
,W/art     ( 5134): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5134): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5134): Render dirty regions requested: true
,D/Atlas   ( 5134): Validating map...
,W/chromium( 5134): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     (  880): Explicit concurrent mark sweep GC freed 13869(683KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.556ms total 113.895ms
,I/OpenGLRenderer( 5134): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5134): Enabling debug mode 0
,I/Keyboard.Facilitator( 1404): onFinishInput()
,I/LaunchCheckinHandler(  880): Displayed com.test.thalitest/.MainActivity,cp,ca,1081
I/ActivityManager(  880): Displayed com.test.thalitest/.MainActivity: +996ms (total +1s82ms)
,W/IInputConnectionWrapper( 5134): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5134): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5134): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5134): Cannot call determinedVisibility() - never saw a connection for the pid: 5134
,D/JsMessageQueue( 5134): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5134): JniHelper::setJavaVM(0xb75a5310), pthread_self() = -1215056920
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5134): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5134):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5134):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5134):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5134):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5134): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a3de22f added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5134): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17d2971a added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5134): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  880): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5134): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5134): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5134): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5134): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5134): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5134): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/art     ( 5134): Suspending all threads took: 15.590ms
,W/jxcore-log( 5134): Initializing JXcore engine
W/jxcore-log( 5134): JXcore engine is ready
,I/art     ( 5134): Background sticky concurrent mark sweep GC freed 7073(643KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 17.138ms total 40.983ms
,W/Thread-584( 5184): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10534 path="socket:[6548]" dev="sockfs" ino=6548 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-584( 5184): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10534 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-584( 5184): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10534 path="socket:[6745]" dev="sockfs" ino=6745 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-584( 5184): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10534 path="socket:[23732]" dev="sockfs" ino=23732 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5134): Starting JXcore engine
,W/jxcore-log( 5134): Platform android
W/jxcore-log( 5134): 
,W/jxcore-log( 5134): Process ARCH arm
W/jxcore-log( 5134): 
,I/jxcore-log( 5134): JXcore Cordova bridge is ready!
I/jxcore-log( 5134): 
,W/jxcore-log( 5134): JXcore engine is started
I/org.thaliproject.p2p.ThaliPermissions( 5134): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5134): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5134): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5134): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  880): Killing 4989:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  880): failed to open /acct/uid_10057/pid_4989/cgroup.procs: No such file or directory
,W/PluginManager( 5134): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 36ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1461): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2494): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2494): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2494): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2494): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2494): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2494): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2494): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2494): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5134): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1404): onFinishInput()
,I/SFPerfTracer(  279):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:248 vsyncs) (2:1129)
,D/TaskPersister(  880): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311137, SEQNUM=4360, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10917, POWER_SUPPLY_CHARGE_COUNTER=-1809, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4312291, SEQNUM=4362, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-13120, POWER_SUPPLY_CHARGE_COUNTER=-1881, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1404): run()
I/Keyboard.Facilitator( 1404): flushDynamicLanguageModels()
,I/ConfigService( 1692): onCreate
,I/ConfigService( 1692): onDestroy
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 2494): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2494): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2494): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
,I/ Nonce  ( 2494):  Nonce Reponse 
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
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,V/AlarmManager(  880): send {2854dfa3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  880): send {3d940ea7, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  880): done {3d940ea7, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [19ms]
,V/AlarmManager(  880): done {2854dfa3, *alarm*:android.intent.action.TIME_TICK} [46ms]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,D/MMApiWebService( 2494): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2494): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2494): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2494): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2494): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
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
,I/UsageStatsService(  880): User[0] Flushing usage stats to disk
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
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311868, SEQNUM=4366, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-4722, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=259, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311561, SEQNUM=4368, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-10316, POWER_SUPPLY_CHARGE_COUNTER=-4767, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/ThermalEngine(  308): Sensor:xo_therm_pu2:28000 mC
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  295): NetlinkHandler, power_supply subsys
I/MDMCTBK (  295): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  295): checkDefaultInst, current pid is = 295
I/MDMCTBK (  295): checkDefaultInst, pid match
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  295): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  295): MdmCutbackHndler,Could not open ''
,D/BatteryService(  880): uevent={POWER_SUPPLY_TEMP=258, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310977, SEQNUM=4370, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-4807, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,TIME-OUT KILL (timeout was 1200000ms)
```
