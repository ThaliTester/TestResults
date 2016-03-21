#### Test 635253937ae73fc_thali04_motorola-XT1072 Logs


```
--------- beginning of system
,03-21 08:38:50.265   878  1218 V AlarmManager: send {3f4ccab5, *walarm*:com.google.android.intent.action.SEND_IDLE}
03-21 08:38:50.277   878   878 V AlarmManager: done {3f4ccab5, *walarm*:com.google.android.intent.action.SEND_IDLE} [12ms]
--------- beginning of main
03-21 08:38:50.528  2018  5851 I PhenotypeConfigurator: Scheduling Phenotype for one-off execution 13430 seconds from now (1458545930528)
03-21 08:38:50.692  2018  5844 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
03-21 08:38:50.708  2018  5844 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-21 08:38:50.789  5842  5842 D AndroidRuntime: 
03-21 08:38:50.789  5842  5842 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 08:38:50.793  5842  5842 D AndroidRuntime: CheckJNI is OFF
03-21 08:38:51.027  5842  5842 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-21 08:38:51.036   878  4457 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 08:38:51.095   878  4457 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5878 uid=10109 gids={50109, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-21 08:38:51.096  5842  5842 D AndroidRuntime: Shutting down VM
03-21 08:38:51.152   878   878 V ActivityManager: Display changed displayId=0
03-21 08:38:51.161  1459  4047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-21 08:38:51.170  1459  4047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
03-21 08:38:51.306  5878  5878 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 08:38:51.326  5878  5878 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5974-5975)
03-21 08:38:51.326  5878  5878 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 08:38:51.350  5878  5878 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e3d3473}
03-21 08:38:51.350  5878  5878 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 08:38:51.350  5878  5878 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-21 08:38:51.372  5878  5878 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-21 08:38:51.372  5878  5878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 08:38:51.373  5878  5878 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-21 08:38:51.389  5878  5878 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 08:38:51.395  5878  5878 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 08:38:51.395  5878  5878 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 08:38:51.395  5878  5878 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107_msm8226_LA.BF.1.1__release_AU ()
03-21 08:38:51.395  5878  5878 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
03-21 08:38:51.395  5878  5878 I Adreno-EGL: Build Date: 10/28/14 Tue
03-21 08:38:51.395  5878  5878 I Adreno-EGL: Local Branch: 
03-21 08:38:51.395  5878  5878 I Adreno-EGL: Remote Branch: quic/l_LNX.LA.3.6
03-21 08:38:51.395  5878  5878 I Adreno-EGL: Local Patches: NONE
03-21 08:38:51.395  5878  5878 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1.04.04.02.162.107 + cb93e16 + f50fe49 + d7c18e6 + 5b9a565 + 0f3a25d + 607156e + 75511aa + e4d16c0 + 686f3eb + 211a271 + dd281ee +  NOTHING
,03-21 08:38:51.467   878  1128 D BluetoothManagerService: Message: 20
03-21 08:38:51.467   878  1128 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f3066c6:true
,03-21 08:38:51.624  5878  5878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:38:51.640  5878  5878 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 08:38:51.656  5878  5878 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-21 08:38:51.662  5878  5878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 08:38:51.663  5878  5878 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 08:38:51.670   878  1099 W ActivityManager: Activity pause timeout for ActivityRecord{1a2d6833 u0 com.test.thalitest/.MainActivity t12}
,03-21 08:38:51.736  5878  5920 D OpenGLRenderer: Render dirty regions requested: true
,03-21 08:38:51.755  5878  5878 D Atlas   : Validating map...
,03-21 08:38:51.763  5878  5907 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-21 08:38:51.805  5878  5920 I OpenGLRenderer: Initialized EGL, version 1.4
,03-21 08:38:51.810  5878  5920 D OpenGLRenderer: Enabling debug mode 0
,03-21 08:38:51.832  1412  1412 I Keyboard.Facilitator: onFinishInput()
,03-21 08:38:51.846   878  1129 I LaunchCheckinHandler: Displayed com.test.thalitest/.MainActivity,cp,ca,796
03-21 08:38:51.846   878  1129 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +677ms (total +796ms)
,03-21 08:38:51.851  5878  5878 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 08:38:51.953   313   400 I ThermalEngine: Sensor:xo_therm_pu2:32000 mC
,03-21 08:38:51.985  5878  5929 E Adreno-ES20: <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
03-21 08:38:51.985  5878  5929 E Adreno-ES20: <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,03-21 08:38:52.012  5878  5878 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5878
,03-21 08:38:52.151  5878  5878 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 08:38:52.474  5878  5927 D jxcore_app_log: JniHelper::setJavaVM(0xb883c310), pthread_self() = -1195559872
,03-21 08:38:52.482  5878  5927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 08:38:52.482  5878  5927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 08:38:52.482  5878  5927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 08:38:52.482  5878  5927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 08:38:52.482  5878  5927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-21 08:38:52.482  5878  5927 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18155e8e added. We now have 1 listener(s)
03-21 08:38:52.482   878  1510 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-21 08:38:52.485  5878  5927 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 44:80:EB:7B:5A:05
03-21 08:38:52.486  5878  5927 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "44:80:EB:7B:5A:05"
,03-21 08:38:52.488  5878  5927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 08:38:52.488  5878  5927 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 44:80:EB:7B:5A:05
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 08:38:52.492  5878  5927 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae64a45 added. We now have 1 listener(s)
03-21 08:38:52.492  5878  5927 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-21 08:38:52.505   878  1232 D WifiService: New client listening to asynchronous messages
,03-21 08:38:52.507  5878  5927 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,03-21 08:38:52.514  5878  5927 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-21 08:38:52.514  5878  5927 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-21 08:38:52.517  5878  5927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-21 08:38:52.517   878  1536 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-21 08:38:52.518  5878  5927 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 44:80:EB:7B:5A:05
,03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 08:38:52.523  5878  5927 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 08:38:52.523  5878  5927 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 08:38:52.523  5878  5927 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 08:38:52.524  5878  5927 I io.jxcore.node.LifeCycleMonitor: start: OK
03-21 08:38:52.525  5878  5878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-21 08:38:52.526  5878  5878 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-21 08:38:52.556  5878  5878 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 08:38:52.672  2018  2033 I art     : Background sticky concurrent mark sweep GC freed 108935(5MB) AllocSpace objects, 18(311KB) LOS objects, 27% free, 16MB/22MB, paused 1.303ms total 134.259ms
,03-21 08:38:52.724  2018  2030 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@2af68424)
,03-21 08:38:52.727  2018  2030 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@3f116b8d)
03-21 08:38:52.727  2018  2030 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@253df142)
,03-21 08:38:52.727  2018  2030 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@15ee0553)
03-21 08:38:52.728  2018  2030 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (internal object: com.google.android.gms.common.data.DataHolder@d29be90)
,03-21 08:38:53.399  5878  5936 W jxcore-log: Initializing JXcore engine
03-21 08:38:53.399  5878  5936 W jxcore-log: JXcore engine is ready
,03-21 08:38:53.488  5936  5936 W Thread-644: type=1400 audit(0.0:4): avc: denied { ioctl } for uid=10109 path="socket:[9324]" dev="sockfs" ino=9324 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 08:38:53.488  5936  5936 W Thread-644: type=1400 audit(0.0:5): avc: denied { ioctl } for uid=10109 path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2122 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-21 08:38:53.488  5936  5936 W Thread-644: type=1400 audit(0.0:6): avc: denied { ioctl } for uid=10109 path="socket:[7540]" dev="sockfs" ino=7540 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 08:38:53.488  5936  5936 W Thread-644: type=1400 audit(0.0:7): avc: denied { ioctl } for uid=10109 path="socket:[25322]" dev="sockfs" ino=25322 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-21 08:38:53.528  5878  5936 W jxcore-log: Starting JXcore engine
,03-21 08:38:53.658  5878  5936 W jxcore-log: Platform android
03-21 08:38:53.658  5878  5936 W jxcore-log: 
03-21 08:38:53.659  5878  5936 W jxcore-log: Process ARCH arm
03-21 08:38:53.659  5878  5936 W jxcore-log: 
,03-21 08:38:53.804  2018  2018 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 08:38:53.806  2018  2018 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-21 08:38:53.954  5878  5936 I jxcore-log: JXcore Cordova bridge is ready!
03-21 08:38:53.954  5878  5936 I jxcore-log: 
,03-21 08:38:53.954  5878  5936 W jxcore-log: JXcore engine is started
,03-21 08:38:53.961  5878  5927 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-21 08:38:53.963  5878  5878 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-21 08:38:53.972  5878  5936 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-21 08:38:53.972  5878  5936 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-21 08:38:53.979  5878  5878 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,03-21 08:38:53.981  5878  5878 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,03-21 08:38:53.985   878  1565 I ActivityManager: Killing 5629:com.google.android.talk/u0a70 (adj 15): empty #7
,03-21 08:38:54.092  5878  5927 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 111ms. Plugin should use CordovaInterface.getThreadPool().
03-21 08:38:54.092   878  1566 W libprocessgroup: failed to open /acct/uid_10070/pid_5629/cgroup.procs: No such file or directory
03-21 08:38:54.092  5878  5878 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
03-21 08:38:54.093  5878  5878 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
03-21 08:38:54.095  5878  5878 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
03-21 08:38:54.095  5878  5878 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
03-21 08:38:54.095  5878  5878 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
03-21 08:38:54.095  5878  5878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
03-21 08:38:54.095  5878  5878 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18155e8e removed from the list
03-21 08:38:54.095  5878  5878 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,03-21 08:38:54.095  5878  5878 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae64a45 removed from the list
03-21 08:38:54.095  5878  5878 D io.jxcore.node.ConnectivityMonitor: stop
03-21 08:38:54.095  5878  5878 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,03-21 08:38:54.107  1459  4047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-21 08:38:54.116  5878  5878 I io.jxcore.node.LifeCycleMonitor: stop: OK
,03-21 08:38:54.118  1459  4047 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1455 android.content.ContextWrapper.sendBroadcast:376 com.motorola.motocare.util.TriggerHelper$TriggerBuilder.send:76 com.motorola.motocare.internal.frameworkevents.PauseResumeTrigger.handleFrameworkEvent:53 com.motorola.motocare.internal.frameworkevents.FwEventMonitor$FrameworkListener.processFrameworkEvent:114 
,03-21 08:38:54.152  2717  2717 D OtaApp  : [debug] > DownloadActivity, FormattedText
,03-21 08:38:54.155  2717  2717 I OtaApp  : [info] > DownloadActivity, handling (Blur_Version.22.46.12.thea_reteu.reteuall.en.EU) from ( upgrade)
03-21 08:38:54.156  2717  2717 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-21 08:38:54.158  2717  2717 I OtaApp  : [info] > Exceed max defer attempts for optional update, suppresing later btn
,03-21 08:38:54.159  2717  2717 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-21 08:38:54.164  2717  2717 D OtaApp  : [debug] > cancelling the previous pending intent set for download later
,03-21 08:38:54.166  2717  2717 I OtaApp  : [info] > next automatic download prompt (serverAnnoy)  is scheduled in : 60 mins.
,03-21 08:38:54.167  2717  2717 D Checkin : publish the event [tag = MOT_OTA event name = LOG]
,03-21 08:38:54.193  5878  5878 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-21 08:38:54.194  1412  1412 I Keyboard.Facilitator: onFinishInput()
,03-21 08:38:54.250  2717  4142 E global frequency: no tags to log
,03-21 08:38:54.251  2717  4142 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-21 08:38:54.265  2717  2717 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-21 08:38:54.267  1537  2553 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-21 08:38:54.327  5966  5966 D AndroidRuntime: 
03-21 08:38:54.327  5966  5966 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-21 08:38:54.331  5966  5966 D AndroidRuntime: CheckJNI is OFF
,03-21 08:38:54.453   878  1566 I art     : Explicit concurrent mark sweep GC freed 44220(2MB) AllocSpace objects, 3(234KB) LOS objects, 33% free, 20MB/30MB, paused 1.458ms total 124.468ms
,03-21 08:38:54.474  2717  2717 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-21 08:38:54.485  2717  2717 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-21 08:38:54.492  2717  2717 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-21 08:38:54.493  1537  1563 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-21 08:38:54.516  5966  5966 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 08:38:54.524   878  1099 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=-1: uninstall pkg
,03-21 08:38:54.524   878  1099 I ActivityManager: Killing 5878:com.test.thalitest/u0a109 (adj 9): stop com.test.thalitest
03-21 08:38:54.524   298   519 I MDMCTBK : NetlinkHandler, power_supply subsys
03-21 08:38:54.524   298   519 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-21 08:38:54.524   298   519 I MDMCTBK : checkDefaultInst, current pid is = 298
03-21 08:38:54.524   298   519 I MDMCTBK : checkDefaultInst, pid match
03-21 08:38:54.524   298   519 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-21 08:38:54.525   298   519 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-21 08:38:54.525   298   519 E MDMCTBK : MdmCutbackHndler,Could not open ''
03-21 08:38:54.525   298   519 I MDMCTBK : NetlinkHandler, power_supply subsys
,03-21 08:38:54.525   298   519 I MDMCTBK : NetlinkHandler, usbChargerStateChanged
03-21 08:38:54.525   298   519 I MDMCTBK : checkDefaultInst, current pid is = 298
03-21 08:38:54.525   298   519 I MDMCTBK : checkDefaultInst, pid match
03-21 08:38:54.525   298   519 I MDMCTBK : MdmCutbackHndler,readFromFile = /sys/class/power_supply/usb/online
03-21 08:38:54.525   298   519 I MDMCTBK : MdmCutbackHndler,readFromFile = 
03-21 08:38:54.525   298   519 E MDMCTBK : MdmCutbackHndler,Could not open ''
,03-21 08:38:54.555   878  1232 D WifiService: Client connection lost with reason: 4
,03-21 08:38:54.577   878  1142 W PackageSettings: Skipping PackageSetting{1ddeac5a com.example.hello/10568} due to missing metadata
,03-21 08:38:54.656  1459  1496 I art     : Explicit concurrent mark sweep GC freed 56295(3MB) AllocSpace objects, 35(1245KB) LOS objects, 39% free, 7MB/12MB, paused 897us total 48.630ms
,03-21 08:38:54.663   878  1497 W ActivityManager: Spurious death for ProcessRecord{1072b8b2 5878:com.test.thalitest/u0a109}, curProc for 5878: null
,03-21 08:38:54.664   878  1142 I ActivityManager: Force stopping com.test.thalitest appid=10109 user=0: pkg removed
,03-21 08:38:54.722  3191  3191 I art     : Explicit concurrent mark sweep GC freed 9166(2MB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 7MB/12MB, paused 713us total 55.101ms
,03-21 08:38:54.732  1412  1412 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-21 08:38:54.744   878  1221 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 08:38:54.747  2018  2221 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 08:38:54.756  1412  5996 I Keyboard.Facilitator.DecoderInitializer: run()
,03-21 08:38:54.758  1412  5996 I Decoder : createOrResetDecoder
,03-21 08:38:54.763  1608  5995 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-21 08:38:54.787  2717  2717 I art     : Explicit concurrent mark sweep GC freed 27770(1611KB) AllocSpace objects, 6(119KB) LOS objects, 40% free, 11MB/19MB, paused 2.023ms total 101.971ms
,03-21 08:38:54.791  2717  2717 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-21 08:38:54.809  1948  1948 I art     : Explicit concurrent mark sweep GC freed 20120(1185KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 14MB/19MB, paused 1.070ms total 132.890ms
,03-21 08:38:54.821  2717  2717 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-21 08:38:54.824   878  1497 I ActivityManager: Start proc com.motorola.MotGallery2 for broadcast com.motorola.MotGallery2/com.android.gallery3d.app.PackagesMonitor: pid=5998 uid=10027 gids={50027, 9997, 1023, 3003, 1028, 1015} abi=armeabi-v7a
,03-21 08:38:54.827  1567  1567 I art     : Explicit concurrent mark sweep GC freed 2497(131KB) AllocSpace objects, 3(128KB) LOS objects, 25% free, 13MB/17MB, paused 1.362ms total 146.811ms
,03-21 08:38:54.884  2717  2717 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
03-21 08:38:54.887  1537  2552 E PhoneInterfaceManager: [PhoneIntfMgr] getIccId: ICC ID is null or empty.
,03-21 08:38:54.892  1412  5996 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-21 08:38:54.907   878   878 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 08:38:54.908   878   878 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-21 08:38:54.916   878  1249 D TaskPersister: removeObsoleteFile: deleting file=12_task.xml
03-21 08:38:54.916   878  1249 D TaskPersister: removeObsoleteFile: deleting file=11_task.xml
,03-21 08:38:54.927  5998  5998 W asset   : Asset path /system/framework/com.motorola.gallery is neither a directory nor file (type=1).
03-21 08:38:54.927  5998  5998 W ResourcesManager: Asset path '/system/framework/com.motorola.gallery' does not exist or contains no resources.
03-21 08:38:54.929  5998  5998 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-21 08:38:54.933  5998  5998 W ResourcesManager: Asset path '/system/framework/com.motorola.frameworks.core.addon.jar' does not exist or contains no resources.
,03-21 08:38:54.970  1412  5996 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-21 08:38:54.973  1412  5996 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-21 08:38:54.973  1412  5996 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,03-21 08:38:54.978  2717  2717 D BSUtils : Error checking isMultiSimEnabled, Exception:java.lang.ClassNotFoundException: android.telephony.MSimTelephonyManager
,03-21 08:38:54.983  1412  5996 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-21 08:38:54.983  1412  5996 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,03-21 08:38:54.988  1412  5996 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-21 08:38:54.988  1412  5996 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-21 08:38:54.991  1412  5996 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-21 08:38:54.992  2717  2717 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
,03-21 08:38:54.995  2717  4142 I BSUtils : failed to get sys.build.version.checksum. Setting swChkSum to default: FFFF
03-21 08:38:54.996  1412  5996 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-21 08:38:54.996  1412  5996 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-21 08:38:54.996  1412  5996 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-21 08:38:54.996  1412  5996 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-21 08:38:54.996  1412  5996 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
03-21 08:38:54.996  2717  4142 I global frequency: BcsDSCheckin.logProperties: root status from persist.qe isqe 0/0
,03-21 08:38:54.997  2717  4142 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
03-21 08:38:54.999  2717  4142 E global frequency: BcsDSCheckin.logProperties: BL State from property is null or empty
,03-21 08:38:55.000  2717  4142 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-21 08:38:55.002  2717  4142 D Checkin : publish the event [tag = DEV_ATTRIBS event name = SW]
,03-21 08:38:55.005  2717  4142 D Checkin : publish the event [tag = MOT_CCE_STATS event name = DataUsage]
,03-21 08:38:55.018  2717  4142 I global frequency: BcsCore.doCallHomeCore: Exceeded maximum number of checkins for one hour. Bailing out
,03-21 08:38:55.021  2717  4142 D Checkin : publish the event [tag = MOT_CHECKIN event name = LOG]
,03-21 08:38:55.047   878  1566 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6022 uid=1000 gids={41000, 9997, 1021, 3004, 3005, 1000, 3009, 1015, 1023, 1010, 1004, 2002, 3006, 1028, 3002, 3001, 3003} abi=armeabi-v7a
,03-21 08:38:55.060   878  1142 I art     : Explicit concurrent mark sweep GC freed 21029(1563KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 20MB/30MB, paused 2.125ms total 291.749ms
,03-21 08:38:55.073  1567  1567 I Launcher: Deferring update until onResume
,03-21 08:38:55.142  5966  5966 D AndroidRuntime: Shutting down VM
,03-21 08:38:55.155  6022  6022 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1820 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2611 
,03-21 08:38:55.185   878  1142 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6040 uid=10010 gids={50010, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-21 08:38:55.210  1567  1567 W Launcher: setApplicationContext called twice! old=com.google.android.velvet.VelvetApplication@26536e5c new=com.google.android.velvet.VelvetApplication@26536e5c
,03-21 08:38:55.222  5578  6058 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,03-21 08:38:55.226  1948  6060 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
03-21 08:38:55.226  1948  6060 D AccountUtils: Clearing selected account for com.test.thalitest
,03-21 08:38:55.249  1948  6060 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,03-21 08:38:55.264  2018  2018 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
03-21 08:38:55.264  2018  2018 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,03-21 08:38:55.306   878  1477 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6066 uid=10057 gids={50057, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,03-21 08:38:55.357  1948  6072 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 08:38:55.361  1948  6072 W BaseAppContext: Using Auth Proxy for data requests.
,03-21 08:38:55.366  1948  6060 I GMPM-SVC: App measurement is starting up, version: 8703
03-21 08:38:55.366  1948  6060 I GMPM-SVC: To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
,03-21 08:38:55.411  1948  2086 I Icing   : doRemovePackageData com.test.thalitest
,03-21 08:38:55.421  1948  6060 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,03-21 08:38:55.453  1948  6093 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
03-21 08:38:55.453  1948  6093 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,03-21 08:38:55.454  1948  6093 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
03-21 08:38:55.454  1948  6093 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,03-21 08:38:55.464  1948  6093 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,03-21 08:38:55.464  1948  6093 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
03-21 08:38:55.464  1948  6093 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,03-21 08:38:55.471  1948  6093 D gH_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,03-21 08:38:55.471  1948  6093 D gH_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
03-21 08:38:55.472  1948  6093 D gH_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
,03-21 08:38:55.473  1948  6093 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
03-21 08:38:55.473  1948  6093 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
03-21 08:38:55.473  1948  6093 D gH_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,03-21 08:38:55.631  5578  6058 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 408 ms] updated apps [took 408 ms] 
,03-21 08:38:55.632   878  4457 I ActivityManager: Killing 5748:com.google.android.apps.plus/u0a90 (adj 15): empty #7
,03-21 08:38:55.702   878  1294 W libprocessgroup: failed to open /acct/uid_10090/pid_5748/cgroup.procs: No such file or directory
,03-21 08:38:55.725  6066  6066 I GAv4    : Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
03-21 08:38:55.725  6066  6066 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-21 08:38:55.725  6066  6066 I GAv4    :   adb logcat -s GAv4
,03-21 08:38:55.742  6066  6066 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-21 08:38:55.761  6066  6103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-21 08:38:55.761  6066  6066 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-21 08:38:55.764  6066  6103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-21 08:38:55.765  6066  6104 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-21 08:38:55.766  6066  6103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,03-21 08:38:55.777  6066  6104 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:38:55.777  6066  6104 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
,03-21 08:38:55.777  6066  6104 E GAv4    : Opening the database failed, dropping the table and recreating it
03-21 08:38:55.778  6066  6103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/google_analytics_v4.db'.
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at fdw$a.getWritableDatabase(Unknown Source)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at fdw.g(Unknown Source)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at fdw.a(Unknown Source)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at fdw.e(Unknown Source)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at fdy.b(Unknown Source)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at feb.run(Unknown Source)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
03-21 08:38:55.779  6066  6104 E SQLiteDatabase: 	at gir$c.run(Unknown Source)
03-21 08:38:55.779  6066  6104 E GAv4    : Failed to open freshly created database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:38:55.779  6066  6104 W GAv4    : Error opening database: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:38:55.779  6066  6103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-21 08:38:55.779  6066  6104 E GAv4    : Job execution failed: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:38:55.779  6066  6103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-21 08:38:55.780  6066  6103 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.apps.docs/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
03-21 08:38:55.784  6066  6066 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.30
,03-21 08:38:55.811  6066  6105 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1276)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at aev.getWritableDatabase(PG:238)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at ael.a(PG:1521)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at hix$a.a(PG:125)
03-21 08:38:55.811  6066  6105 E SQLiteDatabase: 	at aen.run(PG:536)
03-21 08:38:55.829   278   692 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
