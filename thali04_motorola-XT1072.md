#### Test 62548124d9c0fd9_thali04_motorola-XT1072 Logs


```
--------- beginning of main
,03-19 12:54:46.833   291   519 I MDMCTBK : NetlinkHandler, power_supply subsys
03-19 12:54:46.833   291   519 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-19 12:54:46.833   291   519 I MDMCTBK : checkDefaultInst, current pid is = 291
03-19 12:54:46.833   291   519 I MDMCTBK : checkDefaultInst, pid match
03-19 12:54:46.833   291   519 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-19 12:54:46.833   291   519 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-19 12:54:46.833   291   519 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-19 12:54:46.833   291   519 I MDMCTBK : NetlinkHandler, power_supply subsys
03-19 12:54:46.833   291   519 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-19 12:54:46.833   291   519 I MDMCTBK : checkDefaultInst, current pid is = 291
03-19 12:54:46.833   291   519 I MDMCTBK : checkDefaultInst, pid match
03-19 12:54:46.833   291   519 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-19 12:54:46.834   291   519 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-19 12:54:46.834   291   519 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-19 12:54:47.257  6185  6185 D AndroidRuntime: 
03-19 12:54:47.257  6185  6185 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 12:54:47.264  6185  6185 D AndroidRuntime: CheckJNI is OFF
03-19 12:54:47.494  6185  6185 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-19 12:54:47.502   882  1916 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-19 12:54:47.570   882  1916 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6204 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-19 12:54:47.572  6185  6185 D AndroidRuntime: Shutting down VM
03-19 12:54:47.592   882   882 V ActivityManager: Display changed displayId=0
03-19 12:54:47.603  1475  4416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-19 12:54:47.609  1475  4416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-19 12:54:47.757  6204  6204 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
03-19 12:54:47.776  6204  6204 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3382-3383)
03-19 12:54:47.776  6204  6204 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-19 12:54:47.805  6204  6204 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {148afc18}
,03-19 12:54:47.806  6204  6204 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-19 12:54:47.806  6204  6204 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-19 12:54:47.821  6204  6204 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-19 12:54:47.822  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:54:47.823  6204  6204 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-19 12:54:47.840  6204  6204 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-19 12:54:47.845  6204  6204 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-19 12:54:47.845  6204  6204 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-19 12:54:47.846  6204  6204 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-19 12:54:47.846  6204  6204 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-19 12:54:47.846  6204  6204 I Adreno-EGL: Build Date: 10/28/14 Tue
03-19 12:54:47.846  6204  6204 I Adreno-EGL: Local Branch: 
03-19 12:54:47.846  6204  6204 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-19 12:54:47.846  6204  6204 I Adreno-EGL: Local Patches: NONE
03-19 12:54:47.846  6204  6204 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-19 12:54:47.926   882  1138 D BluetoothManagerService: Message: 20
03-19 12:54:47.926   882  1138 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18a047be:true
,03-19 12:54:48.079  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:54:48.108   882  1128 W ActivityManager: Activity pause timeout for ActivityRecord{10244d4b u0 com.test.thalitest/.MainActivity t9}
,03-19 12:54:48.112  6204  6204 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-19 12:54:48.140  6204  6204 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-19 12:54:48.150  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-19 12:54:48.150  6204  6204 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-19 12:54:48.215  6204  6246 D OpenGLRenderer: Render dirty regions requested: true
,03-19 12:54:48.233  6204  6204 D Atlas   : Validating map...
,03-19 12:54:48.242  6204  6233 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-19 12:54:48.290  6204  6246 I OpenGLRenderer: Initialized EGL, version 1.4
,03-19 12:54:48.297  6204  6246 D OpenGLRenderer: Enabling debug mode 0
,03-19 12:54:48.324  1422  1422 I Keyboard.Facilitator: onFinishInput()
,03-19 12:54:48.336   882  1139 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,819
,03-19 12:54:48.338   882  1139 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +728ms (total +819ms)
,03-19 12:54:48.344  6204  6204 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-19 12:54:48.479  6204  6250 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-19 12:54:48.480  6204  6250 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-19 12:54:48.507  6204  6204 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6204
,03-19 12:54:48.662  6204  6204 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-19 12:54:48.972  6204  6249 D jxcore_app_log: JniHelper::setJavaVM(0xb80ef310), pthread_self() = -1203215152
,03-19 12:54:48.978  6204  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-19 12:54:48.978  6204  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-19 12:54:48.978  6204  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-19 12:54:48.978  6204  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-19 12:54:48.978  6204  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-19 12:54:48.978  6204  6249 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f52bab7 added. We now have 1 listener(s)
,03-19 12:54:48.979   882  1572 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 12:54:48.982  6204  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
,03-19 12:54:48.984  6204  6249 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:80:EB:7B:5A:05"
,03-19 12:54:48.985  6204  6249 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-19 12:54:48.985  6204  6249 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-19 12:54:48.988  6204  6249 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28fb8f42 added. We now have 1 listener(s)
03-19 12:54:48.989  6204  6249 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-19 12:54:48.993   882  1237 D WifiService: New client listening to asynchronous messages
,03-19 12:54:48.995  6204  6249 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-19 12:54:49.000  6204  6249 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-19 12:54:49.000  6204  6249 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-19 12:54:49.002  6204  6249 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-19 12:54:49.003   882  1596 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-19 12:54:49.004  6204  6249 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-19 12:54:49.008  6204  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-19 12:54:49.009  6204  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-19 12:54:49.009  6204  6249 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-19 12:54:49.011  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 12:54:49.012  6204  6204 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-19 12:54:49.013  6204  6249 I io.jxcore.node.LifeCycleMonitor: start: OK
,03-19 12:54:49.040  6204  6204 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-19 12:54:49.486   882  1224 V AlarmManager: send {3fc1c85d, *walarm*:com.google.android.intent.action.SEND_IDLE}
,03-19 12:54:49.496   882   882 V AlarmManager: done {3fc1c85d, *walarm*:com.google.android.intent.action.SEND_IDLE} [9ms]
,03-19 12:54:49.825  2027  6263 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 8047 seconds from now (1458388489825)
,03-19 12:54:49.933  6204  6255 W jxcore-log: Initializing JXcore engine
03-19 12:54:49.933  6204  6255 W jxcore-log: JXcore engine is ready
,03-19 12:54:49.957  2027  6257 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,03-19 12:54:49.983  2027  6257 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-19 12:54:50.031  6255  6255 W Thread-690: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[7356]" dev="sockfs" ino=7356 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-19 12:54:50.031  6255  6255 W Thread-690: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-19 12:54:50.031  6255  6255 W Thread-690: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[9436]" dev="sockfs" ino=9436 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-19 12:54:50.031  6255  6255 W Thread-690: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[27055]" dev="sockfs" ino=27055 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-19 12:54:50.057  6204  6255 W jxcore-log: Starting JXcore engine
,03-19 12:54:50.207  6204  6255 W jxcore-log: Platform android
03-19 12:54:50.207  6204  6255 W jxcore-log: 
03-19 12:54:50.207  6204  6255 W jxcore-log: Process ARCH arm
03-19 12:54:50.207  6204  6255 W jxcore-log: 
,03-19 12:54:50.535  6204  6255 I jxcore-log: JXcore Cordova bridge is ready!
03-19 12:54:50.535  6204  6255 I jxcore-log: 
03-19 12:54:50.535  6204  6255 W jxcore-log: JXcore engine is started
,03-19 12:54:50.541  6204  6249 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-19 12:54:50.543  6204  6204 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
03-19 12:54:50.552  6204  6255 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-19 12:54:50.552  6204  6255 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-19 12:54:50.560  6204  6204 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
03-19 12:54:50.561  6204  6204 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
03-19 12:54:50.568   882  1339 I ActivityManager: Killing 5977:com.google.android.gm/u0a63 (adj 15): empty #7
,03-19 12:54:50.593   882  1915 W libprocessgroup: failed to open /acct/uid_10063/pid_5977/cgroup.procs: No such file or directory
03-19 12:54:50.594  6204  6204 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
03-19 12:54:50.594  6204  6204 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-19 12:54:50.595  6204  6204 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
03-19 12:54:50.595  6204  6204 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-19 12:54:50.595  6204  6204 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-19 12:54:50.595  6204  6204 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
03-19 12:54:50.595  6204  6204 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f52bab7 removed from the list
03-19 12:54:50.595  6204  6204 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
03-19 12:54:50.595  6204  6204 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28fb8f42 removed from the list
03-19 12:54:50.595  6204  6204 D io.jxcore.node.ConnectivityMonitor: stop
03-19 12:54:50.595  6204  6204 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,03-19 12:54:50.597  6204  6249 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 34ms. Plugin should use CordovaInterface.getThreadPool().
,03-19 12:54:50.609  1475  4416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-19 12:54:50.616  6204  6204 I io.jxcore.node.LifeCycleMonitor: stop: OK
,03-19 12:54:50.618  1475  4416 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-19 12:54:50.636  2845  2845 D OtaApp  : [debug] > DownloadActivity, FormattedText
03-19 12:54:50.639  2845  2845 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
,03-19 12:54:50.648  2845  2845 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-19 12:54:50.651  2845  2845 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-19 12:54:50.652  2845  2845 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-19 12:54:50.663  2845  2845 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
03-19 12:54:50.672  2845  2845 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
03-19 12:54:50.674  2845  2845 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
03-19 12:54:50.708  1422  1422 I Keyboard.Facilitator: onFinishInput()
03-19 12:54:50.709  6204  6204 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-19 12:54:50.902  6282  6282 D AndroidRuntime: 
03-19 12:54:50.902  6282  6282 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-19 12:54:50.906  6282  6282 D AndroidRuntime: CheckJNI is OFF
,03-19 12:54:50.988   303   392 I ThermalEngine: Sensor:xo_therm_pu2:33000 mC
,03-19 12:54:51.099  2027  2027 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:54:51.104  2027  2027 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-19 12:54:51.120  6282  6282 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-19 12:54:51.133   882  1128 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-19 12:54:51.133   882  1128 I ActivityManager: Killing 6204:com.test.thalitest/u0a109 (adj 9): stop com.test.thalitest
,03-19 12:54:51.170   882  1237 D WifiService: Client connection lost with reason: 4
,03-19 12:54:51.218   882  1148 W PackageSettings: Skipping PackageSetting{1fe90313 com.example.hello/10568} due to missing metadata
,03-19 12:54:51.245   882  1464 W ActivityManager: Spurious death for ProcessRecord{a2a82cd 6204:com.test.thalitest/u0a109}, curProc for 6204: null
,03-19 12:54:51.248   882  1148 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-19 12:54:51.288  3520  3520 I art     : Explicit concurrent mark sweep GC freed 9240(2MB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 897us total 37.606ms
,03-19 12:54:51.322  2027  2326 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-19 12:54:51.329   882  1226 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-19 12:54:51.359  1422  1422 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-19 12:54:51.362  1422  6322 I Keyboard.Facilitator.DecoderInitializer: run()
,03-19 12:54:51.397  1422  6322 I Decoder : createOrResetDecoder
,03-19 12:54:51.404   882  1596 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=6324 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-19 12:54:51.409  1649  6323 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-19 12:54:51.432  1573  1573 I art     : Explicit concurrent mark sweep GC freed 2212(116KB) AllocSpace objects, 3(128KB) LOS objects, 24% free, 13MB/17MB, paused 489us total 145.878ms
,03-19 12:54:51.435  1956  1956 I art     : Explicit concurrent mark sweep GC freed 3558(199KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 14MB/19MB, paused 967us total 181.816ms
,03-19 12:54:51.437  1956  1969 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-19 12:54:51.484  6324  6324 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-19 12:54:51.484  6324  6324 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-19 12:54:51.485  6324  6324 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-19 12:54:51.486  6324  6324 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-19 12:54:51.488   882   882 I art     : Explicit concurrent mark sweep GC freed 62837(3MB) AllocSpace objects, 8(396KB) LOS objects, 33% free, 20MB/30MB, paused 4.960ms total 182.065ms
,03-19 12:54:51.489   882  1148 I art     : WaitForGcToComplete blocked for 179.506ms for cause Explicit
,03-19 12:54:51.569   882  1572 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6348 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,03-19 12:54:51.619  2027  2043 I art     : Explicit concurrent mark sweep GC freed 55294(3MB) AllocSpace objects, 16(279KB) LOS objects, 39% free, 13MB/23MB, paused 1.285ms total 113.488ms
03-19 12:54:51.619  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@13420042)
,03-19 12:54:51.620  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@43a6853)
,03-19 12:54:51.623  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1bd9e590)
,03-19 12:54:51.634  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@1d18ce89)
03-19 12:54:51.634  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3973de8e)
03-19 12:54:51.634  1422  6322 I Keyboard.Facilitator.MainLanguageModelLoader: run()
03-19 12:54:51.634  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@33f936af)
03-19 12:54:51.635  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@a1fcabc)
,03-19 12:54:51.635  2027  2038 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@8b6ca45)
,03-19 12:54:51.672   882   882 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-19 12:54:51.672   882   882 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-19 12:54:51.683   882  1254 D TaskPersister: removeObsoleteFile: deleting file=9_task.xml
03-19 12:54:51.683   882  1254 D TaskPersister: removeObsoleteFile: deleting file=8_task.xml
,03-19 12:54:51.711   882  1148 I art     : Explicit concurrent mark sweep GC freed 8408(482KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 20MB/30MB, paused 3.523ms total 221.147ms
,03-19 12:54:51.712  6348  6348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,03-19 12:54:51.721  1573  1573 I Launcher: Deferring update until onResume
03-19 12:54:51.722  1422  6322 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-19 12:54:51.727  1422  6322 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-19 12:54:51.727  1422  6322 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-19 12:54:51.744  1422  6322 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-19 12:54:51.744  1422  6322 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-19 12:54:51.748  1422  6322 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-19 12:54:51.748  1422  6322 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-19 12:54:51.755  1422  6322 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-19 12:54:51.755  1422  6322 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,03-19 12:54:51.755  1422  6322 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-19 12:54:51.755  1422  6322 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-19 12:54:51.755  1422  6322 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-19 12:54:51.756  1422  6322 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-19 12:54:51.769   882  1916 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6368 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
,03-19 12:54:51.797   882   897 I ActivityManager: Killing 6042:com.google.android.gms:car/u0a16 (adj 15): empty #7
,03-19 12:54:51.803  6282  6282 D AndroidRuntime: Shutting down VM
,03-19 12:54:51.865   882  1148 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6385 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
03-19 12:54:51.865   882  1243 W libprocessgroup: failed to open /acct/uid_10016/pid_6042/cgroup.procs: No such file or directory
,03-19 12:54:51.912   882  1596 I ActivityManager: Killing 5570:com.android.providers.calendar/u0a5 (adj 15): empty #7
,03-19 12:54:52.003   882   898 W libprocessgroup: failed to open /acct/uid_10005/pid_5570/cgroup.procs: No such file or directory
,03-19 12:54:52.025  1573  1573 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@1cc768ad new=com.google.android.velvet.VelvetApplication@1cc768ad
,03-19 12:54:52.036  1956  6405 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-19 12:54:52.037  1956  6405 D AccountUtils: Clearing selected account for com.test.thalitest
,03-19 12:54:52.054  1956  6405 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-19 12:54:52.066  2027  2027 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-19 12:54:52.066  2027  2027 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-19 12:54:52.111   882  1571 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6411 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-19 12:54:52.175  1956  6419 W BaseAppContext: Using Auth Proxy for data requests.
,03-19 12:54:52.184  1956  6419 W BaseAppContext: Using Auth Proxy for data requests.
,03-19 12:54:52.266  1956  6405 I GMPM-SVC: App measurement is starting up, version: 8703
03-19 12:54:52.266  1956  6405 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-19 12:54:52.311   882  1916 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=6437 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-19 12:54:52.325  6368  6403 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-19 12:54:52.347  1956  6448 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
03-19 12:54:52.348  1956  2127 I Icing   : doRemovePackageData com.test.thalitest
,03-19 12:54:52.365  1956  6405 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-19 12:54:52.376  1956  6448 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-19 12:54:52.376  1956  6448 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM2KRjU36UR
03-19 12:54:52.376  1956  6448 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-19 12:54:52.376  1956  6448 I GCore-Chimera-Crash: ==
03-19 12:54:52.376  1956  6448 I GCore-Chimera-Crash: GCore-Chimera-Crash
,03-19 12:54:52.381  1956  6447 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2307)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 12:54:52.381  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
03-19 12:54:52.381  1956  6447 E GMPM-SVC: Opening the database failed, dropping and recreating it
,03-19 12:54:52.382  6368  6403 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.d.getWritableDatabase(InternalIcingCorporaProvider.java:592)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:284)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:325)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.content.ContentResolver.update(ContentResolver.java:1333)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.e.JA(UpdateIcingCorporaService.java:408)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.g.aTY(UpdateIcingCorporaService.java:347)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ba(UpdateIcingCorporaService.java:215)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:201)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-19 12:54:52.382  6368  6403 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
--------- beginning of crash
03-19 12:54:52.385  1956  6448 E AndroidRuntime: FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
03-19 12:54:52.385  1956  6448 E AndroidRuntime: Process: com.google.android.gms, PID: 1956
03-19 12:54:52.385  1956  6448 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:555)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at com.google.android.gms.people.c.e.a(:com.google.android.gms:110)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at com.google.android.gms.people.sync.a.b.d(:com.google.android.gms:3165)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.b.a(:com.google.android.gms:245)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(:com.google.android.gms:77)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-19 12:54:52.385  1956  6448 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.e(:com.google.android.gms:418)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.e.a(:com.google.android.gms:357)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.s(:com.google.android.gms:1591)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.p(:com.google.android.gms:1605)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.aq.c(:com.google.android.gms:306)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ar.run(:com.google.android.gms:195)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-19 12:54:52.387  1956  6447 E SQLiteDatabase: 	at com.google.android.gms.measurement.internal.ap.run(:com.google.android.gms:294)
03-19 12:54:52.388  1956  3250 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
03-19 12:54:52.391  1956  6447 E GMPM-SVC: Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-19 12:54:52.391  1956  6447 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-19 12:54:52.391  1956  6447 E GMPM-SVC: Task exception on worker thread: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2319)
03-19 12:54:52.392  1956  3250 E Icing   : Failed to open Apps corpus file.
03-19 12:54:52.393  1956  6447 W GMPM-SVC: Error opening database: android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
03-19 12:54:52.394  1956  6447 E GMPM-SVC: Error querying app: com.test.thalitest, android.database.sqlite.SQLiteException: Database open failed: com.google.android.gms.measurement.internal.h.getWritableDatabase(:com.google.android.gms:2303)
03-19 12:54:52.394  1956  3250 E Icing   : Failed to open Apps corpus file.
03-19 12:54:52.395  1956  3250 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml to backup file /data/data/com.google.android.gms/shared_prefs/proxy-apps-corpus.xml.bak
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(:com.google.android.gms:99)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:277)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-19 12:54:52.412  1956  6461 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(:com.google.android.gms:99)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.b.a.b(:com.google.android.gms:52)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(:com.google.android.gms:277)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryChimeraIntentService.onHandleIntent(:com.google.android.gms:44)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at com.google.android.chimera.l.handleMessage(:com.google.android.gms:65)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:135)
03-19 12:54:52.413  1956  6461 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 12:54:52.417  1956  6461 W SQLiteOpenHelper: Opened metrics.db in read-only mode
03-19 12:54:52.417  1956  6461 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-19 12:54:52.417  1956  6461 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
03-19 12:54:52.418  1956  6461 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
03-19 12:54:52.419  1956  6461 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
03-19 12:54:52.419  1956  6461 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTEQ-KcFGl8KHWNvbS5nb29nbGUuYW5kcm9pZC
03-19 12:54:52.419  1956  6461 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjYuMjcgKDI2NDcyMTYtMDM2KRjU36UR
03-19 12:54:52.419  1956  6461 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQsN-lEQ
03-19 12:54:52.419  1956  6461 I GCore-Chimera-Crash: ==
03-19 12:54:52.419  1956  6461 I GCore-Chimera-Crash: GCore-Chimera-Crash
03-19 12:54:52.419  1956  6461 I Process : Sending signal. PID: 1956 SIG: 9
03-19 12:54:52.421   278   680 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
03-19 12:54:52.429   882  1915 I ActivityManager: Start proc com.google.android.googlequicksearchbox:crash_report for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService: pid=6462 uid=10039 gids={50039, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a

```
