#### Test 62548124ca582f4_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,03-19 11:47:36.612   885  1225 V AlarmManager: send {a7fc163, *walarm*:com.google.android.intent.action.SEND_IDLE}
03-19 11:47:36.627   885   885 V AlarmManager: done {a7fc163, *walarm*:com.google.android.intent.action.SEND_IDLE} [15ms]
--------- beginning of main
03-19 11:47:37.022  6225  6225 D AndroidRuntime: 
03-19 11:47:37.022  6225  6225 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 11:47:37.028  6225  6225 D AndroidRuntime: CheckJNI is OFF
03-19 11:47:37.331  6225  6225 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-19 11:47:37.341   885  1495 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-19 11:47:37.386   885  1495 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6244 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 11:47:37.387  6225  6225 D AndroidRuntime: Shutting down VM
03-19 11:47:37.420   885   885 V ActivityManager: Display changed displayId=0
03-19 11:47:37.429  1480  4062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-19 11:47:37.436  1480  4062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-19 11:47:37.564  6244  6244 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-19 11:47:37.583  6244  6244 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6181-6183)
03-19 11:47:37.584  6244  6244 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-19 11:47:37.610  6244  6244 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2841c663}
03-19 11:47:37.611  6244  6244 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 11:47:37.611  6244  6244 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-19 11:47:37.626  6244  6244 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-19 11:47:37.627  6244  6244 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:47:37.628  6244  6244 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-19 11:47:37.644  6244  6244 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-19 11:47:37.648  6244  6244 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 11:47:37.648  6244  6244 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 11:47:37.649  6244  6244 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-19 11:47:37.649  6244  6244 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-19 11:47:37.649  6244  6244 I Adreno-EGL: Build Date: 10/28/14 Tue
03-19 11:47:37.649  6244  6244 I Adreno-EGL: Local Branch: 
03-19 11:47:37.649  6244  6244 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-19 11:47:37.649  6244  6244 I Adreno-EGL: Local Patches: NONE
03-19 11:47:37.649  6244  6244 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-19 11:47:37.724   885  1133 D BluetoothManagerService: Message: 20
03-19 11:47:37.724   885  1133 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f1c58b7:true
,03-19 11:47:37.882  6244  6244 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:47:37.912  6244  6244 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-19 11:47:37.935   885  1102 W ActivityManager: Activity pause timeout for ActivityRecord{1ae3b160 u0 com.test.thalitest/.MainActivity t9}
,03-19 11:47:37.948  6244  6244 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-19 11:47:37.956  6244  6244 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:47:37.956  6244  6244 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 11:47:38.007   302   373 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-19 11:47:38.016  6244  6287 D OpenGLRenderer: Render dirty regions requested: true
,03-19 11:47:38.035  6244  6244 D Atlas   : Validating map...
,03-19 11:47:38.043  6244  6274 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-19 11:47:38.096  6244  6287 I OpenGLRenderer: Initialized EGL, version 1.4
,03-19 11:47:38.104  6244  6287 D OpenGLRenderer: Enabling debug mode 0
,03-19 11:47:38.136  1418  1418 I Keyboard.Facilitator: onFinishInput()
,03-19 11:47:38.149   885  1134 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,796
,03-19 11:47:38.150   885  1134 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +715ms (total +796ms)
03-19 11:47:38.155  6244  6244 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-19 11:47:38.290  6244  6290 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-19 11:47:38.290  6244  6290 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-19 11:47:38.320  6244  6244 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6244
,03-19 11:47:38.477  6244  6244 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 11:47:38.804  6244  6289 D jxcore_app_log: JniHelper::setJavaVM(0xb8031310), pthread_self() = -1203994000
,03-19 11:47:38.814  6244  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 11:47:38.814  6244  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 11:47:38.814  6244  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-19 11:47:38.814  6244  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 11:47:38.814  6244  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-19 11:47:38.814  6244  6289 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ea9e53e added. We now have 1 listener(s)
,03-19 11:47:38.815   885  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 11:47:38.818  6244  6289 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-19 11:47:38.820  6244  6289 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:80:EB:7B:5A:05"
,03-19 11:47:38.823  6244  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-19 11:47:38.823  6244  6289 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-19 11:47:38.826  6244  6289 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c2c4b5 added. We now have 1 listener(s)
03-19 11:47:38.826  6244  6289 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-19 11:47:38.831   885  1239 D WifiService: New client listening to asynchronous messages
,03-19 11:47:38.833  6244  6289 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-19 11:47:38.838  6244  6289 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-19 11:47:38.838  6244  6289 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-19 11:47:38.842  6244  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-19 11:47:38.842   885   900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 11:47:38.843  6244  6289 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 11:47:38.848  6244  6289 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 11:47:38.849  6244  6289 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-19 11:47:38.849  6244  6289 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-19 11:47:38.851  6244  6289 I io.jxcore.node.LifeCycleMonitor: start: OK
03-19 11:47:38.851  6244  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-19 11:47:38.852  6244  6244 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 11:47:38.889  6244  6244 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 11:47:39.625  6244  6296 W jxcore-log: Initializing JXcore engine
03-19 11:47:39.625  6244  6296 W jxcore-log: JXcore engine is ready
,03-19 11:47:39.728  6296  6296 W Thread-735: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[7419]" dev="sockfs" ino=7419 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-19 11:47:39.728  6296  6296 W Thread-735: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-19 11:47:39.728  6296  6296 W Thread-735: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[6467]" dev="sockfs" ino=6467 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-19 11:47:39.728  6296  6296 W Thread-735: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[29500]" dev="sockfs" ino=29500 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-19 11:47:39.764  6244  6296 W jxcore-log: Starting JXcore engine
,03-19 11:47:39.892  6244  6296 W jxcore-log: Platform android
03-19 11:47:39.892  6244  6296 W jxcore-log: 
03-19 11:47:39.892  6244  6296 W jxcore-log: Process ARCH arm
03-19 11:47:39.892  6244  6296 W jxcore-log: 
,03-19 11:47:40.172  6244  6296 I jxcore-log: JXcore Cordova bridge is ready!
03-19 11:47:40.172  6244  6296 I jxcore-log: 
03-19 11:47:40.173  6244  6296 W jxcore-log: JXcore engine is started
,03-19 11:47:40.176  6244  6289 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-19 11:47:40.178  6244  6244 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-19 11:47:40.186  6244  6296 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-19 11:47:40.186  6244  6296 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-19 11:47:40.193  6244  6244 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-19 11:47:40.195  6244  6244 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-19 11:47:40.201   885  1573 I ActivityManager: Killing 6013:com.motorola.context/u0a8 (adj 15): empty #7
,03-19 11:47:40.248   885  1517 W libprocessgroup: failed to open /acct/uid_10008/pid_6013/cgroup.procs: No such file or directory
03-19 11:47:40.248  6244  6244 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
03-19 11:47:40.249  6244  6244 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-19 11:47:40.249  6244  6244 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
03-19 11:47:40.249  6244  6244 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-19 11:47:40.249  6244  6244 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-19 11:47:40.249  6244  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
03-19 11:47:40.249  6244  6244 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ea9e53e removed from the list
03-19 11:47:40.249  6244  6244 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
03-19 11:47:40.249  6244  6244 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28c2c4b5 removed from the list
03-19 11:47:40.250  6244  6244 D io.jxcore.node.ConnectivityMonitor: stop
03-19 11:47:40.250  6244  6244 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,03-19 11:47:40.252  6244  6289 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 55ms. Plugin should use CordovaInterface.getThreadPool().
,03-19 11:47:40.262  1480  4062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-19 11:47:40.276  6244  6244 I io.jxcore.node.LifeCycleMonitor: stop: OK
03-19 11:47:40.285  1480  4062 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-19 11:47:40.299  2618  2618 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-19 11:47:40.304  2618  2618 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-19 11:47:40.309  2618  2618 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-19 11:47:40.314  2618  2618 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-19 11:47:40.317  2618  2618 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-19 11:47:40.321  2618  2618 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-19 11:47:40.323  2618  2618 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-19 11:47:40.327  2618  2618 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-19 11:47:40.381  6244  6244 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-19 11:47:40.382  1418  1418 I Keyboard.Facilitator: onFinishInput()
,03-19 11:47:40.527  6305  6305 D AndroidRuntime: 
03-19 11:47:40.527  6305  6305 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-19 11:47:40.531  6305  6305 D AndroidRuntime: CheckJNI is OFF
,03-19 11:47:40.700  6305  6305 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-19 11:47:40.712   885  1102 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-19 11:47:40.713   885  1102 I ActivityManager: Killing 6244:com.test.thalitest/u0a109 (adj 9): stop com.test.thalitest
,03-19 11:47:40.750   885  1239 D WifiService: Client connection lost with reason: 4
,03-19 11:47:40.777   885  1148 W PackageSettings: Skipping PackageSetting{1d9e1e0a com.example.hello/10568} due to missing metadata
,03-19 11:47:40.820   885  1517 W ActivityManager: Spurious death for ProcessRecord{1df17e4a 6244:com.test.thalitest/u0a109}, curProc for 6244: null
03-19 11:47:40.820   885  1148 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-19 11:47:40.861  3238  3238 I art     : Explicit concurrent mark sweep GC freed 9189(2MB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 908us total 37.519ms
,03-19 11:47:40.911  1962  2171 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-19 11:47:40.919  1418  1418 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-19 11:47:40.931   885  1227 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-19 11:47:40.939  1574  1574 I art     : Explicit concurrent mark sweep GC freed 2274(121KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 500us total 96.378ms
,03-19 11:47:40.957  1418  6344 I Keyboard.Facilitator.DecoderInitializer: run()
,03-19 11:47:40.960  1615  6345 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-19 11:47:40.971  1418  6344 I Decoder : createOrResetDecoder
,03-19 11:47:40.974  1984  1984 I art     : Explicit concurrent mark sweep GC freed 4384(229KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/19MB, paused 1.011ms total 148.130ms
,03-19 11:47:41.002   885  1543 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6347 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 11:47:41.018   307   307 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 22.024ms
,03-19 11:47:41.032   885   885 I art     : Explicit concurrent mark sweep GC freed 20947(1366KB) AllocSpace objects, 6(283KB) LOS objects, 33% free, 20MB/30MB, paused 10.349ms total 160.553ms
03-19 11:47:41.032   885  1148 I art     : WaitForGcToComplete blocked for 79.432ms for cause Explicit
,03-19 11:47:41.039   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 247us total 20.648ms
,03-19 11:47:41.041  1962  1962 I ConfigService: onCreate
,03-19 11:47:41.061   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.788ms
,03-19 11:47:41.100  6347  6347 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-19 11:47:41.101  6347  6347 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-19 11:47:41.101  6347  6347 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-19 11:47:41.101  6347  6347 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-19 11:47:41.105  1418  6344 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-19 11:47:41.158  1418  6344 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-19 11:47:41.162  1418  6344 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-19 11:47:41.162  1418  6344 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-19 11:47:41.170  1418  6344 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-19 11:47:41.170  1418  6344 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-19 11:47:41.175  1418  6344 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-19 11:47:41.175  1418  6344 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-19 11:47:41.181  1418  6344 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,03-19 11:47:41.181   885   885 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-19 11:47:41.182   885   885 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-19 11:47:41.183  1418  6344 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-19 11:47:41.183  1418  6344 I Keyboard.Facilitator.Delight2FileSweeper: run()
,03-19 11:47:41.183  1418  6344 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-19 11:47:41.183  1418  6344 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-19 11:47:41.183  1418  6344 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-19 11:47:41.197   885  1517 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6371 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,03-19 11:47:41.200   885  1256 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-19 11:47:41.200   885  1256 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-19 11:47:41.245  1574  1574 I Launcher: Deferring update until onResume
,03-19 11:47:41.270   885  1148 I art     : Explicit concurrent mark sweep GC freed 8623(667KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 1.936ms total 232.275ms
,03-19 11:47:41.348  6305  6305 D AndroidRuntime: Shutting down VM
,03-19 11:47:41.364  6371  6371 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,03-19 11:47:41.416   885  1573 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6389 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-19 11:47:41.422   885  1543 I ActivityManager: Killing 5941:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-19 11:47:41.481   885  1572 W libprocessgroup: failed to open /acct/uid_10005/pid_5941/cgroup.procs: No such file or directory
,03-19 11:47:41.577  2618  3851 E global frequency: no tags to log
,03-19 11:47:41.577  2618  3851 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-19 11:47:41.607   885  1148 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6413 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-19 11:47:41.656  2618  2618 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-19 11:47:41.661  1544  2458 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-19 11:47:41.684  1574  1574 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@a65b48c new=com.google.android.velvet.VelvetApplication@a65b48c
,03-19 11:47:41.702  1574  4347 E SQLiteLog: (3850) statement aborts at 24: [DELETE FROM shortcut_and_widget_previews WHERE name LIKE ? OR name LIKE ?] disk I/O error
,03-19 11:47:41.719  1962  2461 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,03-19 11:47:41.722  1984  6439 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-19 11:47:41.722  1984  6439 D AccountUtils: Clearing selected account for com.test.thalitest
,03-19 11:47:41.750  1962  1962 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,03-19 11:47:41.751  1962  1962 D AndroidRuntime: Shutting down VM
03-19 11:47:41.752   278   688 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
03-19 11:47:41.758  1962  1962 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-19 11:47:41.758  1962  1962 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM2KRjU36UR
03-19 11:47:41.758  1962  1962 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-19 11:47:41.758  1962  1962 I GCore-Chimera-Crash: ==
03-19 11:47:41.758  1962  1962 I GCore-Chimera-Crash: GCore-Chimera-Crash
,03-19 11:47:41.760  1984  6446 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
