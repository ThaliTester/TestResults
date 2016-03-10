#### Test 61362366b225741_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
D/AndroidRuntime( 5191): 
D/AndroidRuntime( 5191): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5191): CheckJNI is OFF
D/AndroidRuntime( 5191): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  896): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  896): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5210 uid=10570 gids={50570, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5191): Shutting down VM
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 322us total 25.701ms
V/ActivityManager(  896): Display changed displayId=0
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 248us total 23.328ms
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 245us total 25.799ms
,I/WebViewFactory( 5210): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5210): Time to load native libraries: 2 ms (timestamps 7388-7390)
I/LibraryLoader( 5210): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5210): Binding Chromium to main looper Looper (main, tid 1) {2841c663}
,I/LibraryLoader( 5210): Expected native library version number "",actual native library version number ""
,I/chromium( 5210): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5210): Initializing chromium process, singleProcess=true
,W/art     ( 5210): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5210): ApplicationContext is null in ApplicationStatus
,W/chromium( 5210): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5210): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5210): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5210): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5210): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5210): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5210): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5210): Local Branch: 
I/Adreno-EGL( 5210): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5210): Local Patches: NONE
I/Adreno-EGL( 5210): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,W/ActivityManager(  896): Activity pause timeout for ActivityRecord{2022fb91 u0 com.test.thalitest/.MainActivity t9}
,D/BluetoothManagerService(  896): Message: 20
D/BluetoothManagerService(  896): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11e398fc:true
,D/BluetoothAdapter( 5210): 343958975: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 5210): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5210): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5210): CordovaWebView is running on device made by: motorola
,W/art     ( 5210): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5210): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5210): Render dirty regions requested: true
,D/Atlas   ( 5210): Validating map...
,W/chromium( 5210): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5210): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5210): Enabling debug mode 0
,I/Keyboard.Facilitator( 1424): onFinishInput()
,I/LaunchCheckinHandler(  896): Displayed com.test.thalitest/.MainActivity,cp,ca,1021
I/ActivityManager(  896): Displayed com.test.thalitest/.MainActivity: +920ms (total +1s21ms)
,W/IInputConnectionWrapper( 5210): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5210): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5210): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5210): Cannot call determinedVisibility() - never saw a connection for the pid: 5210
,D/JsMessageQueue( 5210): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5210): JniHelper::setJavaVM(0xb89a6310), pthread_self() = -1194076400
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5210): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5210):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5210):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5210):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5210):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5210): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e23af9f added. We now have 1 listener(s)
,D/BluetoothManagerService(  896): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5210): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5210): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5210): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5210): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdb174a added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5210): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  896): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5210): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5210): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5210): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5210): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5210): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5210): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5210): Initializing JXcore engine
W/jxcore-log( 5210): JXcore engine is ready
,W/Thread-574( 5267): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10570 path="socket:[9600]" dev="sockfs" ino=9600 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-574( 5267): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10570 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-574( 5267): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10570 path="socket:[6717]" dev="sockfs" ino=6717 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-574( 5267): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10570 path="socket:[23747]" dev="sockfs" ino=23747 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5210): Starting JXcore engine
,W/jxcore-log( 5210): Platform android
W/jxcore-log( 5210): 
,W/jxcore-log( 5210): Process ARCH arm
W/jxcore-log( 5210): 
,I/jxcore-log( 5210): JXcore Cordova bridge is ready!
I/jxcore-log( 5210): 
W/jxcore-log( 5210): JXcore engine is started
I/org.thaliproject.p2p.ThaliPermissions( 5210): execute: REQUEST_ACCESS_COARSE_LOCATION
E/jxcore  ( 5210): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5210): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
I/chromium( 5210): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
I/ActivityManager(  896): Killing 4731:android.process.acore/u0a7 (adj 15): empty #7
W/libprocessgroup(  896): failed to open /acct/uid_10007/pid_4731/cgroup.procs: No such file or directory
W/PluginManager( 5210): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 102ms. Plugin should use CordovaInterface.getThreadPool().
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1479): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
I/art     ( 2573): Explicit concurrent mark sweep GC freed 40417(3MB) AllocSpace objects, 6(148KB) LOS objects, 39% free, 11MB/18MB, paused 1.413ms total 70.708ms
D/OtaApp  ( 2573): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2573): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
D/Checkin ( 2573): publish the event [tag = MOT_OTA event name = LOG]
I/OtaApp  ( 2573): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2573): publish the event [tag = MOT_OTA event name = LOG]
D/OtaApp  ( 2573): [debug] > cancelling the previous pending intent set for download later
I/OtaApp  ( 2573): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
D/Checkin ( 2573): publish the event [tag = MOT_OTA event name = LOG]
I/Keyboard.Facilitator( 1424): onFinishInput()
W/IInputConnectionWrapper( 5210): showStatusIcon on inactive InputConnection
,D/TaskPersister(  896): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  896): uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311692, SEQNUM=4371, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-9715, POWER_SUPPLY_CHARGE_COUNTER=-775, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1424): run()
I/Keyboard.Facilitator( 1424): flushDynamicLanguageModels()
,I/ConfigService( 1736): onCreate
,I/ConfigService( 1736): onDestroy
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  896): send {27a1e0b3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  896): done {27a1e0b3, *alarm*:android.intent.action.TIME_TICK} [35ms]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  896): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311580, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=-1097, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MMApiBackOffService( 2573): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2573): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2573): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2573): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2573):  Nonce Reponse 
I/MMApiWebService( 2573): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2573): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2573): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2573): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2573): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2573): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2573): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2573): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2573): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2573): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,D/CdsService( 2573): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2573): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2573): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  896): send {27a1e0b3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  896): send {234c9c15, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,D/Finsky  ( 4965): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  896): send {2832b548, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene}
,V/AlarmManager(  896): done {2832b548, *walarm*:com.android.vending/com.google.android.finsky.services.DailyHygiene} [33ms]
V/AlarmManager(  896): done {234c9c15, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [33ms]
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  896): done {27a1e0b3, *alarm*:android.intent.action.TIME_TICK} [62ms]
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4965): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 4965): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  896): Explicit concurrent mark sweep GC freed 13884(716KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 19MB/29MB, paused 1.382ms total 127.334ms
,W/Finsky  ( 4965): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 4965): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  896): send {37a506f9, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver}
,D/Finsky  ( 4965): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1736): client connected with version: 8296000
,D/WearableService( 1736): callingUid 10016, callindPid: 1736
,V/AlarmManager(  896): done {37a506f9, *walarm*:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver} [15ms]
,D/Finsky  ( 4965): [575] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4965): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
,D/Finsky  ( 4965): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4965): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  896): send {bba9284, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  896): done {bba9284, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [11ms]
,D/Finsky  ( 4965): [560] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4965): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2573): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2573): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2573): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2573): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2573):  Nonce Reponse 
I/MMApiWebService( 2573): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2573): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2573): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MDMCTBK (  294): NetlinkHandler, power_supply subsys
I/MDMCTBK (  294): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  294): checkDefaultInst, current pid is = 294
I/MDMCTBK (  294): checkDefaultInst, pid match
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  294): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  294): MdmCutbackHndler,Could not open ''
,D/BatteryService(  896): uevent={POWER_SUPPLY_TEMP=274, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311217, SEQNUM=4386, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-369, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2573): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2573): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2573): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1479): Explicit concurrent mark sweep GC freed 3922(188KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 778us total 31.430ms
,D/MMApiWebService( 2573): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2573): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2573): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2573): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2573): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2573): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2573): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2573): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  896): User[0] Flushing usage stats to disk
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  306): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime( 5371): 
D/AndroidRuntime( 5371): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5371): CheckJNI is OFF
D/AndroidRuntime( 5371): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10570 user=-1: uninstall pkg
I/ActivityManager(  896): Killing 5210:com.test.thalitest/u0a570 (adj 11): stop com.test.thalitest
D/WifiService(  896): Client connection lost with reason: 4
W/PackageSettings(  896): Skipping PackageSetting{f36067b com.example.hello/10568} due to missing metadata
W/ActivityManager(  896): Spurious death for ProcessRecord{37203677 5210:com.test.thalitest/u0a570}, curProc for 5210: null
I/ActivityManager(  896): Force stopping com.test.thalitest appid=10570 user=0: pkg removed
I/art     ( 2957): Explicit concurrent mark sweep GC freed 9180(2MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 7MB/12MB, paused 781us total 28.369ms
I/art     ( 4801): Explicit concurrent mark sweep GC freed 11443(683KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 12MB/16MB, paused 654us total 70.095ms
I/art     ( 4858): Explicit concurrent mark sweep GC freed 677(38KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 363us total 66.728ms
I/Keyboard.Facilitator( 1424): resetDictionaries() : en_US
W/GeofencerStateMachine( 1736): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator.DecoderInitializer( 1424): run()
I/Decoder ( 1424): createOrResetDecoder
I/InputReader(  896): Reconfiguring input devices.  changes=0x00000010
I/art     ( 1572): Explicit concurrent mark sweep GC freed 7406(536KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 718us total 79.644ms
I/ActivityManager(  896): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5401 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/ConfigService( 1736): onCreate
I/art     (  896): Explicit concurrent mark sweep GC freed 13979(929KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 19MB/29MB, paused 1.551ms total 141.300ms
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): run()
I/art     (  896): WaitForGcToComplete blocked for 82.981ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1424): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1424): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1424): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1424): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1424): run()
I/StatsUtilsManager( 1424): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1424): shouldRecordStats() = Too Soon
D/VoicemailCleanupService( 5401): Cleaning up data for package: com.test.thalitest
I/ContactLocale( 5401): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
I/ActivityManager(  896): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5423 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
D/BackupManagerService(  896): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  896): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  896): removeObsoleteFile: deleting file=9_task.xml
I/Launcher( 1572): Deferring update until onResume
I/art     (  896): Explicit concurrent mark sweep GC freed 4963(271KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.784ms total 192.145ms
W/asset   ( 5423): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5423): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5423): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5423): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/ActivityManager(  896): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5444 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  896): Killing 4858:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5371): Shutting down VM
W/libprocessgroup(  896): failed to open /acct/uid_10039/pid_4858/cgroup.procs: No such file or directory
W/ContextImpl( 5444): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4801): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4801): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4801): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4801): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4801): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4801): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1736): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1736): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 4801): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 4801): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4801): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4801): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4801): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4801): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4801): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4801): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4801): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4801): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4801): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4801): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4801): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4801): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  896): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5467 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
V/AlarmManager(  896): send {27a1e0b3, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  896): send {234c9c15, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  896): send {3bff9817, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
V/AlarmManager(  896): done {27a1e0b3, *alarm*:android.intent.action.TIME_TICK} [42ms]
W/BaseAppContext( 4801): Using Auth Proxy for data requests.
I/GMPM-SVC( 4801): App measurement is starting up, version: 8489
I/GMPM-SVC( 4801): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/BaseAppContext( 4801): Using Auth Proxy for data requests.
W/Launcher( 1572): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
I/ActivityManager(  896): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5495 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/Icing   ( 4801): doRemovePackageData com.test.thalitest
D/ConnectivityService(  896): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/SQLiteLog( 4801): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 4801): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
E/SharedPreferencesImpl( 4801): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.measurement.prefs.xml.bak
I/qdhwcomposer(  281): handle_blank_event: dpy:0 panel power state: 0

```
