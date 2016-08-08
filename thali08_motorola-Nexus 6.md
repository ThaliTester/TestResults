#### Test 796897753515520_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-08 11:18:45.447  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:18:45.460  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:18:45.465  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:18:45.525  1533  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-08 11:18:45.526  1533  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-08 11:18:45.526  1533  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:18:45.528  1533  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 11:18:45.578  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-08 11:18:45.580  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-08 11:18:45.583  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-08 11:18:47.118  3341  3341 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-08 11:18:47.122  3341  3341 D AndroidRuntime: CheckJNI is OFF
08-08 11:18:47.158  3341  3341 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-08 11:18:47.200  3341  3341 I Radio-JNI: register_android_hardware_Radio DONE
08-08 11:18:47.221  3341  3341 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-08 11:18:47.226   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 11:18:47.270  1818  1829 W SearchService: Abort, client detached.
08-08 11:18:47.277  3341  3341 D AndroidRuntime: Shutting down VM
08-08 11:18:47.295  1818  1818 I HotwordDetector: Closing mic
08-08 11:18:47.296  1818  2157 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@bffbd6c
08-08 11:18:47.296  1818  2164 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-08 11:18:47.300   873  1404 I ActivityManager: Start proc 3350:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-08 11:18:47.329  1818  1818 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-08 11:18:47.354   376  2166 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-08 11:18:47.356   376  2166 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-08 11:18:47.365   376  1288 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-08 11:18:47.367  1818  2161 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-08 11:18:47.368  1818  2163 I MicroRecognitionRnrImpl: Detection finished
08-08 11:18:47.392  3350  3350 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-08 11:18:47.419  3350  3350 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-08 11:18:47.425  3350  3350 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1060-1063)
08-08 11:18:47.426  3350  3350 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 11:18:47.442  3350  3350 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cd0547a}
08-08 11:18:47.442  3350  3350 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 11:18:47.443  3350  3350 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 11:18:47.448  3350  3350 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-08 11:18:47.450  3350  3350 E SysUtils: ApplicationContext is null in ApplicationStatus
08-08 11:18:47.477  3350  3365 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-08 11:18:47.485  3350  3350 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-08 11:18:47.494  3350  3350 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 11:18:47.494  3350  3350 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 11:18:47.495  3350  3350 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 11:18:47.495  3350  3350 I Adreno  : Build Date                       : 10/20/15
08-08 11:18:47.495  3350  3350 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 11:18:47.495  3350  3350 I Adreno  : Local Branch                     : M14
08-08 11:18:47.495  3350  3350 I Adreno  : Remote Branch                    : 
08-08 11:18:47.495  3350  3350 I Adreno  : Remote Branch                    : 
08-08 11:18:47.495  3350  3350 I Adreno  : Reconstruct Branch               : 
,08-08 11:18:47.562   873   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5013c42:true
,08-08 11:18:47.608  3350  3350 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-08 11:18:47.633  3350  3350 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-08 11:18:47.724  3350  3387 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-08 11:18:47.735  3350  3374 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-08 11:18:47.782  3350  3387 I OpenGLRenderer: Initialized EGL, version 1.4
,08-08 11:18:47.854   873   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +579ms
,08-08 11:18:47.857  1653  1653 I Keyboard.Facilitator: onFinishInput()
,08-08 11:18:47.926  3350  3350 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3350
,08-08 11:18:48.024  3350  3350 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-08 11:18:48.106   873  1747 I ActivityManager: Killing 2329:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-08 11:18:48.143   873  1747 I ActivityManager: Killing 3011:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-08 11:18:48.244  3350  3389 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1669334736
,08-08 11:18:48.252  3350  3389 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 11:18:48.252  3350  3389 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 11:18:48.252  3350  3389 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 11:18:48.252  3350  3389 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 11:18:48.252  3350  3389 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-08 11:18:48.252  3350  3389 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d43cade added. We now have 1 listener(s)
,08-08 11:18:48.256  3350  3389 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-08 11:18:48.257  3350  3389 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-08 11:18:48.258  3350  3389 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-08 11:18:48.258  3350  3389 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
,08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-08 11:18:48.262  3350  3389 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f539ed5 added. We now have 1 listener(s)
08-08 11:18:48.262  3350  3389 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 11:18:48.273   873  1318 D WifiService: New client listening to asynchronous messages
,08-08 11:18:48.274  3350  3389 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 11:18:48.274  3350  3389 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-08 11:18:48.274  3350  3389 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-08 11:18:48.274  3350  3389 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-08 11:18:48.274  3350  3389 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-08 11:18:48.276  3350  3389 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 11:18:48.277  3350  3389 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-08 11:18:48.280  3350  3389 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:18:48.280  3350  3389 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:18:48.280  3350  3389 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-08 11:18:48.280  3350  3389 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 11:18:48.281  3350  3389 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-08 11:18:48.398  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:18:48.402  3350  3350 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 11:18:49.378  3350  3398 W jxcore-log: Initializing JXcore engine
,08-08 11:18:49.378  3350  3398 W jxcore-log: JXcore engine is ready
,08-08 11:18:49.418  3398  3398 W Thread-286: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8837 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-08 11:18:49.418  3398  3398 W Thread-286: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11511]" dev="sockfs" ino=11511 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-08 11:18:49.418  3398  3398 W Thread-286: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-08 11:18:49.418  3398  3398 W Thread-286: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24171]" dev="sockfs" ino=24171 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-08 11:18:49.430  3350  3398 W jxcore-log: Starting JXcore engine
,08-08 11:18:49.524  3350  3398 W jxcore-log: Platform android
08-08 11:18:49.524  3350  3398 W jxcore-log: 
,08-08 11:18:49.524  3350  3398 W jxcore-log: Process ARCH arm
08-08 11:18:49.524  3350  3398 W jxcore-log: 
,08-08 11:18:49.747  3350  3398 I jxcore-log: JXcore Cordova bridge is ready!
08-08 11:18:49.747  3350  3398 I jxcore-log: 
,08-08 11:18:49.748  3350  3398 W jxcore-log: JXcore engine is started
,08-08 11:18:49.756  3350  3389 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-08 11:18:49.760  3350  3350 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-08 11:19:05.538  3350  3398 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-08 11:19:05.538  3350  3398 I jxcore-log: 
,08-08 11:19:05.540  3350  3398 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-08 11:19:05.540  3350  3398 I jxcore-log: 
,08-08 11:19:05.541  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:05.541  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:05.542  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:05.542  3350  3398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:05.544  3350  3398 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-08 11:19:05.544  3350  3398 I jxcore-log: 
,08-08 11:19:05.546  3350  3398 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-08 11:19:05.546  3350  3398 I jxcore-log: 
,08-08 11:19:05.908  3350  3398 D ExecuteNativeTests: Running unit tests
,08-08 11:19:05.970  3350  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-08 11:19:05.970  3350  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 added. We now have 2 listener(s)
,08-08 11:19:05.971  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 11:19:05.971  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 11:19:05.971  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 11:19:05.971  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:19:05.971  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e added. We now have 2 listener(s)
08-08 11:19:05.971  3350  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:19:05.971  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-08 11:19:05.986  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 11:19:05.989  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:05.989  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:05.989  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:05.989  3350  3398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:05.990  3350  3398 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 11:19:05.992  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:05.998  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 11:19:05.999  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-08 11:19:05.999  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-08 11:19:06.003  3350  3398 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-08 11:19:06.004  3350  3398 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 11:19:06.005  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 11:19:06.006  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-08 11:19:06.006  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 11:19:06.007  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:19:06.008  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.009  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.009  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.011  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.011  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.012  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-08 11:19:06.012  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 11:19:06.013  3350  3398 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 removed from the list
08-08 11:19:06.013  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.013  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e removed from the list
08-08 11:19:06.013  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.014  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.015  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 11:19:06.015  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:19:06.018  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:19:06.015  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 11:19:06.020  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.021  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 11:19:06.021  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.021  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
,08-08 11:19:06.026  3350  3398 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-08 11:19:06.029  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 11:19:06.029  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 11:19:06.029  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.030  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 11:19:06.030  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.030  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.030  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.030  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.030  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.030  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.030  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.030  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 11:19:06.030  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.030  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.031  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.031  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.031  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.031  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
,08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-08 11:19:06.037  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 11:19:06.038  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 11:19:06.039  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 11:19:06.039  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.039  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 11:19:06.039  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.040  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 11:19:06.040  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.040  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.040  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.040  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.040  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.040  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.040  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.040  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.040  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.040  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.040  1533  2591 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 11:19:06.040  1533  2591 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-08 11:19:06.040  1533  2591 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:06.040  1533  2591 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 11:19:06.041  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.041  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.041  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.041  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.042  3350  3398 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 11:19:06.044  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:19:06.045  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:06.045  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:06.045  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:19:06.045  3350  3398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:06.045  3350  3398 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 11:19:06.045  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 11:19:06.045  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 11:19:06.046  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 11:19:06.046  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:19:06.046  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 11:19:06.048  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:06.049  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 11:19:06.050  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:19:06.050  3350  3398 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 11:19:06.050  3350  3350 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:19:06.052  3350  3398 I io.jxcore.node.ConnectionHelper: start: OK
08-08 11:19:06.053  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.053  3350  3398 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-08 11:19:06.054  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.054  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.054  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 11:19:06.054  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.054  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 11:19:06.054  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 11:19:06.054  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 11:19:06.054  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 11:19:06.054  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 11:19:06.055  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 11:19:06.055  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:19:06.058  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:19:06.058  3350  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:19:06.058  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.059  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.059  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:19:06.059  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.059  3350  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:19:06.059  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.059  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.059  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.059  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.059  3350  3350 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:19:06.060  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.060  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.061  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.061  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.061  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.061  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.062  3350  3398 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 11:19:06.064  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:19:06.065  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:06.065  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:06.065  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.065  3350  3398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:06.065  3350  3398 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 11:19:06.065  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 11:19:06.065  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 11:19:06.066  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 11:19:06.066  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:19:06.066  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 11:19:06.067  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 11:19:06.068  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:19:06.068  3350  3398 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 11:19:06.068  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:06.068  3350  3398 I io.jxcore.node.ConnectionHelper: start: OK
08-08 11:19:06.068  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.068  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.068  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 11:19:06.068  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.068  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 11:19:06.068  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 11:19:06.069  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 11:19:06.069  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 11:19:06.069  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 11:19:06.069  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 11:19:06.069  3350  3350 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 11:19:06.067  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-08 11:19:06.069  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:19:06.069  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:19:06.070  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.073  3350  3398 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-08 11:19:06.073  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.073  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.073  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.070  3350  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:19:06.073  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.073  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 11:19:06.073  3350  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:19:06.073  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.073  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.073  3350  3350 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:19:06.073  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.074  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.074  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.074  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-08 11:19:06.074  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-08 11:19:06.074  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.074  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.074  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.074  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.074  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.075  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.075  3350  3398 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-08 11:19:06.075  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.075  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.075  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.076  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.076  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.076  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.076  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.076  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.076  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.076  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.076  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.076  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.076  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.076  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.076  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.076  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.076  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.076  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
,08-08 11:19:06.077  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 11:19:06.077  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.077  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.077  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.077  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.077  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.077  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.078  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.078  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.078  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.078  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.078  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.078  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.078  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.078  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.078  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.078  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.078  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.078  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.079  3350  3398 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-08 11:19:06.079  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.079  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.079  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.079  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.079  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.079  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.079  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.079  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.079  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.079  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.079  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.079  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.079  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.080  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.080  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.080  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.080  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.080  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.081  3350  3398 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-08 11:19:06.081  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.081  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.081  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.081  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.081  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.081  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.081  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.081  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.081  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.081  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.081  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.081  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.081  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.081  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.082  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.082  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.082  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.082  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.082  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 11:19:06.082  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 11:19:06.082  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 11:19:06.082  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 11:19:06.083  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 11:19:06.083  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 11:19:06.083  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.083  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.083  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.083  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.083  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.083  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.083  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.083  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.083  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.083  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.083  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.083  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.083  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.083  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.084  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.084  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.084  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.084  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.084  3350  3398 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:19:06.085  3350  3398 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 11:19:06.085  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-08 11:19:06.089  3350  3398 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:19:06.089  3350  3398 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-08 11:19:06.089  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 11:19:06.089  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 11:19:06.089  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 11:19:06.089  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 11:19:06.090  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 11:19:06.091  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 11:19:06.091  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-08 11:19:06.091  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 11:19:06.091  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 11:19:06.091  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 11:19:06.091  3350  3398 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-08 11:19:06.091  3350  3398 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 11:19:06.091  3350  3398 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-08 11:19:06.091  3350  3398 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:19:06.091  3350  3398 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 11:19:06.091  3350  3398 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-08 11:19:06.091  3350  3398 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:19:06.091  3350  3398 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 11:19:06.091  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-08 11:19:06.096  3350  3398 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-08 11:19:06.097  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-08 11:19:06.099  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-08 11:19:06.099  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-08 11:19:06.100  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-08 11:19:06.101  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-08 11:19:06.101  3350  3398 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-08 11:19:06.101  3350  3398 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 11:19:06.102  3350  3398 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-08 11:19:06.104  3350  3406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 350)
08-08 11:19:06.105  3350  3406 E BluetoothDevice: Bluetooth is not enabled
08-08 11:19:06.105  3350  3406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-08 11:19:06.105  3350  3406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 350)
08-08 11:19:06.105  3350  3406 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 350)
08-08 11:19:06.105  3350  3406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 350
08-08 11:19:06.105  3350  3350 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
08-08 11:19:06.105  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.105  3350  3406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 350
08-08 11:19:06.106  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.106  3350  3350 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
08-08 11:19:06.106  3350  3406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 350)
08-08 11:19:06.106  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.106  3350  3350 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 11:19:06.106  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.106  3350  3350 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 11:19:06.106  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.107  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.107  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.107  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.108  3350  3407 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 350
08-08 11:19:06.107  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.110  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.110  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.110  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.111  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.111  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.111  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.111  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.111  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.111  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.112  3350  3398 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-08 11:19:06.112  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.112  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.112  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.113  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.113  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.113  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.113  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.113  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.113  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.113  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.113  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.113  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.113  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.113  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.114  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.114  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.114  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.114  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.114  3350  3398 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-08 11:19:06.114  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.114  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.115  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.115  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.115  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.115  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.115  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.115  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.115  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.115  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.115  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.115  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.115  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.115  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.116  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.116  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.116  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.116  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.116  3350  3398 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-08 11:19:06.116  3350  3398 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-08 11:19:06.117  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 11:19:06.117  3350  3398 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-08 11:19:06.117  3350  3398 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 11:19:06.117  3350  3398 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-08 11:19:06.117  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 11:19:06.117  3350  3398 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-08 11:19:06.117  3350  3398 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 11:19:06.117  3350  3398 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 11:19:06.117  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 11:19:06.117  3350  3398 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-08 11:19:06.117  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.118  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.118  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.118  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.118  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.118  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.118  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.118  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.118  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.118  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.118  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.118  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.118  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.118  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.119  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.119  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.119  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.119  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.119  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.119  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.119  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.120  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.120  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.120  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.120  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.120  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.120  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.120  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.120  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.120  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.120  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.120  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.120  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.120  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.121  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.121  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.121  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.121  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.121  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.121  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
,08-08 11:19:06.121  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.121  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.121  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.121  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.121  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.121  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.121  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.122  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.122  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.122  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.122  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.123  3350  3398 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-08 11:19:06.123  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:19:06.123  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-08 11:19:06.123  3350  3398 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 11:19:06.123  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 11:19:06.124  3350  3350 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 11:19:06.124  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.124  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-08 11:19:06.124  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.124  3350  3398 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-08 11:19:06.124  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.124  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.124  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 11:19:06.124  3350  3350 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-08 11:19:06.124  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 11:19:06.124  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 11:19:06.124  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.124  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.125  3350  3398 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:19:06.125  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.125  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.125  3350  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:19:06.125  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.125  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.125  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.125  3350  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 11:19:06.125  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.125  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.126  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.125  3350  3350 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 11:19:06.126  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.126  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.126  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.126  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.126  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.126  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.126  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.126  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.126  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.126  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.126  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.127  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 11:19:06.127  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 11:19:06.127  3350  3398 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-08 11:19:06.127  3350  3398 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 11:19:06.127  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 11:19:06.128  3350  3398 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 11:19:06.128  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.128  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.128  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.128  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.128  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.128  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.128  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.128  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.128  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.128  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.128  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.128  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.128  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.129  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.129  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.129  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.129  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.129  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.131  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.131  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.131  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.131  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.131  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.131  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.131  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.131  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.131  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.131  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.131  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.131  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.131  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.131  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.132  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.132  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.132  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.132  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.133  3350  3398 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 11:19:06.133  3350  3398 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 11:19:06.133  3350  3398 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 11:19:06.133  3350  3398 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 11:19:06.133  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.133  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.133  3350  3398 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e5c7ed9 not in the list
08-08 11:19:06.133  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.133  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.133  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
08-08 11:19:06.134  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.134  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.134  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 11:19:06.134  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 11:19:06.134  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 11:19:06.134  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 11:19:06.134  3350  3398 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 11:19:06.134  3350  3398 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@de509e not in the list
08-08 11:19:06.135  3350  3398 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-08 11:19:06.135  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 11:19:06.135  3350  3398 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-08 11:19:06.135  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 11:19:06.135  3350  3398 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-08 11:19:06.136  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 11:19:06.137  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 11:19:06.137  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-08 11:19:06.138  3350  3398 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-08 11:19:06.138  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 11:19:06.138  3350  3398 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-08 11:19:06.138  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 11:19:06.138  3350  3398 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-08 11:19:06.138  3350  3398 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-08 11:19:06.139  3350  3398 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-08 11:19:06.139  3350  3398 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-08 11:19:06.139  3350  3398 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-08 11:19:06.139  3350  3398 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-08 11:19:06.140  3350  3398 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-08 11:19:06.140  3350  3398 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-08 11:19:06.140  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:19:06.141  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9893838 added. We now have 2 listener(s)
08-08 11:19:06.141  3350  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:19:06.142   873  1747 D WifiService: setWifiEnabled: true pid=3350, uid=10000
08-08 11:19:06.142   873  1747 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-08 11:19:06.144  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:19:06.144  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1de3011 added. We now have 3 listener(s)
08-08 11:19:06.145  3350  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listen,er added - the number of listeners is now 1
08-08 11:19:06.145  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.145  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.146  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:19:06.146  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c65d576 added. We now have 4 listener(s)
08-08 11:19:06.146  3350  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:19:06.147  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 11:19:06.147  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@daa0777 added. We now have 5 listener(s)
08-08 11:19:06.147  3350  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 11:19:06.148   873  1866 D WifiService: setWifiEnabled: false pid=3350, uid=10000
08-08 11:19:06.149   873  1866 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-08 11:19:06.157   873   891 I ActivityManager: Start proc 3410:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-08 11:19:06.157   873  1316 D WifiConfigStore: Loading config and enabling all networks 
08-08 11:19:06.160  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:06.160  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:06.160  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.160  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:06.169   873  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-08 11:19:06.169   873  1316 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-08 11:19:06.170   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-08 11:19:06.170   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-08 11:19:06.171   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-08 11:19:06.172   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-08 11:19:06.172   873   886 I ActivityManager: Start proc 3420:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-08 11:19:06.172   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 11:19:06.172   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-08 11:19:06.173  3350  3398 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 11:19:06.174  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:06.174  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:06.174  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:19:06.174  3350  3398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:06.174  3350  3398 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 11:19:06.175  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:06.220  3420  3420 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-08 11:19:06.224   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-08 11:19:06.226   372   871 D CommandListener: Setting iface cfg
,08-08 11:19:06.227   873  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-08 11:19:06.227   873  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-08 11:19:06.235   873  1315 D WifiNative-HAL: p2pGetDeviceAddress
,08-08 11:19:06.235   873  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-08 11:19:06.238   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-08 11:19:06.242  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:06.242  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:06.242  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:19:06.242  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:06.244  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:06.244  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:06.244  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:06.244  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:06.244  1871  2069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 11:19:06.265  3410  3410 D AdapterServiceConfig: Adding HeadsetService
,08-08 11:19:06.265  3410  3410 D AdapterServiceConfig: Adding A2dpService
08-08 11:19:06.265  3410  3410 D AdapterServiceConfig: Adding HidService
08-08 11:19:06.265  3410  3410 D AdapterServiceConfig: Adding HealthService
08-08 11:19:06.266  3410  3410 D AdapterServiceConfig: Adding PanService
,08-08 11:19:06.266  3410  3410 D AdapterServiceConfig: Adding GattService
08-08 11:19:06.266  3410  3410 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 11:19:06.295  3420  3420 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-08 11:19:06.305   873   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32be85a:true
,08-08 11:19:06.305  3410  3410 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 11:19:06.309  3410  3410 I bt_bluedroid: init
,08-08 11:19:06.309  3410  3447 I BluetoothAdapterState: Entering OffState
,08-08 11:19:06.313  3410  3448 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 11:19:06.314  3410  3448 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 11:19:06.314  3410  3448 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-08 11:19:06.314  3410  3448 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 11:19:06.316  3410  3410 I bt_bluedroid: get_profile_interface socket
,08-08 11:19:06.317  3410  3410 I bt_bluedroid: get_profile_interface sdp
,08-08 11:19:06.318   873  1711 I ActivityManager: Killing 2679:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-08 11:19:06.318  3410  3452 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 11:19:06.347  3410  3452 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 11:19:06.349  3410  3426 I bt_bluedroid: config_hci_snoop_log
,08-08 11:19:06.350   873   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-08 11:19:06.355  3410  3447 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 11:19:06.356  3410  3447 D BluetoothAdapterProperties: Setting state to 14
08-08 11:19:06.356  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 11:19:06.360  3410  3447 D BluetoothBondStateMachine: make
,08-08 11:19:06.363  3410  3453 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-08 11:19:06.369  3410  3447 I BluetoothAdapterState: Entering PendingCommandState
,08-08 11:19:06.370  3410  3410 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 11:19:06.378  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:06.379  3410  3410 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 11:19:06.380  3410  3410 D BtGatt.GattService: Received start request. Starting profile...
,08-08 11:19:06.381  3410  3410 D BtGatt.GattService: start()
08-08 11:19:06.381  3410  3410 I bt_bluedroid: get_profile_interface gatt
,08-08 11:19:06.383  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
08-08 11:19:06.383  3410  3410 D BtGatt.AdvertiseManager: advertise manager created
,08-08 11:19:06.398  3410  3410 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:06.399  3410  3410 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:06.399  3410  3410 V BluetoothAdapterState: isBleTurningOn()=true
08-08 11:19:06.399  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:06.400  3410  3447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-08 11:19:06.400  3410  3447 I bt_bluedroid: enable
08-08 11:19:06.400  3410  3448 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-08 11:19:06.401  3410  3448 I bt_hci  : start_up
,08-08 11:19:06.410  3410  3448 I bt_vendor: alloc value 0xb3a26189
,08-08 11:19:06.410  3410  3448 I bt_vendor: init
08-08 11:19:06.410  3410  3448 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 11:19:06.411  3410  3448 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 11:19:06.517  3410  3448 D bt_hci  : start_up starting async portion
08-08 11:19:06.517  3410  3456 I bt_hci  : event_finish_startup
08-08 11:19:06.517  3410  3456 I bt_hci_h4: hal_open
,08-08 11:19:06.518  3410  3456 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 11:19:06.523  3410  3456 I bt_userial_vendor: device fd = 51 open
,08-08 11:19:06.561  3410  3456 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 11:19:06.593  3410  3456 D bt_hwcfg: Chipset BCM4354A2
,08-08 11:19:06.593  3410  3456 D bt_hwcfg: Target name = [BCM4354A2]
08-08 11:19:06.594  3410  3456 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 11:19:06.627  3350  3350 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-08 11:19:07.353  3410  3456 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 11:19:07.355  3410  3456 D bt_hwcfg: Settlement delay -- 100 ms
08-08 11:19:07.355  3410  3456 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 11:19:07.472  3410  3456 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 11:19:07.473  3410  3456 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 11:19:07.503  3410  3456 I bt_hwcfg: vendor lib fwcfg completed
08-08 11:19:07.503  3410  3456 I bt_vendor: firmware callback
08-08 11:19:07.504  3410  3456 I bt_hci  : firmware_config_callback
,08-08 11:19:07.514  3410  3458 I bt_btu  : btu_task pending for preload complete event
,08-08 11:19:07.515  3410  3458 I bt_btu_task: Bluetooth chip preload is complete
08-08 11:19:07.515  3410  3458 I bt_btu  : btu_task received preload complete event
,08-08 11:19:07.525  3410  3458 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 11:19:07.525  3410  3458 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-08 11:19:07.526  3410  3458 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-08 11:19:07.526  3410  3458 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-08 11:19:07.526  3410  3458 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-08 11:19:07.527  3410  3458 I         : BTE_InitTraceLevels -- TRC_A2D
08-08 11:19:07.527  3410  3458 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 11:19:07.527  3410  3458 I         : BTE_InitTraceLevels -- TRC_BTM
,08-08 11:19:07.528  3410  3458 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 11:19:07.528  3410  3458 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 11:19:07.528  3410  3458 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 11:19:07.528  3410  3458 I         : BTE_InitTraceLevels -- TRC_GATT
,08-08 11:19:07.529  3410  3458 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 11:19:07.529  3410  3458 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 11:19:07.529  3410  3458 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 11:19:07.668  3410  3458 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a3d9d
,08-08 11:19:07.668  3410  3458 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a3d9d 
,08-08 11:19:07.679  3410  3452 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 11:19:07.682  3410  3452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 11:19:07.683  3410  3452 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 11:19:07.685  3410  3452 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 11:19:07.689  3410  3452 D BluetoothAdapterProperties: Scan Mode:20
08-08 11:19:07.689  3410  3452 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 11:19:07.690  3410  3452 D bt_hci  : do_postload posting postload work item
08-08 11:19:07.690  3410  3456 I bt_hci  : event_postload
,08-08 11:19:07.690  3410  3456 I bt_vendor: sco_config_cb
08-08 11:19:07.690  3410  3456 I bt_hci  : sco_config_callback postload finished.
,08-08 11:19:07.694  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:07.699  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:07.700  3410  3456 I bt_vendor: low_power_mode_cb
,08-08 11:19:07.705  3410  3452 D bt_bte_conf: Device ID record 1 : primary
,08-08 11:19:07.705  3410  3452 D bt_bte_conf:   vendorId            = 000f
08-08 11:19:07.706  3410  3452 D bt_bte_conf:   vendorIdSource      = 0001
08-08 11:19:07.706  3410  3452 D bt_bte_conf:   product             = 1200
08-08 11:19:07.706  3410  3452 D bt_bte_conf:   version             = 1436
08-08 11:19:07.706  3410  3452 D bt_bte_conf:   clientExecutableURL = 
08-08 11:19:07.706  3410  3452 D bt_bte_conf:   serviceDescription  = 
08-08 11:19:07.706  3410  3452 D bt_bte_conf:   documentationURL    = 
08-08 11:19:07.707  3410  3452 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-08 11:19:07.707  3410  3448 D bt_stack_manager: event_start_up_stack finished
08-08 11:19:07.707  3410  3447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-08 11:19:07.708  3410  3447 D BluetoothAdapterProperties: Setting state to 15
08-08 11:19:07.709  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-08 11:19:07.712  3410  3447 I BluetoothAdapterState: Entering BleOnState
,08-08 11:19:07.716  3410  3447 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-08 11:19:07.716  3410  3447 D BluetoothAdapterProperties: Setting state to 11
08-08 11:19:07.716  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 11:19:07.721  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
08-08 11:19:07.724  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:07.725  3410  3410 D HeadsetService: Received start request. Starting profile...
,08-08 11:19:07.726  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:07.729  3410  3410 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-08 11:19:07.731  3410  3410 D HeadsetStateMachine: make
,08-08 11:19:07.739   873   886 I ActivityManager: Start proc 3465:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-08 11:19:07.744  3410  3410 D HeadsetStateMachine: max_hf_connections = 1
08-08 11:19:07.744  3410  3410 I bt_bluedroid: get_profile_interface handsfree
08-08 11:19:07.745  3410  3452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-08 11:19:07.745  3410  3452 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-08 11:19:07.750  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:07.751  3410  3447 I BluetoothAdapterState: Entering PendingCommandState
08-08 11:19:07.751   873   873 D BluetoothA2dp: Proxy object connected
08-08 11:19:07.752  3410  3410 D A2dpService: Received start request. Starting profile...
08-08 11:19:07.753  3410  3410 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-08 11:19:07.753  3410  3410 I bt_bluedroid: get_profile_interface avrcp
,08-08 11:19:07.760  3410  3410 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-08 11:19:07.760  3410  3410 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 11:19:07.760  3410  3410 D A2dpStateMachine: make
,08-08 11:19:07.762  3410  3410 I bt_bluedroid: get_profile_interface a2dp
,08-08 11:19:07.763  3410  3452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 11:19:07.764  3410  3477 D A2dpStateMachine: Enter Disconnected: -2
,08-08 11:19:07.766  3410  3410 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 11:19:07.767  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:07.769  1373  1373 D BluetoothInputDevice: Proxy object connected
,08-08 11:19:07.769  3410  3410 D HidService: Received start request. Starting profile...
08-08 11:19:07.769  3410  3410 I bt_bluedroid: get_profile_interface hidhost
,08-08 11:19:07.769  1373  1373 D HidProfile: Bluetooth service connected
08-08 11:19:07.769  3410  3452 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39853e5
08-08 11:19:07.769  3410  3410 D HidService: setHidService(): set to: null
08-08 11:19:07.769  3410  3452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-08 11:19:07.770  3410  3410 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 11:19:07.771  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
08-08 11:19:07.771  3410  3410 D HealthService: Received start request. Starting profile...
,08-08 11:19:07.773  3410  3410 I bt_bluedroid: get_profile_interface health
08-08 11:19:07.773  3410  3410 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 11:19:07.774  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:07.777  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 11:19:07.777  3410  3410 D PanService: Received start request. Starting profile...
,08-08 11:19:07.778  3410  3410 D BluetoothPanServiceJni: initializeNative(L110): pan
08-08 11:19:07.778  3410  3410 I bt_bluedroid: get_profile_interface pan
08-08 11:19:07.778  1373  1373 D PanProfile: Bluetooth service connected
08-08 11:19:07.778  3410  3452 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-08 11:19:07.780  3410  3410 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:07.780  3410  3410 V BluetoothAdapterState: isTurningOn()=true
,08-08 11:19:07.780  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:07.780  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:07.782  3410  3464 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-08 11:19:07.783  3410  3410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
08-08 11:19:07.784  1373  1373 D BluetoothMap: Proxy object connected
08-08 11:19:07.784  1373  1373 D MapProfile: Bluetooth service connected
08-08 11:19:07.784  1373  1373 D BluetoothMap: getConnectedDevices()
08-08 11:19:07.785  3410  3410 D BluetoothMapService: Received start request. Starting profile...
08-08 11:19:07.785  1373  1373 D BluetoothMap: Bluetooth is Not enabled
08-08 11:19:07.785  3410  3410 D BluetoothMapService: start()
08-08 11:19:07.787  3410  3410 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-08 11:19:07.788  3410  3410 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-08 11:19:07.788  3410  3410 D BluetoothMapAppObserver: createReceiver()
,08-08 11:19:07.789  3410  3410 D BluetoothMapAppObserver: initObservers()
08-08 11:19:07.789  3410  3410 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:07.795  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isTurningOn()=true
,08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:07.796  3410  3410 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:07.797  3410  3410 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:07.797  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:07.797  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:07.797  3410  3447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-08 11:19:07.797  3410  3447 D BluetoothAdapterProperties: ScanMode =  20
08-08 11:19:07.797  3410  3447 D BluetoothAdapterProperties: State =  11
08-08 11:19:07.797  3465  3465 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-08 11:19:07.797  3410  3447 D BluetoothAdapterProperties: Setting state to 12
08-08 11:19:07.797  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 11:19:07.798   873   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 11:19:07.798  3410  3447 I BluetoothAdapterState: Entering OnState
,08-08 11:19:07.799  3410  3452 D BluetoothAdapterProperties: Scan Mode:21
,08-08 11:19:07.799  3410  3452 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 11:19:07.800  1373  1838 D BluetoothMap: onBluetoothStateChange: up=true
08-08 11:19:07.800   873   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 11:19:07.800   873   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 11:19:07.800  1373  1387 D BluetoothPbap: onBluetoothStateChange: up=true
,08-08 11:19:07.801  3350  3350 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-08 11:19:07.803  1724  1735 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:19:07.804  3350  3350 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-08 11:19:07.804  1373  1400 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 11:19:07.804  1373  1837 D BluetoothPan: onBluetoothStateChange on: true
,08-08 11:19:07.805   873   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:19:07.807  3350  3350 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-08 11:19:07.806   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-08 11:19:07.807  3410  3410 D BluetoothMapService: onReceive
08-08 11:19:07.807  3410  3410 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-08 11:19:07.808  3410  3410 D BluetoothMapService: STATE_ON
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:07.810  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:07.812  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:07.816  3410  3410 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 11:19:07.816  3410  3410 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:07.816  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:07.817  3410  3410 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 11:19:07.818  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:07.819  1373  1688 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-08 11:19:07.820  3410  3410 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:19:07.820  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:07.821  3410  3410 D ObexServerSockets: Succeed to create listening sockets 
,08-08 11:19:07.821  3410  3410 D ObexServerSockets0: startAccept()
08-08 11:19:07.821  3410  3410 D ObexServerSockets0: prepareForNewConnect()
08-08 11:19:07.821  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:07.823  3410  3410 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-08 11:19:07.823  3410  3410 D BluetoothSdpJni: SDP Create record success - handle: 0
08-08 11:19:07.824  3410  3485 D ObexServerSockets0: Accepting socket connection...
08-08 11:19:07.824  3410  3486 D ObexServerSockets0: Accepting socket connection...
08-08 11:19:07.824  1373  1688 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-08 11:19:07.824  1373  1373 D BluetoothA2dp: Proxy object connected
,08-08 11:19:07.828  3410  3410 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 11:19:07.828  3410  3410 D ObexServerSockets0: prepareForNewConnect()
,08-08 11:19:07.830   873   884 I ActivityManager: Killing 2838:com.google.android.gm/u0a78 (adj 15): empty #17
,08-08 11:19:07.873  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:19:07.899   873  1777 I ActivityManager: Start proc 3487:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-08 11:19:07.900   873   891 D BluetoothHeadset: Proxy object connected
08-08 11:19:07.903   873   891 D BluetoothHeadset: Proxy object connected
,08-08 11:19:07.904  1724  1890 D BluetoothHeadset: Proxy object connected
,08-08 11:19:07.905   873   891 D BluetoothHeadset: Proxy object connected
,08-08 11:19:07.928  1373  1838 D BluetoothHeadset: Proxy object connected
,08-08 11:19:07.929  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-08 11:19:07.942  3487  3487 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-08 11:19:08.127  3487  3487 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.127  3487  3487 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.127  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.128  3487  3487 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.128  3487  3487 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.128  3487  3487 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.k.d(PG:583)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.128  3487  3487 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.128  3487  3487 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.128  3487  3487 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:19:08.128  3487  3487 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:19:08.148  3465  3465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 11:19:08.154   873   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28d44f8:true
08-08 11:19:08.160  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:19:08.175  3465  3465 D LocalBluetoothProfileManager: Adding local A2DP profile
08-08 11:19:08.179  1373  1373 D BluetoothPbap: Proxy object connected
08-08 11:19:08.180  1373  1373 D PbapServerProfile: Bluetooth service connected
08-08 11:19:08.183  3465  3465 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-08 11:19:08.193  3465  3465 D LocalBluetoothProfileManager: Adding local MAP profile
08-08 11:19:08.193  3465  3465 D BluetoothMap: Create BluetoothMap proxy object
08-08 11:19:08.198  3465  3465 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-08 11:19:08.205  3410  3517 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 11:19:08.212  3465  3465 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:19:08.213  3465  3465 D BluetoothA2dp: Proxy object connected
,08-08 11:19:08.218  3465  3465 D BluetoothInputDevice: Proxy object connected
,08-08 11:19:08.219  3465  3465 D HidProfile: Bluetooth service connected
,08-08 11:19:08.221  3465  3465 D BluetoothPan: BluetoothPAN Proxy object connected
,08-08 11:19:08.222  3465  3465 D PanProfile: Bluetooth service connected
08-08 11:19:08.222  3465  3465 D BluetoothMap: Proxy object connected
,08-08 11:19:08.222  3465  3465 D MapProfile: Bluetooth service connected
08-08 11:19:08.222  3465  3465 D BluetoothMap: getConnectedDevices()
,08-08 11:19:08.224  3465  3465 D BluetoothPbap: Proxy object connected
08-08 11:19:08.224  3465  3465 D PbapServerProfile: Bluetooth service connected
,08-08 11:19:08.225   873  1741 I ActivityManager: Killing 3032:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-08 11:19:08.263  3410  3522 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 11:19:08.265  3410  3522 I BtOppRfcommListener: Accept thread started.
,08-08 11:19:08.292  3465  3480 D BluetoothHeadset: Proxy object connected
,08-08 11:19:08.293  3465  3465 D HeadsetProfile: Bluetooth service connected
,08-08 11:19:08.356  3487  3507 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-08 11:19:08.376   873   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28f4eed:true
,08-08 11:19:09.179   873  1741 D WifiService: setWifiEnabled: true pid=3350, uid=10000
,08-08 11:19:09.179   873  1741 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 11:19:09.191   873  1316 D WifiConfigStore: Loading config and enabling all networks 
,08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:09.209  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:19:09.217  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:09.223   873  1316 D WifiConfigStore: loaded 0 passpoint configs
,08-08 11:19:09.224   873  1316 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-08 11:19:09.224   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-08 11:19:09.225   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-08 11:19:09.226   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-08 11:19:09.226   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-08 11:19:09.226   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 11:19:09.226   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-08 11:19:09.228  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:09.229  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:19:09.236  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:09.314   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-08 11:19:09.318   372   871 D CommandListener: Setting iface cfg
,08-08 11:19:09.319   873  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-08 11:19:09.320   873  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-08 11:19:09.331   873  1315 D WifiNative-HAL: p2pGetDeviceAddress
08-08 11:19:09.333   873  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-08 11:19:09.337   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 11:19:09.356   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 11:19:09.693  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-08 11:19:09.734  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-08 11:19:09.735  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-08 11:19:09.741   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 11:19:09.764   873  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 11:19:09.765   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 11:19:09.765   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-08 11:19:09.795   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 11:19:09.812   372   871 D CommandListener: Setting iface cfg
,08-08 11:19:09.832   873  1316 D WifiStateMachine: Start Dhcp Watchdog 1
,08-08 11:19:09.847   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-08 11:19:09.849   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-08 11:19:09.850   873  1320 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-08 11:19:09.899   873  3531 D DhcpClient: Receive thread started
,08-08 11:19:09.981   873  1316 E native  : do suspend false
,08-08 11:19:10.004   873  3530 D DhcpClient: Broadcasting DHCPDISCOVER
,08-08 11:19:10.019   873  3531 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 165431, domain null
,08-08 11:19:10.022   873  3530 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 165431 seconds
,08-08 11:19:10.027   873  3530 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-08 11:19:10.041   873  3531 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-08 11:19:10.042   873  3530 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-08 11:19:10.049   372   871 D CommandListener: Setting iface cfg
,08-08 11:19:10.061   873  3530 D DhcpClient: Scheduling renewal in 86399s
,08-08 11:19:10.064   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-08 11:19:10.080   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-08 11:19:10.083   873  1316 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-08 11:19:10.085   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-08 11:19:10.093   873  1320 D ConnectivityService: Adding iface wlan0 to network 100
,08-08 11:19:10.106   873  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-08 11:19:10.150   873  1320 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-08 11:19:10.151   873  1320 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-08 11:19:10.155   873  1320 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-08 11:19:10.160   873  1320 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-08 11:19:10.161   873  1320 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-08 11:19:10.169   873  1320 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-08 11:19:10.175   873  1320 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-08 11:19:10.175   873  1320 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-08 11:19:10.175   873  1320 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-08 11:19:10.175   873  1320 D ConnectivityService:    accepting network in place of null
08-08 11:19:10.176   873  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-08 11:19:10.176   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 11:19:10.177   873  1320 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 11:19:10.193   873  3529 D NetlinkSocketObserver: NeighborEvent{elapsedMs=143826, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-08 11:19:10.212   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 11:19:10.260   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 11:19:10.260   873  3528 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:815::200e
,08-08 11:19:10.264   873  1320 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-08 11:19:10.277   873  1320 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-08 11:19:10.278   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:19:10.287   873  1320 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-08 11:19:10.289   873   891 D Tethering: MasterInitialState.processMessage what=3
,08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 11:19:10.305  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 11:19:10.307   873  1866 V BackupManagerService: Scheduling immediate backup pass
08-08 11:19:10.309   873   873 V BackupManagerService: Running a backup pass
08-08 11:19:10.311   873  1338 V BackupManagerService: clearing pending backups
08-08 11:19:10.312  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 11:19:10.319   873  1338 V PerformBackupTask: Beginning backup of 16 targets
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 11:19:10.323  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 11:19:10.325  1818  1818 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-08 11:19:10.347   873  1338 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-08 11:19:10.348  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 11:19:10.350   873  1691 D AlarmManagerService: Setting time of day to sec=1470647950
,08-08 11:19:10.537   873  1691 W AlarmManagerService: Unable to set rtc to 1470647950: Invalid argument
,08-08 11:19:10.539   873  1338 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-08 11:19:10.550   873  3528 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Aug 2016 09:19:10 GMT], X-Android-Received-Millis=[1470647950548], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470647950322]}
,08-08 11:19:10.556  1988  1988 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 11:19:10.557   873  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-08 11:19:10.558   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-08 11:19:10.558   873  1320 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-08 11:19:10.559   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-08 11:19:10.561  1988  1988 D SystemUpdateService: onCreate
,08-08 11:19:10.573  1988  1988 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 11:19:10.584  1988  3551 I SystemUpdateService: active receiver: enabled
,08-08 11:19:10.596  1988  3551 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 11:19:10.600   873  1381 I ActivityManager: Start proc 3556:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-08 11:19:10.625  1988  3551 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-08 11:19:10.625  1988  3551 I SystemUpdateService: now status is 0 (complete)
,08-08 11:19:10.625  1988  3551 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-08 11:19:10.625  1988  3551 I SystemUpdateService: file has been verified
08-08 11:19:10.626  1988  3551 I SystemUpdateService: OTA package size = 12249756
08-08 11:19:10.631   873  3569 D GpsLocationProvider: NTP server returned: 1470647950537 (Mon Aug 08 11:19:10 GMT+02:00 2016) reference: 143984 certainty: 8 system time offset: -94
,08-08 11:19:10.631   873  3569 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-08 11:19:10.638   873  1338 I BackupRestoreController: Getting widget state for user: 0
,08-08 11:19:10.639  3556  3556 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-08 11:19:10.663  3420  3550 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-08 11:19:10.666  1988  3551 I SystemUpdateService: showing system update notification
,08-08 11:19:10.669  1988  3575 I iu.SyncManager: SYNC; picasa accounts
,08-08 11:19:10.676  1988  1988 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-08 11:19:10.678  1988  1988 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-08 11:19:10.687  1988  3573 I MDM     : [189] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-08 11:19:10.688  1988  3573 W BaseAppContext: Using Auth Proxy for data requests.
08-08 11:19:10.688  1988  1988 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 11:19:10.689  1988  1988 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 11:19:10.700   873  1718 I ActivityManager: Start proc 3582:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-08 11:19:10.702  1988  1988 D SystemUpdateService: onDestroy
,08-08 11:19:10.715  1988  3573 V GoogleAuthProtoRequest: [189] a.<init>: mAccountName set to: thalitester@gmail.com
,08-08 11:19:10.718  1988  3575 I iu.UploadsManager: num queued entries: 0
,08-08 11:19:10.718  1988  3575 I iu.UploadsManager: num updated entries: 0
,08-08 11:19:10.720  3556  3576 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-08 11:19:10.747  1871  1887 W GmsBackupTransport: Unknown package in backup request: @pm@
08-08 11:19:10.747  1533  2242 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-08 11:19:10.747  1533  2242 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-08 11:19:10.747  1533  2242 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:10.747  1533  2242 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:10.757  1871  1887 V GmsBackupTransport: starting performBackup for @pm@
,08-08 11:19:10.760  1533  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-08 11:19:10.760  1533  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-08 11:19:10.760  1533  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:10.760  1533  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:10.763  3582  3582 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
08-08 11:19:10.766  1871  1887 V GmsBackupTransport: performBackup done for @pm@
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-08 11:19:10.769  3420  3550 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-08 11:19:10.778  3556  3576 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-08 11:19:10.780  3582  3582 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-08 11:19:10.786  1988  3575 I iu.SyncManager: NEXT; no task
08-08 11:19:10.786  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:19:10.792  3582  3582 D SprintDMHelper: simOperator: 
08-08 11:19:10.792  3582  3582 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 11:19:10.789  1988  3555 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-08 11:19:10.806   873  1868 I ActivityManager: Start proc 3604:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-08 11:19:10.824  3556  3576 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-08 11:19:10.855  1533  1533 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-08 11:19:10.874  1533  2242 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-08 11:19:10.874  1533  2242 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-08 11:19:10.874  1533  2242 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 11:19:10.874  1533  2242 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:10.882  3556  3556 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-08 11:19:10.890  1533  2242 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 11:19:10.890  1533  2242 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 11:19:10.890  1533  2242 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 11:19:10.890  1533  2242 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 11:19:10.890  1533  2242 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 11:19:10.890  1533  2242 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 11:19:10.890  1533  2242 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:19:10.893  1871  1886 W GmsBackupTransport: Error sending final backup to server: 
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 11:19:10.893  1871  1886 W GmsBackupTransport: 	... 1 more
08-08 11:19:10.894  1871  2080 I GmsBackupTransport: Next backup will happen in 43199997 millis.
08-08 11:19:10.894   873  1338 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-08 11:19:10.897  1988  3573 E MDM     : [189] SitrepService.a: Error sending sitrep.
,08-08 11:19:10.990  3619  3619 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1842959415.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1842959415.dex
,08-08 11:19:11.008   873  1404 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1988 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-08 11:19:11.045   873  1338 I BackupManagerService: Backup pass finished.
,08-08 11:19:11.049  3556  3556 W InstanceID/Rpc: Found 10011
,08-08 11:19:11.131  3619  3619 I dex2oat : dex2oat took 147.673ms (threads: 4) arena alloc=331KB java alloc=33KB native alloc=1642KB free=1685KB
,08-08 11:19:11.142  1533  2590 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-08 11:19:11.142  1533  2590 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-08 11:19:11.142  1533  2590 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:11.142  1533  2590 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:11.152   873  1707 I ActivityManager: Start proc 3684:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-08 11:19:11.169  3147  3593 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-08 11:19:11.169  3147  3593 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jdm.a(PG:82)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jcs.o(PG:406)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jcn.a(PG:1379)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jcs.i(PG:143)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at blb.a(PG:3937)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at czp.a(PG:18188)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at czp.a(PG:9081)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at czq.run(PG:1686)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 11:19:11.169  3147  3593 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jdj.a(PG:4091)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jdj.a(PG:1125)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jdm.a(PG:77)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	... 12 more
08-08 11:19:11.169  3147  3593 E HttpOperation: Caused by: faj: BadAuthentication
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at fal.a(PG:38)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	at jdj.a(PG:4089)
08-08 11:19:11.169  3147  3593 E HttpOperation: 	... 14 more
,08-08 11:19:11.182   873   885 I ActivityManager: Start proc 3700:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-08 11:19:11.195  3684  3684 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-08 11:19:11.204  1533  2242 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-08 11:19:11.204  1533  2242 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-08 11:19:11.204  1533  2242 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:11.204  1533  2242 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:11.208  1988  3574 W DriveInitializer: Awaiting to be initialized
,08-08 11:19:11.208  1988  3712 W DriveInitializer: Background init thread started
,08-08 11:19:11.209  3700  3700 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-08 11:19:11.290  2366  3686 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-08 11:19:11.294   873  1747 I ActivityManager: Killing 2475:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-08 11:19:11.360  3147  3593 E HttpOperation: [getmobileexperiments] Unexpected exception
08-08 11:19:11.360  3147  3593 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jdm.a(PG:82)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jcs.o(PG:406)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jcn.a(PG:1379)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jcs.i(PG:143)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at hec.a(PG:42)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at hee.a(PG:102)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at czr.a(PG:65)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at kka.a(PG:108)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at czp.a(PG:19176)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at czp.a(PG:9081)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at czq.run(PG:1686)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 11:19:11.360  3147  3593 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jdj.a(PG:4091)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jdj.a(PG:1125)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jdm.a(PG:77)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	... 15 more
08-08 11:19:11.360  3147  3593 E HttpOperation: Caused by: faj: BadAuthentication
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at fal.a(PG:38)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	at jdj.a(PG:4089)
08-08 11:19:11.360  3147  3593 E HttpOperation: 	... 17 more
,08-08 11:19:11.360  3147  3593 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-08 11:19:11.360  3147  3593 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jdm.a(PG:82)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jcs.o(PG:406)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jcn.a(PG:1379)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jcs.i(PG:143)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at hec.a(PG:42)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at hee.a(PG:102)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at czr.a(PG:65)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at kka.a(PG:108)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at czp.a(PG:19176)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at czp.a(PG:9081)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at czq.run(PG:1686)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jdj.a(PG:4091)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jdj.a(PG:1125)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jdm.a(PG:77)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	... 15 more
08-08 11:19:11.360  3147  3593 E ExperimentLoader: Caused by: faj: BadAuthentication
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at fal.a(PG:38)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	at jdj.a(PG:4089)
08-08 11:19:11.360  3147  3593 E ExperimentLoader: 	... 17 more
,08-08 11:19:11.387  1988  3712 W DriveInitializer: Background init thread ended
,08-08 11:19:11.441  1533  3621 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-08 11:19:11.466  3700  3700 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-08 11:19:11.474  3700  3700 I BooksApp: Created application version: 3.6.9 (30609)
,08-08 11:19:11.556   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 24170, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-08 11:19:11.563  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:19:11.597   873  1866 I ProcessStatsService: Added stats: 2016-08-08-09-18-33, over +1h30m26s952ms
,08-08 11:19:11.602   873  1866 I ProcessStatsService: Added stats: 2016-08-08-06-52-30, over +2h0m0s292ms
,08-08 11:19:11.607   873  1866 I ProcessStatsService: Added stats: 2016-08-08-03-52-29, over +3h0m0s403ms
,08-08 11:19:11.611   873  1866 I ProcessStatsService: Added stats: 2016-08-08-00-52-29, over +3h0m0s451ms
,08-08 11:19:11.615   873  1866 I ProcessStatsService: Added stats: 2016-08-07-21-52-28, over +3h0m0s410ms
,08-08 11:19:11.620   873  1866 I ProcessStatsService: Added stats: 2016-08-07-18-52-28, over +3h0m0s425ms
,08-08 11:19:11.624   873  1866 I ProcessStatsService: Added stats: 2016-08-07-15-52-28, over +3h0m0s485ms
,08-08 11:19:11.629   873  1866 I ProcessStatsService: Added stats: 2016-08-07-12-52-27, over +3h0m0s626ms
,08-08 11:19:11.634   873  1866 I ProcessStatsService: Added stats: 2016-08-07-09-52-26, over +3h0m0s410ms
,08-08 11:19:11.660  3700  3736 I BooksSync: Starting books sync for 61035162, extras: ade
,08-08 11:19:11.662  3684  3684 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-08 11:19:11.662  3684  3684 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-08 11:19:11.662  3684  3684 I GAv4    :   adb logcat -s GAv4
,08-08 11:19:11.668  2883  3743 V KeepSync: Connecting to GoogleApiClient
,08-08 11:19:11.672   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-08 11:19:11.683  3684  3684 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-08 11:19:11.689  3684  3684 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-08 11:19:11.744  1533  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-08 11:19:11.744  1533  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-08 11:19:11.744  1533  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:11.745  1533  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:11.750  3684  3750 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-08 11:19:11.755  1988  3751 V BaseAuthAsyncOperation: access token request failed
,08-08 11:19:11.758  2883  3743 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-08 11:19:11.878  3684  3684 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-08 11:19:11.926  3684  3684 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-08 11:19:11.954  3684  3684 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5401-5404)
,08-08 11:19:11.954  3684  3684 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-08 11:19:11.970  3684  3684 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {51e3bbc}
,08-08 11:19:11.971  3684  3684 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 11:19:11.972  3684  3684 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-08 11:19:11.990  3684  3684 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-08 11:19:11.991  3684  3684 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-08 11:19:12.033  3684  3684 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-08 11:19:12.059  3684  3684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 11:19:12.059  3684  3684 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-08 11:19:12.059  3684  3684 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 11:19:12.059  3684  3684 I Adreno  : Build Date                       : 10/20/15
08-08 11:19:12.059  3684  3684 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 11:19:12.059  3684  3684 I Adreno  : Local Branch                     : M14
08-08 11:19:12.059  3684  3684 I Adreno  : Remote Branch                    : 
08-08 11:19:12.059  3684  3684 I Adreno  : Remote Branch                    : 
08-08 11:19:12.059  3684  3684 I Adreno  : Reconstruct Branch               : 
,08-08 11:19:12.221  3700  3785 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-08 11:19:12.279  3684  3684 I NSApplication: Starting up...
,08-08 11:19:12.287  3684  3786 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-08 11:19:12.318   873  1711 I ActivityManager: Start proc 3791:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-08 11:19:12.319   873  1711 I ActivityManager: Killing 2759:android.process.acore/u0a5 (adj 15): empty #17
,08-08 11:19:12.372   873  1866 D WifiService: setWifiEnabled: false pid=3350, uid=10000
,08-08 11:19:12.373   873  1866 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 11:19:12.381  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-08 11:19:12.383   873  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-08 11:19:12.383   873  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-08 11:19:12.383   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 11:19:12.383   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 11:19:12.395   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-08 11:19:12.395   873  3530 D DhcpClient: Clearing IP address
,08-08 11:19:12.398   372   871 D CommandListener: Setting iface cfg
,08-08 11:19:12.409  1533  3602 V NativeCrypto: Read error: ssl=0x9b573400: I/O error during system call, Connection timed out
08-08 11:19:12.411  1533  3602 V NativeCrypto: SSL shutdown failed: ssl=0x9b573400: I/O error during system call, Broken pipe
08-08 11:19:12.413   873  1711 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-08 11:19:12.413   873  3528 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-08 11:19:12.415   873  3528 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.110,2a00:1450:4001:815::200e
,08-08 11:19:12.420   873  3531 D DhcpClient: Receive thread stopped
08-08 11:19:12.423   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-08 11:19:12.423   873  1320 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-08 11:19:12.426   873  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-08 11:19:12.426   408   408 E Parcel  : Reading a NULL string not supported here.,
,08-08 11:19:12.426   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-08 11:19:12.428   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-08 11:19:12.432   873  1320 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-08 11:19:12.433  1533  1548 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-08 11:19:12.433  1533  1548 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-08 11:19:12.434  1533  1548 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:12.434  1533  1548 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 11:19:12.435   873  3528 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:815::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
08-08 11:19:12.440   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
08-08 11:19:12.444   873  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-08 11:19:12.444  1871  2069 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:12.445  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:12.448  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:12.451  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:19:12.453  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:12.470   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 11:19:12.470  3791  3791 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-08 11:19:12.492   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 11:19:12.493   873  1320 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-08 11:19:12.493   873  1320 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:19:12.498  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:12.498   873   891 D Tethering: MasterInitialState.processMessage what=3
08-08 11:19:12.499  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:12.502  1818  1818 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-08 11:19:12.544   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-08 11:19:12.545   873  1320 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 11:19:12.546  1533  3813 I VacuumService: Vacuum at: now=1470647952545 tag=VacuumService
,08-08 11:19:12.553  1533  2590 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-08 11:19:12.553  1533  2590 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-08 11:19:12.553  1533  2590 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 11:19:12.554  1533  2590 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:12.570  2883  3743 E KeepSync: IOException
08-08 11:19:12.570  2883  3743 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-08 11:19:12.570  2883  3743 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 11:19:12.570  2883  3743 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-08 11:19:12.570  2883  3743 E KeepSync: 	... 10 more
,08-08 11:19:12.570  2883  3743 W KeepSync: Sync result 2
,08-08 11:19:12.583  1533  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-08 11:19:12.583  1533  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-08 11:19:12.583  1533  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:12.583  1533  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:12.593  3700  3785 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-08 11:19:12.595  3700  3736 E BooksSync: Soft error
08-08 11:19:12.595  3700  3736 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 11:19:12.595  3700  3736 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-08 11:19:12.595  3700  3736 E BooksSync: Sync error
08-08 11:19:12.595  3700  3736 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 11:19:12.595  3700  3736 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-08 11:19:12.595  3700  3736 I BooksSync: Finished books sync
,08-08 11:19:12.651   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 24181, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-08 11:19:12.658   873   884 I ActivityManager: Killing 3234:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-08 11:19:12.706   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24180, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-08 11:19:12.707   873  1777 I ActivityManager: Killing 3250:com.android.musicfx/u0a18 (adj 15): empty #17
,08-08 11:19:12.783  1533  3814 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-08 11:19:12.785  1533  3814 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-08 11:19:12.823  1533  3814 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-08 11:19:12.985   873  1718 I ActivityManager: Killing 3066:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-08 11:19:13.125  2366  3824 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-08 11:19:13.178  1988  1988 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 11:19:13.186  1988  1988 D SystemUpdateService: onCreate
,08-08 11:19:13.195  1988  1988 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 11:19:13.205  1988  3827 I SystemUpdateService: active receiver: enabled
,08-08 11:19:13.211  1988  1988 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-08 11:19:13.213  1988  3575 I iu.UploadsManager: num queued entries: 0
,08-08 11:19:13.213  1988  3827 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-08 11:19:13.214  1988  3575 I iu.UploadsManager: num updated entries: 0
,08-08 11:19:13.215  1988  3827 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-08 11:19:13.215  1988  3827 I SystemUpdateService: now status is 0 (complete)
,08-08 11:19:13.215  1988  3827 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-08 11:19:13.215  1988  3827 I SystemUpdateService: file has been verified
08-08 11:19:13.215  1988  3827 I SystemUpdateService: OTA package size = 12249756
08-08 11:19:13.216  1988  3575 I iu.SyncManager: NEXT; no task
08-08 11:19:13.219  1988  3827 I SystemUpdateService: showing system update notification
08-08 11:19:13.226  1988  1988 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 11:19:13.227  1988  1988 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 11:19:13.229  3582  3582 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 11:19:13.231  3582  3582 D SprintDMHelper: simOperator: 
08-08 11:19:13.231  3582  3582 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 11:19:13.234  1988  1988 D SystemUpdateService: onDestroy
,08-08 11:19:15.385  3410  3447 D BluetoothAdapterState: Current state: ON, message: 23
,08-08 11:19:15.385  3410  3447 D BluetoothAdapterProperties: Setting state to 13
,08-08 11:19:15.386  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-08 11:19:15.387  3410  3447 D BluetoothAdapterProperties: onBluetoothDisable()
,08-08 11:19:15.397  3410  3447 I BluetoothAdapterState: Entering PendingCommandState
,08-08 11:19:15.397  3410  3410 D BluetoothMapService: onReceive
,08-08 11:19:15.397  3410  3410 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-08 11:19:15.398  3410  3410 D BluetoothMapService: STATE_TURNING_OFF
08-08 11:19:15.399  3410  3410 D BluetoothMapService: MAP Service closeService in
08-08 11:19:15.399  3410  3410 D BluetoothMapMasInstance0: MAP Service shutdown
,08-08 11:19:15.399  3410  3410 D ObexServerSockets0: shutdown(block = true)
,08-08 11:19:15.402  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:15.403  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:19:15.404  3410  3485 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-08 11:19:15.405  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:15.405  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:15.408  3410  3410 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-08 11:19:15.409  3410  3461 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!,
08-08 11:19:15.409  3410  3486 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-08 11:19:15.410  3410  3410 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 11:19:15.411  3410  3410 I BtOppRfcommListener: stopping Accept Thread
,08-08 11:19:15.411  3410  3522 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:19:15.413  3410  3452 D BluetoothAdapterProperties: Scan Mode:20
,08-08 11:19:15.413  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:15.413  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:19:15.413  3410  3447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-08 11:19:15.414  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:19:15.414  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:15.415  3410  3522 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-08 11:19:15.417  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:15.418  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:15.420  3465  3465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 11:19:15.425  3410  3410 D HeadsetService: Received stop request...Stopping profile...
,08-08 11:19:15.427   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:15.427   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:15.427   873   873 D BluetoothHeadset: Proxy object disconnected
,08-08 11:19:15.428  1724  1735 D BluetoothHeadset: Proxy object disconnected
,08-08 11:19:15.428  1373  1838 D BluetoothHeadset: Proxy object disconnected
,08-08 11:19:15.429  1373  1373 D HeadsetProfile: Bluetooth service disconnected
,08-08 11:19:15.430  3410  3410 D A2dpService: Received stop request...Stopping profile...
,08-08 11:19:15.429  3465  3480 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:15.430  3410  3477 D A2dpStateMachine: Exit Disconnected: -1
,08-08 11:19:15.432   873   873 D BluetoothA2dp: Proxy object disconnected
08-08 11:19:15.432  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-08 11:19:15.433  3410  3410 D HidService: Received stop request...Stopping profile...
08-08 11:19:15.433  3410  3410 D HidService: Stopping Bluetooth HidService
,08-08 11:19:15.434  1373  1373 D BluetoothInputDevice: Proxy object disconnected
,08-08 11:19:15.435  1373  1373 D HidProfile: Bluetooth service disconnected
,08-08 11:19:15.435  3410  3410 D HealthService: Received stop request...Stopping profile...
08-08 11:19:15.436  3410  3410 D PanService: Received stop request...Stopping profile...
,08-08 11:19:15.438  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-08 11:19:15.438  1373  1373 D PanProfile: Bluetooth service disconnected
08-08 11:19:15.439  3410  3410 D BluetoothMapService: Received stop request...Stopping profile...
08-08 11:19:15.439  3410  3410 D BluetoothMapService: stop()
,08-08 11:19:15.439  3410  3410 D BluetoothMapAppObserver: deinitObservers()
,08-08 11:19:15.439  3410  3410 D BluetoothMapAppObserver: removeReceiver()
,08-08 11:19:15.441  1373  1373 D BluetoothMap: Proxy object disconnected
,08-08 11:19:15.441  1373  1373 D MapProfile: Bluetooth service disconnected
,08-08 11:19:15.443  3410  3410 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:15.443  3410  3410 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:15.444  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:15.444  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:15.445  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:19:15.445  3465  3465 D DockEventReceiver: finishStartingService: stopping service
08-08 11:19:15.446  3410  3410 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-08 11:19:15.446  3410  3410 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-08 11:19:15.446  3410  3458 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 11:19:15.447  3410  3458 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:15.447  3410  3458 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:15.447  3410  3410 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:15.447  3410  3452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-08 11:19:15.447  3410  3410 V BluetoothAdapterState: isTurningOn()=false
,08-08 11:19:15.447  3410  3452 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-08 11:19:15.447  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:15.447  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:15.448  3410  3458 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:15.449  3410  3458 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:15.449  3410  3458 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-08 11:19:15.449  3410  3458 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:19:15.449  3410  3458 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:19:15.449  3410  3458 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:19:15.449  3410  3410 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:15.449  3410  3452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-08 11:19:15.449  3410  3410 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:15.449  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:15.449  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:15.451  3410  3410 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 11:19:15.452  3410  3410 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-08 11:19:15.452  3410  3452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 11:19:15.452  3410  3410 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:15.452  3410  3410 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:15.452  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:15.452  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:15.452  3410  3410 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-08 11:19:15.452  3410  3452 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-08 11:19:15.453  3410  3410 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-08 11:19:15.453  3410  3410 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:15.454  3410  3410 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:15.454  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:15.454  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:15.454  3410  3410 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 11:19:15.454  3410  3410 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-08 11:19:15.455  3410  3410 D BluetoothMapService: MAP Service closeService in
,08-08 11:19:15.455  3410  3410 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:15.455  3410  3410 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:15.455  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:15.455  3410  3410 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:15.456  3410  3447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-08 11:19:15.456  3410  3447 D BluetoothAdapterProperties: Setting state to 15
08-08 11:19:15.456  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-08 11:19:15.457  3410  3447 I BluetoothAdapterState: Entering BleOnState
08-08 11:19:15.457   873   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:15.457  3465  3480 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:19:15.457  3410  3410 D BluetoothMapService: cleanup()
08-08 11:19:15.457  3410  3410 D BluetoothMapService: MAP Service closeService in
,08-08 11:19:15.458  1373  1400 D BluetoothMap: onBluetoothStateChange: up=false
08-08 11:19:15.458   873   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:15.458   873   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:19:15.458  1373  1837 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:19:15.459  1373  1373 D BluetoothPbap: Proxy object disconnected
08-08 11:19:15.459  3465  3465 D HeadsetProfile: Bluetooth service disconnected
,08-08 11:19:15.459  1373  1387 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 11:19:15.459  3465  3465 D BluetoothInputDevice: Proxy object disconnected
08-08 11:19:15.459  3465  3465 D HidProfile: Bluetooth service disconnected
08-08 11:19:15.460  3465  3465 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 11:19:15.460  3465  3465 D PanProfile: Bluetooth service disconnected
,08-08 11:19:15.460  3465  3465 D BluetoothMap: Proxy object disconnected
08-08 11:19:15.460  3465  3465 D MapProfile: Bluetooth service disconnected
08-08 11:19:15.459  1373  1373 D PbapServerProfile: Bluetooth service disconnected
08-08 11:19:15.460  3465  3465 D BluetoothPbap: Proxy object disconnected
,08-08 11:19:15.460  3465  3465 D PbapServerProfile: Bluetooth service disconnected
08-08 11:19:15.462  3465  3480 D BluetoothMap: onBluetoothStateChange: up=false
08-08 11:19:15.465  3465  3476 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:15.465  1724  1890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 11:19:15.466  3465  3838 D BluetoothPan: onBluetoothStateChange on: false
08-08 11:19:15.467  3465  3480 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 11:19:15.467  1373  1400 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:15.467  1373  1838 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-08 11:19:15.468  1373  1837 D BluetoothPan: onBluetoothStateChange on: false
08-08 11:19:15.468  3465  3476 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 11:19:15.469   873   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:15.469  3410  3447 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-08 11:19:15.470  3410  3447 D BluetoothAdapterProperties: Setting state to 16
,08-08 11:19:15.470  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-08 11:19:15.471  3410  3447 D BluetoothAdapterProperties: onBleDisable
08-08 11:19:15.471  3410  3447 I BluetoothAdapterState: Entering PendingCommandState
08-08 11:19:15.471  3410  3448 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-08 11:19:15.472  3410  3458 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-08 11:19:15.472  3410  3458 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:15.473  3410  3452 D BluetoothAdapterProperties: Scan Mode:20
08-08 11:19:15.473  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:15.474  3465  3465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 11:19:15.474  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:15.476  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:15.478  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:15.478  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:19:15.494  3465  3465 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:19:15.677  3410  3452 I bt_hci  : shut_down
,08-08 11:19:15.687  3410  3456 D bt_hwcfg: hw_epilog_process
,08-08 11:19:15.687  3410  3456 I bt_vendor: low_power_mode_cb
,08-08 11:19:15.708  3410  3456 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-08 11:19:15.709  3410  3456 I bt_vendor: epilog_cb
,08-08 11:19:15.710  3410  3456 I bt_hci  : epilog_finished_callback
,08-08 11:19:15.715  3410  3452 I bt_hci_h4: hal_close
,08-08 11:19:15.716  3410  3452 I bt_userial_vendor: device fd = 51 close
,08-08 11:19:15.837  3410  3448 D bt_stack_manager: event_shut_down_stack finished.
08-08 11:19:15.838  3410  3447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-08 11:19:15.842  3410  3447 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-08 11:19:15.843  3410  3410 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 11:19:15.844  3410  3410 D BtGatt.GattService: Received stop request...Stopping profile...
,08-08 11:19:15.844  3410  3410 D BtGatt.GattService: stop()
08-08 11:19:15.844  3410  3410 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 11:19:15.848  3410  3410 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:15.848  3410  3410 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:15.848  3410  3410 V BluetoothAdapterState: isBleTurningOn()=false,
08-08 11:19:15.848  3410  3410 V BluetoothAdapterState: isBleTurningOff()=true
,08-08 11:19:15.849  3410  3447 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-08 11:19:15.850  3410  3447 D BluetoothAdapterProperties: Setting state to 10
,08-08 11:19:15.851  3410  3447 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-08 11:19:15.853  3410  3447 I BluetoothAdapterState: Entering OffState
,08-08 11:19:15.854   873   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-08 11:19:15.868  3410  3410 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-08 11:19:15.868  3410  3410 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-08 11:19:15.868  3410  3448 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-08 11:19:15.877  3410  3448 D bt_stack_manager: event_clean_up_stack finished.
,08-08 11:19:15.877  3410  3410 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-08 11:19:15.887  3410  3410 I art     : System.exit called, status: 0
,08-08 11:19:15.887  3410  3410 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-08 11:19:15.968   873  1866 I ActivityManager: Process com.android.bluetooth (pid 3410) has died
,08-08 11:19:16.493  3700  3733 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-08 11:19:16.630   873   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-08 11:19:16.644  1653  1653 I Keyboard.Facilitator: onFinishInput()
,08-08 11:19:16.660   873   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 11:19:16.660   873   894 I Adreno  : Build Date                       : 10/20/15
08-08 11:19:16.660   873   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 11:19:16.660   873   894 I Adreno  : Local Branch                     : M14
08-08 11:19:16.660   873   894 I Adreno  : Remote Branch                    : 
08-08 11:19:16.660   873   894 I Adreno  : Remote Branch                    : 
08-08 11:19:16.660   873   894 I Adreno  : Reconstruct Branch               : 
,08-08 11:19:16.711   280   889 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (322 us)
,08-08 11:19:17.331  3350  3350 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-08 11:19:17.331  3350  3350 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-08 11:19:17.367   873   894 V KeyguardServiceDelegate: onScreenTurnedOff()
08-08 11:19:17.372   873   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-08 11:19:17.375   873   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-08 11:19:17.376  3350  3350 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@eb478a0 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@72da413, 16908290=android.view.AbsSavedState$1@72da413}, android:focusedViewId=100}]}]
08-08 11:19:17.376  3350  3350 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-08 11:19:17.376  3350  3350 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-08 11:19:17.377  3350  3350 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-08 11:19:17.379   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-08 11:19:17.379   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-08 11:19:17.430   873   882 I art     : Background partial concurrent mark sweep GC freed 61282(3MB) AllocSpace objects, 44(1424KB) LOS objects, 33% free, 28MB/43MB, paused 839us total 121.758ms
,08-08 11:19:17.594   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-08 11:19:17.596   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-08 11:19:17.599   873  1343 D SurfaceControl: Excessive delay in setPowerMode(): 224ms
,08-08 11:19:17.602   873   894 I DreamManagerService: Entering dreamland.
,08-08 11:19:17.603   873   894 I PowerManagerService: Dozing...
,08-08 11:19:17.603   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-08 11:19:17.648   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-08 11:19:17.648   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-08 11:19:17.657  1712  3850 D NfcService: Discovery configuration equal, not updating.
,08-08 11:19:17.662   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 11:19:17.664   873  1316 E native  : do suspend false
,08-08 11:19:17.692   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 11:19:17.694   873  1316 E native  : do suspend true
,08-08 11:19:17.791   376  1326 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-08 11:19:17.791   376  1326 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-08 11:19:18.368   873  1320 D ConnectivityService: handlePromptUnvalidated 100
,08-08 11:19:18.425   873   891 I ActivityManager: Start proc 3854:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-08 11:19:18.553  3854  3854 D AdapterServiceConfig: Adding HeadsetService
,08-08 11:19:18.553  3854  3854 D AdapterServiceConfig: Adding A2dpService
08-08 11:19:18.553  3854  3854 D AdapterServiceConfig: Adding HidService
,08-08 11:19:18.554  3854  3854 D AdapterServiceConfig: Adding HealthService
08-08 11:19:18.554  3854  3854 D AdapterServiceConfig: Adding PanService
08-08 11:19:18.554  3854  3854 D AdapterServiceConfig: Adding GattService
08-08 11:19:18.554  3854  3854 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 11:19:18.571   873   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a4aa1a9:true
,08-08 11:19:18.572  3854  3854 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 11:19:18.577  3854  3854 I bt_bluedroid: init
,08-08 11:19:18.578  3854  3866 I BluetoothAdapterState: Entering OffState
,08-08 11:19:18.580  3854  3867 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 11:19:18.580  3854  3867 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 11:19:18.580  3854  3867 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-08 11:19:18.581  3854  3867 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-08 11:19:18.581  3854  3854 I bt_bluedroid: get_profile_interface socket
,08-08 11:19:18.585  3854  3854 I bt_bluedroid: get_profile_interface sdp
,08-08 11:19:18.589  3854  3865 I bt_bluedroid: config_hci_snoop_log
,08-08 11:19:18.591  3854  3870 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 11:19:18.593   873   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-08 11:19:18.596  3854  3870 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 11:19:18.603  3854  3866 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 11:19:18.603  3854  3866 D BluetoothAdapterProperties: Setting state to 14
,08-08 11:19:18.604  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 11:19:18.608  3854  3866 D BluetoothBondStateMachine: make
,08-08 11:19:18.612  3854  3871 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-08 11:19:18.621  3854  3866 I BluetoothAdapterState: Entering PendingCommandState
,08-08 11:19:18.624  3854  3854 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 11:19:18.634  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:18.636  3854  3854 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 11:19:18.637  3854  3854 D BtGatt.GattService: Received start request. Starting profile...
,08-08 11:19:18.638  3854  3854 D BtGatt.GattService: start()
08-08 11:19:18.638  3854  3854 I bt_bluedroid: get_profile_interface gatt
,08-08 11:19:18.641  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:18.641  3854  3854 D BtGatt.AdvertiseManager: advertise manager created
,08-08 11:19:18.651  3854  3854 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:18.651  3854  3854 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:18.651  3854  3854 V BluetoothAdapterState: isBleTurningOn()=true
08-08 11:19:18.651  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:18.651  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-08 11:19:18.654  3854  3866 I bt_bluedroid: enable
08-08 11:19:18.654  3854  3867 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-08 11:19:18.655  3854  3867 I bt_hci  : start_up
,08-08 11:19:18.663  3854  3867 I bt_vendor: alloc value 0xb3a26189
,08-08 11:19:18.663  3854  3867 I bt_vendor: init
08-08 11:19:18.663  3854  3867 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 11:19:18.663  3854  3867 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 11:19:18.772  3854  3867 D bt_hci  : start_up starting async portion
,08-08 11:19:18.772  3854  3874 I bt_hci  : event_finish_startup
08-08 11:19:18.773  3854  3874 I bt_hci_h4: hal_open
,08-08 11:19:18.773  3854  3874 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 11:19:18.780  3854  3874 I bt_userial_vendor: device fd = 51 open
,08-08 11:19:18.813  3854  3874 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 11:19:18.845  3854  3874 D bt_hwcfg: Chipset BCM4354A2
,08-08 11:19:18.845  3854  3874 D bt_hwcfg: Target name = [BCM4354A2]
08-08 11:19:18.846  3854  3874 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 11:19:19.498  3854  3874 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 11:19:19.499  3854  3874 D bt_hwcfg: Settlement delay -- 100 ms
,08-08 11:19:19.499  3854  3874 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 11:19:19.616  3854  3874 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 11:19:19.617  3854  3874 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 11:19:19.647  3854  3874 I bt_hwcfg: vendor lib fwcfg completed
,08-08 11:19:19.647  3854  3874 I bt_vendor: firmware callback
08-08 11:19:19.647  3854  3874 I bt_hci  : firmware_config_callback
,08-08 11:19:19.658  3854  3876 I bt_btu  : btu_task pending for preload complete event
,08-08 11:19:19.659  3854  3876 I bt_btu_task: Bluetooth chip preload is complete
08-08 11:19:19.659  3854  3876 I bt_btu  : btu_task received preload complete event
,08-08 11:19:19.668  3854  3876 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 11:19:19.669  3854  3876 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-08 11:19:19.669  3854  3876 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-08 11:19:19.670  3854  3876 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-08 11:19:19.670  3854  3876 I         : BTE_InitTraceLevels -- TRC_AVRC
08-08 11:19:19.670  3854  3876 I         : BTE_InitTraceLevels -- TRC_A2D
,08-08 11:19:19.670  3854  3876 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 11:19:19.671  3854  3876 I         : BTE_InitTraceLevels -- TRC_BTM
,08-08 11:19:19.671  3854  3876 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 11:19:19.671  3854  3876 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 11:19:19.671  3854  3876 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 11:19:19.672  3854  3876 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 11:19:19.672  3854  3876 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 11:19:19.672  3854  3876 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 11:19:19.672  3854  3876 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 11:19:19.804  3854  3876 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a3d9d
,08-08 11:19:19.805  3854  3876 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a3d9d 
,08-08 11:19:19.816  3854  3870 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 11:19:19.819  3854  3870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 11:19:19.820  3854  3870 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 11:19:19.823  3854  3870 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 11:19:19.827  3854  3870 D BluetoothAdapterProperties: Scan Mode:20
,08-08 11:19:19.828  3854  3870 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-08 11:19:19.828  3854  3870 D bt_hci  : do_postload posting postload work item
,08-08 11:19:19.830  3854  3874 I bt_hci  : event_postload
,08-08 11:19:19.830  3854  3874 I bt_vendor: sco_config_cb
,08-08 11:19:19.830  3854  3874 I bt_hci  : sco_config_callback postload finished.
08-08 11:19:19.833  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:19.836  3854  3874 I bt_vendor: low_power_mode_cb
,08-08 11:19:19.836  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:19.837  3854  3870 D bt_bte_conf: Device ID record 1 : primary
08-08 11:19:19.837  3854  3870 D bt_bte_conf:   vendorId            = 000f
08-08 11:19:19.837  3854  3870 D bt_bte_conf:   vendorIdSource      = 0001
,08-08 11:19:19.837  3854  3870 D bt_bte_conf:   product             = 1200
,08-08 11:19:19.837  3854  3870 D bt_bte_conf:   version             = 1436
08-08 11:19:19.838  3854  3870 D bt_bte_conf:   clientExecutableURL = 
08-08 11:19:19.838  3854  3870 D bt_bte_conf:   serviceDescription  = 
08-08 11:19:19.838  3854  3870 D bt_bte_conf:   documentationURL    = 
,08-08 11:19:19.838  3854  3870 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-08 11:19:19.839  3854  3867 D bt_stack_manager: event_start_up_stack finished
08-08 11:19:19.840  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-08 11:19:19.840  3854  3866 D BluetoothAdapterProperties: Setting state to 15
08-08 11:19:19.840  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-08 11:19:19.841  3854  3866 I BluetoothAdapterState: Entering BleOnState
,08-08 11:19:19.846  3854  3866 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-08 11:19:19.847  3854  3866 D BluetoothAdapterProperties: Setting state to 11
08-08 11:19:19.847  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 11:19:19.856  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:19.859  3854  3854 D HeadsetService: Received start request. Starting profile...
,08-08 11:19:19.861  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:19.863  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:19.868  3854  3854 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-08 11:19:19.869  3854  3854 D HeadsetStateMachine: make
,08-08 11:19:19.872  3854  3866 I BluetoothAdapterState: Entering PendingCommandState
,08-08 11:19:19.877  3854  3854 D HeadsetStateMachine: max_hf_connections = 1
,08-08 11:19:19.877  3854  3854 I bt_bluedroid: get_profile_interface handsfree
08-08 11:19:19.877  3854  3870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-08 11:19:19.877  3854  3870 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-08 11:19:19.882  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:19.882  3854  3854 D A2dpService: Received start request. Starting profile...
,08-08 11:19:19.883  3854  3854 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-08 11:19:19.884  3854  3854 I bt_bluedroid: get_profile_interface avrcp
,08-08 11:19:19.891  3854  3854 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 11:19:19.891  3854  3854 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 11:19:19.891  3854  3854 D A2dpStateMachine: make
,08-08 11:19:19.893  3854  3854 I bt_bluedroid: get_profile_interface a2dp
,08-08 11:19:19.894  3854  3870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 11:19:19.896  3854  3885 D A2dpStateMachine: Enter Disconnected: -2
,08-08 11:19:19.896  3854  3854 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 11:19:19.898  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:19.899  3854  3854 D HidService: Received start request. Starting profile...
,08-08 11:19:19.899  3854  3854 I bt_bluedroid: get_profile_interface hidhost
08-08 11:19:19.899  3854  3870 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39853e5
08-08 11:19:19.900  3854  3870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-08 11:19:19.900  3854  3854 D HidService: setHidService(): set to: null
,08-08 11:19:19.901  3854  3854 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-08 11:19:19.902  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:19.903  3854  3854 D HealthService: Received start request. Starting profile...
,08-08 11:19:19.905  3854  3854 I bt_bluedroid: get_profile_interface health
,08-08 11:19:19.908  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:19:19.909  3854  3854 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 11:19:19.909  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:19.910  3854  3854 D PanService: Received start request. Starting profile...
,08-08 11:19:19.910  3854  3854 D BluetoothPanServiceJni: initializeNative(L110): pan
08-08 11:19:19.910  3854  3854 I bt_bluedroid: get_profile_interface pan
08-08 11:19:19.911  3854  3870 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-08 11:19:19.914  3854  3854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c4ebd34
,08-08 11:19:19.915  3854  3854 D BluetoothMapService: Received start request. Starting profile...
08-08 11:19:19.915  3854  3854 D BluetoothMapService: start()
,08-08 11:19:19.918  3854  3854 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-08 11:19:19.919  3854  3854 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-08 11:19:19.919  3854  3854 D BluetoothMapAppObserver: createReceiver()
,08-08 11:19:19.921  3854  3854 D BluetoothMapAppObserver: initObservers()
08-08 11:19:19.921  3854  3854 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 11:19:19.930  3854  3854 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:19.930  3854  3854 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:19.930  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:19.930  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:19.933  3854  3854 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:19.933  3854  3854 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:19.933  3854  3883 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-08 11:19:19.933  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:19.933  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:19.934  3854  3854 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:19.934  3854  3854 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:19.934  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:19.934  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:19.934  3854  3854 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:19.934  3854  3854 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:19.934  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:19.935  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:19.936  3854  3854 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:19.936  3854  3854 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:19.936  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:19.936  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:19.936  3854  3854 V BluetoothAdapterState: isTurningOff()=false
08-08 11:19:19.936  3854  3854 V BluetoothAdapterState: isTurningOn()=true
08-08 11:19:19.936  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:19.937  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:19.938  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-08 11:19:19.938  3854  3866 D BluetoothAdapterProperties: ScanMode =  20
,08-08 11:19:19.938  3854  3866 D BluetoothAdapterProperties: State =  11
08-08 11:19:19.941  3854  3870 D BluetoothAdapterProperties: Scan Mode:21
08-08 11:19:19.942  3854  3866 D BluetoothAdapterProperties: Setting state to 12
08-08 11:19:19.942  3854  3870 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 11:19:19.942  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 11:19:19.943   873   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:19:19.943  3854  3866 I BluetoothAdapterState: Entering OnState
,08-08 11:19:19.944  3465  3476 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:19.947  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:19:19.948  1373  1838 D BluetoothMap: onBluetoothStateChange: up=true
,08-08 11:19:19.948  3854  3854 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 11:19:19.950  3854  3854 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-08 11:19:19.951  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:19.952   873   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:19:19.952   873   891 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 11:19:19.953  1373  1400 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 11:19:19.953  3854  3854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 11:19:19.955  1373  1387 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 11:19:19.957  3854  3854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 11:19:19.957  3465  3838 D BluetoothMap: onBluetoothStateChange: up=true
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:19.957  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 11:19:19.959  3854  3854 D ObexServerSockets: Succeed to create listening sockets 
08-08 11:19:19.959  3854  3854 D ObexServerSockets0: startAccept()
,08-08 11:19:19.959  3854  3854 D ObexServerSockets0: prepareForNewConnect()
,08-08 11:19:19.959  3465  3480 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:19:19.960  1724  1735 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 11:19:19.960  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 11:19:19.961  3854  3854 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-08 11:19:19.962  3854  3854 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-08 11:19:19.963  3854  3891 D ObexServerSockets0: Accepting socket connection...
08-08 11:19:19.963  3854  3892 D ObexServerSockets0: Accepting socket connection...
08-08 11:19:19.964  3465  3476 D BluetoothPan: onBluetoothStateChange on: true
08-08 11:19:19.965   873   873 D BluetoothA2dp: Proxy object connected
,08-08 11:19:19.965  3465  3465 D BluetoothA2dp: Proxy object connected
08-08 11:19:19.966  1373  1373 D BluetoothA2dp: Proxy object connected
08-08 11:19:19.969  3465  3465 D BluetoothMap: Proxy object connected
08-08 11:19:19.969  1373  1373 D BluetoothMap: Proxy object connected
08-08 11:19:19.969  1373  1373 D MapProfile: Bluetooth service connected
08-08 11:19:19.969  3465  3465 D MapProfile: Bluetooth service connected
,08-08 11:19:19.969  1373  1373 D BluetoothMap: getConnectedDevices()
08-08 11:19:19.969  3465  3465 D BluetoothMap: getConnectedDevices()
08-08 11:19:19.972  3465  3465 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 11:19:19.972  3465  3465 D PanProfile: Bluetooth service connected
08-08 11:19:19.973  3465  3480 D BluetoothPbap: onBluetoothStateChange: up=true
,08-08 11:19:19.976  1373  1400 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 11:19:19.977  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-08 11:19:19.981  1373  1838 D BluetoothPan: onBluetoothStateChange on: true
,08-08 11:19:19.982  1373  1373 D BluetoothInputDevice: Proxy object connected
,08-08 11:19:19.982  1373  1373 D HidProfile: Bluetooth service connected
,08-08 11:19:19.983  3465  3838 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-08 11:19:19.985   873   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 11:19:19.985  1373  1373 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 11:19:19.986  1373  1373 D PanProfile: Bluetooth service connected
,08-08 11:19:19.987   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-08 11:19:19.988  3854  3854 D BluetoothMapService: onReceive
08-08 11:19:19.988  3854  3854 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:19:19.988  3854  3854 D BluetoothMapService: STATE_ON
08-08 11:19:19.990  3465  3465 D BluetoothInputDevice: Proxy object connected
08-08 11:19:19.990  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:19.990  3465  3465 D HidProfile: Bluetooth service connected
08-08 11:19:19.992  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:20.000  3465  3465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 11:19:20.008  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:19:20.014  3465  3465 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:19:20.020  1373  1373 D BluetoothPbap: Proxy object connected
,08-08 11:19:20.021  1373  1373 D PbapServerProfile: Bluetooth service connected
08-08 11:19:20.021  3465  3465 D BluetoothPbap: Proxy object connected
08-08 11:19:20.021  3465  3465 D PbapServerProfile: Bluetooth service connected
,08-08 11:19:20.021  3854  3854 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 11:19:20.021  3854  3854 D ObexServerSockets0: prepareForNewConnect()
,08-08 11:19:20.036  3854  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 11:19:20.052   873   873 D BluetoothHeadset: Proxy object connected
,08-08 11:19:20.052   873   873 D BluetoothHeadset: Proxy object connected
08-08 11:19:20.052   873   873 D BluetoothHeadset: Proxy object connected
08-08 11:19:20.053  1724  1890 D BluetoothHeadset: Proxy object connected
,08-08 11:19:20.053  1373  1838 D BluetoothHeadset: Proxy object connected
,08-08 11:19:20.053  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-08 11:19:20.054  3465  3476 D BluetoothHeadset: Proxy object connected
,08-08 11:19:20.056  3465  3465 D HeadsetProfile: Bluetooth service connected
,08-08 11:19:20.060  3465  3838 D BluetoothHeadset: Proxy object connected
,08-08 11:19:20.061  1724  1738 D BluetoothHeadset: Proxy object connected
,08-08 11:19:20.061  3465  3465 D HeadsetProfile: Bluetooth service connected
,08-08 11:19:20.065  3854  3901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 11:19:20.068  3854  3901 I BtOppRfcommListener: Accept thread started.
,08-08 11:19:20.077  1373  1837 D BluetoothHeadset: Proxy object connected
08-08 11:19:20.077  1373  1373 D HeadsetProfile: Bluetooth service connected
,08-08 11:19:20.086   873   891 D BluetoothHeadset: Proxy object connected
,08-08 11:19:21.387  3350  3398 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 11:19:21.388  3350  3398 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 11:19:21.527  2597  2607 D Finsky  : [176] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-08 11:19:21.544  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:19:21.558  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:19:21.563  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:19:21.622  1533  2590 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 11:19:21.622  1533  2590 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 11:19:21.623  1533  2590 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:21.623  1533  2590 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:21.688  2597  2607 D Finsky  : [176] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-08 11:19:22.030  1871  2328 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-08 11:19:24.396  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 11:19:24.396  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed650 added. We now have 6 listener(s)
08-08 11:19:24.397  3350  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 11:19:24.404  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 11:19:24.405  3350  3398 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44dd049 added. We now have 7 listener(s)
,08-08 11:19:24.405  3350  3398 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 11:19:24.409  3350  3398 I System.out: IsBluetoothEnabled
,08-08 11:19:24.421  3854  3866 D BluetoothAdapterState: Current state: ON, message: 23
,08-08 11:19:24.421  3854  3866 D BluetoothAdapterProperties: Setting state to 13
08-08 11:19:24.421  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-08 11:19:24.425  3854  3866 D BluetoothAdapterProperties: onBluetoothDisable()
,08-08 11:19:24.431  3854  3866 I BluetoothAdapterState: Entering PendingCommandState
,08-08 11:19:24.436  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:24.436  3350  3398 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:24.437  3350  3398 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:24.437  3350  3398 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:24.437  3854  3854 D BluetoothMapService: onReceive
,08-08 11:19:24.438  3854  3854 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 11:19:24.438  3854  3854 D BluetoothMapService: STATE_TURNING_OFF
08-08 11:19:24.438  3854  3854 D BluetoothMapService: MAP Service closeService in
08-08 11:19:24.439  3854  3854 D BluetoothMapMasInstance0: MAP Service shutdown
,08-08 11:19:24.439  3854  3854 D ObexServerSockets0: shutdown(block = true)
08-08 11:19:24.440  3854  3891 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-08 11:19:24.441  3854  3854 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 11:19:24.441  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 11:19:24.441  3350  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 11:19:24.441  3854  3892 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-08 11:19:24.442  3854  3879 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-08 11:19:24.442  3854  3870 D BluetoothAdapterProperties: Scan Mode:20
,08-08 11:19:24.442  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-08 11:19:24.443  3350  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 11:19:24.443  3350  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 11:19:24.441  3854  3854 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 11:19:24.446  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:24.447  3854  3854 D HeadsetService: Received stop request...Stopping profile...
08-08 11:19:24.449   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:24.449  3854  3854 I BtOppRfcommListener: stopping Accept Thread
,08-08 11:19:24.449   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:24.449   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:24.450  3854  3901 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 11:19:24.450  1724  1916 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:24.450  3854  3901 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 11:19:24.450  1373  1400 D BluetoothHeadset: Proxy object disconnected
,08-08 11:19:24.451  3465  3838 D BluetoothHeadset: Proxy object disconnected
08-08 11:19:24.451  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,08-08 11:19:24.451  3854  3866 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-08 11:19:24.452  3854  3854 D A2dpService: Received stop request...Stopping profile...
08-08 11:19:24.452  3854  3885 D A2dpStateMachine: Exit Disconnected: -1
08-08 11:19:24.452  3465  3465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 11:19:24.456   873   873 D BluetoothA2dp: Proxy object disconnected
08-08 11:19:24.458  3854  3854 D HidService: Received stop request...Stopping profile...
08-08 11:19:24.458  3854  3854 D HidService: Stopping Bluetooth HidService
,08-08 11:19:24.456  3465  3465 D HeadsetProfile: Bluetooth service disconnected
08-08 11:19:24.459  1373  1373 D HeadsetProfile: Bluetooth service disconnected
08-08 11:19:24.459  1373  1373 D BluetoothA2dp: Proxy object disconnected
08-08 11:19:24.459  3854  3854 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:24.459  1373  1373 D BluetoothInputDevice: Proxy object disconnected
08-08 11:19:24.459  3854  3854 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:24.459  1373  1373 D HidProfile: Bluetooth service disconnected
08-08 11:19:24.459  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:24.459  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:24.460  3854  3854 D HealthService: Received stop request...Stopping profile...
08-08 11:19:24.462  3465  3465 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:19:24.463  3854  3854 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-08 11:19:24.463  3854  3854 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-08 11:19:24.463  3854  3870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-08 11:19:24.463  3854  3876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:24.463  3854  3876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:24.463  3854  3876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 11:19:24.464  3854  3870 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-08 11:19:24.464  3465  3465 D BluetoothA2dp: Proxy object disconnected
08-08 11:19:24.464  3465  3465 D BluetoothInputDevice: Proxy object disconnected
08-08 11:19:24.464  3465  3465 D HidProfile: Bluetooth service disconnected
,08-08 11:19:24.464  3854  3854 D PanService: Received stop request...Stopping profile...
08-08 11:19:24.466  1373  1373 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 11:19:24.466  1373  1373 D PanProfile: Bluetooth service disconnected
08-08 11:19:24.467  3854  3854 D BluetoothMapService: Received stop request...Stopping profile...
,08-08 11:19:24.467  3854  3854 D BluetoothMapService: stop()
08-08 11:19:24.468  3854  3854 D BluetoothMapAppObserver: deinitObservers()
08-08 11:19:24.468  3854  3854 D BluetoothMapAppObserver: removeReceiver()
08-08 11:19:24.470  1373  1373 D BluetoothMap: Proxy object disconnected
08-08 11:19:24.470  1373  1373 D MapProfile: Bluetooth service disconnected
,08-08 11:19:24.470  3465  3465 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 11:19:24.471  3465  3465 D PanProfile: Bluetooth service disconnected
,08-08 11:19:24.471  3465  3465 D BluetoothMap: Proxy object disconnected
08-08 11:19:24.471  3465  3465 D MapProfile: Bluetooth service disconnected
,08-08 11:19:24.473  3854  3854 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:24.473  3854  3854 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:24.473  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:24.473  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:24.474  3854  3870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-08 11:19:24.474  3854  3876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 11:19:24.474  3854  3876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 11:19:24.475  3854  3876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-08 11:19:24.475  3854  3876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:19:24.475  3854  3876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 11:19:24.475  3854  3876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 11:19:24.475  3854  3854 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:24.475  3854  3854 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:24.475  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:24.475  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:24.476  3854  3854 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 11:19:24.476  3854  3854 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 11:19:24.476  3854  3854 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:24.476  3854  3854 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:24.476  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
08-08 11:19:24.476  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 11:19:24.476  3854  3854 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-08 11:19:24.476  3854  3870 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 11:19:24.477  3854  3854 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 11:19:24.477  3854  3870 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-08 11:19:24.477  3854  3854 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:24.477  3854  3854 V BluetoothAdapterState: isTurningOn()=false
,08-08 11:19:24.477  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:24.477  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:24.477  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 11:19:24.477  3854  3854 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 11:19:24.477  3854  3854 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-08 11:19:24.478  3854  3854 D BluetoothMapService: MAP Service closeService in
08-08 11:19:24.478  3854  3854 V BluetoothAdapterState: isTurningOff()=true
08-08 11:19:24.478  3854  3854 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:24.478  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:24.478  3854  3854 V BluetoothAdapterState: isBleTurningOff()=false
08-08 11:19:24.479  3854  3854 D BluetoothMapService: cleanup()
,08-08 11:19:24.479  3854  3854 D BluetoothMapService: MAP Service closeService in
08-08 11:19:24.479  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-08 11:19:24.479  3854  3866 D BluetoothAdapterProperties: Setting state to 15
08-08 11:19:24.479  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-08 11:19:24.480  3854  3866 I BluetoothAdapterState: Entering BleOnState
08-08 11:19:24.480   873   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:24.480  3854  3866 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-08 11:19:24.480  3465  3480 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:19:24.481  1373  1387 D BluetoothMap: onBluetoothStateChange: up=false
,08-08 11:19:24.481  1373  1373 D BluetoothPbap: Proxy object disconnected
08-08 11:19:24.481  1373  1373 D PbapServerProfile: Bluetooth service disconnected
08-08 11:19:24.482   873   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:24.482   873   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:19:24.482  1373  1837 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 11:19:24.482  3465  3465 D BluetoothPbap: Proxy object disconnected
08-08 11:19:24.483  3465  3465 D PbapServerProfile: Bluetooth service disconnected
08-08 11:19:24.483  1373  1838 D BluetoothPbap: onBluetoothStateChange: up=false
,08-08 11:19:24.485  3465  3480 D BluetoothMap: onBluetoothStateChange: up=false
08-08 11:19:24.487  3465  3476 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:24.488  1724  1735 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:24.488  3465  3838 D BluetoothPan: onBluetoothStateChange on: false
08-08 11:19:24.489  3465  3480 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 11:19:24.489  1373  1400 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:24.490  1373  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 11:19:24.490  1373  1837 D BluetoothPan: onBluetoothStateChange on: false
08-08 11:19:24.490  3465  3476 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 11:19:24.491   873   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 11:19:24.491  3854  3866 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-08 11:19:24.491  3854  3866 D BluetoothAdapterProperties: Setting state to 16
,08-08 11:19:24.492  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-08 11:19:24.494  3854  3866 D BluetoothAdapterProperties: onBleDisable
08-08 11:19:24.495  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 11:19:24.495  3854  3866 I BluetoothAdapterState: Entering PendingCommandState
,08-08 11:19:24.495  3854  3867 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-08 11:19:24.495  3854  3870 D BluetoothAdapterProperties: Scan Mode:20
08-08 11:19:24.496  3465  3465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 11:19:24.498  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:24.499  3854  3876 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-08 11:19:24.499  3854  3876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 11:19:24.502  3465  3465 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:19:24.503  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:19:24.701  3854  3870 I bt_hci  : shut_down
,08-08 11:19:24.702  3854  3874 D bt_hwcfg: hw_epilog_process
,08-08 11:19:24.704  3854  3874 I bt_vendor: low_power_mode_cb
,08-08 11:19:24.728  3854  3874 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-08 11:19:24.728  3854  3874 I bt_vendor: epilog_cb
,08-08 11:19:24.728  3854  3874 I bt_hci  : epilog_finished_callback
,08-08 11:19:24.741  3854  3870 I bt_hci_h4: hal_close
,08-08 11:19:24.743  3854  3870 I bt_userial_vendor: device fd = 51 close
,08-08 11:19:24.873  3854  3867 D bt_stack_manager: event_shut_down_stack finished.
,08-08 11:19:24.873  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-08 11:19:24.879  3854  3866 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-08 11:19:24.879  3854  3854 D BtGatt.DebugUtils: handleDebugAction() action=null
08-08 11:19:24.881  3854  3854 D BtGatt.GattService: Received stop request...Stopping profile...
,08-08 11:19:24.881  3854  3854 D BtGatt.GattService: stop()
08-08 11:19:24.883  3854  3854 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 11:19:24.888  3854  3854 V BluetoothAdapterState: isTurningOff()=false
,08-08 11:19:24.889  3854  3854 V BluetoothAdapterState: isTurningOn()=false
08-08 11:19:24.889  3854  3854 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 11:19:24.889  3854  3854 V BluetoothAdapterState: isBleTurningOff()=true
08-08 11:19:24.890  3854  3866 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-08 11:19:24.891  3854  3866 D BluetoothAdapterProperties: Setting state to 10
,08-08 11:19:24.891  3854  3866 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-08 11:19:24.893  3854  3866 I BluetoothAdapterState: Entering OffState
,08-08 11:19:24.903  3350  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 11:19:24.910  3465  3465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 11:19:24.921  3465  3465 D DockEventReceiver: finishStartingService: stopping service
,08-08 11:19:24.924  1533  1533 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 11:19:25.378   873  1718 I ActivityManager: Killing 3195:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-08 11:19:36.027  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:19:36.043  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:19:36.049  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:19:36.132  1533  2591 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 11:19:36.133  1533  2591 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-08 11:19:36.134  1533  2591 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:19:36.134  1533  2591 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:19:36.205  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-08 11:19:36.205  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 11:19:36.206  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-08 11:20:02.556  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:20:02.565  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:20:02.569  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:20:02.607  1533  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 11:20:02.607  1533  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-08 11:20:02.607  1533  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:20:02.607  1533  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:20:02.667  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-08 11:20:02.667  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 11:20:02.667  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-08 11:20:12.548   873  1320 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-08 11:20:16.686  1653  1789 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-08 11:20:16.686  1653  1789 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-08 11:20:16.722  1533  1533 I ConfigService: onCreate
,08-08 11:20:21.796  1533  1533 I ConfigService: onDestroy
,08-08 11:20:23.105  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:20:23.124  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:20:23.131  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:20:23.226  1533  2590 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 11:20:23.226  1533  2590 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 11:20:23.227  1533  2590 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:20:23.227  1533  2590 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:20:23.300  2597  2597 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 11:20:23.302  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 11:20:23.303  2597  2597 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-08 11:21:10.931  1533  2007 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-08 11:22:17.657  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:22:17.670  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:22:17.675  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:22:17.729  1533  2591 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 11:22:17.730  1533  2591 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 11:22:17.730  1533  2591 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:22:17.730  1533  2591 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:22:17.759  1533  2591 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 11:22:17.759  1533  2591 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 11:22:17.759  1533  2591 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 11:22:17.759  1533  2591 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 11:22:17.759  1533  2591 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 11:22:17.759  1533  2591 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 11:22:17.759  1533  2591 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:22:17.766  2597  2626 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 11:22:17.766  2597  2626 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 11:22:17.766  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 11:22:17.766  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 11:22:17.766  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 11:22:17.766  2597  2626 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 11:22:17.766  2597  2626 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:27:17.924  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:27:17.946  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:27:17.949  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:27:18.029  1533  2242 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 11:27:18.029  1533  2242 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 11:27:18.030  1533  2242 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:27:18.030  1533  2242 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:27:18.073  1533  2242 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 11:27:18.073  1533  2242 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 11:27:18.073  1533  2242 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 11:27:18.073  1533  2242 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 11:27:18.073  1533  2242 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 11:27:18.073  1533  2242 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 11:27:18.073  1533  2242 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:27:18.084  2597  2626 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 11:27:18.084  2597  2626 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 11:27:18.084  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 11:27:18.084  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 11:27:18.084  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 11:27:18.084  2597  2626 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 11:27:18.084  2597  2626 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:32:18.225  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:32:18.242  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:32:18.249  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:32:18.350  1533  2590 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 11:32:18.350  1533  2590 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 11:32:18.351  1533  2590 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 11:32:18.351  1533  2590 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:32:18.404  1533  2590 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 11:32:18.404  1533  2590 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 11:32:18.404  1533  2590 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 11:32:18.404  1533  2590 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 11:32:18.404  1533  2590 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 11:32:18.404  1533  2590 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 11:32:18.404  1533  2590 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:32:18.419  2597  2626 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 11:32:18.419  2597  2626 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 11:32:18.419  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 11:32:18.419  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 11:32:18.419  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 11:32:18.419  2597  2626 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 11:32:18.419  2597  2626 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:37:05.604   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-08 11:37:18.558  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:37:18.580  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:37:18.586  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 11:37:18.669  1533  2590 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-08 11:37:18.670  1533  2590 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 11:37:18.670  1533  2590 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:37:18.670  1533  2590 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 11:37:18.713  1533  2590 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 11:37:18.713  1533  2590 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 11:37:18.713  1533  2590 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 11:37:18.713  1533  2590 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 11:37:18.713  1533  2590 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 11:37:18.713  1533  2590 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 11:37:18.713  1533  2590 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 11:37:18.728  2597  2626 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 11:37:18.728  2597  2626 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 11:37:18.728  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 11:37:18.728  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 11:37:18.728  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 11:37:18.728  2597  2626 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 11:37:18.728  2597  2626 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-08 11:42:18.458  3999  3999 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-08 11:42:18.463  3999  3999 D AndroidRuntime: CheckJNI is OFF
08-08 11:42:18.498  3999  3999 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-08 11:42:18.537  3999  3999 I Radio-JNI: register_android_hardware_Radio DONE
08-08 11:42:18.558  3999  3999 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-08 11:42:18.581   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-08 11:42:18.581   873   886 I ActivityManager: Killing 3350:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-08 11:42:18.677   873  1404 D GraphicsStats: Buffer count: 2
08-08 11:42:18.677   873  1741 I WindowState: WIN DEATH: Window{6e539f2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-08 11:42:18.678   873  1318 D WifiService: Client connection lost with reason: 4
08-08 11:42:18.711   873   897 W PackageSettings: Skipping PackageSetting{d727931 com.example.hello/10273} due to missing metadata
08-08 11:42:18.741   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-08 11:42:18.741   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-08 11:42:18.742   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-08 11:42:18.742   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-08 11:42:18.742   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:42:18.742   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:18.742   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 11:42:18.742   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-08 11:42:18.742   873   886 I ActivityManager:   Force finishing activity ActivityRecord{b814aeb u0 com.test.thalitest/.MainActivity t2}
08-08 11:42:18.743   873   897 I art     : Starting a blocking GC Explicit
08-08 11:42:18.755   873   884 W ActivityManager: Spurious death for ProcessRecord{8ca4a3b 0:com.test.thalitest/u0a0}, curProc for 3350: null
08-08 11:42:18.801  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:42:18.804   873   897 I art     : Explicit concurrent mark sweep GC freed 31492(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 1.005ms total 57.365ms
08-08 11:42:18.807  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:42:18.809  1533  1533 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 11:42:18.827   873   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-08 11:42:18.828  1533  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-08 11:42:18.828  1533  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 11:42:18.828  1533  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 11:42:18.828  1533  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 11:42:18.830  3999  3999 I art     : System.exit called, status: 0
08-08 11:42:18.830  3999  3999 I AndroidRuntime: VM exiting with result code 0.
08-08 11:42:18.887   873   897 I ActivityManager: Start proc 4012:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-08 11:42:18.887   873   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-08 11:42:18.923   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-08 11:42:18.938   873  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-08 11:42:18.941  1653  1653 I Keyboard.Facilitator: resetDictionaries() : en_US
08-08 11:42:18.941  1871  2034 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-08 11:42:18.948  3220  3220 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-08 11:42:18.965   873   884 I ActivityManager: Start proc 4029:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-08 11:42:18.968  1653  4027 I Keyboard.Facilitator.DecoderInitializer: run()
08-08 11:42:18.986  1533  1547 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 11:42:18.986  1533  1547 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 11:42:18.986  1533  1547 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 11:42:18.986  1533  1547 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 11:42:18.986  1533  1547 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 11:42:18.986  1533  1547 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 11:42:18.986  1533  1547 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-08 11:42:18.989  1724  1724 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-08 11:42:18.994  1653  4027 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-08 11:42:18.994  1653  4027 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-08 11:42:18.994  1653  4027 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-08 11:42:18.994  1653  4027 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-08 11:42:18.994  1653  4027 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-08 11:42:18.995  1653  4027 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-08 11:42:18.997  2597  2626 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 11:42:18.997  2597  2626 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 11:42:18.997  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 11:42:18.997  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 11:42:18.997  2597  2626 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 11:42:18.997  2597  2626 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 11:42:18.997  2597  2626 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-08 11:42:19.001  1653  4027 I Decoder : createOrResetDecoder
08-08 11:42:19.002   873   883 I ActivityManager: Killing 3272:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-08 11:42:19.017   873  1741 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3350 uid 10000
08-08 11:42:19.022   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-08 11:42:19.030  1653  1653 I Keyboard.Facilitator: onFinishInput()
08-08 11:42:19.044  4029  4029 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:19.078  4029  4043 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:19.078  4029  4043 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 11:42:19.096  4029  4043 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
--------- beginning of crash
08-08 11:42:19.101  4029  4043 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-08 11:42:19.101  4029  4043 E AndroidRuntime: Process: android.process.acore, PID: 4029
08-08 11:42:19.101  4029  4043 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:19.101  4029  4043 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 11:42:19.105   873  1314 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-08 11:42:19.107  4029  4029 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-08 11:42:19.111  1533  1533 I ConfigService: onCreate
08-08 11:42:19.112   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-08 11:42:19.112   873   885 E PackageManager: Failed to write settings, restoring backup
08-08 11:42:19.112   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-08 11:42:19.112   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-08 11:42:19.112   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-08 11:42:19.112   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-08 11:42:19.112   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-08 11:42:19.112   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:42:19.112   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:19.112   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 11:42:19.117  1742  1847 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-08 11:42:19.119   873  4045 E DropBoxManagerService: Can't write: system_app_crash
08-08 11:42:19.119   873  4045 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 11:42:19.119   873  4045 E DropBoxManagerService: 	... 5 more
08-08 11:42:19.125   873   886 I ActivityManager: Start proc 4047:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-08 11:42:19.127   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-08 11:42:19.127   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-08 11:42:19.127   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 11:42:19.127   873   886 E DropBoxManagerService: 	... 13 more
08-08 11:42:19.127   873  1718 I ActivityManager: Killing 1818:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-08 11:42:19.168  1533  4046 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-08 11:42:19.168  1533  4046 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-08 11:42:19.171  1533  4046 W SQLiteOpenHelper: Opened config.db in read-only mode
08-08 11:42:19.190   873  1318 D WifiService: Client connection lost with reason: 4
08-08 11:42:19.196  4029  4043 I Process : Sending signal. PID: 4029 SIG: 9
08-08 11:42:19.205  1653  4027 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-08 11:42:19.209   873  1381 I ActivityManager: Start proc 4059:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-08 11:42:19.210  1742  1847 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-08 11:42:19.210  1742  1847 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1742
08-08 11:42:19.210  1742  1847 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:19.210  1742  1847 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 11:42:19.215   873  1866 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-08 11:42:19.223   873  4069 E DropBoxManagerService: Can't write: system_app_crash
08-08 11:42:19.223   873  4069 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 11:42:19.223   873  4069 E DropBoxManagerService: 	... 5 more
08-08 11:42:19.225  1742  1847 I Process : Sending signal. PID: 1742 SIG: 9
08-08 11:42:19.256  4047  4047 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-08 11:42:19.300  1533  1533 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-08 11:42:19.301   278   278 E lowmemorykiller: Error writing /proc/1742/oom_score_adj; errno=22
08-08 11:42:19.302   278   278 E lowmemorykiller: Error writing /proc/1742/oom_score_adj; errno=22
08-08 11:42:19.303  1533  1533 D AndroidRuntime: Shutting down VM
08-08 11:42:19.303  1533  1533 E AndroidRuntime: FATAL EXCEPTION: main
08-08 11:42:19.303  1533  1533 E AndroidRuntime: Process: com.google.process.gapps, PID: 1533
08-08 11:42:19.303  1533  1533 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-08 11:42:19.303  1533  1533 E AndroidRuntime: 	... 8 more
08-08 11:42:19.307   873  4078 E DropBoxManagerService: Can't write: system_app_crash
08-08 11:42:19.307   873  4078 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 11:42:19.307   873  4078 E DropBoxManagerService: 	... 5 more
08-08 11:42:19.308  1533  1533 I Process : Sending signal. PID: 1533 SIG: 9
08-08 11:42:19.318  1653  4027 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-08 11:42:19.320  1653  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-08 11:42:19.320  1653  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-08 11:42:19.322  1653  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-08 11:42:19.323  1653  4027 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history

```
