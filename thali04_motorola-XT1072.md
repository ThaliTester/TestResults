#### Test 613623661dfc74c_thali04_motorola-XT1072 Logs


```
--------- beginning of main
I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,D/AndroidRuntime( 5994): 
D/AndroidRuntime( 5994): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5994): CheckJNI is OFF
D/AndroidRuntime( 5994): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  882): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  882): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6013 uid=10537 gids={50537, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5994): Shutting down VM
V/ActivityManager(  882): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/WebViewFactory( 6013): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6013): Time to load native libraries: 1 ms (timestamps 7802-7803)
I/LibraryLoader( 6013): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6013): Binding Chromium to main looper Looper (main, tid 1) {23f0c445}
,I/LibraryLoader( 6013): Expected native library version number "",actual native library version number ""
,I/chromium( 6013): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6013): Initializing chromium process, singleProcess=true
W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6013): ApplicationContext is null in ApplicationStatus
,W/chromium( 6013): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 6013): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6013): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6013): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6013): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 6013): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 6013): Build Date: 10/28/14 Tue
I/Adreno-EGL( 6013): Local Branch: 
I/Adreno-EGL( 6013): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 6013): Local Patches: NONE
I/Adreno-EGL( 6013): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  882): Message: 20
D/BluetoothManagerService(  882): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3af3cc27:true
,D/BluetoothAdapter( 6013): 726439764: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  882): Activity pause timeout for ActivityRecord{ad0e710 u0 com.test.thalitest/.MainActivity t6}
,W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6013): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 6013): CordovaWebView is running on device made by: motorola
,W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6013): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6013): Render dirty regions requested: true
,D/Atlas   ( 6013): Validating map...
,W/chromium( 6013): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 6013): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6013): Enabling debug mode 0
,W/IInputConnectionWrapper( 6013): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1407): onFinishInput()
,I/LaunchCheckinHandler(  882): Displayed com.test.thalitest/.MainActivity,cp,ca,876
I/ActivityManager(  882): Displayed com.test.thalitest/.MainActivity: +798ms (total +876ms)
,E/Adreno-ES20( 6013): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 6013): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 6013): Cannot call determinedVisibility() - never saw a connection for the pid: 6013
,D/JsMessageQueue( 6013): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 6013): JniHelper::setJavaVM(0xb88f6310), pthread_self() = -1194808520
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ce2d2a1 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 6013): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Bluetooth MAC address: null
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eae4fb4 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 6013): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  882): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6013): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6013): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): setDiscoveryMode: Discovery mode BLE is supported
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 6013): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 6013): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6013): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 6013): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 6013): Initializing JXcore engine
W/jxcore-log( 6013): JXcore engine is ready
,W/Thread-604( 6063): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10537 path="socket:[9350]" dev="sockfs" ino=9350 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-604( 6063): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10537 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-604( 6063): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10537 path="socket:[7638]" dev="sockfs" ino=7638 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-604( 6063): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10537 path="socket:[22254]" dev="sockfs" ino=22254 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 6013): Starting JXcore engine
,W/jxcore-log( 6013): Platform android
W/jxcore-log( 6013): 
W/jxcore-log( 6013): Process ARCH arm
W/jxcore-log( 6013): 
,I/jxcore-log( 6013): JXcore Cordova bridge is ready!
I/jxcore-log( 6013): 
W/jxcore-log( 6013): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 6013): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 6013): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 6013): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6013): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  882): Killing 5761:com.google.android.apps.docs/u0a57 (adj 15): empty #7
,W/libprocessgroup(  882): failed to open /acct/uid_10057/pid_5761/cgroup.procs: No such file or directory
,W/PluginManager( 6013): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 3163): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 3163): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 3163): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 3163): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 3163): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 3163): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 3163): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 3163): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 6013): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1407): onFinishInput()
,D/TaskPersister(  882): removeObsoleteFile: deleting file=5_task.xml
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1407): run()
I/Keyboard.Facilitator( 1407): flushDynamicLanguageModels()
,I/ConfigService( 1692): onCreate
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ConfigService( 1692): onDestroy
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  299): NetlinkHandler, power_supply subsys
I/MDMCTBK (  299): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  299): checkDefaultInst, current pid is = 299
I/MDMCTBK (  299): checkDefaultInst, pid match
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  299): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  299): MdmCutbackHndler,Could not open ''
,D/BatteryService(  882): uevent={POWER_SUPPLY_TEMP=268, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311455, SEQNUM=4559, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-1105, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 3163): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 3163): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 3163): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 3163): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 3163):  Nonce Reponse 
I/MMApiWebService( 3163): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 3163): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 3163): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 3163): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 3163): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 3163): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 3163): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 3163): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 3163): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 3163): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 3163): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 3163): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 3163): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,V/AlarmManager(  882): send {150e0afb, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  882): send {2dfb0d0, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  882): done {2dfb0d0, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [9ms]
,V/AlarmManager(  882): done {150e0afb, *alarm*:android.intent.action.TIME_TICK} [54ms]
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/MMApiBackOffService( 3163): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 3163): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 3163): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 3163): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 3163):  Nonce Reponse 
I/MMApiWebService( 3163): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 3163): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 3163): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 3163): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 3163): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 3163): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     (  882): Explicit concurrent mark sweep GC freed 12493(649KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 19MB/29MB, paused 1.766ms total 117.158ms
,D/MMApiWebService( 3163): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 3163): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 3163): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 3163): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 3163): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,D/CdsService( 3163): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 3163): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 3163): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/UsageStatsService(  882): User[0] Flushing usage stats to disk
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1692): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,I/ThermalEngine(  314): Sensor:xo_therm_pu2:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 6123): 
D/AndroidRuntime( 6123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6123): CheckJNI is OFF
D/AndroidRuntime( 6123): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10537 user=-1: uninstall pkg
I/ActivityManager(  882): Killing 6013:com.test.thalitest/u0a537 (adj 9): stop com.test.thalitest
D/WifiService(  882): Client connection lost with reason: 4
W/PackageSettings(  882): Skipping PackageSetting{3a98499d com.example.hello/10533} due to missing metadata
I/ActivityManager(  882): Force stopping com.test.thalitest appid=10537 user=0: pkg removed
I/art     ( 3611): Explicit concurrent mark sweep GC freed 3566(709KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 7MB/12MB, paused 780us total 38.783ms
W/ActivityManager(  882): Spurious death for ProcessRecord{ce577e7 6013:com.test.thalitest/u0a537}, curProc for 6013: null
W/GeofencerStateMachine( 1692): Ignoring removeGeofence because network location is disabled.
I/InputReader(  882): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator( 1407): resetDictionaries() : en_US
D/VoicemailCleanupService( 5665): Cleaning up data for package: com.test.thalitest
I/art     ( 1558): Explicit concurrent mark sweep GC freed 7380(537KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 1.600ms total 109.872ms
I/Keyboard.Facilitator.DecoderInitializer( 1407): run()
I/Decoder ( 1407): createOrResetDecoder
I/art     ( 1939): Explicit concurrent mark sweep GC freed 13439(797KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 14MB/19MB, paused 993us total 146.229ms
I/ActivityManager(  882): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6154 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  882): Explicit concurrent mark sweep GC freed 7256(620KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 19MB/29MB, paused 1.335ms total 144.200ms
I/art     (  882): WaitForGcToComplete blocked for 71.001ms for cause Explicit
I/ConfigService( 1692): onCreate
W/asset   ( 6154): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 6154): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 6154): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Keyboard.Facilitator.MainLanguageModelLoader( 1407): run()
W/ResourcesManager( 6154): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
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
D/BackupManagerService(  882): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  882): Receieved: android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  882): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6175 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
D/TaskPersister(  882): removeObsoleteFile: deleting file=6_task.xml
I/Launcher( 1558): Deferring update until onResume
I/art     (  882): Explicit concurrent mark sweep GC freed 5015(257KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 4.265ms total 194.633ms
W/ContextImpl( 6175): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 1939): Clearing selected account for com.test.thalitest
I/LocationSettingsChecker( 1939): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1692): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1692): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 1939): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 1939): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 1939): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 1939): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 1939): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  882): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6203 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
D/AndroidRuntime( 6123): Shutting down VM
I/Icing   ( 1939): doRemovePackageData com.test.thalitest
W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1ba1c366 new=com.google.android.velvet.VelvetApplication@1ba1c366
I/ActivityManager(  882): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6226 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  882): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6253 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
I/art     (  322): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 250us total 20.434ms
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 249us total 18.959ms
I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 258us total 25.849ms
I/UpdateIcingCorporaServi( 6203): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SQLiteDatabase( 6203): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 6203): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
E/SQLiteDatabase( 6203): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
E/SQLiteDatabase( 6203): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6203): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6203): 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
E/SQLiteDatabase( 6203): 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
E/SQLiteDatabase( 6203): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
E/SQLiteDatabase( 6203): 	at android.content.ContentResolver.update(ContentResolver.java:1333)
E/SQLiteDatabase( 6203): 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
E/SQLiteDatabase( 6203): 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
E/SQLiteDatabase( 6203): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
E/SQLiteDatabase( 6203): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
E/SQLiteDatabase( 6203): 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
E/SQLiteDatabase( 6203): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6203): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6203): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 6203): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  882): Killing 5804:com.google.android.apps.plus/u0a90 (adj 15): empty #7
I/qdhwcomposer(  278): handle_blank_event: dpy:0 panel power state: 0

```
