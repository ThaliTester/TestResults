#### Test 61362366b6c9a6f_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
D/AndroidRuntime( 5359): 
D/AndroidRuntime( 5359): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5359): CheckJNI is OFF
D/AndroidRuntime( 5359): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5378 uid=10569 gids={50569, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5359): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5378): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5378): Time to load native libraries: 4 ms (timestamps 7331-7335)
,I/LibraryLoader( 5378): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5378): Binding Chromium to main looper Looper (main, tid 1) {46a3c82}
I/LibraryLoader( 5378): Expected native library version number "",actual native library version number ""
I/chromium( 5378): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5378): Initializing chromium process, singleProcess=true
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5378): ApplicationContext is null in ApplicationStatus
,W/chromium( 5378): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5378): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5378): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5378): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5378): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5378): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5378): Local Branch: 
I/Adreno-EGL( 5378): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5378): Local Patches: NONE
I/Adreno-EGL( 5378): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18c59e8a:true
,D/BluetoothAdapter( 5378): 55097221: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{10e63ce7 u0 com.test.thalitest/.MainActivity t9}
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5378): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5378): CordovaWebView is running on device made by: motorola
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5378): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5378): Render dirty regions requested: true
,D/Atlas   ( 5378): Validating map...
,W/chromium( 5378): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5378): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5378): Enabling debug mode 0
,I/Keyboard.Facilitator( 1409): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,985
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +900ms (total +986ms)
,W/IInputConnectionWrapper( 5378): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5378): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5378): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5378): Cannot call determinedVisibility() - never saw a connection for the pid: 5378
,D/JsMessageQueue( 5378): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5378): JniHelper::setJavaVM(0xb7826310), pthread_self() = -1212429576
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5378): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5378):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5378):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5378):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5378):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5378): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dea9c2e added. We now have 1 listener(s)
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5378): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5378): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5378): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5378): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b0c5c65 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5378): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  881): New client listening to asynchronous messages
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5378): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5378): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5378): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5378): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5378): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5378): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5378): Initializing JXcore engine
W/jxcore-log( 5378): JXcore engine is ready
,W/Thread-610( 5429): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10569 path="socket:[5829]" dev="sockfs" ino=5829 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-610( 5429): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10569 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-610( 5429): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10569 path="socket:[7453]" dev="sockfs" ino=7453 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-610( 5429): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10569 path="socket:[23487]" dev="sockfs" ino=23487 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5378): Starting JXcore engine
,W/jxcore-log( 5378): Platform android
W/jxcore-log( 5378): 
W/jxcore-log( 5378): Process ARCH arm
W/jxcore-log( 5378): 
,I/jxcore-log( 5378): JXcore Cordova bridge is ready!
I/jxcore-log( 5378): 
,W/jxcore-log( 5378): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5378): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5378): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5378): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5378): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  881): Killing 4996:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_4996/cgroup.procs: No such file or directory
W/PluginManager( 5378): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 31ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1465): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2535): [debug] > DownloadActivity, FormattedText
I/OtaApp  ( 2535): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2535): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2535): [info] > Exceed max defer attempts for optional update, suppresing later btn
D/Checkin ( 2535): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2535): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2535): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2535): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5378): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1409): onFinishInput()
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=289, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310399, SEQNUM=4376, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12019, POWER_SUPPLY_CHARGE_COUNTER=-475, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
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
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task.xml
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:32000 mC
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310935, SEQNUM=4378, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-494, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1409): run()
I/Keyboard.Facilitator( 1409): flushDynamicLanguageModels()
,I/ConfigService( 1717): onCreate
,I/ConfigService( 1717): onDestroy
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=280, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311430, SEQNUM=4379, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=0, POWER_SUPPLY_CHARGE_COUNTER=-618, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
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
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310827, SEQNUM=4381, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-7512, POWER_SUPPLY_CHARGE_COUNTER=-815, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2535): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2535): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2535): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 2535): Explicit concurrent mark sweep GC freed 41044(3MB) AllocSpace objects, 6(148KB) LOS objects, 40% free, 11MB/18MB, paused 2.052ms total 140.808ms
,D/MMApiWebService( 2535): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2535):  Nonce Reponse 
I/MMApiWebService( 2535): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiBackOffService( 2535): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
I/MMApiWebService( 2535): MMApiWebService told us not to continue at the moment with this request: nonce.json
D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2535): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2535): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2535): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2535): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2535): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2535): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2535): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,D/CdsService( 2535): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2535): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2535): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1717): Explicit concurrent mark sweep GC freed 42231(2MB) AllocSpace objects, 10(160KB) LOS objects, 40% free, 13MB/22MB, paused 1.118ms total 96.419ms
,E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3ad65ee1)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@373e5ac7)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@21f78f4)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3ef9081d)
,E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13ef7a92)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@133bdc63)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@5353060)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36a30919)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1286adde)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@405dbbf)
V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@342cf28c)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d521dd5)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18cbc9ea)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3b4674db)
E/DataBuffer( 1717): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@30fcab78)
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {26b61bb3, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {55fefda, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): send {32edaa8e, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  881): done {55fefda, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [21ms]
,V/AlarmManager(  881): done {26b61bb3, *alarm*:android.intent.action.TIME_TICK} [49ms]
,V/AlarmManager(  881): done {32edaa8e, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [58ms]
,I/EventLogService( 4945): Aggregate from 1457597540208 (log), 1457597540208 (data)
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2535): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2535): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2535): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     (  881): Explicit concurrent mark sweep GC freed 14189(830KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 19MB/29MB, paused 1.876ms total 116.387ms
,I/art     ( 1465): Explicit concurrent mark sweep GC freed 3874(186KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 7MB/12MB, paused 784us total 26.178ms
,D/MMApiWebService( 2535): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2535):  Nonce Reponse 
I/MMApiWebService( 2535): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2535): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2535): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2535): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2535): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2535): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2535): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2535): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2535): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2535): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2535): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2535): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2535): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2535): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310737, SEQNUM=4398, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=504, POWER_SUPPLY_CHARGE_COUNTER=-20, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=272, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310733, SEQNUM=4399, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1602, POWER_SUPPLY_CHARGE_COUNTER=1, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  309): NetlinkHandler, power_supply subsys
I/MDMCTBK (  309): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  309): checkDefaultInst, current pid is = 309
I/MDMCTBK (  309): checkDefaultInst, pid match
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  309): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  309): MdmCutbackHndler,Could not open ''
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1717): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),I/ThermalEngine(  324): Sensor:xo_therm_pu2:30000 mC
D/AndroidRuntime( 5541): 
D/AndroidRuntime( 5541): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5541): CheckJNI is OFF
D/AndroidRuntime( 5541): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10569 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5378:com.test.thalitest/u0a569 (adj 11): stop com.test.thalitest
D/WifiService(  881): Client connection lost with reason: 4
W/PackageSettings(  881): Skipping PackageSetting{306ac3fa com.example.hello/10568} due to missing metadata
W/ActivityManager(  881): Spurious death for ProcessRecord{17b60b25 5378:com.test.thalitest/u0a569}, curProc for 5378: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10569 user=0: pkg removed
I/art     ( 2962): Explicit concurrent mark sweep GC freed 5025(1007KB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 7MB/12MB, paused 582us total 26.593ms
I/art     ( 1558): Explicit concurrent mark sweep GC freed 7291(530KB) AllocSpace objects, 3(148KB) LOS objects, 24% free, 13MB/17MB, paused 477us total 46.536ms
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1717): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1409): resetDictionaries() : en_US
I/art     ( 4945): Explicit concurrent mark sweep GC freed 3865(262KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 12MB/17MB, paused 1.038ms total 130.610ms
I/Keyboard.Facilitator.DecoderInitializer( 1409): run()
D/VoicemailCleanupService( 4872): Cleaning up data for package: com.test.thalitest
I/Decoder ( 1409): createOrResetDecoder
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5572 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ConfigService( 1717): onCreate
I/art     (  881): Explicit concurrent mark sweep GC freed 11115(857KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 19MB/29MB, paused 7.515ms total 150.342ms
I/art     (  881): WaitForGcToComplete blocked for 74.824ms for cause Explicit
W/asset   ( 5572): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5572): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5572): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 1717): Classify the device as Phone.
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5597 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
W/FetchTask( 1717): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task.xml
I/art     (  881): Explicit concurrent mark sweep GC freed 4493(220KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 1.846ms total 195.324ms
I/Launcher( 1558): Deferring update until onResume
I/CheckinRequestBuilder( 1717): Classify the device as Phone.
W/FetchTask( 1717): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ContextImpl( 5597): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4945): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4945): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4945): Module APK com.google.android.play.games already loaded
I/CheckinRequestBuilder( 1717): Classify the device as Phone.
D/ChimeraCfgMgr( 4945): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4945): Module APK com.google.android.play.games already loaded
W/FetchTask( 1717): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
E/NetworkScheduler.SchedulerReceiver( 1717): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1717): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 4945): Removing dialog suppression flag for package com.test.thalitest
I/CheckinRequestBuilder( 1717): Classify the device as Phone.
D/gH_CompatibleDatabase( 4945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4945): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4945): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4945): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4945): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4945): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5626 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/FetchTask( 1717): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
V/AlarmManager(  881): send {26b61bb3, *alarm*:android.intent.action.TIME_TICK}
D/AndroidRuntime( 5541): Shutting down VM
V/AlarmManager(  881): send {55fefda, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): done {26b61bb3, *alarm*:android.intent.action.TIME_TICK} [54ms]
W/BaseAppContext( 4945): Using Auth Proxy for data requests.
W/BaseAppContext( 4945): Using Auth Proxy for data requests.
I/GMPM-SVC( 4945): App measurement is starting up, version: 8489
I/GMPM-SVC( 4945): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 4945): doRemovePackageData com.test.thalitest
I/CheckinRequestBuilder( 1717): Classify the device as Phone.
W/FetchTask( 1717): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): run()
W/Launcher( 1558): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1fc191ef new=com.google.android.velvet.VelvetApplication@1fc191ef
D/ConnectivityService(  881): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/Keyboard.Facilitator.MainLanguageModelLoader( 1409): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1409): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1409): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1409): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1409): run()
I/StatsUtilsManager( 1409): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1409): shouldRecordStats() = Too Soon
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5656 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  333): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 244us total 21.830ms
I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.495ms
I/art     (  333): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 23.412ms
W/DriveInitializer( 4945): Awaiting to be initialized
W/DriveInitializer( 4945): Background init thread started
E/SQLiteLog( 4945): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 4945): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 4945): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4945): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 4945): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4945): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4945): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 4945): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 4945): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 4945): 	at com.google.android.gms.drive.t.run(SourceFile:62)
W/DriveInitializer( 4945): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 4945): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4945): Process: com.google.android.gms, PID: 4945
E/AndroidRuntime( 4945): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4945): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4945): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 4945): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 4945): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 4945): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/DriveAsyncService( 4945): disk I/O error (code 3850)
E/DriveAsyncService( 4945): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4945): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4945): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 4945): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4945): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4945): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 4945): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 4945): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4945): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4945): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4945): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4945): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4945): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4945): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4945): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4945): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 4945): Sending signal. PID: 4945 SIG: 9
E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.FileNotFoundException: /data/system/dropbox/drop94.tmp: open failed: EROFS (Read-only file system)
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
D/ConnectivityService(  881): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@23e25eed)
D/ConnectivityService(  881): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  881): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
