#### Test 61432979dd0fe92_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,I/ConfigService( 1720): onDestroy
D/AndroidRuntime( 5339): 
D/AndroidRuntime( 5339): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5339): CheckJNI is OFF
D/AndroidRuntime( 5339): Calling main entry com.android.commands.am.Am
--------- beginning of system
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5358 uid=10571 gids={50571, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5339): Shutting down VM
V/ActivityManager(  881): Display changed displayId=0
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5358): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5358): Time to load native libraries: 4 ms (timestamps 1787-1791)
,I/LibraryLoader( 5358): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5358): Binding Chromium to main looper Looper (main, tid 1) {1c297b0}
,I/LibraryLoader( 5358): Expected native library version number "",actual native library version number ""
I/chromium( 5358): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5358): Initializing chromium process, singleProcess=true
,W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5358): ApplicationContext is null in ApplicationStatus
,W/chromium( 5358): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 5358): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5358): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5358): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5358): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5358): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5358): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5358): Local Branch: 
I/Adreno-EGL( 5358): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5358): Local Patches: NONE
I/Adreno-EGL( 5358): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27abb099:true
,D/BluetoothAdapter( 5358): 370698603: getState() :  mService = null. Returning STATE_OFF
,W/ActivityManager(  881): Activity pause timeout for ActivityRecord{5f5e7ba u0 com.test.thalitest/.MainActivity t9}
,W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5358): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5358): CordovaWebView is running on device made by: motorola
,W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5358): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5358): Render dirty regions requested: true
,D/Atlas   ( 5358): Validating map...
,W/chromium( 5358): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5358): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5358): Enabling debug mode 0
,I/Keyboard.Facilitator( 1411): onFinishInput()
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1029
,I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +943ms (total +1s29ms)
,W/IInputConnectionWrapper( 5358): showStatusIcon on inactive InputConnection
,E/Adreno-ES20( 5358): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5358): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5358): Cannot call determinedVisibility() - never saw a connection for the pid: 5358
,D/JsMessageQueue( 5358): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 5358): JniHelper::setJavaVM(0xb8da2310), pthread_self() = -1189896776
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5358): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5358):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5358):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5358):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5358):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5358): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60d9b3c added. We now have 1 listener(s)
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5358): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5358): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5358): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5358): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38eef94b added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5358): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  881): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5358): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5358): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5358): setScanMode: 1 -> 2
W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5358): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5358): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5358): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/jxcore-log( 5358): Initializing JXcore engine
W/jxcore-log( 5358): JXcore engine is ready
,W/Thread-603( 5408): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10571 path="socket:[5569]" dev="sockfs" ino=5569 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-603( 5408): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10571 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-603( 5408): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10571 path="socket:[9537]" dev="sockfs" ino=9537 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-603( 5408): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10571 path="socket:[24795]" dev="sockfs" ino=24795 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5358): Starting JXcore engine
,W/jxcore-log( 5358): Platform android
W/jxcore-log( 5358): 
,W/jxcore-log( 5358): Process ARCH arm
W/jxcore-log( 5358): 
,I/jxcore-log( 5358): JXcore Cordova bridge is ready!
I/jxcore-log( 5358): 
W/jxcore-log( 5358): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5358): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5358): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5358): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5358): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,I/ActivityManager(  881): Killing 4870:android.process.acore/u0a7 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10007/pid_4870/cgroup.procs: No such file or directory
,W/PluginManager( 5358): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 32ms. Plugin should use CordovaInterface.getThreadPool().
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/ContextImpl( 1466): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2598): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2598): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2598): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2598): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2598): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2598): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2598): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2598): publish the event [tag = MOT_OTA event name = LOG]
,W/IInputConnectionWrapper( 5358): showStatusIcon on inactive InputConnection
,I/Keyboard.Facilitator( 1411): onFinishInput()
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task.xml
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=298, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311130, SEQNUM=4378, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-562, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:33000 mC
,V/AlarmManager(  881): send {d6fdb02, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {3082254f, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  881): done {3082254f, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,V/AlarmManager(  881): done {d6fdb02, *alarm*:android.intent.action.TIME_TICK} [37ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311962, SEQNUM=4380, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-12520, POWER_SUPPLY_CHARGE_COUNTER=-616, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/Keyboard.Facilitator.LanguageModelFlusher( 1411): run()
I/Keyboard.Facilitator( 1411): flushDynamicLanguageModels()
,I/ConfigService( 1720): onCreate
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ConfigService( 1720): onDestroy
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310975, SEQNUM=4382, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-888, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=283, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311215, SEQNUM=4383, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-500, POWER_SUPPLY_CHARGE_COUNTER=-960, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MMApiBackOffService( 2598): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2598): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2598): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2598): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2598):  Nonce Reponse 
I/MMApiWebService( 2598): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2598): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2598): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2598): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2598): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2598): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2598): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2598): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2598): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2598): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,D/CdsService( 2598): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2598): [i] > Retry handler returned true; Retry web request after backoff time: 600000
,D/Checkin ( 2598): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1720): Explicit concurrent mark sweep GC freed 41553(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 13MB/21MB, paused 1.097ms total 156.830ms
,E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@155cc5c5)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@18206b1a)
,E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@168bb64b)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3409a828)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1048f941)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@344a1ee6)
,E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@24dd6c27)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@36651ed4)
,E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@246ae87d)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22094372)
,E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2e5f5440)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33c28f79)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@22424be)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1589b91f)
E/DataBuffer( 1720): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2f05746c)
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  293): NetlinkHandler, power_supply subsys
I/MDMCTBK (  293): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  293): checkDefaultInst, current pid is = 293
I/MDMCTBK (  293): checkDefaultInst, pid match
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  293): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  293): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310868, SEQNUM=4387, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-4306, POWER_SUPPLY_CHARGE_COUNTER=-24, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,V/AlarmManager(  881): send {d6fdb02, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {26e3ae, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
,V/AlarmManager(  881): done {26e3ae, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [7ms]
,V/AlarmManager(  881): done {d6fdb02, *alarm*:android.intent.action.TIME_TICK} [52ms]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2598): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2598): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2598): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2598): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2598):  Nonce Reponse 
I/MMApiWebService( 2598): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2598): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2598): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2598): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2598): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2598): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     ( 1466): Explicit concurrent mark sweep GC freed 3958(189KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 7MB/12MB, paused 928us total 30.901ms
,I/art     (  881): Explicit concurrent mark sweep GC freed 13921(805KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 19MB/29MB, paused 1.348ms total 115.842ms
,D/MMApiWebService( 2598): doRequest(): polling manager says we're not connected, returning with an error: 
,I/MMApiWebService( 2598): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2598): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2598): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2598): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,D/CdsService( 2598): [d] > failure response with status code :com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "moto-cds.appspot.com": No address associated with hostname
,I/CdsService( 2598): [i] > Retry handler returned true; Retry web request after backoff time: 1800000
,D/Checkin ( 2598): publish the event [tag = MOT_OTA event name = LOG]
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1720): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  305): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5491): 
D/AndroidRuntime( 5491): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5491): CheckJNI is OFF
D/AndroidRuntime( 5491): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10571 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5358:com.test.thalitest/u0a571 (adj 9): stop com.test.thalitest
D/WifiService(  881): Client connection lost with reason: 4
W/PackageSettings(  881): Skipping PackageSetting{144443e8 com.example.hello/10568} due to missing metadata
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10571 user=0: pkg removed
I/art     ( 2991): Explicit concurrent mark sweep GC freed 4455(860KB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 7MB/12MB, paused 598us total 43.502ms
W/ActivityManager(  881): Spurious death for ProcessRecord{32501e59 5358:com.test.thalitest/u0a571}, curProc for 5358: null
W/GeofencerStateMachine( 1720): Ignoring removeGeofence because network location is disabled.
I/Keyboard.Facilitator( 1411): resetDictionaries() : en_US
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
I/Keyboard.Facilitator.DecoderInitializer( 1411): run()
I/art     ( 5004): Explicit concurrent mark sweep GC freed 694(38KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 9MB/12MB, paused 369us total 92.005ms
I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5519 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     ( 1559): Explicit concurrent mark sweep GC freed 3611(240KB) AllocSpace objects, 1(36KB) LOS objects, 24% free, 13MB/17MB, paused 492us total 99.117ms
I/art     ( 4940): Explicit concurrent mark sweep GC freed 11083(665KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 676us total 121.864ms
I/Decoder ( 1411): createOrResetDecoder
I/ConfigService( 1720): onCreate
I/art     (  881): Explicit concurrent mark sweep GC freed 8632(698KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 19MB/29MB, paused 1.694ms total 165.438ms
I/art     (  881): WaitForGcToComplete blocked for 137.594ms for cause Explicit
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): run()
D/VoicemailCleanupService( 5519): Cleaning up data for package: com.test.thalitest
I/Keyboard.Facilitator.MainLanguageModelLoader( 1411): loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4014912) with up to date LoudsLmContentVersion = 20150512
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run()
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = contacts
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Contacts.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = history
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loaded File = UserHistory.en_US.dict
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Loading LM = user
I/Keyboard.Facilitator.DynamicLanguageModelLoader( 1411): run() : Missing File = Personal.en_US.dict
I/Keyboard.Facilitator.PersonalDictionaryLoader( 1411): run() : Loaded (exit)
I/Keyboard.Facilitator.Delight2FileSweeper( 1411): run()
I/Keyboard.Facilitator.RecurringTaskScheduler( 1411): run()
I/StatsUtilsManager( 1411): startPeriodStatsRecorder() : Success
I/PeriodicStatsRecorder( 1411): shouldRecordStats() = Too Soon
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5543 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5519): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task.xml
W/asset   ( 5543): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5543): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5543): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5543): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  881): Explicit concurrent mark sweep GC freed 4993(254KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 19MB/29MB, paused 2.178ms total 196.549ms
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5565 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 5004:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
D/AndroidRuntime( 5491): Shutting down VM
W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_5004/cgroup.procs: No such file or directory
I/Launcher( 1559): Deferring update until onResume
W/ContextImpl( 5565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
D/PackageBroadcastService( 4940): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 4940): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 4940): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4940): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4940): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4940): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1720): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1720): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/LocationSettingsChecker( 4940): Removing dialog suppression flag for package com.test.thalitest
D/gH_CompatibleDatabase( 4940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4940): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
D/gH_CompatibleDatabase( 4940): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4940): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4940): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4940): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4940): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4940): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5588 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
W/BaseAppContext( 4940): Using Auth Proxy for data requests.
W/BaseAppContext( 4940): Using Auth Proxy for data requests.
I/GMPM-SVC( 4940): App measurement is starting up, version: 8489
I/GMPM-SVC( 4940): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/Icing   ( 4940): doRemovePackageData com.test.thalitest
D/ConnectivityService(  881): listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@29623be5 new=com.google.android.velvet.VelvetApplication@29623be5
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5617 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 242us total 20.110ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 19.725ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 255us total 20.513ms
W/DriveInitializer( 4940): Awaiting to be initialized
W/DriveInitializer( 4940): Background init thread started
E/SQLiteLog( 4940): (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock163] disk I/O error
E/DocListDatabase( 4940): Failed to delete from ContentFileDeletionLock163 table
E/DocListDatabase( 4940): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DocListDatabase( 4940): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DocListDatabase( 4940): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/DocListDatabase( 4940): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DocListDatabase( 4940): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DocListDatabase( 4940): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/DocListDatabase( 4940): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/DocListDatabase( 4940): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/DocListDatabase( 4940): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/SQLiteLog( 4940): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/DriveInitializer( 4940): Background init thread ended
--------- beginning of crash
E/AndroidRuntime( 4940): FATAL EXCEPTION: Background initialization thread
E/AndroidRuntime( 4940): Process: com.google.android.gms, PID: 4940
E/AndroidRuntime( 4940): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 4940): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 4940): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
E/AndroidRuntime( 4940): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 4940): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 4940): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
E/AndroidRuntime( 4940): 	at com.google.android.gms.drive.database.k.a(SourceFile:330)
E/AndroidRuntime( 4940): 	at com.google.android.gms.drive.database.f.h(SourceFile:1065)
E/AndroidRuntime( 4940): 	at com.google.android.gms.drive.t.run(SourceFile:62)
E/DriveAsyncService( 4940): disk I/O error (code 3850)
E/DriveAsyncService( 4940): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 4940): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 4940): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/DriveAsyncService( 4940): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 4940): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 4940): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/DriveAsyncService( 4940): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/DriveAsyncService( 4940): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 4940): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 4940): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 4940): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 4940): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 4940): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 4940): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 4940): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 4940): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 4940): Sending signal. PID: 4940 SIG: 9
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
D/ConnectivityService(  881): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@eb86408)
D/ConnectivityService(  881): releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  881): RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
