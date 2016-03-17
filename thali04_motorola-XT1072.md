#### Test 63186632d456b18_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,03-17 09:52:17.726   895  1231 D BatteryService: uevent={POWER_SUPPLY_TEMP=286, POWER_SUPPLY_STATUS=Full, POWER_SUPPLY_CAPACITY=100, ACTION=change, DEVPATH=/devices/qpnp-charger-e49e5a00/power_supply/battery, POWER_SUPPLY_VOLTAGE_OCV=-22, POWER_SUPPLY_ONLINE=1, SUBSYSTEM=power_supply, POWER_SUPPLY_NUM_SYSTEM_TEMP_LEVELS=4, POWER_SUPPLY_INPUT_CURRENT_MAX=500000, POWER_SUPPLY_VOLTAGE_MAX_DESIGN=4350000, POWER_SUPPLY_CHARGE_FULL=2364000, POWER_SUPPLY_NAME=battery, POWER_SUPPLY_VOLTAGE_MIN_DESIGN=4300000, POWER_SUPPLY_VOLTAGE_MIN=4300000, POWER_SUPPLY_HEALTH=Good, POWER_SUPPLY_CYCLE_COUNT=0, POWER_SUPPLY_TECHNOLOGY=Li-ion, POWER_SUPPLY_CHARGE_TYPE=Fast, POWER_SUPPLY_PRESENT=1, POWER_SUPPLY_INPUT_CURRENT_SETTLED=0, POWER_SUPPLY_MODEL_NAME=UNKNOWN, POWER_SUPPLY_VOLTAGE_NOW=4311709, SEQNUM=4461, POWER_SUPPLY_TEMP_WARM=450, POWER_SUPPLY_TEMP_COOL=0, POWER_SUPPLY_CHARGE_FULL_DESIGN=2366000, POWER_SUPPLY_CURRENT_NOW=-1001, POWER_SUPPLY_CHARGE_COUNTER=-109, POWER_SUPPLY_SYSTEM_TEMP_LEVEL=0, POWER_SUPPLY_INPUT_CURRENT_TRIM=41, POWER_SUPPLY_VOLTAGE_EMPTY=3200000, POWER_SUPPLY_CHARGE_RATE=Normal, POWER_SUPPLY_INPUT_VOLTAGE_REGULATION=0, POWER_SUPPLY_CHARGING_ENABLED=1}
--------- beginning of main
03-17 09:52:17.820  2769  2833 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 09:52:17.894  2769  2833 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-17 09:52:18.073  5872  5872 D AndroidRuntime: 
03-17 09:52:18.073  5872  5872 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 09:52:18.077  5872  5872 D AndroidRuntime: CheckJNI is OFF
03-17 09:52:18.217  5872  5872 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 09:52:18.228   895  1929 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-17 09:52:18.281   895  1929 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5898 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 09:52:18.284  5872  5872 D AndroidRuntime: Shutting down VM
03-17 09:52:18.301   895   895 V ActivityManager: Display changed displayId=0
03-17 09:52:18.311  1477  4183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 09:52:18.323  1477  4183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 09:52:18.444  5898  5898 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-17 09:52:18.463  5898  5898 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2945-2947)
03-17 09:52:18.463  5898  5898 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 09:52:18.480  5898  5898 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3db85fad}
03-17 09:52:18.480  5898  5898 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 09:52:18.481  5898  5898 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-17 09:52:18.501  5898  5898 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 09:52:18.501  5898  5898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:52:18.502  5898  5898 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 09:52:18.520  5898  5898 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-17 09:52:18.524  5898  5898 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 09:52:18.524  5898  5898 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-17 09:52:18.525  5898  5898 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-17 09:52:18.525  5898  5898 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-17 09:52:18.525  5898  5898 I Adreno-EGL: Build Date: 10/28/14 Tue
03-17 09:52:18.525  5898  5898 I Adreno-EGL: Local Branch: 
03-17 09:52:18.525  5898  5898 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-17 09:52:18.525  5898  5898 I Adreno-EGL: Local Patches: NONE
03-17 09:52:18.525  5898  5898 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-17 09:52:18.588   895  1148 D BluetoothManagerService: Message: 20
03-17 09:52:18.588   895  1148 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2be0d4b6:true
,03-17 09:52:18.748  5898  5898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:52:18.773  5898  5898 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 09:52:18.803  5898  5898 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-17 09:52:18.811  5898  5898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-17 09:52:18.811  5898  5898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 09:52:18.817   895  1135 W ActivityManager: Activity pause timeout for ActivityRecord{2ebd2e63 u0 com.test.thalitest/.MainActivity t9}
,03-17 09:52:18.876  5898  5940 D OpenGLRenderer: Render dirty regions requested: true
,03-17 09:52:18.895  5898  5898 D Atlas   : Validating map...
,03-17 09:52:18.909  5898  5927 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 09:52:18.962  5898  5940 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 09:52:18.969  5898  5940 D OpenGLRenderer: Enabling debug mode 0
,03-17 09:52:18.995  1433  1433 I Keyboard.Facilitator: onFinishInput()
,03-17 09:52:19.007   895  1149 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,765
03-17 09:52:19.007   895  1149 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +690ms (total +765ms)
,03-17 09:52:19.012  5898  5898 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 09:52:19.163  5898  5944 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
,03-17 09:52:19.163  5898  5944 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-17 09:52:19.193  5898  5898 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5898
,03-17 09:52:19.348  5898  5898 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 09:52:19.673  5898  5942 D jxcore_app_log: JniHelper::setJavaVM(0xb8045310), pthread_self() = -1203911584
,03-17 09:52:19.679  5898  5942 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 09:52:19.679  5898  5942 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 09:52:19.679  5898  5942 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 09:52:19.679  5898  5942 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 09:52:19.679  5898  5942 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-17 09:52:19.679  5898  5942 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dcbaf90 added. We now have 1 listener(s)
,03-17 09:52:19.679   895  1518 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 09:52:19.682  5898  5942 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-17 09:52:19.684  5898  5942 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 09:52:19.685  5898  5942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-17 09:52:19.685  5898  5942 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"44:80:EB:7B:5A:05"}
03-17 09:52:19.685  5898  5942 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 09:52:19.685  5898  5942 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: MANUFACTURER_DATA
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-17 09:52:19.689  5898  5942 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64508af added. We now have 1 listener(s)
03-17 09:52:19.689  5898  5942 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 09:52:19.693   895  1249 D WifiService: New client listening to asynchronous messages
,03-17 09:52:19.695  5898  5942 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-17 09:52:19.700  5898  5942 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,03-17 09:52:19.700  5898  5942 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-17 09:52:19.703  5898  5942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 09:52:19.703   895  1526 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-17 09:52:19.704  5898  5942 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 09:52:19.709  5898  5942 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-17 09:52:19.710  5898  5942 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-17 09:52:19.710  5898  5942 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 09:52:19.711  5898  5898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:52:19.713  5898  5898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 09:52:19.743  5898  5898 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 09:52:20.543  5898  5948 W jxcore-log: Initializing JXcore engine
03-17 09:52:20.543  5898  5948 W jxcore-log: JXcore engine is ready
,03-17 09:52:20.637  5948  5948 W Thread-634: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[5663]" dev="sockfs" ino=5663 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 09:52:20.637  5948  5948 W Thread-634: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-17 09:52:20.637  5948  5948 W Thread-634: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9388]" dev="sockfs" ino=9388 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-17 09:52:20.637  5948  5948 W Thread-634: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[28919]" dev="sockfs" ino=28919 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-17 09:52:20.670  5898  5948 W jxcore-log: Starting JXcore engine
,03-17 09:52:20.798  5898  5948 W jxcore-log: Platform android
03-17 09:52:20.798  5898  5948 W jxcore-log: 
,03-17 09:52:20.798  5898  5948 W jxcore-log: Process ARCH arm
03-17 09:52:20.798  5898  5948 W jxcore-log: 
,03-17 09:52:21.084  5898  5948 I jxcore-log: JXcore Cordova bridge is ready!
03-17 09:52:21.084  5898  5948 I jxcore-log: 
03-17 09:52:21.084  5898  5948 W jxcore-log: JXcore engine is started
,03-17 09:52:21.089  5898  5942 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 09:52:21.090  5898  5898 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-17 09:52:21.104  5898  5948 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 09:52:21.104  5898  5948 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 09:52:21.111  5898  5898 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-17 09:52:21.112  5898  5898 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 09:52:21.118   895  1512 I ActivityManager: Killing 5657:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-17 09:52:21.137   895   911 W libprocessgroup: failed to open /acct/uid_10090/pid_5657/cgroup.procs: No such file or directory
03-17 09:52:21.139  5898  5942 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
03-17 09:52:21.144  1477  4183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-17 09:52:21.152  1477  4183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-17 09:52:21.175  2876  2876 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-17 09:52:21.178  2876  2876 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-17 09:52:21.179  2876  2876 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 09:52:21.182  2876  2876 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-17 09:52:21.183  2876  2876 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 09:52:21.187  2876  2876 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-17 09:52:21.188  2876  2876 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-17 09:52:21.189  2876  2876 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-17 09:52:21.193  5898  5898 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@a23ec45 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:52:21.193  5898  5898 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@a23ec45 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-17 09:52:21.193  5898  5898 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 09:52:21.198  5898  5898 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@1a6434bc that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:52:21.198  5898  5898 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@1a6434bc that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:907)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:708)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1771)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1751)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1745)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
03-17 09:52:21.198  5898  5898 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 09:52:21.230  5898  5898 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 09:52:21.264  1433  1433 I Keyboard.Facilitator: onFinishInput()
,03-17 09:52:21.455  5950  5950 D AndroidRuntime: 
03-17 09:52:21.455  5950  5950 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 09:52:21.464  5950  5950 D AndroidRuntime: CheckJNI is OFF
,03-17 09:52:21.555   895  1236 V AlarmManager: send {2a56ecb5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE}
,03-17 09:52:21.557   895   895 V AlarmManager: done {2a56ecb5, *walarm*:com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE} [1ms]
,03-17 09:52:21.682  5950  5950 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 09:52:21.699   895  1135 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
03-17 09:52:21.699   895  1135 I ActivityManager: Killing 5898:com.test.thalitest/u0a109 (adj 9): stop com.test.thalitest
,03-17 09:52:21.733   895  1249 D WifiService: Client connection lost with reason: 4
,03-17 09:52:21.780   895  1159 W PackageSettings: Skipping PackageSetting{353afd7c com.example.hello/10568} due to missing metadata
,03-17 09:52:21.808   895  1159 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-17 09:52:21.856  3320  3320 I art     : Explicit concurrent mark sweep GC freed 9555(2MB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 7MB/12MB, paused 1.635ms total 37.836ms
,03-17 09:52:21.906   895  1526 W ActivityManager: Spurious death for ProcessRecord{c201f4a 5898:com.test.thalitest/u0a109}, curProc for 5898: null
,03-17 09:52:21.916   895  1238 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 09:52:21.930  1565  1565 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-17 09:52:21.940  1583  1583 I art     : Explicit concurrent mark sweep GC freed 2525(133KB) AllocSpace objects, 3(128KB) LOS objects, 25% free, 13MB/17MB, paused 482us total 68.377ms
,03-17 09:52:21.952  1433  1433 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-17 09:52:21.954  2042  2164 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 09:52:21.957  1433  5990 I Keyboard.Facilitator.DecoderInitializer: run()
,03-17 09:52:21.964  1433  5990 I Decoder : createOrResetDecoder
,03-17 09:52:21.967  1634  5991 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-17 09:52:21.989  1967  1980 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-17 09:52:21.991  1967  1967 I art     : Explicit concurrent mark sweep GC freed 3610(200KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/19MB, paused 987us total 174.129ms
,03-17 09:52:22.006   895  1529 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5993 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-17 09:52:22.021   895   895 I art     : Explicit concurrent mark sweep GC freed 18345(1237KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 2.166ms total 154.965ms
,03-17 09:52:22.022   895  1159 I art     : WaitForGcToComplete blocked for 52.637ms for cause Explicit
,03-17 09:52:22.046  2042  2042 I ConfigService: onCreate
,03-17 09:52:22.076   306   410 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-17 09:52:22.090  5993  5993 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
,03-17 09:52:22.090  5993  5993 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-17 09:52:22.091  5993  5993 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-17 09:52:22.091  5993  5993 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-17 09:52:22.111  1433  5990 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-17 09:52:22.170   895   895 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-17 09:52:22.170   895   895 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-17 09:52:22.185   895   911 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6017 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,03-17 09:52:22.187   895  1267 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
,03-17 09:52:22.187   895  1267 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-17 09:52:22.203  1433  5990 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-17 09:52:22.206  1433  5990 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-17 09:52:22.206  1433  5990 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-17 09:52:22.236   895  1159 I art     : Explicit concurrent mark sweep GC freed 9376(710KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 20MB/30MB, paused 2.016ms total 212.364ms
,03-17 09:52:22.253  1583  1583 I Launcher: Deferring update until onResume
,03-17 09:52:22.255  1433  5990 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-17 09:52:22.255  1433  5990 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-17 09:52:22.257  1433  5990 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-17 09:52:22.257  1433  5990 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-17 09:52:22.260  1433  5990 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-17 09:52:22.262  1433  5990 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-17 09:52:22.262  1433  5990 I Keyboard.Facilitator.Delight2FileSweeper: run()
,03-17 09:52:22.262  1433  5990 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-17 09:52:22.262  1433  5990 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-17 09:52:22.262  1433  5990 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-17 09:52:22.334  5950  5950 D AndroidRuntime: Shutting down VM
,03-17 09:52:22.352  6017  6017 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,03-17 09:52:22.382   895  1159 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6036 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-17 09:52:22.441   895  1930 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6054 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-17 09:52:22.449   895   910 I ActivityManager: Killing 5430:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-17 09:52:22.480   895  1529 W libprocessgroup: failed to open /acct/uid_10005/pid_5430/cgroup.procs: No such file or directory
,03-17 09:52:22.488   895   910 I ActivityManager: Killing 5630:com.google.android.gms:car/u0a16 (adj 15): empty #7
,03-17 09:52:22.546   895  1600 W libprocessgroup: failed to open /acct/uid_10016/pid_5630/cgroup.procs: No such file or directory
,03-17 09:52:22.566  1583  1583 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@184f0b2e new=com.google.android.velvet.VelvetApplication@184f0b2e
,03-17 09:52:22.577  1967  6077 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-17 09:52:22.578  1967  6077 D AccountUtils: Clearing selected account for com.test.thalitest
,03-17 09:52:22.610  1967  6077 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-17 09:52:22.619  2042  2042 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-17 09:52:22.619  2042  2042 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-17 09:52:22.662   895  1601 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6084 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-17 09:52:22.755  1967  6095 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 09:52:22.769  1967  6095 W BaseAppContext: Using Auth Proxy for data requests.
,03-17 09:52:22.808  1967  6077 I GMPM-SVC: App measurement is starting up, version: 8703
,03-17 09:52:22.808  1967  6077 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-17 09:52:22.878   895  1608 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6116 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-17 09:52:22.897  1967  6122 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-17 09:52:22.898  1967  2101 I Icing   : doRemovePackageData com.test.thalitest
,03-17 09:52:22.909  1967  2740 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-17 09:52:22.910  1967  2740 E Icing   : Failed to open Apps corpus file.
,03-17 09:52:22.917  1967  6112 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2307)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:52:22.917  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
03-17 09:52:22.918  1967  6112 E GMPM-SVC: Opening the database failed, dropping and recreating it
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open,(SQLiteConnection.java:209)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:52:22.920  1967  6112 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
03-17 09:52:22.921  1967  6112 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-17 09:52:22.922  1967  6112 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-17 09:52:22.923  1967  6112 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-17 09:52:22.917  1967  2740 E Icing   : Failed to open Apps corpus file.
03-17 09:52:22.926  1967  6112 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
03-17 09:52:22.926  1967  2740 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
03-17 09:52:22.926  1967  6112 E GMPM-SVC: Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
03-17 09:52:22.946   895  1527 I ActivityManager: Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6136 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
03-17 09:52:22.950   281   709 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
03-17 09:52:22.951  6054  6075 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml to backup file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml.bak
--------- beginning of crash
03-17 09:52:22.953  6054  6075 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
03-17 09:52:22.953  6054  6075 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6054
03-17 09:52:22.953  6054  6075 E AndroidRuntime: java.lang.RuntimeException: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:108)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.j.c(ExtraDexRegistry.java:214)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.bb(UpdateIcingCorporaService.java:232)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:205)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: Caused by: java.util.concurrent.ExecutionException: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.util.concurrent.FutureTask.report(FutureTask.java:93)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.util.concurrent.FutureTask.get(FutureTask.java:163)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.d.get(LazyListenableFuture.java:124)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.j.e(ExtraDexRegistry.java:94)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	... 7 more
03-17 09:52:22.953  6054  6075 E AndroidRuntime: Caused by: com.google.android.libraries.velour.dynloader.h: Failed to load JAR icingsync
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:216)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k.auz(ExtraDexRegistry.java:344)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k.a(ExtraDexRegistry.java:303)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k$1.auD(ExtraDexRegistry.java:323)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.e.k$1.call(ExtraDexRegistry.java:318)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: Caused by: java.io.IOException: open failed: EROFS (Read-only file system)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:941)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjP(JarLoader.java:278)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at com.google.android.libraries.velour.dynloader.i.bjO(JarLoader.java:207)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	... 9 more
03-17 09:52:22.953  6054  6075 E AndroidRuntime: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at libcore.io.Posix.open(Native Method)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	at java.io.File.createNewFile(File.java:934)
03-17 09:52:22.953  6054  6075 E AndroidRuntime: 	... 11 more

```
