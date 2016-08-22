#### Test 821470465fdde63_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-22 10:49:58.647  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:49:58.658  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-22 10:49:58.659  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-22 10:49:58.700  1495  2174 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-22 10:49:58.700  1495  2174 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-22 10:49:58.700  1495  2174 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:49:58.701  1495  2174 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-22 10:49:58.722  3654  3654 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-22 10:49:58.722  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-22 10:49:58.723  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-22 10:49:59.286  3962  3962 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-22 10:49:59.290  3962  3962 D AndroidRuntime: CheckJNI is OFF
08-22 10:49:59.326  3962  3962 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-22 10:49:59.369  3962  3962 I Radio-JNI: register_android_hardware_Radio DONE
08-22 10:49:59.389  3962  3962 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-22 10:49:59.393   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 10:49:59.435  2014  2384 W SearchService: Abort, client detached.
08-22 10:49:59.440  2014  2014 I HotwordDetector: Closing mic
08-22 10:49:59.441  2014  2277 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5bdf0b3
08-22 10:49:59.442  2014  2323 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-22 10:49:59.442  3962  3962 D AndroidRuntime: Shutting down VM
08-22 10:49:59.465   873  1475 I ActivityManager: Start proc 3971:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-22 10:49:59.489   376  2326 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-22 10:49:59.491   376  2326 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-22 10:49:59.499   376  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-22 10:49:59.501  2014  2287 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-22 10:49:59.501  2014  2311 I MicroRecognitionRnrImpl: Detection finished
08-22 10:49:59.542  3971  3971 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-22 10:49:59.561  3971  3971 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-22 10:49:59.568  3971  3971 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 596-599)
08-22 10:49:59.568  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 10:49:59.583  3971  3971 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {622400d}
08-22 10:49:59.583  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 10:49:59.583  3971  3971 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 10:49:59.591  3971  3971 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-22 10:49:59.592  3971  3971 E SysUtils: ApplicationContext is null in ApplicationStatus
08-22 10:49:59.613  3971  3971 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-22 10:49:59.624  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 10:49:59.624  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-22 10:49:59.624  3971  3971 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 10:49:59.624  3971  3971 I Adreno  : Build Date                       : 10/20/15
08-22 10:49:59.624  3971  3971 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 10:49:59.624  3971  3971 I Adreno  : Local Branch                     : M14
08-22 10:49:59.624  3971  3971 I Adreno  : Remote Branch                    : 
08-22 10:49:59.624  3971  3971 I Adreno  : Remote Branch                    : 
08-22 10:49:59.624  3971  3971 I Adreno  : Reconstruct Branch               : 
,08-22 10:49:59.687   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4f42258:true
,08-22 10:49:59.719  3971  3971 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 10:49:59.731  3971  3971 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-22 10:49:59.782  3971  4009 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-22 10:49:59.788  3971  3996 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-22 10:49:59.809  3971  4009 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 10:49:59.824  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-22 10:49:59.861   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +413ms
,08-22 10:49:59.955  3971  3971 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3971
,08-22 10:50:00.056  3971  3971 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 10:50:00.236  3971  4011 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1680869072
,08-22 10:50:00.247  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 10:50:00.247  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 10:50:00.247  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 10:50:00.247  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 10:50:00.247  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 10:50:00.247  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9072e8 added. We now have 1 listener(s)
08-22 10:50:00.250  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-22 10:50:00.251   873  1930 I ActivityManager: Killing 3385:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-22 10:50:00.251  3971  4011 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 10:50:00.252  3971  4011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:00.252  3971  4011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-22 10:50:00.256  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dcfc5e7 added. We now have 1 listener(s)
08-22 10:50:00.256  3971  4011 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:00.270   873  1302 D WifiService: New client listening to asynchronous messages
,08-22 10:50:00.272  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:00.272  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-22 10:50:00.272  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-22 10:50:00.272  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 10:50:00.272  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 10:50:00.299   873  1930 I ActivityManager: Killing 3122:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-22 10:50:00.347  3971  4011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:00.347  3971  4011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-22 10:50:00.356  3971  4011 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:00.357  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:00.357  3971  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-22 10:50:00.357  3971  4011 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:00.358  3971  4011 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 10:50:00.490  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:00.492  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:00.495  3971  3971 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 10:50:01.186  3971  4019 W jxcore-log: Initializing JXcore engine
08-22 10:50:01.186  3971  4019 W jxcore-log: JXcore engine is ready
,08-22 10:50:01.226  4019  4019 W Thread-365: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-22 10:50:01.226  4019  4019 W Thread-365: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9824]" dev="sockfs" ino=9824 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-22 10:50:01.226  4019  4019 W Thread-365: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-22 10:50:01.229  4019  4019 W Thread-365: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27216]" dev="sockfs" ino=27216 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-22 10:50:01.244  3971  4019 W jxcore-log: Starting JXcore engine
,08-22 10:50:01.323  3971  4019 W jxcore-log: Platform android
08-22 10:50:01.323  3971  4019 W jxcore-log: 
,08-22 10:50:01.324  3971  4019 W jxcore-log: Process ARCH arm
08-22 10:50:01.324  3971  4019 W jxcore-log: 
,08-22 10:50:01.563  3971  4019 I jxcore-log: JXcore Cordova bridge is ready!
08-22 10:50:01.563  3971  4019 I jxcore-log: 
,08-22 10:50:01.567  3971  4019 W jxcore-log: JXcore engine is started
,08-22 10:50:01.582  3971  4011 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 10:50:01.585  3971  3971 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 10:50:02.031   873  1301 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-22 10:50:11.533  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 10:50:11.533  3971  4019 I jxcore-log: 
,08-22 10:50:11.535  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 10:50:11.535  3971  4019 I jxcore-log: 
,08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:11.546  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:11.551  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:11.553  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 10:50:11.553  3971  4019 I jxcore-log: 
,08-22 10:50:11.554  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 10:50:11.554  3971  4019 I jxcore-log: 
,08-22 10:50:12.039  3971  4019 D ExecuteNativeTests: Running unit tests
,08-22 10:50:12.096  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:12.096  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 added. We now have 2 listener(s)
,08-22 10:50:12.097  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 10:50:12.098  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:12.098  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:12.098  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:12.098  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 added. We now have 2 listener(s)
08-22 10:50:12.098  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:12.098  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:12.100  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:12.115  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:12.117  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.117  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:12.124  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-22 10:50:12.124  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:12.125  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-22 10:50:12.125  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 10:50:12.127  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.130  3971  4019 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-22 10:50:12.132  3971  4019 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 10:50:12.132  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-22 10:50:12.133  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 10:50:12.134  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 10:50:12.135  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:12.138  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.139  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.140  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.140  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.140  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:12.140  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:12.140  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 removed from the list
,08-22 10:50:12.140  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.140  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 removed from the list
08-22 10:50:12.140  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.140  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.141  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.141  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.142  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.142  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:12.142  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.143  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.144  3971  4019 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-22 10:50:12.144  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.145  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.145  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-22 10:50:12.145  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.145  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:12.145  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.145  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
,08-22 10:50:12.145  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.145  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.145  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:12.145  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:12.145  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.145  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.145  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.146  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.146  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.146  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.146  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 10:50:12.151  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 10:50:12.152  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 10:50:12.152  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.152  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.152  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.153  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.153  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.153  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.153  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.153  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.153  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.153  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.153  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.153  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.153  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.153  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.154  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.154  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.154  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.154  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.155  3971  4019 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 10:50:12.157  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:12.160  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:50:12.162  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.162  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:12.163  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:12.163  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:12.164  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.164  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:12.164  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:12.164  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:12.165  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.168  3971  4019 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 10:50:12.168  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 10:50:12.172  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 10:50:12.173  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 10:50:12.173  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 10:50:12.175  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-22 10:50:12.176  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-22 10:50:12.177  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 10:50:12.177  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:12.177  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 10:50:12.178  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:12.181  2664  2675 D BtGatt.GattService: registerClient() - UUID=67c3608d-c1fe-4399-85d7-6e61619cc132
08-22 10:50:12.181  2664  2687 D BtGatt.GattService: onClientRegistered() - UUID=67c3608d-c1fe-4399-85d7-6e61619cc132, clientIf=5
08-22 10:50:12.182  3971  3982 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 10:50:12.183  2664  2806 D BtGatt.GattService: start scan with filters
08-22 10:50:12.185  2664  2703 D BtGatt.ScanManager: handling starting scan
08-22 10:50:12.186  2664  2703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
08-22 10:50:12.187  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:12.187  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:12.187  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:12.188  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 10:50:12.189  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:12.190  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:12.192  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 10:50:12.193  2664  2687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 10:50:12.193  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.194  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 10:50:12.194  2664  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 10:50:12.196  3971  4019 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 10:50:12.198  2664  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 10:50:12.198  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.199  2664  2703 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:12.199  2664  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 10:50:12.199  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.199  3971  4019 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 10:50:12.199  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.199  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 10:50:12.199  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.199  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:12.200  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:12.200  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:12.200  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:12.200  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:12.200  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:12.200  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 10:50:12.201  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:12.201  2664  2676 D BtGatt.GattService: stopScan() - queue size =1
08-22 10:50:12.202  2664  2675 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 10:50:12.203  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:12.203  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:12.203  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:12.203  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:12.203  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 10:50:12.204  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.204  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 10:50:12.205  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:12.205  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 10:50:12.206  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:12.206  2664  2687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 10:50:12.206  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.207  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.207  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.207  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.207  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.207  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.207  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:12.207  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.208  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.208  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.208  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.208  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.208  3971  4019 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 10:50:12.210  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:12.210  2664  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 10:50:12.211  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:12.213  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:50:12.214  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.215  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:12.216  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:12.216  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:12.216  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:12.216  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:12.216  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:12.216  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.218  2664  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 10:50:12.218  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.218  2664  2703 D BtGatt.ScanManager: stopping BLe Batch
08-22 10:50:12.218  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.222  3971  4019 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 10:50:12.222  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 10:50:12.224  2664  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 10:50:12.224  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.224  2664  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 10:50:12.227  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 10:50:12.228  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 10:50:12.228  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 10:50:12.230  2664  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 10:50:12.230  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.231  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 10:50:12.231  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:12.231  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 10:50:12.232  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:12.235  2664  2806 D BtGatt.GattService: registerClient() - UUID=b1fb9729-4723-43da-a8d8-08d783db5b40
08-22 10:50:12.235  2664  2687 D BtGatt.GattService: onClientRegistered() - UUID=b1fb9729-4723-43da-a8d8-08d783db5b40, clientIf=5
08-22 10:50:12.236  3971  3983 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 10:50:12.236  2664  2676 D BtGatt.GattService: start scan with filters
,08-22 10:50:12.239  2664  2703 D BtGatt.ScanManager: handling starting scan
08-22 10:50:12.239  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:12.239  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:12.239  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:12.241  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 10:50:12.243  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:12.243  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:12.243  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 10:50:12.244  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 10:50:12.245  2664  2687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 10:50:12.245  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.245  2664  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 10:50:12.246  3971  4019 I io.jxcore.node.ConnectionHelper: start: OK
08-22 10:50:12.248  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.248  3971  4019 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 10:50:12.249  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.249  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 10:50:12.249  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.249  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:12.249  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:12.249  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:12.249  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:12.249  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:12.249  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:12.249  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 10:50:12.250  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:12.250  2664  2675 D BtGatt.GattService: stopScan() - queue size =1
08-22 10:50:12.251  2664  2676 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 10:50:12.251  2664  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 10:50:12.251  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.251  2664  2703 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:12.251  2664  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 10:50:12.251  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:12.251  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:12.251  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:12.252  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:12.252  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 10:50:12.253  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.253  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 10:50:12.253  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:12.253  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 10:50:12.254  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:12.254  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.254  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.254  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.255  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.255  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.255  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:12.255  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.255  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.255  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.255  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.255  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.255  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.255  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.256  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.256  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.256  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.256  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.256  3971  4019 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 10:50:12.258  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:12.260  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:50:12.262  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.262  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:12.262  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:12.262  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:12.262  2664  2687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 10:50:12.262  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.264  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.262  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:12.264  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:12.264  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:12.266  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.268  2664  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 10:50:12.268  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.269  3971  4019 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 10:50:12.269  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 10:50:12.272  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 10:50:12.272  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-22 10:50:12.272  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 10:50:12.275  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 10:50:12.275  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:12.276  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:12.276  2664  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 10:50:12.276  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.276  2664  2703 D BtGatt.ScanManager: stopping BLe Batch
08-22 10:50:12.276  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:12.279  2664  2806 D BtGatt.GattService: registerClient() - UUID=9461105b-97bf-4d0d-8fbd-b7098cc266b0
08-22 10:50:12.279  2664  2687 D BtGatt.GattService: onClientRegistered() - UUID=9461105b-97bf-4d0d-8fbd-b7098cc266b0, clientIf=5
08-22 10:50:12.280  3971  3982 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 10:50:12.280  2664  2675 D BtGatt.GattService: start scan with filters
08-22 10:50:12.283  2664  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 10:50:12.284  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.284  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:12.284  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:12.284  2664  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 10:50:12.284  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:12.284  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 10:50:12.287  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:12.287  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 10:50:12.287  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:12.289  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 10:50:12.291  3971  4019 I io.jxcore.node.ConnectionHelper: start: OK
08-22 10:50:12.291  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.291  3971  4019 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 10:50:12.291  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.291  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 10:50:12.291  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.291  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 10:50:12.291  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:12.292  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 10:50:12.292  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:12.292  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:12.292  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:12.292  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 10:50:12.292  2664  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 10:50:12.292  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.293  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:12.293  2664  2676 D BtGatt.GattService: stopScan() - queue size =0
08-22 10:50:12.293  2664  2703 D BtGatt.ScanManager: handling starting scan
08-22 10:50:12.294  2664  2806 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 10:50:12.294  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:12.294  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:12.294  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:12.294  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:12.294  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-22 10:50:12.296  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.296  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 10:50:12.296  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:12.296  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 10:50:12.296  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:12.297  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.297  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.297  3971  4019 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 10:50:12.297  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.297  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.297  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.297  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.297  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.297  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.297  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:12.297  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.297  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.297  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.297  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.297  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.298  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.298  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.298  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.298  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.299  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.299  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.299  3971  4019 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-22 10:50:12.299  2664  2687 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 10:50:12.299  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.299  2664  2703 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 10:50:12.300  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.300  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.300  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.300  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.300  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.300  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.300  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.300  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.300  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.300  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.300  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.300  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.300  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.300  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.301  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.301  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.301  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.301  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.302  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 10:50:12.302  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.302  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.302  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.302  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.302  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.302  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.302  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.302  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.302  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.302  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.302  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.302  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.302  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.303  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.303  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.303  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.303  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.303  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.304  3971  4019 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-22 10:50:12.304  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.304  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.304  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.304  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.304  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.304  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.304  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.304  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.304  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.304  2664  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 10:50:12.304  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.305  2664  2703 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:12.305  2664  2703 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 10:50:12.304  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.305  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.305  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.305  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.305  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.306  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.306  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.306  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.306  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.306  3971  4019 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 10:50:12.306  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.306  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.306  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.306  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.306  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.306  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.307  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.307  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.307  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.308  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.308  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.308  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.309  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.309  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.309  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.309  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.309  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.309  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.310  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 10:50:12.310  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 10:50:12.310  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 10:50:12.310  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 10:50:12.310  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 10:50:12.310  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 10:50:12.310  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.310  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.310  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.310  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.311  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.311  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.311  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.311  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.311  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.311  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.311  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.311  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.311  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.311  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.311  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.312  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.312  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.312  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.312  3971  4019 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:12.312  3971  4019 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 10:50:12.312  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 10:50:12.315  3971  4019 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-22 10:50:12.315  3971  4019 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 10:50:12.315  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 10:50:12.316  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 10:50:12.317  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 10:50:12.317  3971  4019 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 10:50:12.317  2664  2687 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 10:50:12.317  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.317  3971  4019 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 10:50:12.317  3971  4019 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 10:50:12.317  3971  4019 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:12.318  3971  4019 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 10:50:12.318  3971  4019 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-22 10:50:12.318  3971  4019 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 10:50:12.318  3971  4019 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 10:50:12.318  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-22 10:50:12.321  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-22 10:50:12.321  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 10:50:12.321  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-22 10:50:12.322  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 10:50:12.322  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 10:50:12.322  3971  4019 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 10:50:12.322  3971  4019 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-22 10:50:12.322  3971  4019 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 10:50:12.323  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.323  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.323  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.323  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.323  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.323  2664  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 10:50:12.323  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.323  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.323  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-22 10:50:12.325  3971  4030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 429)
,08-22 10:50:12.326  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.326  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.326  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.326  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.326  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.327  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.327  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.327  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.328  3971  4031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 429
08-22 10:50:12.330  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.330  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:12.330  2664  2687 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 10:50:12.330  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.330  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.330  3971  4030 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 10:50:12.330  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.330  2664  2703 D BtGatt.ScanManager: stopping BLe Batch
08-22 10:50:12.331  3971  4019 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-22 10:50:12.331  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.331  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.332  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.332  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.332  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:12.332  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.332  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.332  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.332  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.332  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.332  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.332  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.332  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.332  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.333  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.333  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.333  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:12.333  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.334  3971  4019 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 10:50:12.334  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.334  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.334  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.335  2664  2687 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 10:50:12.335  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:12.335  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.335  2664  2703 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 10:50:12.335  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.335  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.335  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.335  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.335  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.335  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.335  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.335  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.335  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 10:50:12.335  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.336  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.336  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.336  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.337  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.337  3971  4019 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 10:50:12.337  3971  4019 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 10:50:12.337  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left,
08-22 10:50:12.337  3971  4019 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 10:50:12.337  3971  4019 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 10:50:12.338  3971  4019 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 10:50:12.338  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 10:50:12.338  3971  4019 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 10:50:12.338  3971  4019 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,08-22 10:50:12.338  3971  4019 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 10:50:12.338  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 10:50:12.338  3971  4019 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 10:50:12.338  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.338  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.338  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.338  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:12.338  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.338  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.339  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.339  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.339  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.339  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.339  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.339  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.339  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 10:50:12.339  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.340  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.340  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.340  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.341  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.341  2664  2687 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-22 10:50:12.342  2664  2687 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:12.342  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.342  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.342  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.342  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.342  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.342  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.342  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.342  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.342  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.343  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.343  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.343  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.343  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 10:50:12.343  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.343  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.343  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.343  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:12.343  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.343  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.343  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:12.343  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.343  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
,08-22 10:50:12.343  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.344  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
,08-22 10:50:12.344  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.344  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.344  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.344  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:12.344  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.345  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.345  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.345  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.345  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.346  3971  4019 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-22 10:50:12.347  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:12.347  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-22 10:50:12.348  3971  4019 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 10:50:12.348  3971  4019 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-22 10:50:12.348  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-22 10:50:12.348  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:12.348  3971  3971 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 10:50:12.349  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:12.349  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 10:50:12.349  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-22 10:50:12.349  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 10:50:12.349  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.349  3971  4019 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 10:50:12.349  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.349  3971  4032 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 10:50:12.349  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.349  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 10:50:12.349  3971  3971 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 10:50:12.349  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:12.349  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:12.349  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.349  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.351  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.351  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.351  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
,08-22 10:50:12.351  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:12.351  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.351  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:12.351  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.351  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.351  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.351  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.351  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.351  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
,08-22 10:50:12.351  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.351  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.351  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.351  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.351  3971  4032 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-22 10:50:12.351  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.351  3971  4032 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 10:50:12.351  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.352  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.352  3971  4032 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-22 10:50:12.352  3971  3971 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-22 10:50:12.353  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:12.353  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.353  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.353  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.354  3971  4019 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-22 10:50:12.354  3971  4019 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 10:50:12.354  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 10:50:12.355  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 10:50:12.355  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.355  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.355  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.356  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.356  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.356  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.356  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.356  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.356  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.356  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.356  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.356  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.356  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.356  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.357  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 10:50:12.357  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.357  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.357  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.360  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.360  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.360  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.360  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.360  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.360  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.360  3971  4019 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.360  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.360  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.360  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.360  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.360  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.360  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.360  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.361  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.361  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.361  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.361  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.362  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:12.362  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:12.362  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:12.362  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:12.362  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.362  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.362  3971  4019 E org.thaliproject.p2p.btconnectorlib.Conn,ectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cfe191 not in the list
08-22 10:50:12.362  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:12.363  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.363  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:12.363  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.363  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:12.363  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:12.363  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:12.364  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:12.364  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:12.364  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:12.364  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d6368f6 not in the list
08-22 10:50:12.364  3971  4019 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 10:50:12.364  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 10:50:12.365  3971  4019 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 10:50:12.365  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 10:50:12.365  3971  4019 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-22 10:50:12.365  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 10:50:12.366  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 10:50:12.366  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-22 10:50:12.367  3971  4019 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-22 10:50:12.367  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 10:50:12.367  3971  4019 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 10:50:12.367  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 10:50:12.367  3971  4019 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 10:50:12.367  3971  4019 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-22 10:50:12.368  3971  4019 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-22 10:50:12.368  3971  4019 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-22 10:50:12.368  3971  4019 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 10:50:12.368  3971  4019 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 10:50:12.368  3971  4019 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-22 10:50:12.368  3971  4019 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-22 10:50:12.369  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:12.369  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5386e8 added. We now have 2 listener(s)
08-22 10:50:12.369  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:12.371  3971  4019 D BluetoothAdapter: enable(): BT is already enabled..!
08-22 10:50:12.371   873  1968 D WifiService: setWifiEnabled: true pid=3971, uid=10000
,08-22 10:50:12.371   873  1968 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 10:50:12.372  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:12.372  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@21b5101 added. We now have 3 listener(s)
08-22 10:50:12.372  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:12.376  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:12.376  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15fba6 added. We now have 4 listener(s)
08-22 10:50:12.376  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:12.377  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:12.377  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@46ce9e7 added. We now have 5 listener(s)
08-22 10:50:12.378  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:12.379   873  1475 D WifiService: setWifiEnabled: false pid=3971, uid=10000
08-22 10:50:12.379   873  1475 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-22 10:50:12.385  2664  2683 D BluetoothAdapterState: Current state: ON, message: 23
,08-22 10:50:12.385  2664  2683 D BluetoothAdapterProperties: Setting state to 13
08-22 10:50:12.385  2664  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 10:50:12.385  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:12.385  2664  2683 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 10:50:12.386  2664  2683 I BluetoothAdapterState: Entering PendingCommandState
08-22 10:50:12.388  2664  2687 D BluetoothAdapterProperties: Scan Mode:20
08-22 10:50:12.388  2664  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-22 10:50:12.388  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:12.388  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:12.389  2664  2664 D HeadsetService: Received stop request...Stopping profile...
08-22 10:50:12.390  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.390  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:12.390  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:12.391   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:12.391  1934  2075 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:12.392  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.392   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:12.392   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:12.393  1359  2042 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:12.393  1359  1359 D HeadsetProfile: Bluetooth service disconnected
,08-22 10:50:12.394  2664  2664 D A2dpService: Received stop request...Stopping profile...
08-22 10:50:12.394  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.394  2664  2810 D A2dpStateMachine: Exit Disconnected: -1
08-22 10:50:12.397  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:12.397  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:50:12.397  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-22 10:50:12.397  1359  1359 D BluetoothA2dp: Proxy object disconnected
,08-22 10:50:12.397   873   873 D BluetoothA2dp: Proxy object disconnected
08-22 10:50:12.398  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.398  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:12.398  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:12.398  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:12.398  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:12.398  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:12.400  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.400  2664  2664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 10:50:12.400   873  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 10:50:12.400  2664  2687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-22 10:50:12.400  2664  2664 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 10:50:12.401  2664  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 10:50:12.401  2664  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 10:50:12.401  2664  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 10:50:12.401  2664  2687 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-22 10:50:12.400   873  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-22 10:50:12.401   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 10:50:12.401   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 10:50:12.402  2664  2664 D HidService: Received stop request...Stopping profile...
08-22 10:50:12.402  2664  2664 D HidService: Stopping Bluetooth HidService
08-22 10:50:12.403  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-22 10:50:12.403  1359  1359 D HidProfile: Bluetooth service disconnected
08-22 10:50:12.404  2664  2664 D HealthService: Received stop request...Stopping profile...
08-22 10:50:12.406  2664  2664 D PanService: Received stop request...Stopping profile...
08-22 10:50:12.407  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 10:50:12.407  1359  1359 D PanProfile: Bluetooth service disconnected
,08-22 10:50:12.408   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-22 10:50:12.408  2664  2664 D BluetoothMapService: Received stop request...Stopping profile...
,08-22 10:50:12.408  2664  2664 D BluetoothMapService: stop()
,08-22 10:50:12.409  2664  2664 D BluetoothMapAppObserver: deinitObservers()
,08-22 10:50:12.409  2664  2664 D BluetoothMapAppObserver: removeReceiver()
,08-22 10:50:12.409   873  2050 D DhcpClient: Clearing IP address
08-22 10:50:12.410  1359  1359 D BluetoothMap: Proxy object disconnected
,08-22 10:50:12.410  1359  1359 D MapProfile: Bluetooth service disconnected
08-22 10:50:12.411  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:12.411  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:12.411  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:12.411  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:12.412  2664  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 10:50:12.412  2664  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 10:50:12.412  2664  2774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 10:50:12.412  2664  2774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 10:50:12.412  2664  2774 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 10:50:12.412  2664  2774 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-22 10:50:12.412  2664  2687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-22 10:50:12.413  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:12.413  2664  2664 V BluetoothAdapterState: isTurningOn()=false
,08-22 10:50:12.413  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:12.413  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:12.413  1495  2507 V NativeCrypto: Read error: ssl=0x9a934600: I/O error during system call, Connection timed out
08-22 10:50:12.413  2664  2664 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 10:50:12.414  2664  2687 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 10:50:12.414  2664  2664 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 10:50:12.415  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:12.415  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:12.415  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:12.415  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:12.415  2664  2664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-22 10:50:12.415  2664  2687 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-22 10:50:12.415  1495  2507 V NativeCrypto: SSL shutdown failed: ssl=0x9a934600: I/O error during system call, Broken pipe
08-22 10:50:12.415   372   871 D CommandListener: Setting iface cfg
08-22 10:50:12.416  2664  2664 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 10:50:12.416  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:12.416  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:12.416  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:12.417  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:12.417  2664  2664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 10:50:12.417  2664  2664 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 10:50:12.418  2664  2664 D BluetoothMapService: MAP Service closeService in
,08-22 10:50:12.418  2664  2664 D BluetoothMapMasInstance0: MAP Service shutdown
,08-22 10:50:12.418  2664  2664 D ObexServerSockets0: shutdown(block = true)
,08-22 10:50:12.420   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-22 10:50:12.420   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-22 10:50:12.420  2664  2817 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-22 10:50:12.421  2664  2664 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 10:50:12.421  2664  2803 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-22 10:50:12.421  2664  2664 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-22 10:50:12.422  2664  2818 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-22 10:50:12.423   395   395 E Parcel  : Reading a NULL string not supported here.
08-22 10:50:12.424   873  1301 D WifiStateMachine: Start Disconnecting Watchdog 1
08-22 10:50:12.424  2664  2664 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:12.424  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:12.425   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 10:50:12.424  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:12.425  2664  2664 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:12.426  2664  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-22 10:50:12.426  2664  2683 D BluetoothAdapterProperties: Setting state to 15
08-22 10:50:12.426  2664  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-22 10:50:12.426  2664  2683 I BluetoothAdapterState: Entering BleOnState
08-22 10:50:12.426  2664  2664 D BluetoothMapService: cleanup()
08-22 10:50:12.427  2664  2664 D BluetoothMapService: MAP Service closeService in
08-22 10:50:12.430   873  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-22 10:50:12.431   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-22 10:50:12.432   873  2060 D DhcpClient: Receive thread stopped
,08-22 10:50:12.437  2664  2664 I BtOppRfcommListener: stopping Accept Thread
08-22 10:50:12.437  2664  3558 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 10:50:12.438  2664  3558 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 10:50:12.443  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:12.443  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:12.443  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.443  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:12.445  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:12.445  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:12.446  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.446  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:12.454   873  1983 I ActivityManager: Start proc 4037:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-22 10:50:12.458   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:12.459  1359  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 10:50:12.460   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
08-22 10:50:12.462  1359  2042 D BluetoothMap: onBluetoothStateChange: up=false
08-22 10:50:12.463  1359  1371 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:12.464   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:12.464  1934  2176 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:12.464   873  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 10:50:12.464  1359  1370 D BluetoothPan: onBluetoothStateChange on: false
08-22 10:50:12.464   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:12.465  1359  2042 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 10:50:12.466  1359  1371 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 10:50:12.466  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:12.466  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:12.466   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:12.467  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.467  2664  2683 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-22 10:50:12.467  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:12.467  2664  2683 D BluetoothAdapterProperties: Setting state to 16
,08-22 10:50:12.467  2664  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 10:50:12.467  2664  2683 D BluetoothAdapterProperties: onBleDisable
08-22 10:50:12.467  2664  2683 I BluetoothAdapterState: Entering PendingCommandState
08-22 10:50:12.468  2664  2684 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-22 10:50:12.468  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:12.468  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:12.469  2664  2774 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 10:50:12.469  2664  2774 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 10:50:12.469  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:12.469  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:12.470  3971  4030 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 429)
08-22 10:50:12.471  2148  2301 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 10:50:12.473  2664  2687 D BluetoothAdapterProperties: Scan Mode:20
08-22 10:50:12.474  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.476  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.477  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.478  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.482   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:12.496  4037  4037 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-22 10:50:12.500   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:12.501   873  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-22 10:50:12.501   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:12.502   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-22 10:50:12.506  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:12.507  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:12.510  3561  3561 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f3cd01 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-22 10:50:12.516  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:12.520  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:12.523   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@315b42c:true
,08-22 10:50:12.534   873  1968 I ActivityManager: Start proc 4054:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-22 10:50:12.542  4037  4037 D LocalBluetoothProfileManager: Adding local MAP profile
,08-22 10:50:12.544  4037  4037 D BluetoothMap: Create BluetoothMap proxy object
,08-22 10:50:12.552  4037  4037 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-22 10:50:12.556   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-22 10:50:12.557   873  1303 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-22 10:50:12.564  4054  4054 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-22 10:50:12.567  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:12.577   873  1930 I ActivityManager: Killing 3561:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-22 10:50:12.678  2664  2687 I bt_hci  : shut_down
,08-22 10:50:12.690  2664  2704 D bt_hwcfg: hw_epilog_process
,08-22 10:50:12.691  2664  2704 I bt_vendor: low_power_mode_cb
,08-22 10:50:12.713  2664  2704 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-22 10:50:12.713  2664  2704 I bt_vendor: epilog_cb
,08-22 10:50:12.713  2664  2704 I bt_hci  : epilog_finished_callback
,08-22 10:50:12.718  2664  2687 I bt_hci_h4: hal_close
,08-22 10:50:12.719  2664  2687 I bt_userial_vendor: device fd = 51 close
,08-22 10:50:12.827  4054  4054 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 10:50:12.827  4054  4054 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.827  4054  4054 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-22 10:50:12.827  4054  4054 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:12.827  4054  4054 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
,08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:12.827  4054  4054 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.,google.r.k.d(PG:1187)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.k.d(PG:583)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.e.b(PG:170)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:12.827  4054  4054 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.app,s.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.827  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:12.828  4054  4054 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at java.io.File.exists(File.java:361)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:12.828  4054  4054 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:12.828  4054  4054 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:12.852  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 10:50:12.870   873  1354 I ActivityManager: Start proc 4086:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-22 10:50:12.871   873  1354 I ActivityManager: Killing 3714:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-22 10:50:12.921  2664  2684 D bt_stack_manager: event_shut_down_stack finished.
,08-22 10:50:12.922  2664  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-22 10:50:12.928  2664  2683 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-22 10:50:12.929  2664  2664 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 10:50:12.930  2664  2664 D BtGatt.GattService: Received stop request...Stopping profile...
,08-22 10:50:12.930  2664  2664 D BtGatt.GattService: stop()
08-22 10:50:12.930  2664  2664 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 10:50:12.932  2664  2664 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:12.932  2664  2664 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:12.932  2664  2664 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:12.932  2664  2664 V BluetoothAdapterState: isBleTurningOff()=true
08-22 10:50:12.932  2664  2683 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-22 10:50:12.933  2664  2683 D BluetoothAdapterProperties: Setting state to 10
08-22 10:50:12.933  2664  2683 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-22 10:50:12.933  2664  2683 I BluetoothAdapterState: Entering OffState
,08-22 10:50:12.934   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-22 10:50:12.942  2664  2664 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-22 10:50:12.942  2664  2664 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-22 10:50:12.942  2664  2684 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-22 10:50:12.944  2664  2664 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 10:50:12.945  2664  2684 D bt_stack_manager: event_clean_up_stack finished.
,08-22 10:50:12.948  4086  4086 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-22 10:50:12.949  2664  2664 I art     : System.exit called, status: 0
,08-22 10:50:12.949  2664  2664 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 10:50:13.019  4086  4086 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-22 10:50:13.044   873  1929 I ActivityManager: Process com.android.bluetooth (pid 2664) has died
,08-22 10:50:13.050  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:13.077   873  1968 I ActivityManager: Start proc 4113:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-22 10:50:13.081  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:13.186  4113  4113 D AdapterServiceConfig: Adding HeadsetService
08-22 10:50:13.186  4113  4113 D AdapterServiceConfig: Adding A2dpService
,08-22 10:50:13.186  4113  4113 D AdapterServiceConfig: Adding HidService
08-22 10:50:13.186  4113  4113 D AdapterServiceConfig: Adding HealthService
08-22 10:50:13.186  4113  4113 D AdapterServiceConfig: Adding PanService
08-22 10:50:13.186  4113  4113 D AdapterServiceConfig: Adding GattService
08-22 10:50:13.187  4113  4113 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 10:50:13.192   873  1960 I ActivityManager: Killing 3604:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-22 10:50:13.222  4054  4074 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-22 10:50:13.239  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:13.241   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bed83de:true
,08-22 10:50:13.282  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-22 10:50:13.283  1710  2485 I iu.UploadsManager: num queued entries: 0
08-22 10:50:13.286  1710  2485 I iu.UploadsManager: num updated entries: 0
,08-22 10:50:13.288  1710  2485 I iu.SyncManager: NEXT; no task
08-22 10:50:13.288  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 10:50:13.289  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 10:50:13.307   873  1475 I ActivityManager: Start proc 4127:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-22 10:50:13.353  4127  4127 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-22 10:50:13.356  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:13.373  4127  4127 D SprintDMHelper: simOperator: 
08-22 10:50:13.373  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 10:50:13.390   873  1967 I ActivityManager: Start proc 4139:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-22 10:50:13.391   873  1967 I ActivityManager: Killing 3789:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-22 10:50:13.543   873   884 I ActivityManager: Start proc 4154:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-22 10:50:13.546  2852  4153 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-22 10:50:13.551   873  1974 I ActivityManager: Killing 3637:android.process.acore/u0a5 (adj 15): empty #17
,08-22 10:50:13.601  4154  4154 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-22 10:50:13.643  4154  4154 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 10:50:13.643  4154  4154 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 10:50:13.643  4154  4154 I GAv4    :   adb logcat -s GAv4
,08-22 10:50:13.655  4154  4154 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 10:50:13.661  4154  4154 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 10:50:13.679  4154  4171 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 10:50:13.790  4154  4154 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-22 10:50:13.826  4154  4154 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-22 10:50:13.839  4154  4154 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 4863-4870)
,08-22 10:50:13.840  4154  4154 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 10:50:13.854  4154  4154 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {488f871}
,08-22 10:50:13.854  4154  4154 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-22 10:50:13.855  4154  4154 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 10:50:13.866  4154  4154 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-22 10:50:13.868  4154  4154 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 10:50:13.884  4154  4154 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-22 10:50:13.899  4154  4154 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 10:50:13.899  4154  4154 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 10:50:13.899  4154  4154 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 10:50:13.899  4154  4154 I Adreno  : Build Date                       : 10/20/15
08-22 10:50:13.899  4154  4154 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 10:50:13.899  4154  4154 I Adreno  : Local Branch                     : M14
08-22 10:50:13.899  4154  4154 I Adreno  : Remote Branch                    : 
08-22 10:50:13.899  4154  4154 I Adreno  : Remote Branch                    : 
08-22 10:50:13.899  4154  4154 I Adreno  : Reconstruct Branch               : 
,08-22 10:50:13.965  4154  4154 I NSApplication: Starting up...
,08-22 10:50:13.977  4154  4200 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-22 10:50:14.003   873   884 I ActivityManager: Start proc 4205:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-22 10:50:14.004   873   884 I ActivityManager: Killing 3849:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-22 10:50:14.093  4205  4205 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-22 10:50:14.298   873  1984 I ActivityManager: Killing 3866:com.android.musicfx/u0a18 (adj 15): empty #17
,08-22 10:50:15.398   873  1354 D WifiService: setWifiEnabled: true pid=3971, uid=10000
,08-22 10:50:15.398   873  1354 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 10:50:15.410   873  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-22 10:50:15.419  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:15.420  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:15.420  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:15.420  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:15.423  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:15.423  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:15.423  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:15.423  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:15.433   873  1301 D WifiConfigStore: loaded 0 passpoint configs
,08-22 10:50:15.434   873  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-22 10:50:15.435   873  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-22 10:50:15.436   873  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 10:50:15.436   873  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-22 10:50:15.436   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-22 10:50:15.436   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 10:50:15.455   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 10:50:15.457   372   871 D CommandListener: Setting iface cfg
08-22 10:50:15.459   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-22 10:50:15.460   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 10:50:15.467   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-22 10:50:15.468   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-22 10:50:15.469   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:15.480   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:17.049   873  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.47 rxSuccessRate=1.81 delta 1000 -> 1000
,08-22 10:50:17.050   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-22 10:50:17.051   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:17.070   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-22 10:50:17.136   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-22 10:50:17.142  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 10:50:17.561  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 10:50:17.599  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 10:50:17.599  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-22 10:50:17.606   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:17.614   873  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 10:50:17.615   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-22 10:50:17.615   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:17.639   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:17.648   372   871 D CommandListener: Setting iface cfg
,08-22 10:50:17.648   873  1301 D WifiStateMachine: Start Dhcp Watchdog 2
,08-22 10:50:17.660   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-22 10:50:17.660   873  1303 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-22 10:50:17.660   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-22 10:50:17.685   873  4231 D DhcpClient: Receive thread started
,08-22 10:50:17.769   873  1301 E native  : do suspend false
,08-22 10:50:17.790   873  2050 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 10:50:17.805   873  4231 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172684, domain null
,08-22 10:50:17.806   873  2050 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172684 seconds
,08-22 10:50:17.812   873  2050 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 10:50:17.828   873  4231 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-22 10:50:17.830   873  2050 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 10:50:17.837   372   871 D CommandListener: Setting iface cfg
,08-22 10:50:17.847   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 10:50:17.853   873  2050 D DhcpClient: Scheduling renewal in 86399s
,08-22 10:50:17.860   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 10:50:17.864   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-22 10:50:17.866   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 10:50:17.867   873  1303 D ConnectivityService: Adding iface wlan0 to network 101
,08-22 10:50:17.886   873  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 10:50:17.919   873  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-22 10:50:17.919   873  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-22 10:50:17.920   873  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-22 10:50:17.922   873  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-22 10:50:17.923   873  1303 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-22 10:50:17.934   873  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 10:50:17.939   873  1303 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-22 10:50:17.939   873  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-22 10:50:17.939   873  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-22 10:50:17.939   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-22 10:50:17.940   873  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-22 10:50:17.940   873  1303 D ConnectivityService:    accepting network in place of null
,08-22 10:50:17.941   873  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -62]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 10:50:17.966   873  4230 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138996, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 10:50:17.993   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:18.040   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:18.044   873  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-22 10:50:18.045   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:18.049   873  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-22 10:50:18.051   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-22 10:50:18.061   873  4229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-22 10:50:18.063  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:18.063  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:50:18.064  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:18.064  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:18.066  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:18.067  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 10:50:18.068  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:18.068  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 10:50:18.093  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 10:50:18.094  1710  2485 I iu.UploadsManager: num queued entries: 0
,08-22 10:50:18.095  1710  2485 I iu.UploadsManager: num updated entries: 0
,08-22 10:50:18.096  1710  2485 I iu.SyncManager: NEXT; no task
,08-22 10:50:18.102  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 10:50:18.104  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 10:50:18.117   873   885 I ActivityManager: Start proc 4246:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-22 10:50:18.121  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:18.124  1710  4244 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-22 10:50:18.124  1710  4244 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 10:50:18.125  1710  4244 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 10:50:18.128  4127  4127 D SprintDMHelper: simOperator: 
,08-22 10:50:18.128  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.,
,08-22 10:50:18.131  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:18.133  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:18.142   873  4229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 08:50:18 GMT], X-Android-Received-Millis=[1471855818139], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471855818113]}
,08-22 10:50:18.146   873  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 10:50:18.146   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-22 10:50:18.146   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-22 10:50:18.149   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 10:50:18.158  4246  4246 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-22 10:50:18.170  1495  2266 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-22 10:50:18.171  1495  2266 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-22 10:50:18.171  1495  2266 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:50:18.172  1495  2266 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:18.203  1710  4244 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-22 10:50:18.242  4246  4246 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-22 10:50:18.249  4246  4246 I BooksApp: Created application version: 3.6.9 (30609)
,08-22 10:50:18.304  2852  4259 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 10:50:18.331  4246  4272 I BooksSync: Starting books sync for 61035162, extras: ade
,08-22 10:50:18.367  1495  2266 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-22 10:50:18.368  1495  2266 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-22 10:50:18.368  1495  2266 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:50:18.368  1495  2266 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:18.405   873   884 D WifiService: setWifiEnabled: false pid=3971, uid=10000
,08-22 10:50:18.405   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 10:50:18.412  3694  4271 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-22 10:50:18.412  3694  4271 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jdm.a(PG:82)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jcs.o(PG:406)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jcn.a(PG:1379)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jcs.i(PG:143)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at blb.a(PG:3937)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at czp.a(PG:18188)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at czp.a(PG:9081)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at czq.run(PG:1686)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-22 10:50:18.412  3694  4271 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jdj.a(PG:4091)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jdj.a(PG:1125)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jdm.a(PG:77)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	... 12 more
08-22 10:50:18.412  3694  4271 E HttpOperation: Caused by: faj: BadAuthentication
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at fal.a(PG:38)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	at jdj.a(PG:4089)
08-22 10:50:18.412  3694  4271 E HttpOperation: 	... 14 more
,08-22 10:50:18.423  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-22 10:50:18.428   873  1301 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 10:50:18.429   873  1301 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-22 10:50:18.430   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 10:50:18.430   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:18.441   873  2050 D DhcpClient: Clearing IP address
,08-22 10:50:18.441   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-22 10:50:18.444   372   871 D CommandListener: Setting iface cfg
,08-22 10:50:18.453  1495  4268 V NativeCrypto: Read error: ssl=0x9a9abc00: I/O error during system call, Connection timed out
,08-22 10:50:18.456   873  4231 D DhcpClient: Receive thread stopped
,08-22 10:50:18.458  1495  4268 V NativeCrypto: SSL shutdown failed: ssl=0x9a9abc00: I/O error during system call, Broken pipe
,08-22 10:50:18.463   873  1301 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-22 10:50:18.463   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-22 10:50:18.463   873  1930 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-22 10:50:18.463   873  4229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-22 10:50:18.464   873  4229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
08-22 10:50:18.464   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-22 10:50:18.468   395   395 E Parcel  : Reading a NULL string not supported here.
,08-22 10:50:18.469   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-22 10:50:18.469   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-22 10:50:18.473   873  4229 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-22 10:50:18.478   873  1303 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-22 10:50:18.480   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:18.483  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-22 10:50:18.484  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-22 10:50:18.484  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:50:18.484   873  1301 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 10:50:18.484  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:18.487  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:18.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:18.488  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:18.488  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:18.489  2148  2301 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 10:50:18.489  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true,
08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:18.489  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:18.489  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:18.489  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:18.516   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:18.516  3694  4271 E HttpOperation: [getmobileexperiments] Unexpected exception
08-22 10:50:18.516  3694  4271 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jdm.a(PG:82)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jcs.o(PG:406)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jcn.a(PG:1379)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jcs.i(PG:143)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at hec.a(PG:42)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at hee.a(PG:102)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at czr.a(PG:65)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at kka.a(PG:108)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at czp.a(PG:19176)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at czp.a(PG:9081)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at czq.run(PG:1686)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-22 10:50:18.516  3694  4271 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jdj.a(PG:4091)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jdj.a(PG:1125)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jdm.a(PG:77)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	... 15 more
08-22 10:50:18.516  3694  4271 E HttpOperation: Caused by: faj: BadAuthentication
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at fal.a(PG:38)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	at jdj.a(PG:4089)
08-22 10:50:18.516  3694  4271 E HttpOperation: 	... 17 more
08-22 10:50:18.516  3694  4271 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-22 10:50:18.516  3694  4271 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jdm.a(PG:82)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jcs.o(PG:406)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jcn.a(PG:1379)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jcs.i(PG:143)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at hec.a(PG:42)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at hee.a(PG:102)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at czr.a(PG:65)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at kka.a(PG:108)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at czp.a(PG:19176)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at czp.a(PG:9081)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at czq.run(PG:1686)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jdj.a(PG:4091)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jdm.a(PG:77)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	... 15 more
08-22 10:50:18.516  3694  4271 E ExperimentLoader: Caused by: faj: BadAuthentication
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at fal.a(PG:38)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	at jdj.a(PG:4089)
08-22 10:50:18.516  3694  4271 E ExperimentLoader: 	... 17 more
,08-22 10:50:18.543   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:18.544   873  1303 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-22 10:50:18.544   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:18.545   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-22 10:50:18.547  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:18.548  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:18.569  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-22 10:50:18.580  1710  2485 I iu.UploadsManager: num queued entries: 0
,08-22 10:50:18.586  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 10:50:18.587  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 10:50:18.590  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:18.598  4127  4127 D SprintDMHelper: simOperator: 
,08-22 10:50:18.599  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 10:50:18.602   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-22 10:50:18.603   873  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-22 10:50:18.623  1710  2485 I iu.UploadsManager: num updated entries: 0
,08-22 10:50:18.627  2852  4292 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-22 10:50:18.643  4246  4286 E BooksSync: annotations sync failed
08-22 10:50:18.643  4246  4286 E BooksSync: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Skipping sync: not connected
08-22 10:50:18.643  4246  4286 E BooksSync: com.google.android.apps.books.annotations.AnnotationControllerImpl.uploadAllPendingOperations(AnnotationControllerImpl.java:826)
,08-22 10:50:18.653  1710  2485 I iu.SyncManager: NEXT; no task
,08-22 10:50:18.655  4246  4295 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-22 10:50:18.667   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 135845, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-22 10:50:18.725  1495  2266 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-22 10:50:18.725  1495  2266 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-22 10:50:18.726  1495  2266 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 10:50:18.726  1495  2266 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:18.753  1495  2174 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-22 10:50:18.753  1495  2174 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-22 10:50:18.753  1495  2174 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-22 10:50:18.753  1495  2174 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:18.766  4246  4295 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-22 10:50:18.768  4246  4272 E BooksSync: Soft error
08-22 10:50:18.768  4246  4272 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-22 10:50:18.768  4246  4272 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-22 10:50:18.768  4246  4272 E BooksSync: Sync error
08-22 10:50:18.768  4246  4272 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-22 10:50:18.768  4246  4272 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-22 10:50:18.768  4246  4272 I BooksSync: Finished books sync
,08-22 10:50:18.773   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 134914, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-22 10:50:18.773   873   884 I ActivityManager: Killing 3888:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-22 10:50:18.815   873   884 I ActivityManager: Killing 2230:com.google.android.gms.wearable/u0a11 (adj 15): empty #18
,08-22 10:50:19.046   873  1303 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-22 10:50:21.455   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@da1040d:true
,08-22 10:50:21.455  4113  4113 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 10:50:21.460  4113  4113 I bt_bluedroid: init
,08-22 10:50:21.461  4113  4296 I BluetoothAdapterState: Entering OffState
,08-22 10:50:21.463  4113  4297 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 10:50:21.463  4113  4297 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-22 10:50:21.463  4113  4297 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-22 10:50:21.463  4113  4297 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-22 10:50:21.465  4113  4113 I bt_bluedroid: get_profile_interface socket
,08-22 10:50:21.467  4113  4113 I bt_bluedroid: get_profile_interface sdp
,08-22 10:50:21.470  4113  4300 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 10:50:21.473  4113  4124 I bt_bluedroid: config_hci_snoop_log
,08-22 10:50:21.474  4113  4300 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 10:50:21.477   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 10:50:21.486  4113  4296 D BluetoothAdapterState: Current state: OFF, message: 0
,08-22 10:50:21.487  4113  4296 D BluetoothAdapterProperties: Setting state to 14
08-22 10:50:21.487  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-22 10:50:21.491  4113  4296 D BluetoothBondStateMachine: make
,08-22 10:50:21.495  4113  4301 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 10:50:21.500  4113  4296 I BluetoothAdapterState: Entering PendingCommandState
,08-22 10:50:21.501  4113  4113 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 10:50:21.504  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:21.505  4113  4113 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 10:50:21.506  4113  4113 D BtGatt.GattService: Received start request. Starting profile...
08-22 10:50:21.506  4113  4113 D BtGatt.GattService: start()
08-22 10:50:21.506  4113  4113 I bt_bluedroid: get_profile_interface gatt
08-22 10:50:21.507  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
08-22 10:50:21.507  4113  4113 D BtGatt.AdvertiseManager: advertise manager created
,08-22 10:50:21.515  4113  4113 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:21.515  4113  4113 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:21.516  4113  4113 V BluetoothAdapterState: isBleTurningOn()=true
08-22 10:50:21.516  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:21.516  4113  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-22 10:50:21.517  4113  4296 I bt_bluedroid: enable
08-22 10:50:21.517  4113  4297 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-22 10:50:21.517  4113  4297 I bt_hci  : start_up
,08-22 10:50:21.534  4113  4297 I bt_vendor: alloc value 0xb39d4189
,08-22 10:50:21.535  4113  4297 I bt_vendor: init
08-22 10:50:21.535  4113  4297 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-22 10:50:21.535  4113  4297 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 10:50:21.645  4113  4297 D bt_hci  : start_up starting async portion
,08-22 10:50:21.646  4113  4304 I bt_hci  : event_finish_startup
,08-22 10:50:21.646  4113  4304 I bt_hci_h4: hal_open
,08-22 10:50:21.649  4113  4304 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 10:50:21.656  4113  4304 I bt_userial_vendor: device fd = 51 open
,08-22 10:50:21.685  4113  4304 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 10:50:21.718  4113  4304 D bt_hwcfg: Chipset BCM4354A2
,08-22 10:50:21.718  4113  4304 D bt_hwcfg: Target name = [BCM4354A2]
,08-22 10:50:21.719  4113  4304 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 10:50:22.446  4113  4304 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-22 10:50:22.447  4113  4304 D bt_hwcfg: Settlement delay -- 100 ms
,08-22 10:50:22.448  4113  4304 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 10:50:22.565  4113  4304 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 10:50:22.567  4113  4304 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 10:50:22.594  4113  4304 I bt_hwcfg: vendor lib fwcfg completed
,08-22 10:50:22.595  4113  4304 I bt_vendor: firmware callback
,08-22 10:50:22.595  4113  4304 I bt_hci  : firmware_config_callback
,08-22 10:50:22.606  4113  4306 I bt_btu  : btu_task pending for preload complete event
,08-22 10:50:22.606  4113  4306 I bt_btu_task: Bluetooth chip preload is complete
08-22 10:50:22.607  4113  4306 I bt_btu  : btu_task received preload complete event
,08-22 10:50:22.619  4113  4306 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 10:50:22.619  4113  4306 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 10:50:22.620  4113  4306 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-22 10:50:22.620  4113  4306 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 10:50:22.620  4113  4306 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-22 10:50:22.621  4113  4306 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 10:50:22.621  4113  4306 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 10:50:22.621  4113  4306 I         : BTE_InitTraceLevels -- TRC_BTM
,08-22 10:50:22.621  4113  4306 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 10:50:22.622  4113  4306 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 10:50:22.622  4113  4306 I         : BTE_InitTraceLevels -- TRC_SDP
,08-22 10:50:22.622  4113  4306 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 10:50:22.622  4113  4306 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 10:50:22.623  4113  4306 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-22 10:50:22.623  4113  4306 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 10:50:22.762  4113  4306 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3951d9d
,08-22 10:50:22.762  4113  4306 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3951d9d 
,08-22 10:50:22.774  4113  4300 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 10:50:22.775  4113  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-22 10:50:22.776  4113  4300 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 10:50:22.779  4113  4300 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 10:50:22.783  4113  4300 D BluetoothAdapterProperties: Scan Mode:20
,08-22 10:50:22.784  4113  4300 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 10:50:22.786  4113  4300 D bt_hci  : do_postload posting postload work item
08-22 10:50:22.786  4113  4304 I bt_hci  : event_postload
,08-22 10:50:22.786  4113  4304 I bt_vendor: sco_config_cb
08-22 10:50:22.786  4113  4304 I bt_hci  : sco_config_callback postload finished.
08-22 10:50:22.788  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:22.789  4113  4300 D bt_bte_conf: Device ID record 1 : primary
,08-22 10:50:22.789  4113  4300 D bt_bte_conf:   vendorId            = 000f
,08-22 10:50:22.789  4113  4300 D bt_bte_conf:   vendorIdSource      = 0001
,08-22 10:50:22.790  4113  4300 D bt_bte_conf:   product             = 1200
,08-22 10:50:22.790  4113  4300 D bt_bte_conf:   version             = 1436
08-22 10:50:22.791  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:22.791  4113  4300 D bt_bte_conf:   clientExecutableURL = 
08-22 10:50:22.793  4113  4300 D bt_bte_conf:   serviceDescription  = 
,08-22 10:50:22.793  4113  4304 I bt_vendor: low_power_mode_cb
08-22 10:50:22.794  4113  4300 D bt_bte_conf:   documentationURL    = 
08-22 10:50:22.795  4113  4300 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-22 10:50:22.795  4113  4297 D bt_stack_manager: event_start_up_stack finished
08-22 10:50:22.798  4113  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 10:50:22.799  4113  4296 D BluetoothAdapterProperties: Setting state to 15
08-22 10:50:22.799  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-22 10:50:22.803  4113  4296 I BluetoothAdapterState: Entering BleOnState
,08-22 10:50:22.805  4113  4296 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-22 10:50:22.805  4113  4296 D BluetoothAdapterProperties: Setting state to 11
08-22 10:50:22.806  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-22 10:50:22.817  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:22.819  4113  4113 D HeadsetService: Received start request. Starting profile...
,08-22 10:50:22.822  4113  4113 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-22 10:50:22.822  4113  4113 D HeadsetStateMachine: make
,08-22 10:50:22.823  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:22.826  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:22.840  4113  4113 D HeadsetStateMachine: max_hf_connections = 1
,08-22 10:50:22.840  4113  4113 I bt_bluedroid: get_profile_interface handsfree
08-22 10:50:22.840  4113  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-22 10:50:22.840  4113  4300 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-22 10:50:22.855  4113  4296 I BluetoothAdapterState: Entering PendingCommandState
,08-22 10:50:22.858  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:22.858  4113  4113 D A2dpService: Received start request. Starting profile...
,08-22 10:50:22.860  4113  4113 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-22 10:50:22.860  4113  4113 I bt_bluedroid: get_profile_interface avrcp
,08-22 10:50:22.868  4113  4113 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-22 10:50:22.868  4113  4113 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-22 10:50:22.868  4113  4113 D A2dpStateMachine: make
,08-22 10:50:22.871  4113  4113 I bt_bluedroid: get_profile_interface a2dp
,08-22 10:50:22.871  4113  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 10:50:22.877  4113  4316 D A2dpStateMachine: Enter Disconnected: -2
,08-22 10:50:22.879  4113  4113 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 10:50:22.881  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:22.883  4037  4037 D BluetoothInputDevice: Proxy object connected
,08-22 10:50:22.884  4113  4113 D HidService: Received start request. Starting profile...
,08-22 10:50:22.884  4037  4037 D HidProfile: Bluetooth service connected
08-22 10:50:22.884  4113  4113 I bt_bluedroid: get_profile_interface hidhost
08-22 10:50:22.885  4113  4113 D HidService: setHidService(): set to: null
,08-22 10:50:22.885  4113  4300 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39333e5
08-22 10:50:22.885  4113  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-22 10:50:22.888  4113  4113 I BluetoothHealthServiceJni: classInitNative: succeeds
08-22 10:50:22.888  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:22.890  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:22.891  4113  4113 D HealthService: Received start request. Starting profile...
,08-22 10:50:22.893  4113  4113 I bt_bluedroid: get_profile_interface health
,08-22 10:50:22.894  4113  4113 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 10:50:22.895  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:22.897  4113  4113 D PanService: Received start request. Starting profile...
,08-22 10:50:22.897  4037  4037 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 10:50:22.897  4113  4113 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-22 10:50:22.897  4113  4113 I bt_bluedroid: get_profile_interface pan,
,08-22 10:50:22.898  4113  4300 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 10:50:22.899  4037  4037 D PanProfile: Bluetooth service connected
08-22 10:50:22.903  4113  4113 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
08-22 10:50:22.905  4113  4113 D BluetoothMapService: Received start request. Starting profile...
08-22 10:50:22.905  4113  4113 D BluetoothMapService: start()
08-22 10:50:22.906  4037  4037 D BluetoothMap: Proxy object connected
,08-22 10:50:22.907  4037  4037 D MapProfile: Bluetooth service connected
,08-22 10:50:22.909  4037  4037 D BluetoothMap: getConnectedDevices()
,08-22 10:50:22.910  4037  4037 D BluetoothMap: Bluetooth is Not enabled
,08-22 10:50:22.910  4113  4113 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 10:50:22.911  4113  4113 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-22 10:50:22.911  4113  4113 D BluetoothMapAppObserver: createReceiver()
,08-22 10:50:22.913  4113  4113 D BluetoothMapAppObserver: initObservers()
,08-22 10:50:22.913  4113  4113 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 10:50:22.927  4113  4113 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:22.927  4113  4113 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:22.927  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:22.927  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:22.930  4113  4314 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-22 10:50:22.931  4113  4113 V BluetoothAdapterState: isTurningOff()=false
08-22 10:50:22.931  4113  4113 V BluetoothAdapterState: isTurningOn()=true
,08-22 10:50:22.931  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:22.931  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:22.931  4113  4113 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:22.932  4113  4113 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:22.932  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:22.932  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:22.934  4113  4113 V BluetoothAdapterState: isTurningOff()=false
08-22 10:50:22.934  4113  4113 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:22.934  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false,
,08-22 10:50:22.934  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:22.934  4113  4113 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:22.934  4113  4113 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:22.934  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:22.935  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:22.935  4113  4113 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:22.935  4113  4113 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:22.935  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:22.935  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:22.935  4113  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-22 10:50:22.935  4113  4296 D BluetoothAdapterProperties: ScanMode =  20
,08-22 10:50:22.935  4113  4296 D BluetoothAdapterProperties: State =  11
08-22 10:50:22.935  4113  4296 D BluetoothAdapterProperties: Setting state to 12
08-22 10:50:22.936  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-22 10:50:22.936  4113  4296 I BluetoothAdapterState: Entering OnState,
08-22 10:50:22.936  4037  4049 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 10:50:22.937   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 10:50:22.937  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=true,
08-22 10:50:22.940  4113  4300 D BluetoothAdapterProperties: Scan Mode:21
08-22 10:50:22.940  4113  4300 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 10:50:22.941  1359  2042 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 10:50:22.942  1359  1371 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 10:50:22.942  1359  1359 D BluetoothMap: Proxy object connected
,08-22 10:50:22.942  1359  1359 D MapProfile: Bluetooth service connected
08-22 10:50:22.942  1359  1359 D BluetoothMap: getConnectedDevices()
,08-22 10:50:22.942   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 10:50:22.943  4037  4048 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 10:50:22.943  1934  2075 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 10:50:22.944  1359  2042 D BluetoothPan: onBluetoothStateChange on: true
,08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:22.944  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:22.945  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 10:50:22.945  1359  1359 D PanProfile: Bluetooth service connected
,08-22 10:50:22.945  4037  4049 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 10:50:22.946  1359  1359 D BluetoothA2dp: Proxy object connected
08-22 10:50:22.947  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:22.947  4113  4113 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 10:50:22.948  4113  4113 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-22 10:50:22.948  4037  4048 D BluetoothPan: onBluetoothStateChange on: true
08-22 10:50:22.949  4113  4113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:22.949   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:22.950  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:22.950   873   873 D BluetoothA2dp: Proxy object connected,
08-22 10:50:22.950  1359  2042 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 10:50:22.951  4113  4113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 10:50:22.952  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:22.952  1359  1359 D BluetoothInputDevice: Proxy object connected
08-22 10:50:22.952  1359  1359 D HidProfile: Bluetooth service connected
08-22 10:50:22.952  4113  4113 D ObexServerSockets: Succeed to create listening sockets 
08-22 10:50:22.952  4113  4113 D ObexServerSockets0: startAccept()
08-22 10:50:22.952  4113  4113 D ObexServerSockets0: prepareForNewConnect()
,08-22 10:50:22.953  1359  1370 D BluetoothPbap: onBluetoothStateChange: up=true
08-22 10:50:22.954   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 10:50:22.955  4113  4113 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-22 10:50:22.955  4113  4113 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 10:50:22.956  4113  4113 D BluetoothMapService: onReceive
08-22 10:50:22.956  4113  4113 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:22.957  4113  4113 D BluetoothMapService: STATE_ON
08-22 10:50:22.958  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:22.959   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 10:50:22.960  4113  4321 D ObexServerSockets0: Accepting socket connection...
08-22 10:50:22.960  4113  4322 D ObexServerSockets0: Accepting socket connection...
08-22 10:50:22.960  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:22.960  4037  4037 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-22 10:50:22.966  4037  4037 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-22 10:50:22.972  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:22.974  4037  4037 D BluetoothA2dp: Proxy object connected
,08-22 10:50:22.976  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:22.988  1359  1359 D BluetoothPbap: Proxy object connected
,08-22 10:50:22.988  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-22 10:50:22.988  4037  4037 D DockEventReceiver: finishStartingService: stopping service
08-22 10:50:22.989  4037  4037 D BluetoothPbap: Proxy object connected
08-22 10:50:22.989  4113  4113 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 10:50:22.989  4113  4113 D ObexServerSockets0: prepareForNewConnect()
08-22 10:50:22.990  4037  4037 D PbapServerProfile: Bluetooth service connected
,08-22 10:50:22.997  4113  4327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:23.013  4113  4331 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:23.014  4113  4331 I BtOppRfcommListener: Accept thread started.
,08-22 10:50:23.039   873   873 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.039  1934  1957 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.039   873   873 D BluetoothHeadset: Proxy object connected
08-22 10:50:23.039   873   873 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.040  1359  2042 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.040  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-22 10:50:23.042  1359  1370 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.042   873   890 D BluetoothHeadset: Proxy object connected
08-22 10:50:23.043  1359  1359 D HeadsetProfile: Bluetooth service connected,
08-22 10:50:23.044  1934  1966 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.054   873   890 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.070  4037  4049 D BluetoothHeadset: Proxy object connected
,08-22 10:50:23.072  4037  4037 D HeadsetProfile: Bluetooth service connected
,08-22 10:50:23.259  4246  4267 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-22 10:50:24.421  4113  4296 D BluetoothAdapterState: Current state: ON, message: 23
08-22 10:50:24.421  4113  4296 D BluetoothAdapterProperties: Setting state to 13
,08-22 10:50:24.422  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-22 10:50:24.425  4113  4296 D BluetoothAdapterProperties: onBluetoothDisable()
,08-22 10:50:24.428  4113  4296 I BluetoothAdapterState: Entering PendingCommandState
,08-22 10:50:24.435  4113  4113 D BluetoothMapService: onReceive
,08-22 10:50:24.435  4113  4113 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:24.436  4113  4113 D BluetoothMapService: STATE_TURNING_OFF
,08-22 10:50:24.437  4113  4113 D BluetoothMapService: MAP Service closeService in
,08-22 10:50:24.437  4113  4113 D BluetoothMapMasInstance0: MAP Service shutdown
,08-22 10:50:24.437  4113  4113 D ObexServerSockets0: shutdown(block = true)
,08-22 10:50:24.438  4113  4321 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-22 10:50:24.441  4113  4113 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-22 10:50:24.441  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:24.441  4113  4322 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:24.442  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:24.444  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:24.445  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:24.447  4113  4309 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-22 10:50:24.448  4113  4113 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-22 10:50:24.448  4113  4300 D BluetoothAdapterProperties: Scan Mode:20
08-22 10:50:24.449  4113  4113 I BtOppRfcommListener: stopping Accept Thread
,08-22 10:50:24.449  4113  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-22 10:50:24.450  4113  4331 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 10:50:24.450  4113  4331 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 10:50:24.451  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:24.451  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:24.451  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 10:50:24.452  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 10:50:24.452  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 10:50:24.454  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:24.456  4113  4113 D HeadsetService: Received stop request...Stopping profile...
08-22 10:50:24.457  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:24.457   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:24.457  1934  2176 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:24.458   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:24.458   873   873 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:24.458  4037  4049 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:24.459  4113  4113 D A2dpService: Received stop request...Stopping profile...
08-22 10:50:24.459  4113  4316 D A2dpStateMachine: Exit Disconnected: -1
08-22 10:50:24.459  1359  1371 D BluetoothHeadset: Proxy object disconnected
08-22 10:50:24.461   873   873 D BluetoothA2dp: Proxy object disconnected
,08-22 10:50:24.466  4113  4113 V BluetoothAdapterState: isTurningOff()=true
,08-22 10:50:24.466  4113  4113 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:24.466  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:24.466  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:24.467  4113  4113 D HidService: Received stop request...Stopping profile...
,08-22 10:50:24.467  1359  1359 D HeadsetProfile: Bluetooth service disconnected
,08-22 10:50:24.467  4113  4113 D HidService: Stopping Bluetooth HidService
08-22 10:50:24.468  1359  1359 D BluetoothA2dp: Proxy object disconnected
,08-22 10:50:24.471  1359  1359 D BluetoothInputDevice: Proxy object disconnected
,08-22 10:50:24.471  1359  1359 D HidProfile: Bluetooth service disconnected
,08-22 10:50:24.472  4037  4037 D DockEventReceiver: finishStartingService: stopping service
08-22 10:50:24.472  4113  4113 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-22 10:50:24.472  4113  4113 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 10:50:24.473  4113  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 10:50:24.473  4113  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 10:50:24.473  4113  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 10:50:24.473  4113  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-22 10:50:24.474  4113  4300 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-22 10:50:24.475  4113  4113 D HealthService: Received stop request...Stopping profile...
08-22 10:50:24.475  4037  4037 D HeadsetProfile: Bluetooth service disconnected
08-22 10:50:24.476  4037  4037 D BluetoothA2dp: Proxy object disconnected
,08-22 10:50:24.476  4037  4037 D BluetoothInputDevice: Proxy object disconnected
,08-22 10:50:24.476  4037  4037 D HidProfile: Bluetooth service disconnected
08-22 10:50:24.477  4113  4113 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:24.477  4113  4113 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:24.477  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:24.477  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:24.478  4113  4113 D PanService: Received stop request...Stopping profile...
08-22 10:50:24.480  4037  4037 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 10:50:24.480  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 10:50:24.481  1359  1359 D PanProfile: Bluetooth service disconnected
08-22 10:50:24.481  4037  4037 D PanProfile: Bluetooth service disconnected
08-22 10:50:24.482  4113  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-22 10:50:24.482  4113  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 10:50:24.482  4113  4306 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 10:50:24.482  4113  4306 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 10:50:24.482  4113  4306 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 10:50:24.482  4113  4306 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 10:50:24.482  4113  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-22 10:50:24.487  4113  4113 D BluetoothMapService: Received stop request...Stopping profile...
,08-22 10:50:24.488  4113  4113 D BluetoothMapService: stop()
08-22 10:50:24.489  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:24.490  4113  4113 D BluetoothMapAppObserver: deinitObservers()
08-22 10:50:24.490  4113  4113 D BluetoothMapAppObserver: removeReceiver()
,08-22 10:50:24.491  4037  4037 D BluetoothMap: Proxy object disconnected
,08-22 10:50:24.491  4037  4037 D MapProfile: Bluetooth service disconnected
08-22 10:50:24.491  1359  1359 D BluetoothMap: Proxy object disconnected
,08-22 10:50:24.491  1359  1359 D MapProfile: Bluetooth service disconnected
08-22 10:50:24.491  4113  4113 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:24.492  4113  4113 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:24.492  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:24.492  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:24.492  4113  4113 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 10:50:24.492  4113  4113 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 10:50:24.492  4113  4300 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-22 10:50:24.492  4113  4113 V BluetoothAdapterState: isTurningOff()=true
,08-22 10:50:24.492  4113  4113 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:24.492  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:24.492  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:24.492  4113  4113 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-22 10:50:24.493  4113  4300 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-22 10:50:24.493  4113  4113 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 10:50:24.493  4113  4113 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:24.493  4113  4113 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:24.493  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:24.493  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:24.493  4113  4113 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 10:50:24.494  4113  4113 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-22 10:50:24.497  4037  4037 D BluetoothPbap: Proxy object disconnected
,08-22 10:50:24.497  4037  4037 D PbapServerProfile: Bluetooth service disconnected
,08-22 10:50:24.497  1359  1359 D BluetoothPbap: Proxy object disconnected
,08-22 10:50:24.497  1359  1359 D PbapServerProfile: Bluetooth service disconnected
08-22 10:50:24.498  4113  4113 D BluetoothMapService: MAP Service closeService in
,08-22 10:50:24.498  4113  4113 V BluetoothAdapterState: isTurningOff()=true
08-22 10:50:24.498  4113  4113 V BluetoothAdapterState: isTurningOn()=false
08-22 10:50:24.498  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:24.498  4113  4113 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:24.498  4113  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-22 10:50:24.499  4113  4296 D BluetoothAdapterProperties: Setting state to 15
08-22 10:50:24.499  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-22 10:50:24.499  4113  4296 I BluetoothAdapterState: Entering BleOnState
08-22 10:50:24.499  4113  4113 D BluetoothMapService: cleanup()
,08-22 10:50:24.499  4113  4113 D BluetoothMapService: MAP Service closeService in
08-22 10:50:24.500  4037  4048 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 10:50:24.501  4037  4049 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 10:50:24.501   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:24.501  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:24.503  1359  2042 D BluetoothMap: onBluetoothStateChange: up=false
08-22 10:50:24.503  1359  1370 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:24.503   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:24.504  4037  4048 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:24.504  4037  4049 D BluetoothMap: onBluetoothStateChange: up=false
,08-22 10:50:24.504  1934  2075 D BluetoothHeadset: onBluetoothStateChange: up=false
08-22 10:50:24.505  1359  1371 D BluetoothPan: onBluetoothStateChange on: false
,08-22 10:50:24.505  4037  4048 D BluetoothPbap: onBluetoothStateChange: up=false
,08-22 10:50:24.506  4037  4049 D BluetoothPan: onBluetoothStateChange on: false
08-22 10:50:24.506   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 10:50:24.506  1359  2042 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-22 10:50:24.507  1359  1370 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 10:50:24.507   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-22 10:50:24.508  4113  4296 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-22 10:50:24.508  4113  4296 D BluetoothAdapterProperties: Setting state to 16
08-22 10:50:24.508  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-22 10:50:24.508  4113  4296 D BluetoothAdapterProperties: onBleDisable
,08-22 10:50:24.508  4113  4296 I BluetoothAdapterState: Entering PendingCommandState
,08-22 10:50:24.509  4113  4297 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-22 10:50:24.509  4113  4306 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-22 10:50:24.509  4113  4306 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-22 10:50:24.511  4113  4300 D BluetoothAdapterProperties: Scan Mode:20
08-22 10:50:24.512  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:24.513  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:24.514  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 10:50:24.514  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:24.516  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:24.518  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:24.522  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:24.711  4113  4300 I bt_hci  : shut_down
,08-22 10:50:24.722  4113  4304 D bt_hwcfg: hw_epilog_process
,08-22 10:50:24.722  4113  4304 I bt_vendor: low_power_mode_cb
,08-22 10:50:24.738  4113  4304 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-22 10:50:24.738  4113  4304 I bt_vendor: epilog_cb
08-22 10:50:24.738  4113  4304 I bt_hci  : epilog_finished_callback
,08-22 10:50:24.744  4113  4300 I bt_hci_h4: hal_close
,08-22 10:50:24.745  4113  4300 I bt_userial_vendor: device fd = 51 close
,08-22 10:50:24.864  4113  4297 D bt_stack_manager: event_shut_down_stack finished.
,08-22 10:50:24.865  4113  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-22 10:50:24.871  4113  4113 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 10:50:24.873  4113  4296 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-22 10:50:24.873  4113  4113 D BtGatt.GattService: Received stop request...Stopping profile...
,08-22 10:50:24.873  4113  4113 D BtGatt.GattService: stop()
08-22 10:50:24.873  4113  4113 D BtGatt.AdvertiseManager: advertise clients cleared
,08-22 10:50:24.878  4113  4113 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:24.878  4113  4113 V BluetoothAdapterState: isTurningOn()=false
,08-22 10:50:24.879  4113  4113 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:24.879  4113  4113 V BluetoothAdapterState: isBleTurningOff()=true
,08-22 10:50:24.880  4113  4296 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-22 10:50:24.881  4113  4296 D BluetoothAdapterProperties: Setting state to 10
,08-22 10:50:24.881  4113  4296 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-22 10:50:24.883  4113  4296 I BluetoothAdapterState: Entering OffState
08-22 10:50:24.884   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-22 10:50:24.905  4113  4113 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-22 10:50:24.905  4113  4113 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-22 10:50:24.906  4113  4297 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-22 10:50:24.909  4113  4297 D bt_stack_manager: event_clean_up_stack finished.
08-22 10:50:24.909  4113  4113 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 10:50:24.911  4113  4113 I art     : System.exit called, status: 0
,08-22 10:50:24.912  4113  4113 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 10:50:24.976   873   883 I ActivityManager: Process com.android.bluetooth (pid 4113) has died
,08-22 10:50:25.455  1495  2196 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-22 10:50:25.946   873  1303 D ConnectivityService: handlePromptUnvalidated 101
,08-22 10:50:26.803  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:26.813  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:26.818  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:26.875  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-22 10:50:26.876  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-22 10:50:26.876  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:50:26.876  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:26.922  3654  3654 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-22 10:50:26.923  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-22 10:50:26.924  3654  3654 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-22 10:50:27.418  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:27.419  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:28.296  3654  3664 D Finsky  : [300] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-22 10:50:28.315  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:28.367  1495  2265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-22 10:50:28.368  1495  2265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-22 10:50:28.368  1495  2265 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:50:28.368  1495  2265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:28.414  3654  3664 D Finsky  : [300] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-22 10:50:29.171   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-22 10:50:29.181  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-22 10:50:29.190   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-22 10:50:29.190   873   893 I Adreno  : Build Date                       : 10/20/15
08-22 10:50:29.190   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-22 10:50:29.190   873   893 I Adreno  : Local Branch                     : M14
08-22 10:50:29.190   873   893 I Adreno  : Remote Branch                    : 
08-22 10:50:29.190   873   893 I Adreno  : Remote Branch                    : 
08-22 10:50:29.190   873   893 I Adreno  : Reconstruct Branch               : 
,08-22 10:50:29.229   281   370 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (267 us)
,08-22 10:50:29.927  3971  3971 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 10:50:29.928  3971  3971 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 10:50:29.962   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-22 10:50:29.964  3971  3971 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8ab11a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@b6afc3d, 16908290=android.view.AbsSavedState$1@b6afc3d}, android:focusedViewId=100}]}]
,08-22 10:50:29.964  3971  3971 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-22 10:50:29.965  3971  3971 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 10:50:29.965  3971  3971 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 10:50:29.975   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-22 10:50:29.979   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-22 10:50:29.980   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-22 10:50:29.982   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-22 10:50:29.999   873   882 I art     : Background partial concurrent mark sweep GC freed 14657(1137KB) AllocSpace objects, 4(124KB) LOS objects, 33% free, 28MB/43MB, paused 1.359ms total 110.656ms
,08-22 10:50:30.215   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-22 10:50:30.219   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-22 10:50:30.225   873  1326 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,08-22 10:50:30.228   873   893 I DreamManagerService: Entering dreamland.
,08-22 10:50:30.230   873   893 I PowerManagerService: Dozing...
,08-22 10:50:30.231   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-22 10:50:30.277   376  1310 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-22 10:50:30.277   376  1310 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-22 10:50:30.288   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:30.297  1921  4345 D NfcService: Discovery configuration equal, not updating.
,08-22 10:50:30.301   873  1301 E native  : do suspend false
,08-22 10:50:30.335   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:30.340   873  1301 E native  : do suspend true
,08-22 10:50:30.416   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-22 10:50:30.417   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-22 10:50:30.427  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:30.427  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9962c32 added. We now have 6 listener(s)
,08-22 10:50:30.428  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:30.431  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:30.433  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7143d83 added. We now have 7 listener(s)
08-22 10:50:30.433  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:30.435  3971  4019 I System.out: IsBluetoothEnabled
,08-22 10:50:30.447  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:30.480   873   890 I ActivityManager: Start proc 4351:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-22 10:50:30.594  4351  4351 D AdapterServiceConfig: Adding HeadsetService
,08-22 10:50:30.594  4351  4351 D AdapterServiceConfig: Adding A2dpService
,08-22 10:50:30.595  4351  4351 D AdapterServiceConfig: Adding HidService
,08-22 10:50:30.595  4351  4351 D AdapterServiceConfig: Adding HealthService
,08-22 10:50:30.595  4351  4351 D AdapterServiceConfig: Adding PanService
,08-22 10:50:30.595  4351  4351 D AdapterServiceConfig: Adding GattService
,08-22 10:50:30.596  4351  4351 D AdapterServiceConfig: Adding BluetoothMapService
,08-22 10:50:30.612   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b666f3a:true
,08-22 10:50:30.613  4351  4351 D BluetoothAdapterState: make() - Creating AdapterState
,08-22 10:50:30.621  4351  4363 I BluetoothAdapterState: Entering OffState
,08-22 10:50:30.621  4351  4351 I bt_bluedroid: init
,08-22 10:50:30.627  4351  4364 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-22 10:50:30.628  4351  4364 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-22 10:50:30.628  4351  4364 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-22 10:50:30.628  4351  4364 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-22 10:50:30.630  4351  4351 I bt_bluedroid: get_profile_interface socket
,08-22 10:50:30.634  4351  4367 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 10:50:30.635  4351  4351 I bt_bluedroid: get_profile_interface sdp
,08-22 10:50:30.638  4351  4367 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 10:50:30.644  4351  4362 I bt_bluedroid: config_hci_snoop_log
,08-22 10:50:30.645   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 10:50:30.654  4351  4363 D BluetoothAdapterState: Current state: OFF, message: 0
08-22 10:50:30.654  4351  4363 D BluetoothAdapterProperties: Setting state to 14
08-22 10:50:30.655  4351  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-22 10:50:30.656  4351  4363 D BluetoothBondStateMachine: make
,08-22 10:50:30.658  4351  4368 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 10:50:30.663  4351  4363 I BluetoothAdapterState: Entering PendingCommandState
,08-22 10:50:30.667  4351  4351 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-22 10:50:30.675  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:30.676  4351  4351 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 10:50:30.678  4351  4351 D BtGatt.GattService: Received start request. Starting profile...
,08-22 10:50:30.678  4351  4351 D BtGatt.GattService: start()
,08-22 10:50:30.678  4351  4351 I bt_bluedroid: get_profile_interface gatt
,08-22 10:50:30.680  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:30.680  4351  4351 D BtGatt.AdvertiseManager: advertise manager created
,08-22 10:50:30.693  4351  4351 V BluetoothAdapterState: isTurningOff()=false
08-22 10:50:30.693  4351  4351 V BluetoothAdapterState: isTurningOn()=false
,08-22 10:50:30.694  4351  4351 V BluetoothAdapterState: isBleTurningOn()=true
,08-22 10:50:30.695  4351  4351 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:30.697  4351  4363 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-22 10:50:30.698  4351  4363 I bt_bluedroid: enable
08-22 10:50:30.698  4351  4364 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-22 10:50:30.699  4351  4364 I bt_hci  : start_up
,08-22 10:50:30.725  4351  4364 I bt_vendor: alloc value 0xb39e4189
,08-22 10:50:30.725  4351  4364 I bt_vendor: init
,08-22 10:50:30.725  4351  4364 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-22 10:50:30.725  4351  4364 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-22 10:50:30.834  4351  4364 D bt_hci  : start_up starting async portion
,08-22 10:50:30.835  4351  4371 I bt_hci  : event_finish_startup
,08-22 10:50:30.835  4351  4371 I bt_hci_h4: hal_open
08-22 10:50:30.835  4351  4371 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-22 10:50:30.845  4351  4371 I bt_userial_vendor: device fd = 51 open
,08-22 10:50:30.876  4351  4371 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 10:50:30.908  4351  4371 D bt_hwcfg: Chipset BCM4354A2
,08-22 10:50:30.908  4351  4371 D bt_hwcfg: Target name = [BCM4354A2]
,08-22 10:50:30.909  4351  4371 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-22 10:50:31.570  4351  4371 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-22 10:50:31.572  4351  4371 D bt_hwcfg: Settlement delay -- 100 ms
,08-22 10:50:31.572  4351  4371 I bt_hwcfg: Setting fw settlement delay to 100 
,08-22 10:50:31.689  4351  4371 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-22 10:50:31.690  4351  4371 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-22 10:50:31.719  4351  4371 I bt_hwcfg: vendor lib fwcfg completed
,08-22 10:50:31.720  4351  4371 I bt_vendor: firmware callback
,08-22 10:50:31.720  4351  4371 I bt_hci  : firmware_config_callback
,08-22 10:50:31.732  4351  4373 I bt_btu  : btu_task pending for preload complete event
,08-22 10:50:31.733  4351  4373 I bt_btu_task: Bluetooth chip preload is complete
08-22 10:50:31.733  4351  4373 I bt_btu  : btu_task received preload complete event
,08-22 10:50:31.743  4351  4373 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 10:50:31.743  4351  4373 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 10:50:31.743  4351  4373 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-22 10:50:31.744  4351  4373 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 10:50:31.744  4351  4373 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-22 10:50:31.744  4351  4373 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 10:50:31.744  4351  4373 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-22 10:50:31.745  4351  4373 I         : BTE_InitTraceLevels -- TRC_BTM
,08-22 10:50:31.745  4351  4373 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 10:50:31.745  4351  4373 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 10:50:31.746  4351  4373 I         : BTE_InitTraceLevels -- TRC_SDP
,08-22 10:50:31.746  4351  4373 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 10:50:31.746  4351  4373 I         : BTE_InitTraceLevels -- TRC_SMP
,08-22 10:50:31.746  4351  4373 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 10:50:31.746  4351  4373 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-22 10:50:31.880  4351  4373 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3961d9d
,08-22 10:50:31.881  4351  4373 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3961d9d 
,08-22 10:50:31.907  4351  4367 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-22 10:50:31.908  4351  4367 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-22 10:50:31.910  4351  4367 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-22 10:50:31.913  4351  4367 D BluetoothAdapterProperties: Name is: Nexus 6
,08-22 10:50:31.917  4351  4367 D BluetoothAdapterProperties: Scan Mode:20
,08-22 10:50:31.917  4351  4367 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 10:50:31.918  4351  4367 D bt_hci  : do_postload posting postload work item
08-22 10:50:31.918  4351  4371 I bt_hci  : event_postload
08-22 10:50:31.918  4351  4371 I bt_vendor: sco_config_cb
08-22 10:50:31.918  4351  4371 I bt_hci  : sco_config_callback postload finished.
,08-22 10:50:31.923  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:31.926  4351  4371 I bt_vendor: low_power_mode_cb
,08-22 10:50:31.927  4351  4367 D bt_bte_conf: Device ID record 1 : primary
,08-22 10:50:31.927  4351  4367 D bt_bte_conf:   vendorId            = 000f
08-22 10:50:31.928  4351  4367 D bt_bte_conf:   vendorIdSource      = 0001
,08-22 10:50:31.928  4351  4367 D bt_bte_conf:   product             = 1200
08-22 10:50:31.929  4351  4367 D bt_bte_conf:   version             = 1436
08-22 10:50:31.929  4351  4367 D bt_bte_conf:   clientExecutableURL = 
,08-22 10:50:31.929  4351  4367 D bt_bte_conf:   serviceDescription  = 
08-22 10:50:31.929  4351  4367 D bt_bte_conf:   documentationURL    = 
08-22 10:50:31.930  4351  4367 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-22 10:50:31.931  4351  4364 D bt_stack_manager: event_start_up_stack finished
,08-22 10:50:31.934  4351  4363 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-22 10:50:31.935  4351  4363 D BluetoothAdapterProperties: Setting state to 15
,08-22 10:50:31.936  4351  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-22 10:50:31.939  4351  4363 I BluetoothAdapterState: Entering BleOnState
,08-22 10:50:31.944  4351  4363 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-22 10:50:31.944  4351  4363 D BluetoothAdapterProperties: Setting state to 11
08-22 10:50:31.944  4351  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-22 10:50:31.948  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:31.949  4351  4351 D HeadsetService: Received start request. Starting profile...
08-22 10:50:31.953  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:31.956  4351  4351 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 10:50:31.957  4351  4351 D HeadsetStateMachine: make
,08-22 10:50:31.965  4351  4363 I BluetoothAdapterState: Entering PendingCommandState
,08-22 10:50:31.966  4351  4351 D HeadsetStateMachine: max_hf_connections = 1
,08-22 10:50:31.967  4351  4351 I bt_bluedroid: get_profile_interface handsfree
08-22 10:50:31.967  4351  4367 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-22 10:50:31.967  4351  4367 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-22 10:50:31.971  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:31.972  4351  4351 D A2dpService: Received start request. Starting profile...
,08-22 10:50:31.973  4351  4351 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 10:50:31.973  4351  4351 I bt_bluedroid: get_profile_interface avrcp
,08-22 10:50:31.981  4351  4351 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 10:50:31.982  4351  4351 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 10:50:31.982  4351  4351 D A2dpStateMachine: make
,08-22 10:50:31.983  4351  4351 I bt_bluedroid: get_profile_interface a2dp
,08-22 10:50:31.984  4351  4367 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-22 10:50:31.987  4351  4381 D A2dpStateMachine: Enter Disconnected: -2
,08-22 10:50:31.987  4351  4351 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 10:50:31.988  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:31.989  4351  4351 D HidService: Received start request. Starting profile...
,08-22 10:50:31.989  4351  4351 I bt_bluedroid: get_profile_interface hidhost
,08-22 10:50:31.990  4351  4367 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39433e5
,08-22 10:50:31.990  4351  4367 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-22 10:50:31.990  4351  4351 D HidService: setHidService(): set to: null
,08-22 10:50:31.992  4351  4351 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 10:50:31.993  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:31.993  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:31.993  4351  4351 D HealthService: Received start request. Starting profile...
,08-22 10:50:31.995  4351  4351 I bt_bluedroid: get_profile_interface health
,08-22 10:50:31.996  4351  4351 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 10:50:31.997  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:31.997  4351  4351 D PanService: Received start request. Starting profile...
,08-22 10:50:31.997  4351  4351 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 10:50:31.997  4351  4351 I bt_bluedroid: get_profile_interface pan
08-22 10:50:31.998  4351  4367 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 10:50:32.003  4351  4351 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
08-22 10:50:32.004  4351  4351 D BluetoothMapService: Received start request. Starting profile...
08-22 10:50:32.004  4351  4351 D BluetoothMapService: start()
,08-22 10:50:32.007  4351  4351 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-22 10:50:32.009  4351  4351 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-22 10:50:32.009  4351  4351 D BluetoothMapAppObserver: createReceiver()
,08-22 10:50:32.010  4351  4351 D BluetoothMapAppObserver: initObservers()
,08-22 10:50:32.011  4351  4351 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-22 10:50:32.021  4351  4351 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:32.022  4351  4351 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:32.022  4351  4351 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:32.022  4351  4351 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:32.024  4351  4351 V BluetoothAdapterState: isTurningOff()=false
08-22 10:50:32.024  4351  4351 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:32.024  4351  4351 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:32.024  4351  4351 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:32.024  4351  4379 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 10:50:32.025  4351  4351 V BluetoothAdapterState: isTurningOff()=false
08-22 10:50:32.025  4351  4351 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:32.025  4351  4351 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:32.025  4351  4351 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:32.025  4351  4351 V BluetoothAdapterState: isTurningOff()=false
08-22 10:50:32.025  4351  4351 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isTurningOff()=false
,08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isBleTurningOn()=false
08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isBleTurningOff()=false
,08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isTurningOff()=false
08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isTurningOn()=true
08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isBleTurningOn()=false
,08-22 10:50:32.026  4351  4351 V BluetoothAdapterState: isBleTurningOff()=false
08-22 10:50:32.027  4351  4363 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-22 10:50:32.027  4351  4363 D BluetoothAdapterProperties: ScanMode =  20
08-22 10:50:32.027  4351  4363 D BluetoothAdapterProperties: State =  11
08-22 10:50:32.027  4351  4363 D BluetoothAdapterProperties: Setting state to 12
08-22 10:50:32.027  4351  4363 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-22 10:50:32.028  4351  4363 I BluetoothAdapterState: Entering OnState
08-22 10:50:32.028  4037  4049 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-22 10:50:32.029  4351  4367 D BluetoothAdapterProperties: Scan Mode:21
08-22 10:50:32.030  4351  4367 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:32.033  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:32.037  4037  4048 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:32.039  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:32.040   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 10:50:32.041  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 10:50:32.041  4037  4037 D BluetoothInputDevice: Proxy object connected
08-22 10:50:32.041  4037  4037 D HidProfile: Bluetooth service connected
08-22 10:50:32.042  4351  4351 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-22 10:50:32.042  4351  4351 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-22 10:50:32.043  1359  1359 D BluetoothA2dp: Proxy object connected
08-22 10:50:32.043  1359  2042 D BluetoothMap: onBluetoothStateChange: up=true
08-22 10:50:32.044  4351  4351 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 10:50:32.045  4037  4037 D BluetoothA2dp: Proxy object connected
08-22 10:50:32.045  1359  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 10:50:32.046   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 10:50:32.046  4037  4049 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 10:50:32.047  4037  4049 D BluetoothMap: onBluetoothStateChange: up=true
08-22 10:50:32.048  4351  4351 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:32.049  4351  4351 D ObexServerSockets: Succeed to create listening sockets 
08-22 10:50:32.050  4351  4351 D ObexServerSockets0: startAccept()
08-22 10:50:32.050  1934  2176 D BluetoothHeadset: onBluetoothStateChange: up=true
08-22 10:50:32.050  4351  4351 D ObexServerSockets0: prepareForNewConnect()
,08-22 10:50:32.051  1359  1371 D BluetoothPan: onBluetoothStateChange on: true
,08-22 10:50:32.053  4037  4389 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 10:50:32.053  4351  4351 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-22 10:50:32.054  4351  4351 D BluetoothSdpJni: SDP Create record success - handle: 0
08-22 10:50:32.054  4351  4390 D ObexServerSockets0: Accepting socket connection...
08-22 10:50:32.055  4037  4048 D BluetoothPan: onBluetoothStateChange on: true
08-22 10:50:32.055  4351  4391 D ObexServerSockets0: Accepting socket connection...
,08-22 10:50:32.056  1359  1359 D BluetoothMap: Proxy object connected
08-22 10:50:32.056  1359  1359 D MapProfile: Bluetooth service connected
08-22 10:50:32.056  1359  1359 D BluetoothMap: getConnectedDevices()
,08-22 10:50:32.058   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 10:50:32.058  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 10:50:32.058  1359  1359 D PanProfile: Bluetooth service connected
08-22 10:50:32.059   873   873 D BluetoothA2dp: Proxy object connected
,08-22 10:50:32.060  1359  1371 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 10:50:32.060  4037  4037 D BluetoothMap: Proxy object connected
08-22 10:50:32.061  4037  4037 D MapProfile: Bluetooth service connected
,08-22 10:50:32.061  4037  4037 D BluetoothMap: getConnectedDevices()
,08-22 10:50:32.062  1359  1359 D BluetoothInputDevice: Proxy object connected
,08-22 10:50:32.063  1359  1359 D HidProfile: Bluetooth service connected
08-22 10:50:32.063  1359  1370 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 10:50:32.064  4037  4037 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 10:50:32.064  4037  4037 D PanProfile: Bluetooth service connected
08-22 10:50:32.064   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-22 10:50:32.066   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 10:50:32.067  4351  4351 D BluetoothMapService: onReceive
,08-22 10:50:32.067  4351  4351 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-22 10:50:32.067  4351  4351 D BluetoothMapService: STATE_ON
08-22 10:50:32.069  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:32.074  4037  4037 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 10:50:32.081  1495  1495 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-22 10:50:32.089  4037  4037 D DockEventReceiver: finishStartingService: stopping service
,08-22 10:50:32.092  4037  4037 D BluetoothPbap: Proxy object connected
,08-22 10:50:32.092  4037  4037 D PbapServerProfile: Bluetooth service connected
,08-22 10:50:32.095  1359  1359 D BluetoothPbap: Proxy object connected
,08-22 10:50:32.095  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-22 10:50:32.098  4351  4351 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-22 10:50:32.098  4351  4351 D ObexServerSockets0: prepareForNewConnect()
08-22 10:50:32.101  4351  4395 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:32.114  4351  4399 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 10:50:32.115  4351  4399 I BtOppRfcommListener: Accept thread started.
,08-22 10:50:32.143   873   873 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.144  1934  2075 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.144   873   873 D BluetoothHeadset: Proxy object connected
08-22 10:50:32.145   873   873 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.145  4037  4049 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.146  4037  4037 D HeadsetProfile: Bluetooth service connected
08-22 10:50:32.146  1359  2042 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.146  1359  1359 D HeadsetProfile: Bluetooth service connected
,08-22 10:50:32.147  1359  1371 D BluetoothHeadset: Proxy object connected
08-22 10:50:32.147   873   890 D BluetoothHeadset: Proxy object connected
08-22 10:50:32.147  4037  4389 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.149  1359  1359 D HeadsetProfile: Bluetooth service connected
08-22 10:50:32.150  4037  4037 D HeadsetProfile: Bluetooth service connected
08-22 10:50:32.150  1934  1957 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.164   873   890 D BluetoothHeadset: Proxy object connected
,08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:32.468  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:32.475  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:32.479  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:32.480  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4ae4b00 added. We now have 8 listener(s)
,08-22 10:50:32.480  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:32.487   873  1960 D WifiService: setWifiEnabled: false pid=3971, uid=10000
,08-22 10:50:32.488   873  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 10:50:32.507  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:32.508   873  1679 D WifiService: setWifiEnabled: true pid=3971, uid=10000
,08-22 10:50:32.508   873  1679 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-22 10:50:32.525   873  1301 D WifiConfigStore: Loading config and enabling all networks 
,08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:32.538  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:32.541  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:32.562   873  1301 D WifiConfigStore: loaded 0 passpoint configs
08-22 10:50:32.563   873  1301 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-22 10:50:32.564   873  1301 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-22 10:50:32.565   873  1301 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 10:50:32.566   873  1301 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-22 10:50:32.566   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-22 10:50:32.566   873  1301 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-22 10:50:32.580   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-22 10:50:32.581   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-22 10:50:32.582   372   871 D CommandListener: Setting iface cfg
,08-22 10:50:32.584   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-22 10:50:32.584   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 10:50:32.641   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
,08-22 10:50:32.641   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-22 10:50:32.642   873  1301 E native  : do suspend true
,08-22 10:50:32.703   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:33.532  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:33.539  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:33.552  3971  4019 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-22 10:50:33.556  3971  4019 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 10:50:33.563  3971  4019 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8ab11a Bundle[{}]
,08-22 10:50:33.564  3971  4019 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 10:50:33.564  3971  4019 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-22 10:50:33.565  3971  4019 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 10:50:33.566  3971  4019 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-22 10:50:33.567  3971  4019 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-22 10:50:33.568  3971  4019 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 10:50:33.573  3971  4019 I System.out: Running OutgoingSocketThread
,08-22 10:50:33.576  3971  4406 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 459)
,08-22 10:50:33.578  3971  4406 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41429
,08-22 10:50:33.578  3971  4406 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 10:50:34.077   873  1301 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-22 10:50:34.161   873  1301 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.03 rxSuccessRate=0.03 delta 1000 -> 1000
,08-22 10:50:34.162   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-22 10:50:34.163   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:34.184   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-22 10:50:34.256   873  1301 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-22 10:50:34.259  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-22 10:50:34.576  3971  4019 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 460)
,08-22 10:50:34.577  3971  4019 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 460)
,08-22 10:50:34.589  3971  4019 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 465)
,08-22 10:50:34.591  3971  4019 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-22 10:50:34.592  3971  4019 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 466)
,08-22 10:50:34.601  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 10:50:34.601  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b101f39 added. We now have 2 listener(s)
,08-22 10:50:34.609  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 10:50:34.610  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:34.610  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:34.610  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.611  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e76d97e added. We now have 9 listener(s)
08-22 10:50:34.611  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:34.612  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:34.617  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:34.622  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:34.626  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:34.626  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:34.627  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:34.627  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2d172c added. We now have 3 listener(s)
08-22 10:50:34.628  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:34.629  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 10:50:34.629  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:34.629  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.629  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.629  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4a75f5 added. We now have 10 listener(s)
08-22 10:50:34.629  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:34.629  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:34.630  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:34.630  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:34.630  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:34.630  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.630  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:34.630  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 10:50:34.630  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b101f39 removed from the list
08-22 10:50:34.630  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:34.630  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e76d97e removed from the list
08-22 10:50:34.632  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:34.632  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:34.632  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:34.633  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.633  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:34.635  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.635  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:34.635  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.635  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e76d97e not in the list
08-22 10:50:34.635  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.635  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:34.637  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:34.637  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.637  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.637  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4a75f5 removed from the list
08-22 10:50:34.637  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:34.637  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.637  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.637  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:34.637  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2d172c removed from the list
08-22 10:50:34.638  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:34.638  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f230f8a added. We now have 2 listener(s)
08-22 10:50:34.640  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 10:50:34.640  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:34.640  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.641  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.641  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f65d9fb added. We now have 9 listener(s)
08-22 10:50:34.641  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:34.641  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 10:50:34.644  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:34.650  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:34.652  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:34.653  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:34.653  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:34.653  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@997c71 added. We now have 3 listener(s)
08-22 10:50:34.654  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:34.656  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 10:50:34.656  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:34.656  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.656  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.656  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5aa9a56 added. We now have 10 listener(s)
08-22 10:50:34.656  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:34.657  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:34.657  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:34.657  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 10:50:34.657  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:34.657  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:34.657  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:34.660  3971  4019 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-22 10:50:34.660  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 10:50:34.665  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 10:50:34.667  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 10:50:34.667  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 10:50:34.672  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 10:50:34.672  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:34.672  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-22 10:50:34.673  3971  4019 D BluetoothAdapter: STATE_ON
,08-22 10:50:34.679  4351  4387 D BtGatt.GattService: registerClient() - UUID=3dd59027-9f43-498a-be4d-3c331a703a2b
,08-22 10:50:34.680  4351  4367 D BtGatt.GattService: onClientRegistered() - UUID=3dd59027-9f43-498a-be4d-3c331a703a2b, clientIf=5
,08-22 10:50:34.682  3971  3983 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 10:50:34.683  4351  4361 D BtGatt.GattService: start scan with filters
,08-22 10:50:34.688  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:34.688  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 10:50:34.688  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:34.688  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 10:50:34.689  4351  4370 D BtGatt.ScanManager: handling starting scan
,08-22 10:50:34.692  4351  4370 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f5fd42f
,08-22 10:50:34.693  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:34.693  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 10:50:34.693  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:34.696  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:34.700  4351  4367 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 10:50:34.701  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.702  4351  4370 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 10:50:34.706  3971  4019 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 10:50:34.706  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:34.706  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 10:50:34.707  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:34.707  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 10:50:34.707  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 10:50:34.707  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 10:50:34.707  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:34.708  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 10:50:34.708  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 10:50:34.709  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:34.710  3971  4019 D BluetoothAdapter: STATE_ON
,08-22 10:50:34.711  4351  4361 D BtGatt.GattService: stopScan() - queue size =1
,08-22 10:50:34.713  4351  4386 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-22 10:50:34.714  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:34.715  4351  4367 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15,
08-22 10:50:34.715  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-22 10:50:34.715  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.715  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-22 10:50:34.716  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 10:50:34.716  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 10:50:34.716  4351  4370 D BtGatt.ScanManager: Starting BLE batch scan
08-22 10:50:34.717  4351  4370 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 10:50:34.719  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:34.719  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 10:50:34.719  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:34.720  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 10:50:34.721  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:34.724  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 10:50:34.724  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:34.724  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:34.728  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:34.728  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:34.728  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:34.728  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:34.729  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.729  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:34.729  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:34.729  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f230f8a removed from the list
08-22 10:50:34.729  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.729  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f65d9fb removed from the list
08-22 10:50:34.730  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:34.730  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.730  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.730  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.732  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.732  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:34.732  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.732  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f65d9fb not in the list
08-22 10:50:34.732  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.732  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.734  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:34.735  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.735  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.735  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5aa9a56 removed from the list
,08-22 10:50:34.736  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:34.736  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.736  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.736  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 10:50:34.737  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@997c71 removed from the list
,08-22 10:50:34.738  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-22 10:50:34.739  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 10:50:34.739  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4e05e2 added. We now have 2 listener(s),
,08-22 10:50:34.743  4351  4367 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-22 10:50:34.743  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.751  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 10:50:34.752  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:34.752  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.753  4351  4367 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-22 10:50:34.753  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.753  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-22 10:50:34.753  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cf8d73 added. We now have 9 listener(s)
,08-22 10:50:34.753  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:34.754  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:34.761  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:34.763  4351  4367 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 10:50:34.763  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.763  4351  4370 D BtGatt.ScanManager: stopping BLe Batch
,08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:34.766  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:34.768  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:34.768  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:34.768  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 10:50:34.768  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da48a9 added. We now have 3 listener(s)
08-22 10:50:34.769  4351  4367 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-22 10:50:34.769  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.770  4351  4370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-22 10:50:34.770  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 10:50:34.770  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 10:50:34.770  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:50:34.770  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 10:50:34.770  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:34.771  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aca9e2e added. We now have 10 listener(s)
,08-22 10:50:34.771  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:34.771  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 10:50:34.772  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:34.772  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-22 10:50:34.772  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:34.772  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 10:50:34.772  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:34.772  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:34.775  3971  4019 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-22 10:50:34.775  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 10:50:34.776  4351  4367 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 10:50:34.776  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.778  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-22 10:50:34.778  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
08-22 10:50:34.781   873  1301 D WifiConfigStore: Retrieve network priorities after PNO.
,08-22 10:50:34.783  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-22 10:50:34.784  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 10:50:34.784  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 10:50:34.786   873  1301 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 10:50:34.786   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 10:50:34.786   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-22 10:50:34.788  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 10:50:34.788  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 10:50:34.788  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
08-22 10:50:34.789  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:34.791  4351  4361 D BtGatt.GattService: registerClient() - UUID=be1c747d-7920-40a6-88c6-b7f127ee5699
08-22 10:50:34.792  4351  4367 D BtGatt.GattService: onClientRegistered() - UUID=be1c747d-7920-40a6-88c6-b7f127ee5699, clientIf=5
08-22 10:50:34.792  3971  3982 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-22 10:50:34.793  4351  4387 D BtGatt.GattService: start scan with filters
08-22 10:50:34.796  4351  4370 D BtGatt.ScanManager: handling starting scan
08-22 10:50:34.797  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 10:50:34.797  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:34.797  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:34.797  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 10:50:34.800   873  1301 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-22 10:50:34.801  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:34.801  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:34.801  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 10:50:34.804  4351  4367 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-22 10:50:34.804  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.804  4351  4370 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-22 10:50:34.809   372   871 D CommandListener: Setting iface cfg
08-22 10:50:34.809  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:34.809   873  1301 D WifiStateMachine: Start Dhcp Watchdog 3
08-22 10:50:34.810  4351  4367 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 10:50:34.810  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.810  4351  4370 D BtGatt.ScanManager: Starting BLE batch scan,
08-22 10:50:34.810  4351  4370 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-22 10:50:34.812  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 10:50:34.812  3971  4019 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-22 10:50:34.812  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:34.812  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:34.812  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:34.813  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:34.813  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:34.813  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 10:50:34.813  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:34.813  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b4e05e2 removed from the list
08-22 10:50:34.813  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.813  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cf8d73 removed from the list
,08-22 10:50:34.813  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:34.813  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:34.814  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.814  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 10:50:34.814  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:34.814  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:34.815  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.815  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:34.815  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.815  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cf8d73 not in the list
08-22 10:50:34.815  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 10:50:34.815  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:34.815  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:34.815  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:34.815  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 10:50:34.816  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:34.816   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
08-22 10:50:34.816  4351  4387 D BtGatt.GattService: stopScan() - queue size =1
,08-22 10:50:34.817  4351  4362 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 10:50:34.817  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 10:50:34.817  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-22 10:50:34.817  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:34.818  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:34.818  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 10:50:34.818  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:34.818  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 10:50:34.819  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:34.819  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 10:50:34.819  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.820  4351  4367 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-22 10:50:34.820  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.820  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:34.820  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:34.820  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 10:50:34.821  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 10:50:34.821  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.821  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.821  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aca9e2e removed from the list
08-22 10:50:34.821  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:34.821  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:34.821  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.821  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 10:50:34.821  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da48a9 removed from the list
08-22 10:50:34.822  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:34.822  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b666f3a added. We now have 2 listener(s)
08-22 10:50:34.824  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 10:50:34.824  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:34.824  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.824  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.824  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d37eb added. We now have 9 listener(s)
,08-22 10:50:34.824  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:34.825  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 10:50:34.825  4351  4367 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 10:50:34.825  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.827  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:34.829  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:34.831  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:34.831  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:50:34.831  4351  4367 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-22 10:50:34.831  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.832  4351  4370 D BtGatt.ScanManager: stopping BLe Batch
,08-22 10:50:34.832  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:34.832  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7163e1 added. We now have 3 listener(s)
08-22 10:50:34.832  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:34.833  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:50:34.834  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 10:50:34.834  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:34.834  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.834  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.834  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc4506 added. We now have 10 listener(s)
,08-22 10:50:34.834  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:50:34.835  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:34.835  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 10:50:34.835  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-22 10:50:34.835  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:50:34.835  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 10:50:34.837  4351  4367 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-22 10:50:34.837  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.837  4351  4370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 10:50:34.837  3971  4019 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-22 10:50:34.837  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 10:50:34.840  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 10:50:34.841  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-22 10:50:34.841  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 10:50:34.841  4351  4367 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 10:50:34.842  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.843  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 10:50:34.843  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 10:50:34.843   873  4410 D DhcpClient: Receive thread started
08-22 10:50:34.843  3971  4019 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 10:50:34.844  3971  4019 D BluetoothAdapter: STATE_ON
,08-22 10:50:34.846  4351  4387 D BtGatt.GattService: registerClient() - UUID=2cba061a-07d3-44ff-8c71-8863b0c85271
,08-22 10:50:34.846  4351  4367 D BtGatt.GattService: onClientRegistered() - UUID=2cba061a-07d3-44ff-8c71-8863b0c85271, clientIf=5
08-22 10:50:34.846  3971  3983 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-22 10:50:34.846  4351  4386 D BtGatt.GattService: start scan with filters
,08-22 10:50:34.848  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 10:50:34.848  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 10:50:34.848  4351  4370 D BtGatt.ScanManager: handling starting scan
08-22 10:50:34.848  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 10:50:34.848  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 10:50:34.850  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 10:50:34.850  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 10:50:34.851  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 10:50:34.852  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 10:50:34.853  4351  4367 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-22 10:50:34.853  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.854  4351  4370 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-22 10:50:34.856  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 10:50:34.856  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:34.856  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 10:50:34.856  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:34.856  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.856  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-22 10:50:34.856  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:34.856  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b666f3a removed from the list
08-22 10:50:34.856  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.856  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d37eb removed from the list
08-22 10:50:34.856  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 10:50:34.856  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 10:50:34.857  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.857  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 10:50:34.857  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.857  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:34.858  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.858  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:34.858  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.858  4351  4367 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-22 10:50:34.858  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15d37eb not in the list
08-22 10:50:34.858  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 10:50:34.858  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.858  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 10:50:34.858  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 10:50:34.859  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 10:50:34.859  4351  4370 D BtGatt.ScanManager: Starting BLE batch scan
,08-22 10:50:34.859  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-22 10:50:34.859  4351  4370 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-22 10:50:34.859  3971  4019 D BluetoothAdapter: STATE_ON
08-22 10:50:34.860  4351  4361 D BtGatt.GattService: stopScan() - queue size =1
08-22 10:50:34.860  4351  4387 D BtGatt.GattService: unregisterClient() - clientIf=5
08-22 10:50:34.860  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 10:50:34.861  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 10:50:34.861  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 10:50:34.861  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 10:50:34.861  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 10:50:34.861  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:34.862  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 10:50:34.862  3971  4019 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 10:50:34.862  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 10:50:34.862  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.863  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:34.863  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 10:50:34.863  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 10:50:34.863  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:34.864  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 10:50:34.864  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:34.864  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc4506 removed from the list
08-22 10:50:34.864  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 10:50:34.864  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.864  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.864  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 10:50:34.864  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f7163e1 removed from the list
08-22 10:50:34.864  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:34.865  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b47ab92 added. We now have 2 listener(s)
,08-22 10:50:34.866  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-22 10:50:34.866  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 10:50:34.866  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.866  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 10:50:34.867  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b6b963 added. We now have 9 listener(s)
08-22 10:50:34.867  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:34.867  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 10:50:34.869  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 10:50:34.869  4351  4367 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-22 10:50:34.869  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 10:50:34.871  3971  4019 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 10:50:34.873  3971  4019 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 10:50:34.873  3971  4019 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 10:50:34.873  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 10:50:34.873  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f9ae19 added. We now have 3 listener(s)
,08-22 10:50:34.874  4351  4367 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-22 10:50:34.874  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.874  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-22 10:50:34.875  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-22 10:50:34.875  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-22 10:50:34.875  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:50:34.875  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 10:50:34.875  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 10:50:34.875  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b0eede added. We now have 10 listener(s)
08-22 10:50:34.875  3971  4019 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 10:50:34.875  3971  4019 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 10:50:34.875  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 10:50:34.876  3971  4019 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 10:50:34.876  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:34.876  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.876  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 10:50:34.876  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:34.876  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b47ab92 removed from the list
,08-22 10:50:34.876  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 10:50:34.876  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b6b963 removed from the list
,08-22 10:50:34.876  3971  4019 D io.jxcore.node.ConnectivityMonitor: stop
08-22 10:50:34.876  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.876  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 10:50:34.877  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 10:50:34.877  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-22 10:50:34.877  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:34.877  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-22 10:50:34.877  3971  4019 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b6b963 not in the list
08-22 10:50:34.878  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 10:50:34.878  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:34.878  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 10:50:34.878  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-22 10:50:34.879  3971  4019 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 10:50:34.879  3971  4019 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b0eede removed from the list
08-22 10:50:34.879  3971  4019 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-22 10:50:34.879  3971  4019 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 10:50:34.879  3971  4019 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 10:50:34.879  3971  4019 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 10:50:34.879  3971  4019 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f9ae19 removed from the list
08-22 10:50:34.880  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-22 10:50:34.880  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-22 10:50:34.880  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-22 10:50:34.880  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 10:50:34.880  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-22 10:50:34.880  3971  4019 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 10:50:34.881  4351  4367 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-22 10:50:34.881  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.881  4351  4370 D BtGatt.ScanManager: stopping BLe Batch
08-22 10:50:34.885  3971  4411 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 473, name: My test thread name)
,08-22 10:50:34.885  3971  4411 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 473, thread name: My test thread name)
08-22 10:50:34.885  3971  4411 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 473, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-22 10:50:34.887  4351  4367 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-22 10:50:34.887  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-22 10:50:34.887  4351  4370 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-22 10:50:34.890  3971  4412 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 475, name: My test thread name)
,08-22 10:50:34.890  3971  4412 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 475, thread name: My test thread name)
08-22 10:50:34.890  3971  4412 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 475, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-22 10:50:34.892  4351  4367 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-22 10:50:34.892  4351  4367 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-22 10:50:34.893  3971  4019 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-22 10:50:34.893  3971  4019 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-22 10:50:34.893  3971  4019 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 10:50:34.893  3971  4019 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-22 10:50:34.893  3971  4019 D com.test.thalitest.ThaliTestRunner: Total duration: 22799 ms
,08-22 10:50:34.896  3971  4019 I jxcore-log: Total number of executed tests:  80
08-22 10:50:34.896  3971  4019 I jxcore-log: 
,08-22 10:50:34.896  3971  4019 I jxcore-log: Number of passed tests:  80
08-22 10:50:34.896  3971  4019 I jxcore-log: 
,08-22 10:50:34.896  3971  4019 I jxcore-log: Number of failed tests:  0
08-22 10:50:34.896  3971  4019 I jxcore-log: 
,08-22 10:50:34.897  3971  4019 I jxcore-log: Number of ignored tests:  0
08-22 10:50:34.897  3971  4019 I jxcore-log: 
08-22 10:50:34.897  3971  4019 I jxcore-log: Total duration:  22799
08-22 10:50:34.897  3971  4019 I jxcore-log: 
08-22 10:50:34.897  3971  4019 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 10:50:34.897  3971  4019 I jxcore-log: 
,08-22 10:50:34.900  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.900  3971  4019 I jxcore-log: 
08-22 10:50:34.903  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.903  3971  4019 I jxcore-log: 
08-22 10:50:34.904  3971  3971 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-22 10:50:34.905  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.905  3971  4019 I jxcore-log: 
08-22 10:50:34.906  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.906  3971  4019 I jxcore-log: 
,08-22 10:50:34.906  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.906  3971  4019 I jxcore-log: 
08-22 10:50:34.907  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.907  3971  4019 I jxcore-log: 
,08-22 10:50:34.909  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.909  3971  4019 I jxcore-log: 
08-22 10:50:34.910  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.910  3971  4019 I jxcore-log: 
08-22 10:50:34.911  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.911  3971  4019 I jxcore-log: 
08-22 10:50:34.911  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.911  3971  4019 I jxcore-log: 
08-22 10:50:34.912  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.912  3971  4019 I jxcore-log: 
08-22 10:50:34.912  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:34.912  3971  4019 I jxcore-log: 
08-22 10:50:34.913  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.913  3971  4019 I jxcore-log: 
08-22 10:50:34.913  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.913  3971  4019 I jxcore-log: 
,08-22 10:50:34.914  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.914  3971  4019 I jxcore-log: 
08-22 10:50:34.914  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:34.914  3971  4019 I jxcore-log: 
08-22 10:50:34.915  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.915  3971  4019 I jxcore-log: 
08-22 10:50:34.916  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.916  3971  4019 I jxcore-log: 
,08-22 10:50:34.918  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.918  3971  4019 I jxcore-log: 
,08-22 10:50:34.918  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.918  3971  4019 I jxcore-log: 
08-22 10:50:34.919  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.919  3971  4019 I jxcore-log: 
08-22 10:50:34.919  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.919  3971  4019 I jxcore-log: 
,08-22 10:50:34.920  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.920  3971  4019 I jxcore-log: 
,08-22 10:50:34.920  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 10:50:34.920  3971  4019 I jxcore-log: 
,08-22 10:50:34.921  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.921  3971  4019 I jxcore-log: 
,08-22 10:50:34.922  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.922  3971  4019 I jxcore-log: 
,08-22 10:50:34.923  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.923  3971  4019 I jxcore-log: 
,08-22 10:50:34.924  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.924  3971  4019 I jxcore-log: 
08-22 10:50:34.924  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.924  3971  4019 I jxcore-log: 
08-22 10:50:34.925  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.925  3971  4019 I jxcore-log: 
08-22 10:50:34.925  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 10:50:34.925  3971  4019 I jxcore-log: 
,08-22 10:50:34.928   873  1301 E native  : do suspend false
,08-22 10:50:34.938   873  2050 D DhcpClient: Broadcasting DHCPDISCOVER
,08-22 10:50:34.955   873  4410 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-22 10:50:34.956   873  2050 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-22 10:50:34.957   873  2050 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-22 10:50:34.992   873  4410 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-22 10:50:34.993   873  2050 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-22 10:50:34.998   372   871 D CommandListener: Setting iface cfg
,08-22 10:50:35.004   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-22 10:50:35.008   873  1301 E native  : do suspend true
,08-22 10:50:35.009   873  2050 D DhcpClient: Scheduling renewal in 86399s
,08-22 10:50:35.026   873  1301 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-22 10:50:35.027   873  1301 D WifiConfigStore: No blacklist allowed without epno enabled
,08-22 10:50:35.028   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-22 10:50:35.029   873  1303 D ConnectivityService: Adding iface wlan0 to network 102
,08-22 10:50:35.036   873  1301 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 10:50:35.072   873  1303 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-22 10:50:35.073   873  1303 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-22 10:50:35.076   873  1303 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-22 10:50:35.077   873  1303 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-22 10:50:35.079   873  1303 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-22 10:50:35.086   873  1303 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-22 10:50:35.091   873  1303 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-22 10:50:35.091   873  1303 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-22 10:50:35.091   873  1301 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: [],
08-22 10:50:35.092   873  1301 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,08-22 10:50:35.092   873  1303 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-22 10:50:35.092   873  1303 D ConnectivityService:    accepting network in place of null
,08-22 10:50:35.094   873  1303 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-22 10:50:35.135   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:35.152   873  4409 D NetlinkSocketObserver: NeighborEvent{elapsedMs=156183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-22 10:50:35.201   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-22 10:50:35.204   873  1303 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-22 10:50:35.204   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:35.205   873  1303 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-22 10:50:35.212   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:50:35.224  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:50:35.225  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 10:50:35.225  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-22 10:50:35.226  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 10:50:35.226  3971  4019 I jxcore-log: 
08-22 10:50:35.227  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:35.227  3971  4019 I jxcore-log: 
,08-22 10:50:35.235   873  4408 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,08-22 10:50:35.265  1710  1710 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-22 10:50:35.273  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-22 10:50:35.275  1710  1710 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-22 10:50:35.276  4127  4127 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-22 10:50:35.281  1710  4426 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-22 10:50:35.281  1710  4426 W BaseAppContext: Using Auth Proxy for data requests.
,08-22 10:50:35.283  4127  4127 D SprintDMHelper: simOperator: 
,08-22 10:50:35.283  4127  4127 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-22 10:50:35.291  1710  4426 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-22 10:50:35.294  1710  2485 I iu.UploadsManager: num queued entries: 0
,08-22 10:50:35.314  1710  2485 I iu.UploadsManager: num updated entries: 0
,08-22 10:50:35.315  1710  2485 I iu.SyncManager: NEXT; no task
,08-22 10:50:35.320  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:35.321  1495  1495 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-22 10:50:35.322  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 10:50:35.323  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:35.323  3971  4019 I jxcore-log: 
,08-22 10:50:35.330   873  4408 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 08:50:35 GMT], X-Android-Received-Millis=[1471855835329], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471855835302]}
08-22 10:50:35.331   873  1303 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-22 10:50:35.331   873  1303 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-22 10:50:35.332   873  1303 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-22 10:50:35.333   873  1303 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 10:50:35.357  3776  4423 V KeepSync: Connecting to GoogleApiClient
,08-22 10:50:35.357   873  1984 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-22 10:50:35.363  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 10:50:35.364  3971  4019 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 10:50:35.364  3971  4019 I jxcore-log: 
,08-22 10:50:35.376  1495  3217 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-22 10:50:35.376  1495  3217 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-22 10:50:35.376  1495  3217 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:50:35.376  1495  3217 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:35.393  1710  4426 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-22 10:50:35.403  1495  2174 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-22 10:50:35.403  1495  2174 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-22 10:50:35.403  1495  2174 I GLSUser : [GLSUser] Extracting token using key: Auth
08-22 10:50:35.403  1495  2174 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:35.411  1710  4434 V BaseAuthAsyncOperation: access token request failed
,08-22 10:50:35.412  3776  4423 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-22 10:50:35.426  2852  4428 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-22 10:50:35.455  1495  1506 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-22 10:50:35.455  1495  1506 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-22 10:50:35.456  1495  1506 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-22 10:50:35.456  1495  1506 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-22 10:50:35.473  3776  4423 E KeepSync: IOException
08-22 10:50:35.473  3776  4423 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-22 10:50:35.473  3776  4423 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-22 10:50:35.473  3776  4423 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-22 10:50:35.473  3776  4423 E KeepSync: 	... 10 more
,08-22 10:50:35.473  3776  4423 W KeepSync: Sync result 2
,08-22 10:50:35.478   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 136198, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-22 10:50:35.591  4413  4413 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-22 10:50:35.596  4413  4413 D AndroidRuntime: CheckJNI is OFF
,08-22 10:50:35.642  4413  4413 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-22 10:50:35.685  4413  4413 I Radio-JNI: register_android_hardware_Radio DONE
,08-22 10:50:35.709  4413  4413 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-22 10:50:35.718   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-22 10:50:35.719   873   886 I ActivityManager: Killing 3971:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-22 10:50:35.807   873  1968 D GraphicsStats: Buffer count: 2
,08-22 10:50:35.807   873  1929 I WindowState: WIN DEATH: Window{860d188 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-22 10:50:35.808   873  1302 D WifiService: Client connection lost with reason: 4
,08-22 10:50:35.869   873   896 W PackageSettings: Skipping PackageSetting{688cc60 com.example.hello/10273} due to missing metadata
,08-22 10:50:35.907   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-22 10:50:35.908   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-22 10:50:35.909   873   896 I art     : Starting a blocking GC Explicit
,08-22 10:50:35.910   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-22 10:50:35.910   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-22 10:50:35.910   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:35.910   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:35.910   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 10:50:35.910   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-22 10:50:35.911   873   886 I ActivityManager:   Force finishing activity ActivityRecord{c36dd09 u0 com.test.thalitest/.MainActivity t2}
,08-22 10:50:35.919   873   883 W ActivityManager: Spurious death for ProcessRecord{8f3503f 0:com.test.thalitest/u0a0}, curProc for 3971: null
,08-22 10:50:35.960   873   896 I art     : Explicit concurrent mark sweep GC freed 20460(1336KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.186ms total 51.511ms
,08-22 10:50:35.986   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-22 10:50:35.990  4413  4413 I art     : System.exit called, status: 0
,08-22 10:50:35.990  4413  4413 I AndroidRuntime: VM exiting with result code 0.
,08-22 10:50:35.992   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-22 10:50:36.015   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-22 10:50:36.023  1853  1853 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-22 10:50:36.025  4351  4351 D BluetoothMapAppObserver: onReceive
,08-22 10:50:36.025  4351  4351 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-22 10:50:36.026  2148  2247 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 10:50:36.027   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 10:50:36.027  3836  3836 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-22 10:50:36.040  1853  4446 I Keyboard.Facilitator.DecoderInitializer: run()
,08-22 10:50:36.052  1934  1934 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-22 10:50:36.056   873  1679 I ActivityManager: Start proc 4449:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-22 10:50:36.094  1853  4446 I Decoder : createOrResetDecoder
,08-22 10:50:36.103   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 10:50:36.108  1495  1495 I ConfigService: onCreate
,08-22 10:50:36.111  4449  4449 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-22 10:50:36.121  1853  4446 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-22 10:50:36.134   873  1974 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3971 uid 10000
,08-22 10:50:36.135  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-22 10:50:36.154  1945  2055 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-22 10:50:36.158   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-22 10:50:36.159   873   885 E PackageManager: Failed to write settings, restoring backup
08-22 10:50:36.159   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-22 10:50:36.159   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-22 10:50:36.159   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-22 10:50:36.159   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-22 10:50:36.159   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-22 10:50:36.159   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.159   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.159   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 10:50:36.164   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-22 10:50:36.164   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-22 10:50:36.164   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:36.164   873   886 E DropBoxManagerService: 	... 13 more
,08-22 10:50:36.167   873  1944 I ActivityManager: Start proc 4466:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-22 10:50:36.167  1945  2055 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-22 10:50:36.167  1945  2055 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1945
08-22 10:50:36.167  1945  2055 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.167  1945  2055 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 10:50:36.170   873  1983 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-22 10:50:36.170   873  4471 E DropBoxManagerService: Can't write: system_app_crash
08-22 10:50:36.170   873  4471 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:36.170   873  4471 E DropBoxManagerService: 	... 5 more
,08-22 10:50:36.173  4449  4449 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-22 10:50:36.177  1945  2055 I Process : Sending signal. PID: 1945 SIG: 9
,08-22 10:50:36.178  1853  4446 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-22 10:50:36.181  1853  4446 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-22 10:50:36.181  1853  4446 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-22 10:50:36.183  1853  4446 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-22 10:50:36.183  1853  4446 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-22 10:50:36.184  1853  4446 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-22 10:50:36.184  1853  4446 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-22 10:50:36.185  1853  4446 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-22 10:50:36.185  1853  4446 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-22 10:50:36.185  1853  4446 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-22 10:50:36.185  1853  4446 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-22 10:50:36.185  1853  4446 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-22 10:50:36.185  1853  4446 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-22 10:50:36.200  4449  4480 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-22 10:50:36.202   873  1679 I ActivityManager: Start proc 4481:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-22 10:50:36.240  4481  4481 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-22 10:50:36.278  1495  1495 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-22 10:50:36.279  1495  1495 D AndroidRuntime: Shutting down VM
08-22 10:50:36.279  1495  1495 E AndroidRuntime: FATAL EXCEPTION: main
08-22 10:50:36.279  1495  1495 E AndroidRuntime: Process: com.google.process.gapps, PID: 1495
08-22 10:50:36.279  1495  1495 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-22 10:50:36.279  1495  1495 E AndroidRuntime: 	... 8 more
,08-22 10:50:36.282   873  4498 E DropBoxManagerService: Can't write: system_app_crash
08-22 10:50:36.282   873  4498 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:36.282   873  4498 E DropBoxManagerService: 	... 5 more
,08-22 10:50:36.283  1495  1495 I Process : Sending signal. PID: 1495 SIG: 9
,08-22 10:50:36.306   873  1983 D GraphicsStats: Buffer count: 1
,08-22 10:50:36.306   873  1968 I WindowState: WIN DEATH: Window{1f6f940 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-22 10:50:36.314   873  1302 D WifiService: Client connection lost with reason: 4
,08-22 10:50:36.320  4449  4463 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.320  4449  4463 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.321  4449  4463 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 10:50:36.322   873  1679 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1945) has died
,08-22 10:50:36.323   873  1679 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-22 10:50:36.326   873  1679 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-22 10:50:36.331   873  1983 I ActivityManager: Process com.google.process.gapps (pid 1495) has died
,08-22 10:50:36.331   873  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-22 10:50:36.331   873  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-22 10:50:36.331   873  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
,08-22 10:50:36.331   873  1983 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,08-22 10:50:36.344  1710  1710 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-22 10:50:36.344   873  1967 I ActivityManager: Start proc 4501:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-22 10:50:36.355   873   886 I ActivityManager: Start proc 4513:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-22 10:50:36.373  4501  4501 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-22 10:50:36.385  4501  4501 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-22 10:50:36.387  4501  4501 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:36.387  4501  4501 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:36.387  4501  4501 D AndroidRuntime: Shutting down VM
08-22 10:50:36.387  4501  4501 E AndroidRuntime: FATAL EXCEPTION: main
08-22 10:50:36.387  4501  4501 E AndroidRuntime: Process: com.google.process.gapps, PID: 4501
08-22 10:50:36.38,7  4501  4501 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-22 10:50:36.387  4501  4501 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22, 10:50:36.387  4501  4501 E AndroidRuntime: 	... 10 more
08-22 10:50:36.390   873  4527 E DropBoxManagerService: Can't write: system_app_crash
08-22 10:50:36.390   873  4527 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:36.390   873  4527 E DropBoxManagerService: 	... 5 more
08-22 10:50:36.391  4501  4501 I Process : Sending signal. PID: 4501 SIG: 9
,08-22 10:50:36.407  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-22 10:50:36.407  4513  4513 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:36.407  4513  4513 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:36.407  1710  1710 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-22 10:50:36.407  4513  4513 D AndroidRuntime: Shutting down VM
08-22 10:50:36.410  1710  1710 D ChimeraCfgMgr: Loading module com.google.android.gms.games from AP,K com.google.android.play.games
08-22 10:50:36.410  1710  1710 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-22 10:50:36.413  1710  4528 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-22 10:50:36.415  4513  4513 E AndroidRuntime: FATAL EXCEPTION: main
08-22 10:50:36.415  4513  4513 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4513
08-22 10:50:36.415  4513  4513 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 10:50:36.415  4513  4513 E AndroidRuntime: 	... 10 more
08-22 10:50:36.418   873  1475 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-22 10:50:36.418  4513  4513 I Process : Sending signal. PID: 4513 SIG: 9
08-22 10:50:36.419   873  4530 E DropBoxManagerService: Can't write: system_app_crash
08-22 10:50:36.419   873  4530 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:36.419   873  4530 E DropBoxManagerService: 	... 5 more
08-22 10:50:36.427  1710  4528 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-22 10:50:36.427  1710  4528 E AndroidRuntime: Process: com.google.android.gms, PID: 1710
08-22 10:50:36.427  1710  4528 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-22 10:50:36.427  1710  4528 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-22 10:50:36.429  1710  4528 I Process : Sending signal. PID: 1710 SIG: 9
08-22 10:50:36.429   873  1974 I ActivityManager: Process com.google.process.gapps (pid 4501) has died
08-22 10:50:36.429   873  1974 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{e57f8f1 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
08-22 10:50:36.430   873  4532 E DropBoxManagerService: Can't write: system_app_crash
08-22 10:50:36.430   873  4532 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:36.430   873  4532 E DropBoxManagerService: 	... 5 more
08-22 10:50:36.430   873  1974 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{d1eb759 u0 com.google.android.gms/.config.ConfigService}
08-22 10:50:36.430   873  1974 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{784edf7 u0 com.google.android.gms/.gcm.GcmService}
08-22 10:50:36.430   873  1974 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{6844efe u0 com.google.android.gms/.auth.GetToken}
08-22 10:50:36.435  4449  4463 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-22 10:50:36.441   873  1974 I ActivityManager: Start proc 4533:com.google.process.gapps/u0a11 for restart com.google.process.gapps
08-22 10:50:36.442   873  1679 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4513) has died
08-22 10:50:36.443   873  1679 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-22 10:50:36.447  2014  4531 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-22 10:50:36.458   873   886 I ActivityManager: Start proc 4545:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-22 10:50:36.491  4533  4533 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
08-22 10:50:36.495  2014  4531 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-22 10:50:36.506  2014  4531 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-22 10:50:36.507  2014  4531 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-22 10:50:36.507  2014  4531 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2014
08-22 10:50:36.507  2014  4531 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.507  2014  4531 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: Can't write: system_app_crash
08-22 10:50:36.509   873  4557 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-22 10:50:36.509   873  4557 E DropBoxManagerService: 	... 5 more
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-22 10:50:36.509  4545  4545 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```
