#### Test 623288225dc9f88_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=312, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311503, SEQNUM=4322, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-8112, POWER_SUPPLY_CHARGE_COUNTER=-191, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
--------- beginning of main
D/AndroidRuntime( 5297): 
D/AndroidRuntime( 5297): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5297): CheckJNI is OFF
D/AndroidRuntime( 5297): Calling main entry com.android.commands.am.Am
I/ActivityManager(  881): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/PermissionCache(  280): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (146 us)
W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
D/AndroidRuntime( 5297): Shutting down VM
I/ActivityManager(  881): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5316 uid=10566 gids={50566, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,I/WebViewFactory( 5316): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5316): Time to load native libraries: 3 ms (timestamps 3245-3248)
I/LibraryLoader( 5316): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5316): Binding Chromium to main looper Looper (main, tid 1) {22789f59}
I/LibraryLoader( 5316): Expected native library version number "",actual native library version number ""
I/chromium( 5316): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5316): Initializing chromium process, singleProcess=true
W/art     ( 5316): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5316): ApplicationContext is null in ApplicationStatus
W/chromium( 5316): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 5316): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5316): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5316): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL( 5316): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5316): Build Date: 10/28/14 Tue
I/Adreno-EGL( 5316): Local Branch: 
I/Adreno-EGL( 5316): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL( 5316): Local Patches: NONE
I/Adreno-EGL( 5316): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
D/BluetoothManagerService(  881): Message: 20
D/BluetoothManagerService(  881): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3feb7da1:true
D/BluetoothAdapter( 5316): 456300330: getState() :  mService = null. Returning STATE_OFF
W/art     ( 5316): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5316): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5316): CordovaWebView is running on device made by: motorola
W/art     ( 5316): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5316): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5316): Render dirty regions requested: true
,D/Atlas   ( 5316): Validating map...
,W/chromium( 5316): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/OpenGLRenderer( 5316): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5316): Enabling debug mode 0
,I/LaunchCheckinHandler(  881): Displayed com.test.thalitest/.MainActivity,cp,ca,1064
I/ActivityManager(  881): Displayed com.test.thalitest/.MainActivity: +1s64ms
,I/Keyboard.Facilitator( 1405): onFinishInput()
,E/Adreno-ES20( 5316): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5316): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,W/BindingManager( 5316): Cannot call determinedVisibility() - never saw a connection for the pid: 5316
,D/JsMessageQueue( 5316): Set native->JS mode to OnlineEventsBridgeMode
,E/Adreno-ES20( 5316): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5316): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,I/art     (  881): Explicit concurrent mark sweep GC freed 12831(636KB) AllocSpace objects, 1(95KB) LOS objects, 33% free, 20MB/30MB, paused 1.531ms total 122.833ms
,D/jxcore_app_log( 5316): JniHelper::setJavaVM(0xb7389310), pthread_self() = -1217439496
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5316): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5316):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5316):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5316):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5316):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5316): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@404f28a added. We now have 1 listener(s)
,D/BluetoothManagerService(  881): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316): setBluetoothMacAddress: 08:00:00:10:DD:3C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5316): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5316): setIdentityString: {"name":"<no peer name>","address":"08:00:00:10:DD:3C"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5316): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5316): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Bluetooth MAC address: 08:00:00:10:DD:3C
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e02fb71 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5316): addListener: New listener added - the number of listeners is now 1
,D/WifiService(  881): New client listening to asynchronous messages
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5316): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5316): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316): setAdvertiseMode: 1 -> 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316): setAdvertiseTxPowerLevel: 2 -> 3
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5316): setScanMode: 1 -> 2
,W/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5316): isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5316): isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,I/chromium( 5316): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (0:290 vsyncs) (2:1174)
,I/art     ( 5316): Background sticky concurrent mark sweep GC freed 4435(649KB) AllocSpace objects, 0(0B) LOS objects, 1% free, 18MB/19MB, paused 5.031ms total 30.469ms
,W/jxcore-log( 5316): Initializing JXcore engine
,W/jxcore-log( 5316): JXcore engine is ready
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task_thumbnail.png
,W/Thread-625( 5388): type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10566 path="socket:[9695]" dev="sockfs" ino=9695 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-625( 5388): type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10566 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-625( 5388): type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10566 path="socket:[6701]" dev="sockfs" ino=6701 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-625( 5388): type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10566 path="socket:[23103]" dev="sockfs" ino=23103 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5316): Starting JXcore engine
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:34000 mC
,W/jxcore-log( 5316): Platform android
W/jxcore-log( 5316): 
,W/jxcore-log( 5316): Process ARCH arm
W/jxcore-log( 5316): 
,I/jxcore-log( 5316): JXcore Cordova bridge is ready!
I/jxcore-log( 5316): 
W/jxcore-log( 5316): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 5316): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/jxcore  ( 5316): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 5316): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 5316): [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,W/PluginManager( 5316): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 20ms. Plugin should use CordovaInterface.getThreadPool().
,I/SFPerfTracer(  280):      triggers: (rate: 14:313) (compose: 0:2) (post: 0:1) (render: 0:2) (16:1104 frames) (17:1190)
D/SFPerfTracer(  280):        layers: (3:11) (FocusedStackFrame (0xb89e0230): 0:17)* (DimLayer (0xb8a01f98): 0:6)* (StatusBar (0xb8a05150): 0:178) (NavigationBar (0xb8a86b48): 0:34) (com.android.systemui.ImageWallpaper (0xb8a42be0): 0:8)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8a478e0): 0:49)- (Starting com.test.thalitest (0xb8a575f8): 0:40)- (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a84178): 17:55) 
,W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/OtaApp  ( 2551): [debug] > DownloadActivity, FormattedText
,I/OtaApp  ( 2551): [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,D/Checkin ( 2551): publish the event [tag = MOT_OTA event name = LOG]
,I/OtaApp  ( 2551): [info] > Exceed max defer attempts for optional update, suppresing later btn
,D/Checkin ( 2551): publish the event [tag = MOT_OTA event name = LOG]
,D/OtaApp  ( 2551): [debug] > cancelling the previous pending intent set for download later
,I/OtaApp  ( 2551): [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,D/Checkin ( 2551): publish the event [tag = MOT_OTA event name = LOG]
,V/AlarmManager(  881): send {10fb8a4e, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService}
,V/AlarmManager(  881): done {10fb8a4e, *walarm*:com.android.vending/com.google.android.finsky.services.ContentSyncService} [2ms]
,W/IInputConnectionWrapper( 5316): showStatusIcon on inactive InputConnection
I/Keyboard.Facilitator( 1405): onFinishInput()
,D/Finsky  ( 5013): [590] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5013): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SFPerfTracer(  280):      triggers: (rate: 14:313) (compose: 0:2) (post: 0:1) (render: 0:3) (17:1145 frames) (18:1239)
D/SFPerfTracer(  280):        layers: (4:10) (FocusedStackFrame (0xb89e0230): 0:19)* (DimLayer (0xb8a01f98): 0:7) (StatusBar (0xb8a05150): 0:196) (NavigationBar (0xb8a86b48): 0:47) (com.android.systemui.ImageWallpaper (0xb8a42be0): 0:8)* (com.test.thalitest/com.test.thalitest.MainActivity (0xb8a84178): 1:82)* (com.motorola.ccc.ota/com.motorola.ccc.ota.ui.DownloadActivity (0xb8a575f8): 18:29) 
,I/ActivityManager(  881): Killing 5113:com.google.android.videos/u0a98 (adj 15): empty #7
,W/libprocessgroup(  881): failed to open /acct/uid_10098/pid_5113/cgroup.procs: No such file or directory
,D/TaskPersister(  881): removeObsoleteFile: deleting file=8_task.xml
,V/AlarmManager(  881): send {3d946081, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  881): done {3d946081, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [7ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:34000 mC
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=307, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2363000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311712, SEQNUM=4338, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-235, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,I/art     ( 2551): Explicit concurrent mark sweep GC freed 19318(1161KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 10MB/18MB, paused 1.075ms total 68.796ms
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1455): Explicit concurrent mark sweep GC freed 20773(1154KB) AllocSpace objects, 17(473KB) LOS objects, 39% free, 7MB/12MB, paused 985us total 39.458ms
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2551):  Nonce Reponse 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 60000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  881): send {1a15f1f6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  881): done {1a15f1f6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [3ms]
,V/AlarmManager(  881): send {3790be5b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): done {3790be5b, *alarm*:android.intent.action.TIME_TICK} [39ms]
,I/PowerManagerService(  881): Nap time (uid 1000)...
I/PowerManagerService(  881): Going to sleep due to screen timeout (uid 1000)...
,I/Adreno-EGL(  881): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
I/Adreno-EGL(  881): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  881): Build Date: 10/28/14 Tue
I/Adreno-EGL(  881): Local Branch: 
I/Adreno-EGL(  881): Remote Branch: quic/l_LNX.LA.3.6
I/Adreno-EGL(  881): Local Patches: NONE
I/Adreno-EGL(  881): Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,D/        (  881): activate, handle: 1598182242, enabled: 0, index 2
,D/        (  881): BstSensorExt: id=1598182242, en=0
D/        (  881): enable ID_SORI, path /sys/class/srot_sensor/g_sensor/en_disp_rotation, fd 221
,D/        (  881): activate, handle: 2, enabled: 0, index 5
,I/DisplayManagerService(  881): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  881): Display changed displayId=0
,D/SurfaceFlinger(  280): Set power mode=0, type=0 flinger=0xb8943550
,D/qdhwcomposer(  280): hwc_blank: Blanking display: 0
,I/rmt_storage(  293): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8d2e820
I/rmt_storage(  293): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  293): wakelock acquired: 1, error no: 42
I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1194138312)
,I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  293): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1194138312) wakelock released: 1, error no: 0
I/rmt_storage(  293): 
,I/rmt_storage(  293): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb8d2e820
,I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0
,I/qdhwcomposer(  280): enable_dcabc: Done setting OFF mode
D/qdhwcomposer(  280): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  881): Excessive delay in setPowerMode(): 323ms
,I/PowerManagerService(  881): Sleeping (uid 1000)...
,I/WindowManager(  881): AOD feature not enabled!
,W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,D/audio_hw_primary(  299): adev_set_parameters: enter: screen_state=on
,V/msm8974_platform(  299): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  299): platform_set_parameters: exit with code(0)
,E/msm8974_platform(  299): platform_update_tpa_poll: Could not get ctl for mixer cmd - TPA6165 POLL ACC DET
D/audio_hw_extn(  299): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  299): adev_set_parameters: ERROR: set param called even when stream out is null
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e7089c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb7389310, mCls = 0x201872
,I/WifiNative-HAL(  881): Could not start hal
D/WifiStateMachine(  881): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  881): setSuspendOptimizations: 4 false
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 4
,I/Keyboard.Facilitator( 1405): onFinishInput()
,D/        (  881): activate, handle: 1598182229, enabled: 0, index 0
E/        (  881): <BST> disable accel, orig state: 1
,I/        (  881): <BST> disable sensor <BOSCH BMC150 Acceleration Sensor>
,I/WifiNative-HAL(  881): startHal
E/wifi    (  881): getStaticLongField sWifiHalHandle 0xa2e7089c
D/wifi    (  881): halHandle = 0x0, mVM = 0xb7389310, mCls = 0x1836
I/WifiNative-HAL(  881): Could not start hal
D/WifiStateMachine(  881): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  881): handleScreenStateChanged Exit: false
,D/audio_hw_primary(  299): adev_set_parameters: enter: screen_state=off
V/msm8974_platform(  299): platform_set_parameters: enter: screen_state=off
,V/msm8974_platform(  299): platform_set_parameters: exit with code(0)
,E/WifiStateMachine(  881): setSuspendOptimizations: 4 true
E/WifiStateMachine(  881): mSuspendOptNeedsDisabled 0
,D/audio_hw_extn(  299): audio_extn_set_anc_parameters: anc_enabled:0
,E/audio_a2dp_hw(  299): adev_set_parameters: ERROR: set param called even when stream out is null
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:33000 mC
,W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,W/ContextImpl( 1455): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.motorola.motocare.internal.batterystats.BatteryStatsAction.onReceive:33 android.app.ActivityThread.handleReceiver:2611 
,V/AlarmManager(  881): send {23921880, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD}
,V/AlarmManager(  881): done {23921880, *walarm*:com.android.internal.policy.impl.PhoneWindowManager.DELAYED_KEYGUARD} [5ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=295, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310626, SEQNUM=4352, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-14122, POWER_SUPPLY_CHARGE_COUNTER=-341, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,V/AlarmManager(  881): send {1bab9eb9, *walarm*:com.google.android.intent.action.SEND_IDLE}
,V/AlarmManager(  881): done {1bab9eb9, *walarm*:com.google.android.intent.action.SEND_IDLE} [5ms]
,E/global frequency( 2551): no tags to log
,D/Checkin ( 2551): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/BSUtils ( 2551): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,D/BSUtils ( 2551): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2551): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2551): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     ( 1455): Explicit concurrent mark sweep GC freed 37810(2029KB) AllocSpace objects, 16(570KB) LOS objects, 39% free, 7MB/12MB, paused 515us total 34.471ms
,D/BSUtils ( 2551): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2551): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/BSUtils ( 2551): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,E/PhoneInterfaceManager( 1540): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,I/art     (  881): Explicit concurrent mark sweep GC freed 14186(858KB) AllocSpace objects, 6(256KB) LOS objects, 33% free, 20MB/31MB, paused 1.504ms total 123.883ms
,D/BSUtils ( 2551): Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,I/BSUtils ( 2551): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/BSUtils ( 2551): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,I/global frequency( 2551): BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,D/Checkin ( 2551): publish the event [tag = MOT_CHECKIN event name = LOG]
,E/global frequency( 2551): BcsDSCheckin.logProperties: BL State from property is null or empty
,D/Checkin ( 2551): publish the event [tag = MOT_CHECKIN event name = LOG]
,D/Checkin ( 2551): publish the event [tag = DEV_ATTRIBS event name = SW]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/global frequency( 2551): BcsDSCheckin.events found events 2000
,D/Checkin ( 2551): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/BSUtils ( 2551): failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(v1/cs/checkin)
,I/art     ( 2551): Explicit concurrent mark sweep GC freed 25125(1818KB) AllocSpace objects, 5(132KB) LOS objects, 40% free, 12MB/20MB, paused 852us total 59.652ms
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/CCE     ( 2551): AppWSProxy - handleResponse(): error=RadioDownError errorText= statusCode=0 reqId=
D/CCE     ( 2551): AppWSProxy - sendAIDLWSResponse() sending reponse
,I/ErrorTranslator( 2551): unknown error code mapping for: 0
I/global frequency( 2551): BcsCore.status() called with error code=ERROR_FAIL
,D/Checkin ( 2551): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/global frequency( 2551): BcsTimer.onReceive checkin completed (0:ERROR_FAIL)
,D/Checkin ( 2551): publish the event [tag = MOT_CHECKIN event name = LOG]
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,I/art     ( 1455): Explicit concurrent mark sweep GC freed 3210(127KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 4.391ms total 39.748ms
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2551):  Nonce Reponse 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 300000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:32000 mC
,I/ClearcutLoggerApiImpl( 1726): disconnect managed GoogleApiClient
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=287, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311398, SEQNUM=4356, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-11318, POWER_SUPPLY_CHARGE_COUNTER=-496, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,V/AlarmManager(  881): send {1a15f1f6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL}
,V/AlarmManager(  881): send {3790be5b, *alarm*:android.intent.action.TIME_TICK}
V/AlarmManager(  881): send {6de6d75, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
V/AlarmManager(  881): send {3d946081, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE}
,V/AlarmManager(  881): done {1a15f1f6, *alarm*:com.android.server.NetworkTimeUpdateService.action.POLL} [7ms]
,V/AlarmManager(  881): done {6de6d75, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [25ms]
V/AlarmManager(  881): done {3d946081, *walarm*:com.google.android.gms.gcm.ACTION_CHECK_QUEUE} [25ms]
,V/AlarmManager(  881): done {3790be5b, *alarm*:android.intent.action.TIME_TICK} [56ms]
,I/VacuumService( 1726): Vacuum at: now=1457577364216 tag=VacuumService
,I/Keyboard.Facilitator.LanguageModelFlusher( 1405): run()
,I/Keyboard.Facilitator( 1405): flushDynamicLanguageModels()
,I/ConfigService( 1726): onCreate
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ConfigService( 1726): onDestroy
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=278, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310994, SEQNUM=4364, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-6510, POWER_SUPPLY_CHARGE_COUNTER=-873, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:31000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/AlarmManager(  881): send {3790be5b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): done {3790be5b, *alarm*:android.intent.action.TIME_TICK} [36ms]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2551):  Nonce Reponse 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 600000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311182, SEQNUM=4369, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-8, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,V/AlarmManager(  881): send {3790be5b, *alarm*:android.intent.action.TIME_TICK}
,V/AlarmManager(  881): send {3b02ee91, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED}
V/AlarmManager(  881): send {25d3b6d1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver}
,V/AlarmManager(  881): done {3b02ee91, *walarm*:android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED} [19ms]
,V/AlarmManager(  881): done {3790be5b, *alarm*:android.intent.action.TIME_TICK} [43ms]
,V/AlarmManager(  881): done {25d3b6d1, *walarm*:com.google.android.gms/.checkin.EventLogService$Receiver} [108ms]
,I/EventLogService( 4856): Aggregate from 1457576347959 (log), 1457576347959 (data)
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=270, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310878, SEQNUM=4372, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-20, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(/v1/gdi/nonce.json)
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: nonce.json
I/ Nonce  ( 2551):  Nonce Reponse 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: nonce.json
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): MMAPIWebServiceRequest backOff fired!
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,D/MMApiWebService( 2551): MMApiBackOffService told us it's okay to retry the waiting requests: 1
,D/MMApiWebService( 2551): doRequest() with req : MMApiWSRequest(v1/gns/list/messages)
,I/art     (  881): Explicit concurrent mark sweep GC freed 12842(674KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/31MB, paused 1.930ms total 115.026ms
,D/MMApiWebService( 2551): doRequest(): polling manager says we're not connected, returning with an error: 
I/MMApiWebService( 2551): inspectMMApiResponse(): found an error from a web service response: RadioDownError msg: RadioDownError req: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiBackOffService( 2551): connectStatus(): app: MMAPIWebServiceRequest backing off: 1200000 ms until next web service attempt
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/MMApiWebService( 2551): MMApiWebService told us not to continue at the moment with this request: 
,D/Checkin ( 2551): publish the event [tag = MOT_CCE event name = LOG]
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/MDMCTBK (  297): NetlinkHandler, power_supply subsys
I/MDMCTBK (  297): NetlinkHandler, usbChargerStateChanged
I/MDMCTBK (  297): checkDefaultInst, current pid is = 297
I/MDMCTBK (  297): checkDefaultInst, pid match
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
I/MDMCTBK (  297): MdmCutbackHndler,readFromFile = 
E/MDMCTBK (  297): MdmCutbackHndler,Could not open ''
,D/BatteryService(  881): uevent={POWER_SUPPLY_TEMP=269, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2365000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4310861, SEQNUM=4375, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-3705, POWER_SUPPLY_CHARGE_COUNTER=-23, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/UsageStatsService(  881): User[0] Flushing usage stats to disk
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,I/ThermalEngine(  313): Sensor:xo_therm_pu2:30000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 5561): 
D/AndroidRuntime( 5561): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5561): CheckJNI is OFF
D/AndroidRuntime( 5561): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10566 user=-1: uninstall pkg
I/ActivityManager(  881): Killing 5316:com.test.thalitest/u0a566 (adj 11): stop com.test.thalitest
D/WifiService(  881): Client connection lost with reason: 4
W/PackageSettings(  881): Skipping PackageSetting{365a0131 com.example.hello/10564} due to missing metadata
W/ActivityManager(  881): Spurious death for ProcessRecord{38f57928 5316:com.test.thalitest/u0a566}, curProc for 5316: null
I/ActivityManager(  881): Force stopping com.test.thalitest appid=10566 user=0: pkg removed
I/art     ( 2943): Explicit concurrent mark sweep GC freed 3701(791KB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 7MB/12MB, paused 601us total 28.709ms
I/Keyboard.Facilitator( 1405): resetDictionaries() : en_US
I/InputReader(  881): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1726): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  881): Start proc android.process.acore for broadcast com.android.providers.contacts/.PackageIntentReceiver: pid=5580 uid=10007 gids={50007, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
I/art     (  317): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 243us total 31.342ms
I/Keyboard.Facilitator.DecoderInitializer( 1405): run()
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.472ms
I/art     ( 4856): Explicit concurrent mark sweep GC freed 5026(315KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 12MB/17MB, paused 700us total 145.087ms
I/Decoder ( 1405): createOrResetDecoder
I/art     (  317): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 254us total 20.218ms
I/art     ( 4914): Explicit concurrent mark sweep GC freed 633(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 9MB/12MB, paused 414us total 143.236ms
I/ConfigService( 1726): onCreate
I/art     ( 1559): Explicit concurrent mark sweep GC freed 7296(530KB) AllocSpace objects, 3(148KB) LOS objects, 25% free, 13MB/17MB, paused 503us total 154.790ms
I/SFPerfTracer(  280):      triggers: (rate: 0:0) (0 sw vsyncs) (0 skipped) (23:376 vsyncs) (25:1275)
I/art     (  881): Explicit concurrent mark sweep GC freed 8735(723KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 20MB/31MB, paused 1.687ms total 188.913ms
I/art     (  881): WaitForGcToComplete blocked for 63.596ms for cause Explicit
I/CheckinRequestBuilder( 1726): Classify the device as Phone.
D/VoicemailCleanupService( 5580): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  881): Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5615 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
I/ContactLocale( 5580): AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
D/BackupManagerService(  881): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  881): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task.xml
D/TaskPersister(  881): removeObsoleteFile: deleting file=9_task_thumbnail.png
I/Launcher( 1559): Deferring update until onResume
W/asset   ( 5615): Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
W/ResourcesManager( 5615): Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
W/ResourcesManager( 5615): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5615): Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
I/art     (  881): Explicit concurrent mark sweep GC freed 4232(202KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 21MB/31MB, paused 1.979ms total 206.136ms
I/art     ( 1726): Explicit concurrent mark sweep GC freed 36058(2MB) AllocSpace objects, 11(176KB) LOS objects, 40% free, 13MB/22MB, paused 1.102ms total 84.303ms
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1e7aabcb)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@4952fa8)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2bfaaac1)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2c07b266)
E/DataBuffer( 1726): Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@388639a7)
W/FetchTask( 1726): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ActivityManager(  881): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5637 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  881): Killing 4914:com.google.android.googlequicksearchbox:search/u0a39 (adj 15): empty #7
I/CheckinRequestBuilder( 1726): Classify the device as Phone.
D/AndroidRuntime( 5561): Shutting down VM
W/libprocessgroup(  881): failed to open /acct/uid_10039/pid_4914/cgroup.procs: No such file or directory
W/FetchTask( 1726): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/CheckinRequestBuilder( 1726): Classify the device as Phone.
W/ContextImpl( 5637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
W/FetchTask( 1726): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/PackageBroadcastService( 4856): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4856): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/AccountUtils( 4856): Clearing selected account for com.test.thalitest
D/ChimeraModuleLdr( 4856): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4856): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4856): Module APK com.google.android.play.games already loaded
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid parameter app
E/NetworkScheduler.SchedulerReceiver( 1726): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
I/CheckinRequestBuilder( 1726): Classify the device as Phone.
I/ActivityManager(  881): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=5662 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/LocationSettingsChecker( 4856): Removing dialog suppression flag for package com.test.thalitest
W/FetchTask( 1726): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/gH_CompatibleDatabase( 4856): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 4856): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/gH_MetricsDatabase( 4856): 0 metrics were deleted when clearing package com.test.thalitest.
D/gH_CompatibleDatabase( 4856): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
D/gH_CompatibleDatabase( 4856): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
D/gH_CompatibleDatabase( 4856): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
D/gH_CompatibleDatabase( 4856): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
W/BaseAppContext( 4856): Using Auth Proxy for data requests.
D/gH_CompatibleDatabase( 4856): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
D/gH_CompatibleDatabase( 4856): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
D/gH_CompatibleDatabase( 4856): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/gH_CompatibleDatabase( 4856): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/gH_CompatibleDatabase( 4856): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
D/gH_CompatibleDatabase( 4856): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
W/BaseAppContext( 4856): Using Auth Proxy for data requests.
I/GMPM-SVC( 4856): App measurement is starting up, version: 8489
I/GMPM-SVC( 4856): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
W/Launcher( 1559): setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1b32972a new=com.google.android.velvet.VelvetApplication@1b32972a
I/ActivityManager(  881): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5690 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/CheckinRequestBuilder( 1726): Classify the device as Phone.
W/FetchTask( 1726): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
--------- beginning of crash
E/AndroidRuntime( 1726): FATAL EXCEPTION: Thread-243
E/AndroidRuntime( 1726): Process: com.google.android.gms.persistent, PID: 1726
E/AndroidRuntime( 1726): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 1726): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
E/AndroidRuntime( 1726): 	at com.google.android.gms.config.j.a(SourceFile:1163)
E/AndroidRuntime( 1726): 	at com.google.android.gms.config.t.run(SourceFile:76)
E/AndroidRuntime( 1726): 	at java.lang.Thread.run(Thread.java:818)
I/Process ( 1726): Sending signal. PID: 1726 SIG: 9
D/GpsStatusListenerHelper(  881): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@31b89dd5
D/WifiService(  881): Client connection lost with reason: 4
V/BackupManagerService(  881): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  881): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
E/DropBoxManagerService(  881): Can't write: system_app_crash
E/DropBoxManagerService(  881): java.io.IOException: Can't rename /data/system/dropbox/drop94.tmp to /data/system/dropbox/system_app_crash@1457578475570.txt
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService$EntryFile.<init>(DropBoxManagerService.java:504)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.createEntry(DropBoxManagerService.java:685)
E/DropBoxManagerService(  881): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:245)
E/DropBoxManagerService(  881): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  881): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12258)
W/FileUtils( 4856): Failed to chmod(/data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
I/Icing   ( 4856): doRemovePackageData com.test.thalitest
I/ActivityManager(  881): Process com.google.android.gms.persistent (pid 1726) has died
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 1000ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 10999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 20999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 30999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 40999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 50999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 60999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 70999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 80999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geofencer.service.GeofenceProviderService in 90999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.service.FusedProviderService in 100999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 110999ms
W/ActivityManager(  881): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 120999ms
I/qdhwcomposer(  280): handle_blank_event: dpy:0 panel power state: 0

```
