#### Test 796897752095895_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-08 12:02:50.943  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 12:02:50.951  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 12:02:50.953  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 12:02:50.971  1511  2064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-08 12:02:50.971  1511  2064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-08 12:02:50.971  1511  2064 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:02:50.971  1511  2064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 12:02:50.985  2599  2599 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-08 12:02:50.985  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-08 12:02:50.985  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
08-08 12:02:51.536  3328  3328 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-08 12:02:51.541  3328  3328 D AndroidRuntime: CheckJNI is OFF
08-08 12:02:51.577  3328  3328 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-08 12:02:51.622  3328  3328 I Radio-JNI: register_android_hardware_Radio DONE
08-08 12:02:51.643  3328  3328 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-08 12:02:51.648   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 12:02:51.703  1833  1848 W SearchService: Abort, client detached.
08-08 12:02:51.716  3328  3328 D AndroidRuntime: Shutting down VM
08-08 12:02:51.724  1833  2158 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@d85861c
08-08 12:02:51.724  1833  2166 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-08 12:02:51.725  1833  1833 I HotwordDetector: Closing mic
08-08 12:02:51.751   873  1691 I ActivityManager: Start proc 3337:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-08 12:02:51.762  1833  1833 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-08 12:02:51.780   376  2168 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-08 12:02:51.782   376  2168 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-08 12:02:51.790   376  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-08 12:02:51.794  1833  2165 I MicroRecognitionRnrImpl: Detection finished
08-08 12:02:51.794  1833  2162 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-08 12:02:51.837  3337  3337 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-08 12:02:51.870  3337  3337 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-08 12:02:51.959  3337  3337 I LibraryLoader: Time to load native libraries: 82 ms (timestamps 1476-1558)
08-08 12:02:51.959  3337  3337 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-08 12:02:51.987  3337  3337 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8f3333e}
08-08 12:02:51.987  3337  3337 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 12:02:51.988  3337  3337 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 12:02:51.995  3337  3337 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-08 12:02:51.996  3337  3337 E SysUtils: ApplicationContext is null in ApplicationStatus
08-08 12:02:52.041  3337  3352 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-08 12:02:52.051  3337  3337 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-08 12:02:52.061  3337  3337 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 12:02:52.061  3337  3337 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 12:02:52.061  3337  3337 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 12:02:52.061  3337  3337 I Adreno  : Build Date                       : 10/20/15
08-08 12:02:52.061  3337  3337 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 12:02:52.061  3337  3337 I Adreno  : Local Branch                     : M14
08-08 12:02:52.061  3337  3337 I Adreno  : Remote Branch                    : 
08-08 12:02:52.061  3337  3337 I Adreno  : Remote Branch                    : 
08-08 12:02:52.061  3337  3337 I Adreno  : Reconstruct Branch               : 
08-08 12:02:52.148   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bbf4cd1:true
08-08 12:02:52.192  3337  3337 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-08 12:02:52.208  3337  3337 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-08 12:02:52.256  3337  3375 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-08 12:02:52.267  3337  3361 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-08 12:02:52.289  3337  3375 I OpenGLRenderer: Initialized EGL, version 1.4
08-08 12:02:52.341   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +623ms
08-08 12:02:52.351  1661  1661 I Keyboard.Facilitator: onFinishInput()
08-08 12:02:52.415  3337  3337 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3337
08-08 12:02:52.534  3337  3337 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-08 12:02:52.543   873  1691 I ActivityManager: Killing 2705:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
08-08 12:02:52.570   873  1691 I ActivityManager: Killing 3002:com.qualcomm.telephony/1001 (adj 15): empty #18
08-08 12:02:52.744  3337  3378 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1684014800
08-08 12:02:52.778  3337  3378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 12:02:52.778  3337  3378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 12:02:52.778  3337  3378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 12:02:52.778  3337  3378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 12:02:52.778  3337  3378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-08 12:02:52.778  3337  3378 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@925262 added. We now have 1 listener(s)
08-08 12:02:52.786  3337  3378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-08 12:02:52.790  3337  3378 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 12:02:52.791  3337  3378 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 12:02:52.792  3337  3378 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-08 12:02:52.800  3337  3378 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cd25f29 added. We now have 1 listener(s)
08-08 12:02:52.800  3337  3378 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 12:02:52.803   873  1313 D WifiService: New client listening to asynchronous messages
08-08 12:02:52.804  3337  3378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 12:02:52.804  3337  3378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-08 12:02:52.804  3337  3378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-08 12:02:52.805  3337  3378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-08 12:02:52.805  3337  3378 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-08 12:02:52.806  3337  3378 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:02:52.806  3337  3378 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-08 12:02:52.808  3337  3378 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:02:52.808  3337  3378 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:02:52.808  3337  3378 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-08 12:02:52.808  3337  3378 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 12:02:52.809  3337  3378 I io.jxcore.node.LifeCycleMonitor: start: OK
08-08 12:02:52.911  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:02:52.917  3337  3337 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 12:02:53.428  3337  3346 I art     : Background sticky concurrent mark sweep GC freed 78336(7MB) AllocSpace objects, 17(1584KB) LOS objects, 28% free, 23MB/32MB, paused 884us total 191.640ms
,08-08 12:02:54.160  3337  3387 W jxcore-log: Initializing JXcore engine
08-08 12:02:54.160  3337  3387 W jxcore-log: JXcore engine is ready
,08-08 12:02:54.201  3387  3387 W Thread-290: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-08 12:02:54.201  3387  3387 W Thread-290: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10650]" dev="sockfs" ino=10650 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-08 12:02:54.201  3387  3387 W Thread-290: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-08 12:02:54.201  3387  3387 W Thread-290: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24228]" dev="sockfs" ino=24228 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-08 12:02:54.218  3337  3387 W jxcore-log: Starting JXcore engine
,08-08 12:02:54.313  3337  3387 W jxcore-log: Platform android
08-08 12:02:54.313  3337  3387 W jxcore-log: 
08-08 12:02:54.313  3337  3387 W jxcore-log: Process ARCH arm
08-08 12:02:54.313  3337  3387 W jxcore-log: 
,08-08 12:02:54.589  3337  3387 I jxcore-log: JXcore Cordova bridge is ready!
08-08 12:02:54.589  3337  3387 I jxcore-log: 
,08-08 12:02:54.590  3337  3387 W jxcore-log: JXcore engine is started
,08-08 12:02:54.606  3337  3378 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-08 12:02:54.616  3337  3337 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-08 12:03:10.469  3337  3387 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-08 12:03:10.469  3337  3387 I jxcore-log: 
,08-08 12:03:10.471  3337  3387 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-08 12:03:10.471  3337  3387 I jxcore-log: 
,08-08 12:03:10.474  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:10.475  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 12:03:10.476  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:10.477  3337  3387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 12:03:10.484  3337  3387 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-08 12:03:10.484  3337  3387 I jxcore-log: 
,08-08 12:03:10.488  3337  3387 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-08 12:03:10.488  3337  3387 I jxcore-log: 
,08-08 12:03:10.823  3337  3387 D ExecuteNativeTests: Running unit tests
,08-08 12:03:10.883  3337  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-08 12:03:10.884  3337  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed added. We now have 2 listener(s)
,08-08 12:03:10.885  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
08-08 12:03:10.885  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-08 12:03:10.885  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 12:03:10.885  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 12:03:10.885  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 added. We now have 2 listener(s)
,08-08 12:03:10.885  3337  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 12:03:10.885  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 12:03:10.888  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:03:10.889  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:10.889  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 12:03:10.889  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:10.889  3337  3387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:10.889  3337  3387 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 12:03:10.891  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-08 12:03:10.892  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-08 12:03:10.892  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 12:03:10.892  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:10.893  3337  3387 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-08 12:03:10.893  3337  3387 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 12:03:10.893  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 12:03:10.893  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 12:03:10.893  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 12:03:10.894  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.894  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.894  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.894  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.894  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.895  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 12:03:10.895  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 12:03:10.895  3337  3387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed removed from the list
,08-08 12:03:10.895  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 12:03:10.895  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 removed from the list
08-08 12:03:10.895  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.895  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.896  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.896  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.896  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.896  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.896  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 12:03:10.896  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.898  3337  3387 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-08 12:03:10.898  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.898  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.898  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.898  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.898  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.899  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.899  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.899  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.899  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list,
08-08 12:03:10.899  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.899  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.899  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.899  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.899  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.899  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.899  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.899  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.899  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 12:03:10.905  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 12:03:10.906  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 12:03:10.906  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.907  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.907  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.907  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.907  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.907  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.907  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.907  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.907  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.907  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.907  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.907  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.907  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.907  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.908  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.908  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.908  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.908  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.908  3337  3387 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 12:03:10.910  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:03:10.911  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:10.911  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:10.911  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.911  3337  3387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:10.912  3337  3387 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 12:03:10.912  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 12:03:10.912  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 12:03:10.912  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 12:03:10.912  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:03:10.912  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 12:03:10.912  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:10.915  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 12:03:10.915  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 12:03:10.915  3337  3387 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 12:03:10.915  3337  3387 I io.jxcore.node.ConnectionHelper: start: OK
08-08 12:03:10.915  3337  3337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 12:03:10.916  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.916  3337  3387 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
08-08 12:03:10.917  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.917  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.917  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 12:03:10.917  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.917  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 12:03:10.917  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 12:03:10.917  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 12:03:10.917  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 12:03:10.917  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 12:03:10.918  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 12:03:10.918  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 12:03:10.918  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 12:03:10.919  3337  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 12:03:10.919  3337  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 12:03:10.919  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.919  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.919  3337  3337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 12:03:10.919  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 12:03:10.919  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.919  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.919  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.919  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.919  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.919  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.919  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.920  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.920  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.920  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.920  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.921  3337  3387 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 12:03:10.921  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:03:10.922  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:10.922  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:10.922  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.922  3337  3387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:10.922  3337  3387 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 12:03:10.922  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 12:03:10.922  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 12:03:10.922  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 12:03:10.922  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:03:10.923  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 12:03:10.923  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:10.924  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 12:03:10.924  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 12:03:10.924  3337  3387 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-08 12:03:10.924  3337  3387 I io.jxcore.node.ConnectionHelper: start: OK
08-08 12:03:10.924  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.924  3337  3337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 12:03:10.924  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.924  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-08 12:03:10.924  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.924  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 12:03:10.924  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 12:03:10.924  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 12:03:10.924  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 12:03:10.924  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 12:03:10.924  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 12:03:10.925  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 12:03:10.925  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 12:03:10.925  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.925  3337  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 12:03:10.925  3337  3387 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-08 12:03:10.925  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.925  3337  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 12:03:10.925  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.925  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.925  3337  3337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 12:03:10.925  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.925  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 12:03:10.926  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.926  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.926  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.926  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.926  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.926  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.926  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.926  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.926  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.926  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.926  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.927  3337  3387 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-08 12:03:10.927  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.927  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.927  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.927  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.927  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.927  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.927  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.927  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.927  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.928  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.928  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.928  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.928  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.928  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.928  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.928  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.928  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.928  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.929  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 12:03:10.929  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.929  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.929  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.929  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.929  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.929  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.929  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.931  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.931  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.931  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.931  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.931  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.931  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.931  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.932  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.932  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.932  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.932  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.932  3337  3387 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-08 12:03:10.932  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.932  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.932  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.933  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.933  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.933  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.933  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.933  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.933  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.933  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 12:03:10.933  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.933  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.933  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.933  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.933  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.933  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.933  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.933  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.934  3337  3387 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-08 12:03:10.934  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.934  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.934  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.934  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.934  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.934  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.934  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.934  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.934  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.934  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.934  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.934  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.934  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.934  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.935  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.935  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.935  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.935  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.935  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 12:03:10.935  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 12:03:10.935  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 12:03:10.935  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 12:03:10.936  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 12:03:10.936  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 12:03:10.936  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.936  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.936  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.936  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.936  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.936  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.936  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.936  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.936  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.936  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.936  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.936  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.936  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.936  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.937  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.937  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.937  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.937  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.937  3337  3387 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 12:03:10.937  3337  3387 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 12:03:10.938  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-08 12:03:10.940  3337  3387 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 12:03:10.940  3337  3387 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-08 12:03:10.940  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 12:03:10.940  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 12:03:10.940  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 12:03:10.940  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 12:03:10.940  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 12:03:10.940  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 12:03:10.940  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-08 12:03:10.941  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 12:03:10.942  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 12:03:10.942  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 12:03:10.942  3337  3387 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-08 12:03:10.942  3337  3387 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 12:03:10.942  3337  3387 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-08 12:03:10.942  3337  3387 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 12:03:10.942  3337  3387 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 12:03:10.942  3337  3387 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-08 12:03:10.942  3337  3387 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 12:03:10.943  3337  3387 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 12:03:10.943  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-08 12:03:10.944  3337  3387 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-08 12:03:10.944  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-08 12:03:10.944  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-08 12:03:10.944  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-08 12:03:10.945  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-08 12:03:10.945  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-08 12:03:10.945  3337  3387 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-08 12:03:10.945  3337  3387 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 12:03:10.945  3337  3387 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-08 12:03:10.946  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.946  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.946  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.946  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.946  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.946  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.946  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-08 12:03:10.946  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.946  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.947  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.947  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.947  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.947  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.947  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.947  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.947  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.947  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.948  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.948  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.948  3337  3387 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-08 12:03:10.949  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.949  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.949  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.949  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.949  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.949  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.949  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.949  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.949  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.949  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.949  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.949  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.949  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.949  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.950  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.950  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.950  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.950  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.950  3337  3387 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-08 12:03:10.950  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.951  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.951  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.951  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.951  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.951  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.952  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.952  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.953  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.953  3337  3395 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 354
08-08 12:03:10.953  3337  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 354)
08-08 12:03:10.953  3337  3394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 354)
08-08 12:03:10.953  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.954  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.954  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.954  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.954  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.955  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.955  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.955  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.955  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.955  3337  3387 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-08 12:03:10.955  3337  3387 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-08 12:03:10.955  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 12:03:10.955  3337  3387 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-08 12:03:10.956  3337  3387 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 12:03:10.956  3337  3387 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-08 12:03:10.956  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 12:03:10.956  3337  3387 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-08 12:03:10.956  3337  3387 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 12:03:10.956  3337  3387 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 12:03:10.956  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 12:03:10.956  3337  3387 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-08 12:03:10.956  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.956  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.956  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.956  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.956  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.956  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.956  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.957  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.957  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.957  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.957  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.957  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.957  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.957  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.957  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.957  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.957  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.957  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.958  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.958  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.958  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.958  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.958  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.958  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.958  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.958  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.958  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.958  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.958  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.958  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.958  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.958  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.958  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.958  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.958  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.958  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.959  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.959  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.959  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.959  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.959  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.959  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.959  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.959  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.959  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.959  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.959  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.959  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.959  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.959  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.959  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.961  3337  3387 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-08 12:03:10.961  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:03:10.961  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-08 12:03:10.962  3337  3387 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 12:03:10.962  3337  3337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 12:03:10.962  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 12:03:10.962  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.962  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-08 12:03:10.962  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.962  3337  3387 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-08 12:03:10.962  3337  3337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-08 12:03:10.962  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.963  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.963  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 12:03:10.963  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 12:03:10.963  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 12:03:10.963  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.963  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.963  3337  3387 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 12:03:10.963  3337  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 12:03:10.963  3337  3337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 12:03:10.964  333,7  3337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 12:03:10.964  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.964  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.964  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.964  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.964  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.964  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.964  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.964  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.964  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.964  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.964  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.964  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.964  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.964  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.964  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.965  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.965  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.965  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.965  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.966  3337  3387 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-08 12:03:10.966  3337  3387 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-08 12:03:10.966  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 12:03:10.966  3337  3387 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 12:03:10.966  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.966  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.966  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.966  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.967  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.967  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.967  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.967  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.967  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.967  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.967  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.967  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.967  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.967  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.967  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.967  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.967  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.967  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.969  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.969  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.969  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.969  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.969  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.969  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.969  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.969  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.969  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.969  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.969  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.969  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.970  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.970  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.970  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.970  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.970  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.970  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.971  3337  3387 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 12:03:10.971  3337  3387 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 12:03:10.971  3337  3387 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 12:03:10.971  3337  3387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 12:03:10.971  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.971  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.971  3337  3387 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7425ed not in the list
08-08 12:03:10.971  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.971  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.971  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
08-08 12:03:10.971  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.971  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.971  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 12:03:10.971  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 12:03:10.972  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 12:03:10.972  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 12:03:10.972  3337  3387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 12:03:10.972  3337  3387 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9508c22 not in the list
08-08 12:03:10.972  3337  3387 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-08 12:03:10.972  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 12:03:10.972  3337  3387 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-08 12:03:10.973  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 12:03:10.973  3337  3387 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-08 12:03:10.973  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 12:03:10.974  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 12:03:10.974  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-08 12:03:10.974  3337  3387 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-08 12:03:10.975  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 12:03:10.975  3337  3387 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-08 12:03:10.975  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 12:03:10.975  3337  3387 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-08 12:03:10.975  3337  3387 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-08 12:03:10.975  3337  3387 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-08 12:03:10.975  3337  3387 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-08 12:03:10.975  3337  3387 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-08 12:03:10.976  3337  3387 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-08 12:03:10.976  3337  3387 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-08 12:03:10.976  3337  3387 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-08 12:03:10.976  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 12:03:10.976  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44ef79c added. We now have 2 listener(s)
08-08 12:03:10.976  3337  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 12:03:10.978   873  1706 D WifiService: setWifiEnabled: true pid=3337, uid=10000
08-08 12:03:10.978   873  1706 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-08 12:03:10.979  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 12:03:10.979  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b925a5 added. We now have 3 listener(s)
08-08 12:03:10.980  3337  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 12:03:10.980  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.980  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:10.980  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 12:03:10.980  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1eb7d7a added. We now have 4 listener(s)
08-08 12:03:10.980  3337  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 12:03:10.981  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 12:03:10.981  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7dbc92b added. We now have 5 listener(s)
08-08 12:03:10.981  3337  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 12:03:10.982   873  1691 D WifiService: setWifiEnabled: false pid=3337, uid=10000
08-08 12:03:10.982   873  1691 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-08 12:03:10.996   873   890 I ActivityManager: Start proc 3398:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-08 12:03:10.997   873  1312 D WifiConfigStore: Loading config and enabling all networks 
08-08 12:03:11.007  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:11.007  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:11.007  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:11.007  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:11.016   873   886 I ActivityManager: Start proc 3410:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-08 12:03:11.017  3337  3387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 12:03:11.020   873  1312 D WifiConfigStore: loaded 0 passpoint configs
08-08 12:03:11.020   873  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-08 12:03:11.031   873  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-08 12:03:11.031  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:11.031  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 12:03:11.031  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:11.032  3337  3387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:11.032  3337  3387 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 12:03:11.032   873  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-08 12:03:11.032  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:11.032   873  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-08 12:03:11.032   873  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-08 12:03:11.033   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 12:03:11.033   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-08 12:03:11.062  3410  3410 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-08 12:03:11.082   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-08 12:03:11.085   372   871 D CommandListener: Setting iface cfg
,08-08 12:03:11.088   873  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
08-08 12:03:11.088   873  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-08 12:03:11.090   873  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-08 12:03:11.090   873  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-08 12:03:11.090  3398  3398 D AdapterServiceConfig: Adding HeadsetService
,08-08 12:03:11.091  3398  3398 D AdapterServiceConfig: Adding A2dpService
,08-08 12:03:11.091  3398  3398 D AdapterServiceConfig: Adding HidService
,08-08 12:03:11.091  3398  3398 D AdapterServiceConfig: Adding HealthService
,08-08 12:03:11.091  3398  3398 D AdapterServiceConfig: Adding PanService
,08-08 12:03:11.091  3398  3398 D AdapterServiceConfig: Adding GattService
,08-08 12:03:11.091  3398  3398 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 12:03:11.103   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 12:03:11.105  1698  2061 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 12:03:11.107  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:11.107  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:11.107  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:11.107  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:11.108  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:11.108  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:11.108  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:11.108  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 12:03:11.129   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4baddff:true
,08-08 12:03:11.129  3398  3398 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 12:03:11.132  3398  3398 I bt_bluedroid: init
,08-08 12:03:11.132  3398  3432 I BluetoothAdapterState: Entering OffState
,08-08 12:03:11.134  3398  3433 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 12:03:11.135  3398  3433 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 12:03:11.135  3398  3433 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-08 12:03:11.135  3398  3433 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 12:03:11.136  3410  3410 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-08 12:03:11.136  3398  3398 I bt_bluedroid: get_profile_interface socket
,08-08 12:03:11.137  3398  3398 I bt_bluedroid: get_profile_interface sdp
,08-08 12:03:11.139  3398  3436 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 12:03:11.140  3398  3436 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 12:03:11.141  3398  3409 I bt_bluedroid: config_hci_snoop_log
,08-08 12:03:11.142   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-08 12:03:11.145  3398  3432 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 12:03:11.145  3398  3432 D BluetoothAdapterProperties: Setting state to 14
,08-08 12:03:11.145  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 12:03:11.146  3398  3432 D BluetoothBondStateMachine: make
,08-08 12:03:11.150  3398  3439 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-08 12:03:11.151  3398  3432 I BluetoothAdapterState: Entering PendingCommandState
,08-08 12:03:11.152  3398  3398 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 12:03:11.153  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:11.154  3398  3398 D BtGatt.DebugUtils: handleDebugAction() action=null,
,08-08 12:03:11.154  3398  3398 D BtGatt.GattService: Received start request. Starting profile...
,08-08 12:03:11.154  3398  3398 D BtGatt.GattService: start()
,08-08 12:03:11.155  3398  3398 I bt_bluedroid: get_profile_interface gatt
,08-08 12:03:11.155  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:11.155  3398  3398 D BtGatt.AdvertiseManager: advertise manager created
,08-08 12:03:11.160  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:11.160  3398  3398 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:11.160  3398  3398 V BluetoothAdapterState: isBleTurningOn()=true
08-08 12:03:11.160  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:11.160  3398  3432 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-08 12:03:11.160  3398  3432 I bt_bluedroid: enable
,08-08 12:03:11.160  3398  3433 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-08 12:03:11.161  3398  3433 I bt_hci  : start_up
,08-08 12:03:11.168  3398  3433 I bt_vendor: alloc value 0xb3a85189
,08-08 12:03:11.168  3398  3433 I bt_vendor: init
08-08 12:03:11.168  3398  3433 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 12:03:11.168  3398  3433 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 12:03:11.226  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:11.232  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:11.233  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:11.252  1511  2683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 12:03:11.252  1511  2683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 12:03:11.252  1511  2683 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 12:03:11.253  1511  2683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:11.270  2599  2599 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 12:03:11.270  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 12:03:11.270  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-08 12:03:11.274  3398  3433 D bt_hci  : start_up starting async portion
08-08 12:03:11.277  3398  3443 I bt_hci  : event_finish_startup
,08-08 12:03:11.277  3398  3443 I bt_hci_h4: hal_open
08-08 12:03:11.277  3398  3443 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 12:03:11.283  3398  3443 I bt_userial_vendor: device fd = 51 open
,08-08 12:03:11.284   873  1612 I ActivityManager: Killing 2685:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-08 12:03:11.316  3398  3443 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 12:03:11.349  3398  3443 D bt_hwcfg: Chipset BCM4354A2
,08-08 12:03:11.349  3398  3443 D bt_hwcfg: Target name = [BCM4354A2]
08-08 12:03:11.349  3398  3443 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 12:03:11.464  3337  3337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-08 12:03:11.971  3398  3443 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 12:03:11.972  3398  3443 D bt_hwcfg: Settlement delay -- 100 ms
,08-08 12:03:11.972  3398  3443 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 12:03:12.089  3398  3443 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 12:03:12.090  3398  3443 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 12:03:12.120  3398  3443 I bt_hwcfg: vendor lib fwcfg completed
,08-08 12:03:12.121  3398  3443 I bt_vendor: firmware callback
,08-08 12:03:12.121  3398  3443 I bt_hci  : firmware_config_callback
,08-08 12:03:12.132  3398  3445 I bt_btu  : btu_task pending for preload complete event
08-08 12:03:12.132  3398  3445 I bt_btu_task: Bluetooth chip preload is complete
,08-08 12:03:12.133  3398  3445 I bt_btu  : btu_task received preload complete event
,08-08 12:03:12.143  3398  3445 I         : BTE_InitTraceLevels -- TRC_HCI
08-08 12:03:12.143  3398  3445 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-08 12:03:12.143  3398  3445 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-08 12:03:12.144  3398  3445 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-08 12:03:12.144  3398  3445 I         : BTE_InitTraceLevels -- TRC_AVRC
08-08 12:03:12.144  3398  3445 I         : BTE_InitTraceLevels -- TRC_A2D
,08-08 12:03:12.145  3398  3445 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-08 12:03:12.145  3398  3445 I         : BTE_InitTraceLevels -- TRC_BTM
,08-08 12:03:12.145  3398  3445 I         : BTE_InitTraceLevels -- TRC_GAP
,08-08 12:03:12.145  3398  3445 I         : BTE_InitTraceLevels -- TRC_PAN
,08-08 12:03:12.146  3398  3445 I         : BTE_InitTraceLevels -- TRC_SDP
,08-08 12:03:12.146  3398  3445 I         : BTE_InitTraceLevels -- TRC_GATT
,08-08 12:03:12.146  3398  3445 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 12:03:12.146  3398  3445 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-08 12:03:12.147  3398  3445 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 12:03:12.287  3398  3445 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a02d9d
,08-08 12:03:12.288  3398  3445 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a02d9d 
,08-08 12:03:12.297  3398  3436 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 12:03:12.299  3398  3436 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 12:03:12.300  3398  3436 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 12:03:12.303  3398  3436 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 12:03:12.307  3398  3436 D BluetoothAdapterProperties: Scan Mode:20
,08-08 12:03:12.307  3398  3436 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-08 12:03:12.308  3398  3436 D bt_hci  : do_postload posting postload work item
,08-08 12:03:12.309  3398  3443 I bt_hci  : event_postload
08-08 12:03:12.309  3398  3443 I bt_vendor: sco_config_cb
,08-08 12:03:12.309  3398  3443 I bt_hci  : sco_config_callback postload finished.
,08-08 12:03:12.312  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:12.318  3398  3443 I bt_vendor: low_power_mode_cb
,08-08 12:03:12.318  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:12.319  3398  3436 D bt_bte_conf: Device ID record 1 : primary
08-08 12:03:12.320  3398  3436 D bt_bte_conf:   vendorId            = 000f
08-08 12:03:12.320  3398  3436 D bt_bte_conf:   vendorIdSource      = 0001
,08-08 12:03:12.321  3398  3436 D bt_bte_conf:   product             = 1200
,08-08 12:03:12.321  3398  3436 D bt_bte_conf:   version             = 1436
,08-08 12:03:12.321  3398  3436 D bt_bte_conf:   clientExecutableURL = 
,08-08 12:03:12.321  3398  3436 D bt_bte_conf:   serviceDescription  = 
08-08 12:03:12.321  3398  3436 D bt_bte_conf:   documentationURL    = 
08-08 12:03:12.322  3398  3436 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-08 12:03:12.322  3398  3433 D bt_stack_manager: event_start_up_stack finished
,08-08 12:03:12.324  3398  3432 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-08 12:03:12.325  3398  3432 D BluetoothAdapterProperties: Setting state to 15
08-08 12:03:12.325  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-08 12:03:12.328  3398  3432 I BluetoothAdapterState: Entering BleOnState
,08-08 12:03:12.331  3398  3432 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-08 12:03:12.331  3398  3432 D BluetoothAdapterProperties: Setting state to 11
08-08 12:03:12.331  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 12:03:12.338  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:12.341  3398  3398 D HeadsetService: Received start request. Starting profile...
,08-08 12:03:12.346  3398  3398 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-08 12:03:12.346  3398  3398 D HeadsetStateMachine: make
,08-08 12:03:12.351  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:12.356  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:12.374   873   886 I ActivityManager: Start proc 3452:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-08 12:03:12.377  3398  3432 I BluetoothAdapterState: Entering PendingCommandState
,08-08 12:03:12.377  3398  3398 D HeadsetStateMachine: max_hf_connections = 1
,08-08 12:03:12.377  3398  3398 I bt_bluedroid: get_profile_interface handsfree
,08-08 12:03:12.378  3398  3436 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-08 12:03:12.378  3398  3436 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-08 12:03:12.386  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:12.387   873   873 D BluetoothA2dp: Proxy object connected
,08-08 12:03:12.388  3398  3398 D A2dpService: Received start request. Starting profile...
,08-08 12:03:12.389  3398  3398 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-08 12:03:12.390  3398  3398 I bt_bluedroid: get_profile_interface avrcp
,08-08 12:03:12.398  3398  3398 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 12:03:12.398  3398  3398 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 12:03:12.398  3398  3398 D A2dpStateMachine: make
,08-08 12:03:12.399  3398  3398 I bt_bluedroid: get_profile_interface a2dp
,08-08 12:03:12.400  3398  3436 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 12:03:12.405  3398  3465 D A2dpStateMachine: Enter Disconnected: -2
,08-08 12:03:12.406  3398  3398 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 12:03:12.409  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
08-08 12:03:12.410  1367  1367 D BluetoothInputDevice: Proxy object connected
08-08 12:03:12.411  1367  1367 D HidProfile: Bluetooth service connected
08-08 12:03:12.412  3398  3398 D HidService: Received start request. Starting profile...
08-08 12:03:12.412  3398  3398 I bt_bluedroid: get_profile_interface hidhost
08-08 12:03:12.412  3398  3398 D HidService: setHidService(): set to: null
08-08 12:03:12.412  3398  3436 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e43e5
08-08 12:03:12.412  3398  3436 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-08 12:03:12.413  3398  3398 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 12:03:12.414  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
08-08 12:03:12.417  3398  3398 D HealthService: Received start request. Starting profile...
,08-08 12:03:12.418  3398  3398 I bt_bluedroid: get_profile_interface health
08-08 12:03:12.419  3398  3398 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 12:03:12.420  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
08-08 12:03:12.421  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 12:03:12.421  3398  3398 D PanService: Received start request. Starting profile...
08-08 12:03:12.421  1367  1367 D PanProfile: Bluetooth service connected
08-08 12:03:12.422  3398  3398 D BluetoothPanServiceJni: initializeNative(L110): pan
08-08 12:03:12.422  3398  3398 I bt_bluedroid: get_profile_interface pan
08-08 12:03:12.422  3398  3436 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-08 12:03:12.427  3398  3398 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
08-08 12:03:12.428  1367  1367 D BluetoothMap: Proxy object connected
08-08 12:03:12.428  3398  3398 D BluetoothMapService: Received start request. Starting profile...
08-08 12:03:12.428  3398  3398 D BluetoothMapService: start()
08-08 12:03:12.429  1367  1367 D MapProfile: Bluetooth service connected
08-08 12:03:12.429  1367  1367 D BluetoothMap: getConnectedDevices()
08-08 12:03:12.429  1367  1367 D BluetoothMap: Bluetooth is Not enabled
,08-08 12:03:12.430  3398  3398 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-08 12:03:12.431  3398  3398 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-08 12:03:12.431  3398  3398 D BluetoothMapAppObserver: createReceiver()
08-08 12:03:12.433  3398  3398 D BluetoothMapAppObserver: initObservers()
08-08 12:03:12.433  3398  3398 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 12:03:12.436  3452  3452 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-08 12:03:12.439  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:12.439  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-08 12:03:12.439  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:12.439  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:12.440  3398  3451 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isTurningOff()=false
08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isTurningOff()=false
08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isTurningOn()=true
,08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:12.441  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isTurningOff()=false
08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isTurningOn()=true
08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:12.442  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:12.442  3398  3432 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-08 12:03:12.442  3398  3432 D BluetoothAdapterProperties: ScanMode =  20
08-08 12:03:12.442  3398  3432 D BluetoothAdapterProperties: State =  11
,08-08 12:03:12.442  3398  3432 D BluetoothAdapterProperties: Setting state to 12
08-08 12:03:12.443  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 12:03:12.443  3398  3432 I BluetoothAdapterState: Entering OnState
08-08 12:03:12.443  1776  1787 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:12.443  3398  3436 D BluetoothAdapterProperties: Scan Mode:21
08-08 12:03:12.443  3398  3436 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 12:03:12.445   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 12:03:12.445   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:12.445  1367  1387 D BluetoothPan: onBluetoothStateChange on: true
08-08 12:03:12.446   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 12:03:12.446  3337  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-08 12:03:12.446  1367  1855 D BluetoothMap: onBluetoothStateChange: up=true
08-08 12:03:12.447  1367  1854 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 12:03:12.447   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 12:03:12.447  1367  1394 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 12:03:12.449  3337  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-08 12:03:12.450   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-08 12:03:12.451  3337  3337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-08 12:03:12.451  3398  3398 D BluetoothMapService: onReceive
08-08 12:03:12.451  3398  3398 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 12:03:12.451  3398  3398 D BluetoothMapService: STATE_ON
,08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:12.453  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:12.455  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 12:03:12.459  3398  3398 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:12.459  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:12.460  3398  3398 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-08 12:03:12.461  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 12:03:12.462  3398  3398 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 12:03:12.463  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:12.465  3398  3398 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 12:03:12.465  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:12.466  3398  3398 D ObexServerSockets: Succeed to create listening sockets 
08-08 12:03:12.466  3398  3398 D ObexServerSockets0: startAccept()
08-08 12:03:12.466  3398  3398 D ObexServerSockets0: prepareForNewConnect()
,08-08 12:03:12.467  1367  1672 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-08 12:03:12.468  3398  3398 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-08 12:03:12.469  3398  3398 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-08 12:03:12.469  3398  3476 D ObexServerSockets0: Accepting socket connection...
08-08 12:03:12.470  3398  3475 D ObexServerSockets0: Accepting socket connection...
,08-08 12:03:12.471   873   884 I ActivityManager: Killing 2842:com.google.android.gm/u0a78 (adj 15): empty #17
,08-08 12:03:12.472  3398  3398 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 12:03:12.472  3398  3398 D ObexServerSockets0: prepareForNewConnect()
,08-08 12:03:12.516  1367  1367 D BluetoothA2dp: Proxy object connected
,08-08 12:03:12.515  1367  1672 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-08 12:03:12.518  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 12:03:12.545  1776  2049 D BluetoothHeadset: Proxy object connected
,08-08 12:03:12.546   873   890 D BluetoothHeadset: Proxy object connected
08-08 12:03:12.547   873   890 D BluetoothHeadset: Proxy object connected
08-08 12:03:12.547   873   890 D BluetoothHeadset: Proxy object connected
,08-08 12:03:12.550   873  1718 I ActivityManager: Start proc 3477:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-08 12:03:12.585  3477  3477 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-08 12:03:12.621  1367  1387 D BluetoothHeadset: Proxy object connected
,08-08 12:03:12.622  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-08 12:03:12.804  3477  3477 D StrictMode: StrictMode policy violation; ~duration=167 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.804  3477  3477 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.804  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.805  3477  3477 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.805  3477  3477 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.805  3477  3477 D StrictMode: StrictMode policy violation; ~duration=163 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.k.d(PG:583)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.805  3477  3477 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.805  3477  3477 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.805  3477  3477 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:03:12.805  3477  3477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 12:03:12.828  3452  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 12:03:12.835   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@abc4bde:true
,08-08 12:03:12.839  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 12:03:12.849  3452  3452 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-08 12:03:12.859  3452  3452 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-08 12:03:12.860  1367  1367 D BluetoothPbap: Proxy object connected
,08-08 12:03:12.861  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-08 12:03:12.881  3398  3506 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 12:03:12.883  3452  3452 D LocalBluetoothProfileManager: Adding local MAP profile
,08-08 12:03:12.884  3452  3452 D BluetoothMap: Create BluetoothMap proxy object
,08-08 12:03:12.889  3452  3452 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-08 12:03:12.895  3452  3452 D DockEventReceiver: finishStartingService: stopping service
,08-08 12:03:12.897  3452  3452 D BluetoothA2dp: Proxy object connected
,08-08 12:03:12.899  3452  3452 D BluetoothInputDevice: Proxy object connected
,08-08 12:03:12.899  3452  3452 D HidProfile: Bluetooth service connected
,08-08 12:03:12.901  3452  3452 D BluetoothPan: BluetoothPAN Proxy object connected
,08-08 12:03:12.902  3452  3452 D PanProfile: Bluetooth service connected
08-08 12:03:12.902  3452  3452 D BluetoothMap: Proxy object connected
08-08 12:03:12.902  3452  3452 D MapProfile: Bluetooth service connected
,08-08 12:03:12.903  3452  3452 D BluetoothMap: getConnectedDevices()
,08-08 12:03:12.904  3452  3452 D BluetoothPbap: Proxy object connected
08-08 12:03:12.905  3452  3452 D PbapServerProfile: Bluetooth service connected
,08-08 12:03:12.906   873   884 I ActivityManager: Killing 3024:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-08 12:03:12.950  3398  3512 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 12:03:12.954  3477  3492 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-08 12:03:12.959  3398  3512 I BtOppRfcommListener: Accept thread started.
,08-08 12:03:12.963   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f574ec:true
,08-08 12:03:12.968  3452  3464 D BluetoothHeadset: Proxy object connected
,08-08 12:03:12.970  3452  3452 D HeadsetProfile: Bluetooth service connected
,08-08 12:03:14.036   873   884 D WifiService: setWifiEnabled: true pid=3337, uid=10000
,08-08 12:03:14.036   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 12:03:14.048   873  1312 D WifiConfigStore: Loading config and enabling all networks 
,08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:14.069  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 12:03:14.073   873  1312 D WifiConfigStore: loaded 0 passpoint configs
,08-08 12:03:14.074   873  1312 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-08 12:03:14.074   873  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-08 12:03:14.074  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:14.075   873  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-08 12:03:14.076   873  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-08 12:03:14.076   873  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-08 12:03:14.076   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 12:03:14.076   873  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-08 12:03:14.078  1471  1471 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:14.083  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 12:03:14.088  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 12:03:14.165   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-08 12:03:14.168   372   871 D CommandListener: Setting iface cfg
,08-08 12:03:14.171   873  1311 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-08 12:03:14.171   873  1311 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-08 12:03:14.180   873  1311 D WifiNative-HAL: p2pGetDeviceAddress
,08-08 12:03:14.181   873  1311 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-08 12:03:14.222   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 12:03:14.232   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 12:03:14.539  1471  1471 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-08 12:03:14.586  1471  1471 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-08 12:03:14.588  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-08 12:03:14.596   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 12:03:14.625   873  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 12:03:14.626   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 12:03:14.626   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-08 12:03:14.668   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 12:03:14.692   372   871 D CommandListener: Setting iface cfg
,08-08 12:03:14.712   873  1312 D WifiStateMachine: Start Dhcp Watchdog 1
,08-08 12:03:14.743   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-08 12:03:14.746   873  1314 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-08 12:03:14.752   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-08 12:03:14.768   873  3521 D DhcpClient: Receive thread started
,08-08 12:03:14.848   873  1312 E native  : do suspend false
,08-08 12:03:14.871   873  3520 D DhcpClient: Broadcasting DHCPDISCOVER
,08-08 12:03:14.886   873  3521 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 170156, domain null
,08-08 12:03:14.888   873  3520 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 170156 seconds
,08-08 12:03:14.893   873  3520 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-08 12:03:14.907   873  3521 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-08 12:03:14.908   873  3520 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-08 12:03:14.913   372   871 D CommandListener: Setting iface cfg
,08-08 12:03:14.924   873  3520 D DhcpClient: Scheduling renewal in 86399s
,08-08 12:03:14.925   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-08 12:03:14.941   873  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-08 12:03:14.946   873  1312 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-08 12:03:14.947   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-08 12:03:14.953   873  1314 D ConnectivityService: Adding iface wlan0 to network 100
,08-08 12:03:14.963   873  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-08 12:03:14.999   873  1314 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-08 12:03:14.999   873  1314 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-08 12:03:15.002   873  1314 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-08 12:03:15.005   873  1314 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-08 12:03:15.007   873  1314 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-08 12:03:15.018   873  1314 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-08 12:03:15.024   873  1314 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-08 12:03:15.025   873  1314 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
08-08 12:03:15.025   873  1314 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
08-08 12:03:15.025   873  1314 D ConnectivityService:    accepting network in place of null
08-08 12:03:15.025   873  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-08 12:03:15.029   873  1314 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 12:03:15.027   873  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-08 12:03:15.035   873  3519 D NetlinkSocketObserver: NeighborEvent{elapsedMs=144632, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-08 12:03:15.067   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 12:03:15.098   873  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:811::200e
,08-08 12:03:15.104   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 12:03:15.110   873  1314 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-08 12:03:15.118   873  1314 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-08 12:03:15.119   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-08 12:03:15.121   873  1314 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-08 12:03:15.123   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-08 12:03:15.140   873  1706 V BackupManagerService: Scheduling immediate backup pass
,08-08 12:03:15.142   873   873 V BackupManagerService: Running a backup pass
,08-08 12:03:15.147   873  1334 V BackupManagerService: clearing pending backups
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 12:03:15.152  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 12:03:15.153   873  1334 V PerformBackupTask: Beginning backup of 16 targets
,08-08 12:03:15.155  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 12:03:15.176   873  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Aug 2016 10:03:14 GMT], X-Android-Received-Millis=[1470650595175], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470650595151]}
,08-08 12:03:15.176   873  1334 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 12:03:15.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 12:03:15.182   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-08 12:03:15.182   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-08 12:03:15.182   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-08 12:03:15.183   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-08 12:03:15.183  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 12:03:15.189   873  1334 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-08 12:03:15.191  1732  1732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 12:03:15.194   873  1722 D AlarmManagerService: Setting time of day to sec=1470650594
,08-08 12:03:14.793   873  1722 W AlarmManagerService: Unable to set rtc to 1470650594: Invalid argument
08-08 12:03:14.797  1732  1732 D SystemUpdateService: onCreate
,08-08 12:03:14.819   873  1795 I ActivityManager: Start proc 3541:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
08-08 12:03:14.823  1732  1732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 12:03:14.838  1732  3547 I SystemUpdateService: active receiver: enabled
,08-08 12:03:14.855  1732  3547 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 12:03:14.857  1732  3547 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-08 12:03:14.857  1732  3547 I SystemUpdateService: now status is 0 (complete)
08-08 12:03:14.857  1732  3547 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-08 12:03:14.857  1732  3547 I SystemUpdateService: file has been verified
08-08 12:03:14.857  1732  3547 I SystemUpdateService: OTA package size = 12249756
,08-08 12:03:14.862  1732  3547 I SystemUpdateService: showing system update notification
,08-08 12:03:14.871   873  1334 I BackupRestoreController: Getting widget state for user: 0
,08-08 12:03:14.878  3541  3541 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-08 12:03:14.886   873  3562 D GpsLocationProvider: NTP server returned: 1470650594793 (Mon Aug 08 12:03:14 GMT+02:00 2016) reference: 144793 certainty: 14 system time offset: -93
,08-08 12:03:14.887   873  3562 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-08 12:03:14.891  1732  3564 I iu.SyncManager: SYNC; picasa accounts
,08-08 12:03:14.901  1732  1732 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-08 12:03:14.902  1732  1732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-08 12:03:14.920  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 12:03:14.920  1732  3563 I MDM     : [163] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-08 12:03:14.920  1732  3563 W BaseAppContext: Using Auth Proxy for data requests.
08-08 12:03:14.921  1732  1732 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 12:03:14.932   873  1718 I ActivityManager: Start proc 3571:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-08 12:03:14.935  1732  1732 D SystemUpdateService: onDestroy
,08-08 12:03:14.939  3541  3565 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-08 12:03:14.941  1732  3563 V GoogleAuthProtoRequest: [163] a.<init>: mAccountName set to: thalitester@gmail.com
,08-08 12:03:14.947  3410  3539 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,08-08 12:03:14.958  1732  3564 I iu.UploadsManager: num queued entries: 0
,08-08 12:03:14.958  1732  3564 I iu.UploadsManager: num updated entries: 0
,08-08 12:03:14.966  1732  3564 I iu.SyncManager: NEXT; no task
,08-08 12:03:14.978  3571  3571 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
08-08 12:03:14.981  1698  1710 W GmsBackupTransport: Unknown package in backup request: @pm@
08-08 12:03:14.981  1698  1710 V GmsBackupTransport: starting performBackup for @pm@
,08-08 12:03:14.989  3571  3571 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 12:03:14.995  3541  3565 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-08 12:03:14.995  3571  3571 D SprintDMHelper: simOperator: 
08-08 12:03:14.995  3571  3571 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 12:03:15.003  1732  3558 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-08 12:03:15.006   873  1397 I ActivityManager: Start proc 3589:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-08 12:03:15.016  1698  1710 V GmsBackupTransport: performBackup done for @pm@
,08-08 12:03:15.015  1511  2683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-08 12:03:15.021  1511  2683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-08 12:03:15.021  1511  2683 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:15.021  1511  2683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 12:03:15.022  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:15.040  3541  3565 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-08 12:03:15.049  1511  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
08-08 12:03:15.049  1511  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-08 12:03:15.049  1511  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:15.049  1511  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 12:03:15.057  1511  1882 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 12:03:15.057  1511  1882 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 12:03:15.057  1511  1882 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 12:03:15.057  1511  1882 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 12:03:15.057  1511  1882 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 12:03:15.057  1511  1882 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 12:03:15.057  1511  1882 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:03:15.061  1698  2079 W GmsBackupTransport: Error sending final backup to server: 
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 12:03:15.061  1698  2079 W GmsBackupTransport: 	... 1 more
,08-08 12:03:15.066  1698  2080 I GmsBackupTransport: Next backup will happen in 43199992 millis.
,08-08 12:03:15.066   873  1334 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-08 12:03:15.079  1732  3563 E MDM     : [163] SitrepService.a: Error sending sitrep.
,08-08 12:03:15.084  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-08 12:03:15.084  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-08 12:03:15.084  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:15.084  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-08 12:03:15.110  3410  3539 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-08 12:03:15.127  1732  1732 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-08 12:03:15.134  3541  3541 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-08 12:03:15.140   873  1718 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1732 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-08 12:03:15.156  3610  3610 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-492481209.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-492481209.dex
,08-08 12:03:15.208  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:15.261  1732  3561 W DriveInitializer: Awaiting to be initialized
,08-08 12:03:15.261  1732  3637 W DriveInitializer: Background init thread started
,08-08 12:03:15.271  3610  3610 I dex2oat : dex2oat took 116.406ms (threads: 4) arena alloc=272KB java alloc=41KB native alloc=1514KB free=1557KB
,08-08 12:03:15.274   873  1334 I BackupManagerService: Backup pass finished.
,08-08 12:03:15.304  3541  3541 W InstanceID/Rpc: Found 10011
,08-08 12:03:15.324  1732  3637 W DriveInitializer: Background init thread ended
,08-08 12:03:15.412  1511  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-08 12:03:15.412  1511  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-08 12:03:15.412  1511  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:15.412  1511  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:15.472   873   885 I ActivityManager: Start proc 3682:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-08 12:03:15.482  3128  3586 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-08 12:03:15.482  3128  3586 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jdm.a(PG:82)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jcs.o(PG:406)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jcn.a(PG:1379)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jcs.i(PG:143)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at blb.a(PG:3937)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at czp.a(PG:18188)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at czp.a(PG:9081)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at czq.run(PG:1686)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 12:03:15.482  3128  3586 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jdj.a(PG:4091)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jdj.a(PG:1125)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jdm.a(PG:77)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	... 12 more
08-08 12:03:15.482  3128  3586 E HttpOperation: Caused by: faj: BadAuthentication
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at fal.a(PG:38)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	at jdj.a(PG:4089)
08-08 12:03:15.482  3128  3586 E HttpOperation: 	... 14 more
,08-08 12:03:15.488  3682  3682 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-08 12:03:15.538   873  1718 I ActivityManager: Start proc 3698:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-08 12:03:15.561  1511  2064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-08 12:03:15.562  1511  2064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-08 12:03:15.562  1511  2064 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:15.562  1511  2064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:15.588  3128  3586 E HttpOperation: [getmobileexperiments] Unexpected exception
08-08 12:03:15.588  3128  3586 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jdm.a(PG:82)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jcs.o(PG:406)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jcn.a(PG:1379)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jcs.i(PG:143)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at hec.a(PG:42)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at hee.a(PG:102)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at czr.a(PG:65)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at kka.a(PG:108)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at czp.a(PG:19176)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at czp.a(PG:9081)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at czq.run(PG:1686)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 12:03:15.588  3128  3586 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jdj.a(PG:4091)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jdj.a(PG:1125)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jdm.a(PG:77)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	... 15 more
08-08 12:03:15.588  3128  3586 E HttpOperation: Caused by: faj: BadAuthentication
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at fal.a(PG:38)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	at jdj.a(PG:4089)
08-08 12:03:15.588  3128  3586 E HttpOperation: 	... 17 more
,08-08 12:03:15.589  3128  3586 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-08 12:03:15.589  3128  3586 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jdm.a(PG:82)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jcs.o(PG:406)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jcn.a(PG:1379)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jcs.i(PG:143)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at hec.a(PG:42)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at hee.a(PG:102)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at czr.a(PG:65)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at kka.a(PG:108)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at czp.a(PG:19176)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at czp.a(PG:9081)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at czq.run(PG:1686)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jdj.a(PG:4091)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jdj.a(PG:1125)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jdm.a(PG:77)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	... 15 more
08-08 12:03:15.589  3128  3586 E ExperimentLoader: Caused by: faj: BadAuthentication
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at fal.a(PG:38)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	at jdj.a(PG:4089)
08-08 12:03:15.589  3128  3586 E ExperimentLoader: 	... 17 more
,08-08 12:03:15.629  3698  3698 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-08 12:03:15.663  2353  3697 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-08 12:03:15.664   873  1691 I ActivityManager: Killing 2478:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-08 12:03:15.797   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 23990, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-08 12:03:15.799   873  2063 I ActivityManager: Killing 2750:android.process.acore/u0a5 (adj 15): empty #17
,08-08 12:03:15.904  3682  3682 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-08 12:03:15.918  3682  3682 I BooksApp: Created application version: 3.6.9 (30609)
,08-08 12:03:15.939  3698  3698 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-08 12:03:15.939  3698  3698 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-08 12:03:15.939  3698  3698 I GAv4    :   adb logcat -s GAv4
,08-08 12:03:15.969  3698  3698 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-08 12:03:15.980  3698  3698 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-08 12:03:16.010  3698  3727 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-08 12:03:16.044  3682  3724 I BooksSync: Starting books sync for 61035162, extras: ade
,08-08 12:03:16.069  2877  3723 V KeepSync: Connecting to GoogleApiClient
,08-08 12:03:16.070   873  1706 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-08 12:03:16.175  1511  2064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-08 12:03:16.175  1511  2064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-08 12:03:16.176  1511  2064 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:16.176  1511  2064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:16.183  3698  3698 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-08 12:03:16.196  1732  3736 V BaseAuthAsyncOperation: access token request failed
,08-08 12:03:16.201  2877  3723 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-08 12:03:16.247  3698  3698 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-08 12:03:16.261  3698  3698 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 6252-6262)
08-08 12:03:16.261  3698  3698 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-08 12:03:16.275  3698  3698 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cfcc9e0}
08-08 12:03:16.275  3698  3698 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 12:03:16.276  3698  3698 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-08 12:03:16.288  3698  3698 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-08 12:03:16.293  3698  3698 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-08 12:03:16.310  3698  3698 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-08 12:03:16.323  3698  3698 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 12:03:16.323  3698  3698 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 12:03:16.323  3698  3698 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 12:03:16.323  3698  3698 I Adreno  : Build Date                       : 10/20/15
08-08 12:03:16.323  3698  3698 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 12:03:16.323  3698  3698 I Adreno  : Local Branch                     : M14
08-08 12:03:16.323  3698  3698 I Adreno  : Remote Branch                    : 
08-08 12:03:16.323  3698  3698 I Adreno  : Remote Branch                    : 
08-08 12:03:16.323  3698  3698 I Adreno  : Reconstruct Branch               : 
,08-08 12:03:16.420  3698  3698 I NSApplication: Starting up...
,08-08 12:03:16.430  3698  3760 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-08 12:03:16.466   873  1911 I ActivityManager: Start proc 3765:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-08 12:03:16.522  3765  3765 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-08 12:03:16.602  1511  2683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-08 12:03:16.602  1511  2683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-08 12:03:16.603  1511  2683 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:16.603  1511  2683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:16.630  3682  3779 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-08 12:03:16.641   873  1718 D WifiService: setWifiEnabled: false pid=3337, uid=10000
,08-08 12:03:16.641   873  1718 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 12:03:16.658  1471  1471 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-08 12:03:16.662   873  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-08 12:03:16.662   873  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-08 12:03:16.662   873  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 12:03:16.662   873  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 12:03:16.666  2877  3723 E KeepSync: IOException
08-08 12:03:16.666  2877  3723 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-08 12:03:16.666  2877  3723 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 12:03:16.666  2877  3723 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-08 12:03:16.666  2877  3723 E KeepSync: 	... 10 more
08-08 12:03:16.666  2877  3723 W KeepSync: Sync result 2
,08-08 12:03:16.679   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 24001, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-08 12:03:16.684   873   884 I ActivityManager: Killing 3227:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-08 12:03:16.691   873  3520 D DhcpClient: Clearing IP address
,08-08 12:03:16.692   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-08 12:03:16.695   372   871 D CommandListener: Setting iface cfg
08-08 12:03:16.697   873  3521 D DhcpClient: Receive thread stopped
,08-08 12:03:16.698  1511  3605 V NativeCrypto: Read error: ssl=0x9ac49c00: I/O error during system call, Connection timed out
,08-08 12:03:16.703  1511  3605 V NativeCrypto: SSL shutdown failed: ssl=0x9ac49c00: I/O error during system call, Broken pipe
08-08 12:03:16.705   873  1718 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-08 12:03:16.706   873  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-08 12:03:16.708   873  3518 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-08 12:03:16.709   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-08 12:03:16.709   873  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-08 12:03:16.712   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-08 12:03:16.750   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-08 12:03:16.750   873  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-08 12:03:16.750   873  1314 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-08 12:03:16.751   873  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-08 12:03:16.751   395   395 E Parcel  : Reading a NULL string not supported here.
08-08 12:03:16.753  1511  3584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-08 12:03:16.753  1511  3584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-08 12:03:16.753  1511  3584 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 12:03:16.753  1511  3584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:16.756   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-08 12:03:16.760   873  1314 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-08 12:03:16.763   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 12:03:16.766  1698  2061 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:16.767  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:16.767   873  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-08 12:03:16.768  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:16.772  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 12:03:16.776  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 12:03:16.816   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 12:03:16.830  1511  3786 I VacuumService: Vacuum at: now=1470650596830 tag=VacuumService
,08-08 12:03:16.845   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 12:03:16.845   873  1314 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-08 12:03:16.846   873  1314 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 12:03:16.852   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-08 12:03:16.854  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:16.855  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:16.861  1511  2683 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-08 12:03:16.861  1511  2683 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-08 12:03:16.861  1511  2683 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:03:16.861  1511  2683 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:16.874  3682  3779 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-08 12:03:16.875  3682  3724 E BooksSync: Soft error
08-08 12:03:16.875  3682  3724 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 12:03:16.875  3682  3724 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-08 12:03:16.882  3682  3724 E BooksSync: Sync error
08-08 12:03:16.882  3682  3724 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 12:03:16.882  3682  3724 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-08 12:03:16.882  3682  3724 I BooksSync: Finished books sync
,08-08 12:03:16.909   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-08 12:03:16.910   873  1314 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 12:03:16.920  1511  3787 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
08-08 12:03:16.921   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24001, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-08 12:03:16.921  1511  3787 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-08 12:03:16.926   873   883 I ActivityManager: Killing 3242:com.android.musicfx/u0a18 (adj 15): empty #17
,08-08 12:03:16.986  1511  3787 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,08-08 12:03:17.123   873  1795 I ActivityManager: Killing 3061:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-08 12:03:17.231  2353  3802 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-08 12:03:17.281  1732  1732 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 12:03:17.290  1732  1732 D SystemUpdateService: onCreate
,08-08 12:03:17.296  1732  1732 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 12:03:17.310  1732  3805 I SystemUpdateService: active receiver: enabled
,08-08 12:03:17.315  1732  3805 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 12:03:17.323  1732  3805 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-08 12:03:17.324  1732  3805 I SystemUpdateService: now status is 0 (complete)
08-08 12:03:17.324  1732  3805 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-08 12:03:17.324  1732  3805 I SystemUpdateService: file has been verified
08-08 12:03:17.324  1732  3805 I SystemUpdateService: OTA package size = 12249756
,08-08 12:03:17.324  1732  1732 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-08 12:03:17.330  1732  3564 I iu.UploadsManager: num queued entries: 0
08-08 12:03:17.331  1732  3805 I SystemUpdateService: showing system update notification
08-08 12:03:17.331  1732  3564 I iu.UploadsManager: num updated entries: 0
,08-08 12:03:17.335  1732  1732 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 12:03:17.335  1732  3564 I iu.SyncManager: NEXT; no task
,08-08 12:03:17.337  1732  1732 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 12:03:17.339  3571  3571 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 12:03:17.343  3571  3571 D SprintDMHelper: simOperator: 
,08-08 12:03:17.344  3571  3571 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-08 12:03:17.344  1732  1732 D SystemUpdateService: onDestroy
,08-08 12:03:19.654  3398  3432 D BluetoothAdapterState: Current state: ON, message: 23
,08-08 12:03:19.655  3398  3432 D BluetoothAdapterProperties: Setting state to 13
08-08 12:03:19.655  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-08 12:03:19.657  3398  3432 D BluetoothAdapterProperties: onBluetoothDisable()
,08-08 12:03:19.661  3398  3432 I BluetoothAdapterState: Entering PendingCommandState
,08-08 12:03:19.672  3398  3398 D BluetoothMapService: onReceive
,08-08 12:03:19.673  3398  3398 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 12:03:19.673  3398  3398 D BluetoothMapService: STATE_TURNING_OFF
08-08 12:03:19.674  3398  3398 D BluetoothMapService: MAP Service closeService in
08-08 12:03:19.674  3398  3398 D BluetoothMapMasInstance0: MAP Service shutdown
08-08 12:03:19.674  3398  3398 D ObexServerSockets0: shutdown(block = true)
,08-08 12:03:19.679  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:19.679  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:19.681  3398  3436 D BluetoothAdapterProperties: Scan Mode:20
08-08 12:03:19.681  3398  3432 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-08 12:03:19.683  3398  3398 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 12:03:19.683  3398  3475 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-08 12:03:19.684  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:19.684  3398  3448 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-08 12:03:19.684  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 12:03:19.684  3398  3476 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-08 12:03:19.683  3398  3398 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 12:03:19.689  3452  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 12:03:19.691  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:19.691  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:19.691  3398  3398 D HeadsetService: Received stop request...Stopping profile...
08-08 12:03:19.693  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:19.693  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:19.697   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:19.697   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:19.697  1776  1796 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:19.698  3452  3464 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:19.698  3398  3398 I BtOppRfcommListener: stopping Accept Thread
08-08 12:03:19.698  1367  1387 D BluetoothHeadset: Proxy object disconnected
,08-08 12:03:19.698  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:19.698  3398  3512 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 12:03:19.698   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:19.699  3398  3512 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 12:03:19.700  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:19.701  3398  3398 D A2dpService: Received stop request...Stopping profile...
08-08 12:03:19.702  3398  3465 D A2dpStateMachine: Exit Disconnected: -1
08-08 12:03:19.703   873   873 D BluetoothA2dp: Proxy object disconnected
,08-08 12:03:19.707  3398  3398 D HidService: Received stop request...Stopping profile...
08-08 12:03:19.707  3398  3398 D HidService: Stopping Bluetooth HidService
08-08 12:03:19.707  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 12:03:19.709  3398  3398 V BluetoothAdapterState: isTurningOff()=true
,08-08 12:03:19.709  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-08 12:03:19.709  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:19.709  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:19.710  3398  3398 D HealthService: Received stop request...Stopping profile...
,08-08 12:03:19.711  3452  3452 D DockEventReceiver: finishStartingService: stopping service
,08-08 12:03:19.714  3398  3398 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
08-08 12:03:19.714  3398  3398 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 12:03:19.714  3398  3436 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-08 12:03:19.714  3398  3445 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:19.714  3398  3445 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:19.714  3452  3452 D HeadsetProfile: Bluetooth service disconnected
08-08 12:03:19.714  3398  3445 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:19.715  3398  3436 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-08 12:03:19.715  3452  3452 D BluetoothA2dp: Proxy object disconnected
08-08 12:03:19.715  3452  3452 D BluetoothInputDevice: Proxy object disconnected
08-08 12:03:19.715  3452  3452 D HidProfile: Bluetooth service disconnected
08-08 12:03:19.715  1367  1367 D HeadsetProfile: Bluetooth service disconnected
08-08 12:03:19.716  1367  1367 D BluetoothA2dp: Proxy object disconnected
08-08 12:03:19.716  1367  1367 D BluetoothInputDevice: Proxy object disconnected
08-08 12:03:19.716  1367  1367 D HidProfile: Bluetooth service disconnected
08-08 12:03:19.717  3398  3398 D PanService: Received stop request...Stopping profile...
,08-08 12:03:19.719  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-08 12:03:19.719  1367  1367 D PanProfile: Bluetooth service disconnected
08-08 12:03:19.720  3452  3452 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 12:03:19.720  3452  3452 D PanProfile: Bluetooth service disconnected
,08-08 12:03:19.721  3398  3398 D BluetoothMapService: Received stop request...Stopping profile...
,08-08 12:03:19.722  3398  3398 D BluetoothMapService: stop()
08-08 12:03:19.723  3398  3398 D BluetoothMapAppObserver: deinitObservers()
,08-08 12:03:19.723  3398  3398 D BluetoothMapAppObserver: removeReceiver()
,08-08 12:03:19.724  1367  1367 D BluetoothMap: Proxy object disconnected
,08-08 12:03:19.724  1367  1367 D MapProfile: Bluetooth service disconnected
,08-08 12:03:19.724  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:19.725  3398  3398 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:19.725  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:19.725  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:19.725  3452  3452 D BluetoothMap: Proxy object disconnected
08-08 12:03:19.725  3452  3452 D MapProfile: Bluetooth service disconnected
,08-08 12:03:19.726  3398  3445 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:19.726  3398  3445 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:19.727  3398  3445 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 12:03:19.727  3398  3445 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 12:03:19.727  3398  3445 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 12:03:19.727  3398  3445 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 12:03:19.727  3398  3436 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-08 12:03:19.727  3452  3452 D BluetoothPbap: Proxy object disconnected
,08-08 12:03:19.727  3452  3452 D PbapServerProfile: Bluetooth service disconnected
,08-08 12:03:19.728  1367  1367 D BluetoothPbap: Proxy object disconnected
,08-08 12:03:19.728  1367  1367 D PbapServerProfile: Bluetooth service disconnected
,08-08 12:03:19.728  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:19.728  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-08 12:03:19.729  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:19.729  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:19.729  3398  3398 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 12:03:19.729  3398  3398 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-08 12:03:19.729  3398  3436 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 12:03:19.730  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:19.730  3398  3398 V BluetoothAdapterState: isTurningOn()=false
08-08 12:03:19.730  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:19.730  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:19.731  3398  3398 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-08 12:03:19.731  3398  3436 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-08 12:03:19.731  3398  3398 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-08 12:03:19.732  3398  3398 V BluetoothAdapterState: isTurningOff()=true
,08-08 12:03:19.732  3398  3398 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:19.732  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:19.732  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:19.732  3398  3398 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 12:03:19.732  3398  3398 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-08 12:03:19.735  3398  3398 D BluetoothMapService: MAP Service closeService in
08-08 12:03:19.735  3398  3398 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:19.735  3398  3398 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:19.735  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:19.735  3398  3398 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:19.736  3398  3432 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-08 12:03:19.736  3398  3432 D BluetoothAdapterProperties: Setting state to 15
08-08 12:03:19.736  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-08 12:03:19.736  3398  3432 I BluetoothAdapterState: Entering BleOnState
08-08 12:03:19.736  3398  3398 D BluetoothMapService: cleanup()
08-08 12:03:19.736  3398  3398 D BluetoothMapService: MAP Service closeService in
08-08 12:03:19.737  3452  3462 D BluetoothPbap: onBluetoothStateChange: up=false
,08-08 12:03:19.738  3452  3464 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 12:03:19.739  3452  3464 D BluetoothPan: onBluetoothStateChange on: false
08-08 12:03:19.739  1776  1787 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:19.740  1367  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 12:03:19.740   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:19.740  3452  3462 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:19.741  3452  3464 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-08 12:03:19.741   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:19.741  1367  1855 D BluetoothPan: onBluetoothStateChange on: false
08-08 12:03:19.742  3452  3462 D BluetoothMap: onBluetoothStateChange: up=false
08-08 12:03:19.742   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 12:03:19.743  1367  1854 D BluetoothMap: onBluetoothStateChange: up=false
08-08 12:03:19.743  1367  1394 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 12:03:19.744  1367  1387 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 12:03:19.744   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:19.744  1367  1855 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 12:03:19.745  3398  3432 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-08 12:03:19.745  3398  3432 D BluetoothAdapterProperties: Setting state to 16
08-08 12:03:19.745  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-08 12:03:19.746  3398  3432 D BluetoothAdapterProperties: onBleDisable
,08-08 12:03:19.746  3398  3433 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-08 12:03:19.746  3398  3432 I BluetoothAdapterState: Entering PendingCommandState
08-08 12:03:19.747  3398  3445 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-08 12:03:19.747  3398  3445 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:19.748  3398  3436 D BluetoothAdapterProperties: Scan Mode:20
08-08 12:03:19.750  3452  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 12:03:19.750  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:19.751  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:19.753  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:19.755  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:19.755  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 12:03:19.764  3452  3452 D DockEventReceiver: finishStartingService: stopping service
,08-08 12:03:19.955  3398  3436 I bt_hci  : shut_down
,08-08 12:03:19.964  3398  3443 D bt_hwcfg: hw_epilog_process
,08-08 12:03:19.965  3398  3443 I bt_vendor: low_power_mode_cb
,08-08 12:03:19.988  3398  3443 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-08 12:03:19.988  3398  3443 I bt_vendor: epilog_cb
08-08 12:03:19.988  3398  3443 I bt_hci  : epilog_finished_callback
,08-08 12:03:19.991  3398  3436 I bt_hci_h4: hal_close
,08-08 12:03:19.992  3398  3436 I bt_userial_vendor: device fd = 51 close
,08-08 12:03:20.055   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-08 12:03:20.074  1661  1661 I Keyboard.Facilitator: onFinishInput()
,08-08 12:03:20.092   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 12:03:20.092   873   893 I Adreno  : Build Date                       : 10/20/15
08-08 12:03:20.092   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 12:03:20.092   873   893 I Adreno  : Local Branch                     : M14
08-08 12:03:20.092   873   893 I Adreno  : Remote Branch                    : 
08-08 12:03:20.092   873   893 I Adreno  : Remote Branch                    : 
08-08 12:03:20.092   873   893 I Adreno  : Reconstruct Branch               : 
,08-08 12:03:20.114   281   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (113 us)
,08-08 12:03:20.118  3398  3433 D bt_stack_manager: event_shut_down_stack finished.
,08-08 12:03:20.121  3398  3432 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-08 12:03:20.128  3398  3398 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 12:03:20.128  3398  3432 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-08 12:03:20.129  3398  3398 D BtGatt.GattService: Received stop request...Stopping profile...
08-08 12:03:20.129  3398  3398 D BtGatt.GattService: stop()
08-08 12:03:20.130  3398  3398 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 12:03:20.135  3398  3398 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:20.137  3398  3398 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:20.137  3398  3398 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:20.139  3398  3398 V BluetoothAdapterState: isBleTurningOff()=true
,08-08 12:03:20.140  3398  3432 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-08 12:03:20.141  3398  3432 D BluetoothAdapterProperties: Setting state to 10
08-08 12:03:20.142  3398  3432 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-08 12:03:20.143  3398  3432 I BluetoothAdapterState: Entering OffState
,08-08 12:03:20.145   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-08 12:03:20.160  3398  3398 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-08 12:03:20.160  3398  3398 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-08 12:03:20.160  3398  3433 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-08 12:03:20.162  3398  3433 D bt_stack_manager: event_clean_up_stack finished.
08-08 12:03:20.162  3398  3398 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-08 12:03:20.163  3398  3398 I art     : System.exit called, status: 0
,08-08 12:03:20.164  3398  3398 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-08 12:03:20.216   873  1706 I ActivityManager: Process com.android.bluetooth (pid 3398) has died
,08-08 12:03:20.738  3337  3337 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-08 12:03:20.738  3337  3337 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-08 12:03:20.765  3337  3337 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@499a784 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5cbcd07, 16908290=android.view.AbsSavedState$1@5cbcd07}, android:focusedViewId=100}]}]
,08-08 12:03:20.765  3337  3337 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-08 12:03:20.765  3337  3337 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-08 12:03:20.765  3337  3337 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-08 12:03:20.765   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-08 12:03:20.772   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-08 12:03:20.775   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-08 12:03:20.777   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-08 12:03:20.777   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-08 12:03:20.928  3682  3716 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-08 12:03:21.012   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-08 12:03:21.015   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-08 12:03:21.021   873  1339 D SurfaceControl: Excessive delay in setPowerMode(): 246ms
,08-08 12:03:21.024   873   893 I DreamManagerService: Entering dreamland.
,08-08 12:03:21.026   873   893 I PowerManagerService: Dozing...
08-08 12:03:21.027   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-08 12:03:21.079   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-08 12:03:21.079   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-08 12:03:21.092  1760  3824 D NfcService: Discovery configuration equal, not updating.
,08-08 12:03:21.093   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 12:03:21.096   873  1312 E native  : do suspend false
,08-08 12:03:21.130   873  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 12:03:21.135   873  1312 E native  : do suspend true
,08-08 12:03:21.221   376  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-08 12:03:21.222   376  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-08 12:03:22.630   873  1314 D ConnectivityService: handlePromptUnvalidated 100
,08-08 12:03:22.713   873   890 I ActivityManager: Start proc 3828:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-08 12:03:22.807  3828  3828 D AdapterServiceConfig: Adding HeadsetService
08-08 12:03:22.807  3828  3828 D AdapterServiceConfig: Adding A2dpService
,08-08 12:03:22.807  3828  3828 D AdapterServiceConfig: Adding HidService
08-08 12:03:22.807  3828  3828 D AdapterServiceConfig: Adding HealthService
08-08 12:03:22.808  3828  3828 D AdapterServiceConfig: Adding PanService
08-08 12:03:22.808  3828  3828 D AdapterServiceConfig: Adding GattService
08-08 12:03:22.808  3828  3828 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 12:03:22.818  3828  3828 D BluetoothAdapterState: make() - Creating AdapterState
08-08 12:03:22.818   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7c7f175:true
,08-08 12:03:22.827  3828  3828 I bt_bluedroid: init
,08-08 12:03:22.827  3828  3840 I BluetoothAdapterState: Entering OffState
,08-08 12:03:22.832  3828  3841 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 12:03:22.833  3828  3841 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-08 12:03:22.833  3828  3841 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-08 12:03:22.833  3828  3841 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 12:03:22.835  3828  3828 I bt_bluedroid: get_profile_interface socket
,08-08 12:03:22.837  3828  3844 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 12:03:22.838  3828  3828 I bt_bluedroid: get_profile_interface sdp
,08-08 12:03:22.838  3828  3844 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 12:03:22.844  3828  3839 I bt_bluedroid: config_hci_snoop_log
,08-08 12:03:22.848   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-08 12:03:22.857  3828  3840 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 12:03:22.858  3828  3840 D BluetoothAdapterProperties: Setting state to 14
08-08 12:03:22.858  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 12:03:22.863  3828  3840 D BluetoothBondStateMachine: make
,08-08 12:03:22.868  3828  3845 I BluetoothBondStateMachine: StableState(): Entering Off State
08-08 12:03:22.869  3828  3840 I BluetoothAdapterState: Entering PendingCommandState
,08-08 12:03:22.872  3828  3828 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 12:03:22.880  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:22.882  3828  3828 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 12:03:22.883  3828  3828 D BtGatt.GattService: Received start request. Starting profile...
08-08 12:03:22.884  3828  3828 D BtGatt.GattService: start()
,08-08 12:03:22.884  3828  3828 I bt_bluedroid: get_profile_interface gatt
,08-08 12:03:22.886  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:22.886  3828  3828 D BtGatt.AdvertiseManager: advertise manager created
,08-08 12:03:22.894  3828  3828 V BluetoothAdapterState: isTurningOff()=false
08-08 12:03:22.894  3828  3828 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:22.895  3828  3828 V BluetoothAdapterState: isBleTurningOn()=true
08-08 12:03:22.895  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:22.895  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-08 12:03:22.895  3828  3840 I bt_bluedroid: enable
08-08 12:03:22.895  3828  3841 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-08 12:03:22.896  3828  3841 I bt_hci  : start_up
,08-08 12:03:22.902  3828  3841 I bt_vendor: alloc value 0xb3a85189
,08-08 12:03:22.903  3828  3841 I bt_vendor: init
08-08 12:03:22.903  3828  3841 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 12:03:22.903  3828  3841 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 12:03:23.011  3828  3841 D bt_hci  : start_up starting async portion
,08-08 12:03:23.011  3828  3848 I bt_hci  : event_finish_startup
08-08 12:03:23.012  3828  3848 I bt_hci_h4: hal_open
,08-08 12:03:23.012  3828  3848 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 12:03:23.021  3828  3848 I bt_userial_vendor: device fd = 51 open
,08-08 12:03:23.053  3828  3848 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 12:03:23.085  3828  3848 D bt_hwcfg: Chipset BCM4354A2
,08-08 12:03:23.085  3828  3848 D bt_hwcfg: Target name = [BCM4354A2]
08-08 12:03:23.086  3828  3848 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 12:03:23.741  3828  3848 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 12:03:23.742  3828  3848 D bt_hwcfg: Settlement delay -- 100 ms
08-08 12:03:23.743  3828  3848 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 12:03:23.858  3828  3848 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 12:03:23.858  3828  3848 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 12:03:23.890  3828  3848 I bt_hwcfg: vendor lib fwcfg completed
,08-08 12:03:23.890  3828  3848 I bt_vendor: firmware callback
08-08 12:03:23.890  3828  3848 I bt_hci  : firmware_config_callback
,08-08 12:03:23.895  3828  3850 I bt_btu  : btu_task pending for preload complete event
,08-08 12:03:23.895  3828  3850 I bt_btu_task: Bluetooth chip preload is complete
08-08 12:03:23.895  3828  3850 I bt_btu  : btu_task received preload complete event
,08-08 12:03:23.899  3828  3850 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 12:03:23.899  3828  3850 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-08 12:03:23.899  3828  3850 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-08 12:03:23.899  3828  3850 I         : BTE_InitTraceLevels -- TRC_AVDT
08-08 12:03:23.900  3828  3850 I         : BTE_InitTraceLevels -- TRC_AVRC
08-08 12:03:23.900  3828  3850 I         : BTE_InitTraceLevels -- TRC_A2D
08-08 12:03:23.900  3828  3850 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 12:03:23.900  3828  3850 I         : BTE_InitTraceLevels -- TRC_BTM
08-08 12:03:23.901  3828  3850 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 12:03:23.901  3828  3850 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 12:03:23.901  3828  3850 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 12:03:23.901  3828  3850 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 12:03:23.901  3828  3850 I         : BTE_InitTraceLevels -- TRC_SMP
,08-08 12:03:23.902  3828  3850 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 12:03:23.902  3828  3850 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 12:03:24.028  3828  3850 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a02d9d
08-08 12:03:24.028  3828  3850 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a02d9d 
,08-08 12:03:24.038  3828  3844 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 12:03:24.041  3828  3844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 12:03:24.041  3828  3844 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 12:03:24.048  3828  3844 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 12:03:24.052  3828  3844 D BluetoothAdapterProperties: Scan Mode:20
08-08 12:03:24.053  3828  3844 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-08 12:03:24.053  3828  3844 D bt_hci  : do_postload posting postload work item
,08-08 12:03:24.054  3828  3848 I bt_hci  : event_postload
,08-08 12:03:24.054  3828  3848 I bt_vendor: sco_config_cb
,08-08 12:03:24.054  3828  3848 I bt_hci  : sco_config_callback postload finished.
,08-08 12:03:24.059  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:24.063  3828  3844 D bt_bte_conf: Device ID record 1 : primary
08-08 12:03:24.063  3828  3844 D bt_bte_conf:   vendorId            = 000f
08-08 12:03:24.063  3828  3844 D bt_bte_conf:   vendorIdSource      = 0001
08-08 12:03:24.063  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:24.063  3828  3844 D bt_bte_conf:   product             = 1200
,08-08 12:03:24.064  3828  3844 D bt_bte_conf:   version             = 1436
08-08 12:03:24.064  3828  3848 I bt_vendor: low_power_mode_cb
08-08 12:03:24.064  3828  3844 D bt_bte_conf:   clientExecutableURL = 
,08-08 12:03:24.066  3828  3844 D bt_bte_conf:   serviceDescription  = 
08-08 12:03:24.066  3828  3844 D bt_bte_conf:   documentationURL    = 
,08-08 12:03:24.066  3828  3844 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-08 12:03:24.068  3828  3841 D bt_stack_manager: event_start_up_stack finished
,08-08 12:03:24.069  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-08 12:03:24.070  3828  3840 D BluetoothAdapterProperties: Setting state to 15
08-08 12:03:24.070  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-08 12:03:24.070  3828  3840 I BluetoothAdapterState: Entering BleOnState
,08-08 12:03:24.075  3828  3840 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-08 12:03:24.075  3828  3840 D BluetoothAdapterProperties: Setting state to 11
08-08 12:03:24.075  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 12:03:24.084  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:24.087  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:24.089  3828  3828 D HeadsetService: Received start request. Starting profile...
08-08 12:03:24.091  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:24.092  3828  3828 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-08 12:03:24.093  3828  3828 D HeadsetStateMachine: make
08-08 12:03:24.096  3828  3840 I BluetoothAdapterState: Entering PendingCommandState
,08-08 12:03:24.101  3828  3828 D HeadsetStateMachine: max_hf_connections = 1
,08-08 12:03:24.101  3828  3828 I bt_bluedroid: get_profile_interface handsfree
,08-08 12:03:24.101  3828  3844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-08 12:03:24.101  3828  3844 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-08 12:03:24.107  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:24.108  3828  3828 D A2dpService: Received start request. Starting profile...
08-08 12:03:24.108  3828  3828 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-08 12:03:24.109  3828  3828 I bt_bluedroid: get_profile_interface avrcp
,08-08 12:03:24.115  3828  3828 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 12:03:24.116  3828  3828 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 12:03:24.116  3828  3828 D A2dpStateMachine: make
,08-08 12:03:24.118  3828  3828 I bt_bluedroid: get_profile_interface a2dp
,08-08 12:03:24.118  3828  3844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 12:03:24.120  3828  3860 D A2dpStateMachine: Enter Disconnected: -2
,08-08 12:03:24.121  3828  3828 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 12:03:24.122  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:24.123  3828  3828 D HidService: Received start request. Starting profile...
,08-08 12:03:24.123  3828  3828 I bt_bluedroid: get_profile_interface hidhost
08-08 12:03:24.123  3828  3844 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e43e5
,08-08 12:03:24.123  3828  3844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-08 12:03:24.124  3828  3828 D HidService: setHidService(): set to: null
,08-08 12:03:24.126  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 12:03:24.127  3828  3828 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-08 12:03:24.128  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
08-08 12:03:24.129  3828  3828 D HealthService: Received start request. Starting profile...
,08-08 12:03:24.130  3828  3828 I bt_bluedroid: get_profile_interface health
,08-08 12:03:24.131  3828  3828 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 12:03:24.132  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:24.132  3828  3828 D PanService: Received start request. Starting profile...
08-08 12:03:24.132  3828  3828 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-08 12:03:24.133  3828  3828 I bt_bluedroid: get_profile_interface pan
,08-08 12:03:24.133  3828  3844 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-08 12:03:24.136  3828  3828 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5e05d8
,08-08 12:03:24.138  3828  3828 D BluetoothMapService: Received start request. Starting profile...
,08-08 12:03:24.138  3828  3828 D BluetoothMapService: start()
,08-08 12:03:24.141  3828  3828 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-08 12:03:24.142  3828  3828 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-08 12:03:24.143  3828  3828 D BluetoothMapAppObserver: createReceiver()
,08-08 12:03:24.144  3828  3828 D BluetoothMapAppObserver: initObservers()
,08-08 12:03:24.144  3828  3828 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 12:03:24.153  3828  3828 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:24.153  3828  3828 V BluetoothAdapterState: isTurningOn()=true
08-08 12:03:24.153  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:24.153  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:24.156  3828  3828 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:24.156  3828  3828 V BluetoothAdapterState: isTurningOn()=true,
,08-08 12:03:24.156  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false,
,08-08 12:03:24.156  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:24.156  3828  3828 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:24.156  3828  3828 V BluetoothAdapterState: isTurningOn()=true
,08-08 12:03:24.157  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:24.157  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:24.157  3828  3858 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-08 12:03:24.159  3828  3828 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:24.159  3828  3828 V BluetoothAdapterState: isTurningOn()=true
,08-08 12:03:24.160  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:24.160  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false,
,08-08 12:03:24.160  3828  3828 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:24.161  3828  3828 V BluetoothAdapterState: isTurningOn()=true
,08-08 12:03:24.161  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:24.161  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 12:03:24.162  3828  3828 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:24.162  3828  3828 V BluetoothAdapterState: isTurningOn()=true
,08-08 12:03:24.162  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:24.162  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false,
,08-08 12:03:24.163  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-08 12:03:24.163  3828  3840 D BluetoothAdapterProperties: ScanMode =  20
,08-08 12:03:24.163  3828  3840 D BluetoothAdapterProperties: State =  11
08-08 12:03:24.164  3828  3840 D BluetoothAdapterProperties: Setting state to 12
08-08 12:03:24.164  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 12:03:24.165  3452  3462 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 12:03:24.165  3828  3840 I BluetoothAdapterState: Entering OnState
08-08 12:03:24.165  3828  3844 D BluetoothAdapterProperties: Scan Mode:21
08-08 12:03:24.165  3828  3844 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-08 12:03:24.169  3452  3464 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 12:03:24.171  3452  3462 D BluetoothPan: onBluetoothStateChange on: true
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:24.172  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:24.173  1776  2049 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:24.173  3828  3828 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 12:03:24.174  1367  1855 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 12:03:24.174  3828  3828 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-08 12:03:24.175  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:24.175   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:24.176  3452  3464 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:24.176  3452  3462 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 12:03:24.178   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:24.178  1367  1394 D BluetoothPan: onBluetoothStateChange on: true
,08-08 12:03:24.178  3828  3828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 12:03:24.180  3452  3464 D BluetoothMap: onBluetoothStateChange: up=true
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:24.181  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:24.183   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 12:03:24.183  1367  1387 D BluetoothMap: onBluetoothStateChange: up=true
08-08 12:03:24.184  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:24.184  3828  3828 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 12:03:24.185  1367  1854 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 12:03:24.187  1367  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:24.188  3828  3828 D ObexServerSockets: Succeed to create listening sockets 
08-08 12:03:24.188   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 12:03:24.188  3828  3828 D ObexServerSockets0: startAccept()
,08-08 12:03:24.188  1367  1394 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 12:03:24.188  3828  3828 D ObexServerSockets0: prepareForNewConnect()
,08-08 12:03:24.191   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-08 12:03:24.193  3828  3828 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-08 12:03:24.193  3828  3828 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-08 12:03:24.195   873   873 D BluetoothA2dp: Proxy object connected
,08-08 12:03:24.195  1367  1367 D BluetoothA2dp: Proxy object connected
08-08 12:03:24.198  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:24.199  3828  3866 D ObexServerSockets0: Accepting socket connection...
,08-08 12:03:24.200  3828  3865 D ObexServerSockets0: Accepting socket connection...
08-08 12:03:24.200  3828  3828 D BluetoothMapService: onReceive
,08-08 12:03:24.200  3828  3828 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 12:03:24.200  3828  3828 D BluetoothMapService: STATE_ON
08-08 12:03:24.200  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:24.201  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
,08-08 12:03:24.201  1367  1367 D PanProfile: Bluetooth service connected
,08-08 12:03:24.201  1367  1367 D BluetoothInputDevice: Proxy object connected
08-08 12:03:24.202  1367  1367 D HidProfile: Bluetooth service connected
,08-08 12:03:24.202  3452  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 12:03:24.203  1367  1367 D BluetoothMap: Proxy object connected
,08-08 12:03:24.203  1367  1367 D MapProfile: Bluetooth service connected
08-08 12:03:24.203  1367  1367 D BluetoothMap: getConnectedDevices()
08-08 12:03:24.205  3452  3452 D BluetoothA2dp: Proxy object connected
,08-08 12:03:24.208  3452  3452 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 12:03:24.208  3452  3452 D PanProfile: Bluetooth service connected
08-08 12:03:24.208  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 12:03:24.208  3452  3452 D BluetoothInputDevice: Proxy object connected
08-08 12:03:24.208  3452  3452 D HidProfile: Bluetooth service connected
,08-08 12:03:24.211  3452  3452 D BluetoothMap: Proxy object connected
,08-08 12:03:24.211  3452  3452 D MapProfile: Bluetooth service connected
,08-08 12:03:24.211  3452  3452 D BluetoothMap: getConnectedDevices()
,08-08 12:03:24.216  3452  3452 D DockEventReceiver: finishStartingService: stopping service
,08-08 12:03:24.219  3452  3452 D BluetoothPbap: Proxy object connected
,08-08 12:03:24.219  3452  3452 D PbapServerProfile: Bluetooth service connected
,08-08 12:03:24.224  3828  3828 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 12:03:24.224  3828  3828 D ObexServerSockets0: prepareForNewConnect()
08-08 12:03:24.225  3828  3871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 12:03:24.226  1367  1367 D BluetoothPbap: Proxy object connected
08-08 12:03:24.226  1367  1367 D PbapServerProfile: Bluetooth service connected
,08-08 12:03:24.241  3828  3875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 12:03:24.242  3828  3875 I BtOppRfcommListener: Accept thread started.
,08-08 12:03:24.275   873   873 D BluetoothHeadset: Proxy object connected
,08-08 12:03:24.275   873   873 D BluetoothHeadset: Proxy object connected
,08-08 12:03:24.276   873   890 D BluetoothHeadset: Proxy object connected
,08-08 12:03:24.276  3452  3462 D BluetoothHeadset: Proxy object connected
,08-08 12:03:24.277  1776  1957 D BluetoothHeadset: Proxy object connected
08-08 12:03:24.277  3452  3464 D BluetoothHeadset: Proxy object connected
08-08 12:03:24.277  3452  3452 D HeadsetProfile: Bluetooth service connected
08-08 12:03:24.277  1367  1854 D BluetoothHeadset: Proxy object connected
08-08 12:03:24.278  1367  1367 D HeadsetProfile: Bluetooth service connected
08-08 12:03:24.278   873   873 D BluetoothHeadset: Proxy object connected
08-08 12:03:24.279   873   890 D BluetoothHeadset: Proxy object connected
08-08 12:03:24.281  3452  3452 D HeadsetProfile: Bluetooth service connected
,08-08 12:03:24.288  1367  1387 D BluetoothHeadset: Proxy object connected
08-08 12:03:24.288  1367  1367 D HeadsetProfile: Bluetooth service connected
,08-08 12:03:24.288   873   890 D BluetoothHeadset: Proxy object connected
,08-08 12:03:25.609  1698  2333 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-08 12:03:25.658  3337  3387 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 12:03:25.659  3337  3387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 12:03:25.998  2599  2609 D Finsky  : [176] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-08 12:03:26.017  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:26.029  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:26.032  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:26.096  1511  3584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 12:03:26.096  1511  3584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 12:03:26.097  1511  3584 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 12:03:26.097  1511  3584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:26.146  2599  2609 D Finsky  : [176] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-08 12:03:28.666  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 12:03:28.667  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aa89e34 added. We now have 6 listener(s)
,08-08 12:03:28.667  3337  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 12:03:28.673  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 12:03:28.674  3337  3387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a37645d added. We now have 7 listener(s)
08-08 12:03:28.674  3337  3387 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 12:03:28.677  3337  3387 I System.out: IsBluetoothEnabled
,08-08 12:03:28.683  3828  3840 D BluetoothAdapterState: Current state: ON, message: 23
,08-08 12:03:28.684  3828  3840 D BluetoothAdapterProperties: Setting state to 13
,08-08 12:03:28.684  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-08 12:03:28.685  3828  3840 D BluetoothAdapterProperties: onBluetoothDisable()
,08-08 12:03:28.691  3828  3840 I BluetoothAdapterState: Entering PendingCommandState
,08-08 12:03:28.706  3828  3828 D BluetoothMapService: onReceive,
,08-08 12:03:28.706  3828  3828 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-08 12:03:28.706  3828  3828 D BluetoothMapService: STATE_TURNING_OFF
08-08 12:03:28.706  3828  3828 D BluetoothMapService: MAP Service closeService in
08-08 12:03:28.706  3828  3828 D BluetoothMapMasInstance0: MAP Service shutdown
,08-08 12:03:28.706  3828  3828 D ObexServerSockets0: shutdown(block = true)
08-08 12:03:28.707  3828  3865 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-08 12:03:28.707  3828  3828 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-08 12:03:28.708  3828  3828 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 12:03:28.708  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:28.708  3828  3866 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:28.708  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 12:03:28.708  3828  3852 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-08 12:03:28.709  3828  3844 D BluetoothAdapterProperties: Scan Mode:20
08-08 12:03:28.710  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-08 12:03:28.710  3337  3337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:28.710  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:28.711  3828  3828 I BtOppRfcommListener: stopping Accept Thread
08-08 12:03:28.711  3828  3875 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 12:03:28.711  3828  3875 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 12:03:28.712  3452  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 12:03:28.713  3828  3828 D HeadsetService: Received stop request...Stopping profile...
08-08 12:03:28.718  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 12:03:28.718  3337  3387 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 12:03:28.718  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:28.719   873   873 D BluetoothHeadset: Proxy object disconnected
,08-08 12:03:28.719   873   873 D BluetoothHeadset: Proxy object disconnected
,08-08 12:03:28.719  1776  1796 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:28.720  3452  3462 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:28.720  1367  1855 D BluetoothHeadset: Proxy object disconnected
08-08 12:03:28.721   873   873 D BluetoothHeadset: Proxy object disconnected
,08-08 12:03:28.721  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,08-08 12:03:28.721  3337  3387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 12:03:28.721  3337  3387 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 12:03:28.723  3828  3828 D A2dpService: Received stop request...Stopping profile...
08-08 12:03:28.723  3828  3860 D A2dpStateMachine: Exit Disconnected: -1
,08-08 12:03:28.724  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-08 12:03:28.724  3828  3840 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
08-08 12:03:28.726   873   873 D BluetoothA2dp: Proxy object disconnected
08-08 12:03:28.727  1367  1367 D BluetoothA2dp: Proxy object disconnected
08-08 12:03:28.727  3828  3828 D HidService: Received stop request...Stopping profile...
08-08 12:03:28.727  3828  3828 D HidService: Stopping Bluetooth HidService,
,08-08 12:03:28.728  1367  1367 D BluetoothInputDevice: Proxy object disconnected
,08-08 12:03:28.729  3828  3828 D HealthService: Received stop request...Stopping profile...
,08-08 12:03:28.729  1367  1367 D HidProfile: Bluetooth service disconnected
08-08 12:03:28.731  3828  3828 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:28.731  3828  3828 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:28.731  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:28.731  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:28.732  3828  3828 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-08 12:03:28.733  3828  3828 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 12:03:28.733  3828  3844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-08 12:03:28.733  3828  3850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:28.733  3828  3850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:28.733  3828  3850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 12:03:28.733  3828  3844 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-08 12:03:28.734  3452  3452 D DockEventReceiver: finishStartingService: stopping service
08-08 12:03:28.735  3828  3828 D PanService: Received stop request...Stopping profile...
08-08 12:03:28.735  3452  3452 D HeadsetProfile: Bluetooth service disconnected
08-08 12:03:28.735  3452  3452 D BluetoothA2dp: Proxy object disconnected
08-08 12:03:28.736  3452  3452 D BluetoothInputDevice: Proxy object disconnected
08-08 12:03:28.736  3452  3452 D HidProfile: Bluetooth service disconnected
08-08 12:03:28.736  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-08 12:03:28.736  1367  1367 D PanProfile: Bluetooth service disconnected
08-08 12:03:28.736  3828  3828 D BluetoothMapService: Received stop request...Stopping profile...
08-08 12:03:28.737  3828  3828 D BluetoothMapService: stop()
08-08 12:03:28.738  3828  3828 D BluetoothMapAppObserver: deinitObservers()
08-08 12:03:28.738  3828  3828 D BluetoothMapAppObserver: removeReceiver()
08-08 12:03:28.740  1367  1367 D BluetoothMap: Proxy object disconnected
08-08 12:03:28.740  1367  1367 D MapProfile: Bluetooth service disconnected
08-08 12:03:28.740  3452  3452 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 12:03:28.740  3452  3452 D PanProfile: Bluetooth service disconnected
08-08 12:03:28.740  3452  3452 D BluetoothMap: Proxy object disconnected
08-08 12:03:28.741  3452  3452 D MapProfile: Bluetooth service disconnected
,08-08 12:03:28.742  3828  3828 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:28.742  3828  3828 V BluetoothAdapterState: isTurningOn()=false
08-08 12:03:28.742  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:28.742  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:28.743  3828  3850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:28.743  3828  3828 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:28.743  3828  3844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-08 12:03:28.744  3828  3828 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:28.744  3828  3850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 12:03:28.744  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:28.744  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:28.744  3828  3850 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 12:03:28.744  3828  3850 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 12:03:28.744  3828  3850 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 12:03:28.744  3828  3850 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-08 12:03:28.744  3828  3828 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-08 12:03:28.744  3828  3828 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 12:03:28.744  3828  3844 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 12:03:28.744  3828  3828 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:28.744  3828  3828 V BluetoothAdapterState: isTurningOn()=false
08-08 12:03:28.744  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:28.744  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:28.745  3828  3828 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-08 12:03:28.745  3828  3844 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-08 12:03:28.745  3828  3828 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 12:03:28.745  3828  3828 V BluetoothAdapterState: isTurningOff()=true
08-08 12:03:28.745  3828  3828 V BluetoothAdapterState: isTurningOn()=false
08-08 12:03:28.746  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:28.746  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:28.745  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 12:03:28.747  3828  3828 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 12:03:28.747  3828  3828 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-08 12:03:28.748  3828  3828 D BluetoothMapService: MAP Service closeService in
,08-08 12:03:28.748  3828  3828 V BluetoothAdapterState: isTurningOff()=true
,08-08 12:03:28.748  3828  3828 V BluetoothAdapterState: isTurningOn()=false
08-08 12:03:28.748  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
08-08 12:03:28.748  3828  3828 V BluetoothAdapterState: isBleTurningOff()=false
08-08 12:03:28.749  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-08 12:03:28.749  3828  3840 D BluetoothAdapterProperties: Setting state to 15
08-08 12:03:28.749  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-08 12:03:28.749  3828  3840 I BluetoothAdapterState: Entering BleOnState
08-08 12:03:28.749  3828  3840 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-08 12:03:28.750  3452  3464 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 12:03:28.750  3828  3828 D BluetoothMapService: cleanup()
08-08 12:03:28.750  3828  3828 D BluetoothMapService: MAP Service closeService in
08-08 12:03:28.750  3452  3462 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-08 12:03:28.751  3452  3464 D BluetoothPan: onBluetoothStateChange on: false
08-08 12:03:28.751  1367  1367 D BluetoothPbap: Proxy object disconnected
08-08 12:03:28.751  1367  1367 D PbapServerProfile: Bluetooth service disconnected
08-08 12:03:28.752  1776  1787 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:28.752  1367  1394 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-08 12:03:28.754   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:28.754  3452  3462 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 12:03:28.755  3452  3464 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 12:03:28.755   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:28.755  1367  1855 D BluetoothPan: onBluetoothStateChange on: false
08-08 12:03:28.756  3452  3462 D BluetoothMap: onBluetoothStateChange: up=false
,08-08 12:03:28.757   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 12:03:28.758  1367  1854 D BluetoothMap: onBluetoothStateChange: up=false
,08-08 12:03:28.758  1367  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-08 12:03:28.759  1367  1394 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:28.759   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 12:03:28.759  1367  1855 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 12:03:28.760  3828  3840 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-08 12:03:28.760  3828  3840 D BluetoothAdapterProperties: Setting state to 16
,08-08 12:03:28.760  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-08 12:03:28.761  3828  3840 D BluetoothAdapterProperties: onBleDisable
08-08 12:03:28.761  3828  3840 I BluetoothAdapterState: Entering PendingCommandState
,08-08 12:03:28.761  3828  3841 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-08 12:03:28.762  3828  3850 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-08 12:03:28.762  3828  3850 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 12:03:28.763  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:28.764  3828  3844 D BluetoothAdapterProperties: Scan Mode:20
08-08 12:03:28.765  3452  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 12:03:28.766  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 12:03:28.771  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 12:03:28.772  3452  3452 D DockEventReceiver: finishStartingService: stopping service
,08-08 12:03:28.973  3828  3844 I bt_hci  : shut_down
,08-08 12:03:28.974  3828  3848 D bt_hwcfg: hw_epilog_process
,08-08 12:03:28.985  3828  3848 I bt_vendor: low_power_mode_cb
,08-08 12:03:29.009  3828  3848 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-08 12:03:29.009  3828  3848 I bt_vendor: epilog_cb
08-08 12:03:29.009  3828  3848 I bt_hci  : epilog_finished_callback
,08-08 12:03:29.018  3828  3844 I bt_hci_h4: hal_close
,08-08 12:03:29.020  3828  3844 I bt_userial_vendor: device fd = 51 close
,08-08 12:03:29.154  3828  3841 D bt_stack_manager: event_shut_down_stack finished.
,08-08 12:03:29.155  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-08 12:03:29.161  3828  3840 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-08 12:03:29.161  3828  3828 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 12:03:29.162  3828  3828 D BtGatt.GattService: Received stop request...Stopping profile...
08-08 12:03:29.164  3828  3828 D BtGatt.GattService: stop()
08-08 12:03:29.164  3828  3828 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 12:03:29.172  3828  3828 V BluetoothAdapterState: isTurningOff()=false
,08-08 12:03:29.172  3828  3828 V BluetoothAdapterState: isTurningOn()=false
,08-08 12:03:29.172  3828  3828 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 12:03:29.173  3828  3828 V BluetoothAdapterState: isBleTurningOff()=true
,08-08 12:03:29.174  3828  3840 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-08 12:03:29.174  3828  3840 D BluetoothAdapterProperties: Setting state to 10
,08-08 12:03:29.174  3828  3840 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-08 12:03:29.176  3828  3840 I BluetoothAdapterState: Entering OffState
08-08 12:03:29.189  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 12:03:29.193  3452  3452 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 12:03:29.205  1511  1511 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 12:03:29.211  3452  3452 D DockEventReceiver: finishStartingService: stopping service
,08-08 12:03:29.497   873  1397 I ActivityManager: Killing 3173:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-08 12:03:42.623  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:42.638  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:42.641  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:03:42.678  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-08 12:03:42.678  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 12:03:42.678  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 12:03:42.678  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:03:42.710  2599  2599 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 12:03:42.710  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 12:03:42.710  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-08 12:04:02.923  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:04:02.929  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:04:02.932  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:04:02.970  1511  3584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-08 12:04:02.970  1511  3584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 12:04:02.971  1511  3584 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:04:02.971  1511  3584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:04:03.012  2599  2599 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-08 12:04:03.012  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-08 12:04:03.012  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-08 12:04:11.387  1511  1950 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-08 12:04:16.901   873  1314 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-08 12:04:20.115  1661  1808 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-08 12:04:20.116  1661  1808 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-08 12:04:20.150  1511  1511 I ConfigService: onCreate
,08-08 12:04:23.272  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:04:23.282  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:04:23.286  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:04:23.324  1511  1522 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 12:04:23.324  1511  1522 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 12:04:23.325  1511  1522 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:04:23.325  1511  1522 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:04:23.360  2599  2599 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 12:04:23.360  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 12:04:23.361  2599  2599 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-08 12:04:25.185  1511  1511 I ConfigService: onDestroy
,08-08 12:06:21.539  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:06:21.553  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:06:21.560  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:06:21.603  1511  2064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-08 12:06:21.603  1511  2064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 12:06:21.603  1511  2064 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:06:21.603  1511  2064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:06:21.640  1511  2064 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 12:06:21.640  1511  2064 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 12:06:21.640  1511  2064 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 12:06:21.640  1511  2064 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 12:06:21.640  1511  2064 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 12:06:21.640  1511  2064 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 12:06:21.640  1511  2064 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:06:21.645  2599  2629 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 12:06:21.645  2599  2629 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 12:06:21.645  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 12:06:21.645  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 12:06:21.645  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 12:06:21.645  2599  2629 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 12:06:21.645  2599  2629 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:11:21.810  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:11:21.829  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:11:21.834  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:11:21.897  1511  1882 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 12:11:21.898  1511  1882 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 12:11:21.898  1511  1882 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:11:21.899  1511  1882 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:11:21.950  1511  1882 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 12:11:21.950  1511  1882 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 12:11:21.950  1511  1882 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 12:11:21.950  1511  1882 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 12:11:21.950  1511  1882 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 12:11:21.950  1511  1882 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 12:11:21.950  1511  1882 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:11:21.963  2599  2629 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 12:11:21.963  2599  2629 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 12:11:21.963  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 12:11:21.963  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 12:11:21.963  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 12:11:21.963  2599  2629 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 12:11:21.963  2599  2629 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:16:22.106  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:16:22.120  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:16:22.123  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:16:22.180  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 12:16:22.180  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 12:16:22.181  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:16:22.181  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:16:22.234  1511  1523 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 12:16:22.234  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 12:16:22.234  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 12:16:22.234  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 12:16:22.234  1511  1523 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 12:16:22.234  1511  1523 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 12:16:22.234  1511  1523 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:16:22.248  2599  2629 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 12:16:22.248  2599  2629 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 12:16:22.248  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 12:16:22.248  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 12:16:22.248  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 12:16:22.248  2599  2629 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 12:16:22.248  2599  2629 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:21:08.829   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-08 12:21:22.390  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:21:22.409  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:21:22.413  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:21:22.481  1511  2064 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 12:21:22.481  1511  2064 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 12:21:22.482  1511  2064 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 12:21:22.482  1511  2064 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:21:22.527  1511  2064 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 12:21:22.527  1511  2064 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 12:21:22.527  1511  2064 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 12:21:22.527  1511  2064 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 12:21:22.527  1511  2064 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 12:21:22.527  1511  2064 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 12:21:22.527  1511  2064 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:21:22.537  2599  2629 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 12:21:22.537  2599  2629 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 12:21:22.537  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 12:21:22.537  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 12:21:22.537  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 12:21:22.537  2599  2629 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 12:21:22.537  2599  2629 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:26:22.676  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:26:22.699  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:26:22.706  1511  1511 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 12:26:22.797  1511  1523 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 12:26:22.798  1511  1523 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 12:26:22.798  1511  1523 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 12:26:22.799  1511  1523 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 12:26:22.834  1511  1523 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 12:26:22.834  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 12:26:22.834  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 12:26:22.834  1511  1523 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 12:26:22.834  1511  1523 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 12:26:22.834  1511  1523 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 12:26:22.834  1511  1523 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 12:26:22.846  2599  2629 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 12:26:22.846  2599  2629 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 12:26:22.846  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 12:26:22.846  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 12:26:22.846  2599  2629 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 12:26:22.846  2599  2629 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 12:26:22.846  2599  2629 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-08 12:26:23.627  3976  3976 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-08 12:26:23.631  3976  3976 D AndroidRuntime: CheckJNI is OFF
08-08 12:26:23.667  3976  3976 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-08 12:26:23.708  3976  3976 I Radio-JNI: register_android_hardware_Radio DONE
08-08 12:26:23.729  3976  3976 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-08 12:26:23.742   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-08 12:26:23.743   873   886 I ActivityManager: Killing 3337:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-08 12:26:23.850   873  1612 I WindowState: WIN DEATH: Window{35c0c41 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-08 12:26:23.851   873  1313 D WifiService: Client connection lost with reason: 4
08-08 12:26:23.851   873   884 D GraphicsStats: Buffer count: 2
08-08 12:26:23.868   873   897 W PackageSettings: Skipping PackageSetting{1f7d4c5 com.example.hello/10273} due to missing metadata
08-08 12:26:23.918   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-08 12:26:23.918   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-08 12:26:23.921   873   897 I art     : Starting a blocking GC Explicit
08-08 12:26:23.925   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-08 12:26:23.925   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-08 12:26:23.925   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:26:23.925   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:23.925   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 12:26:23.925   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-08 12:26:23.926   873   886 I ActivityManager:   Force finishing activity ActivityRecord{357e5ae u0 com.test.thalitest/.MainActivity t2}
08-08 12:26:23.930   873  1911 W ActivityManager: Spurious death for ProcessRecord{89219d8 0:com.test.thalitest/u0a0}, curProc for 3337: null
08-08 12:26:23.963   873   897 I art     : Explicit concurrent mark sweep GC freed 33790(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 716us total 41.516ms
08-08 12:26:24.007   873   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-08 12:26:24.014  3976  3976 I art     : System.exit called, status: 0
08-08 12:26:24.014  3976  3976 I AndroidRuntime: VM exiting with result code 0.
08-08 12:26:24.062   873   897 I ActivityManager: Start proc 3989:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-08 12:26:24.062   873   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-08 12:26:24.088   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-08 12:26:24.096   873  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-08 12:26:24.097  1698  2000 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-08 12:26:24.104  3213  3213 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-08 12:26:24.099  1661  1661 I Keyboard.Facilitator: resetDictionaries() : en_US
08-08 12:26:24.111  1661  4002 I Keyboard.Facilitator.DecoderInitializer: run()
08-08 12:26:24.113  1661  4002 I Decoder : createOrResetDecoder
08-08 12:26:24.149   873  1697 I ActivityManager: Start proc 4006:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-08 12:26:24.158  1776  1776 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-08 12:26:24.163   873  1310 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-08 12:26:24.169   873  1612 I ActivityManager: Killing 3266:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-08 12:26:24.186   873  1795 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3337 uid 10000
08-08 12:26:24.187  1661  1661 I Keyboard.Facilitator: onFinishInput()
08-08 12:26:24.221  1511  1511 I ConfigService: onCreate
08-08 12:26:24.223   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-08 12:26:24.233  4006  4006 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-08 12:26:24.238  1511  4018 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-08 12:26:24.239  1789  1862 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-08 12:26:24.239  1511  4018 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-08 12:26:24.239   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-08 12:26:24.240   873   885 E PackageManager: Failed to write settings, restoring backup
08-08 12:26:24.240   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-08 12:26:24.240   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-08 12:26:24.240   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-08 12:26:24.240   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-08 12:26:24.240   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-08 12:26:24.240   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:26:24.240   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.240   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 12:26:24.240  1511  4018 W SQLiteOpenHelper: Opened config.db in read-only mode
08-08 12:26:24.251   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-08 12:26:24.251   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-08 12:26:24.251   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 12:26:24.251   873   886 E DropBoxManagerService: 	... 13 more
08-08 12:26:24.252   873  2063 I ActivityManager: Start proc 4019:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-08 12:26:24.253  1789  1862 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-08 12:26:24.253  1789  1862 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1789
08-08 12:26:24.253  1789  1862 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.253  1789  1862 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 12:26:24.255   873  1911 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-08 12:26:24.259  1789  1862 I Process : Sending signal. PID: 1789 SIG: 9
08-08 12:26:24.260   873  4025 E DropBoxManagerService: Can't write: system_app_crash
08-08 12:26:24.260   873  4025 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 12:26:24.260   873  4025 E DropBoxManagerService: 	... 5 more
08-08 12:26:24.285  1661  4002 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-08 12:26:24.307  1661  4002 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-08 12:26:24.309  1661  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-08 12:26:24.309  1661  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-08 12:26:24.311  1661  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-08 12:26:24.311  1661  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-08 12:26:24.312  1661  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-08 12:26:24.313  1661  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-08 12:26:24.319  1661  4002 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-08 12:26:24.319  1661  4002 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-08 12:26:24.319  1661  4002 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-08 12:26:24.321  1661  4002 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-08 12:26:24.321  1661  4002 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-08 12:26:24.321  1661  4002 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-08 12:26:24.330   873  2063 I WindowState: WIN DEATH: Window{f436551 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-08 12:26:24.330   873   883 D GraphicsStats: Buffer count: 1
08-08 12:26:24.342   873  1911 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1789) has died
08-08 12:26:24.343   873  1911 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-08 12:26:24.346   873  1911 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-08 12:26:24.362   873   886 I ActivityManager: Start proc 4038:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-08 12:26:24.365  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-08 12:26:24.384   873  1795 I ActivityManager: Start proc 4050:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-08 12:26:24.401  4006  4055 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:26:24.418  4038  4038 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 12:26:24.418  4038  4038 D AndroidRuntime: Shutting down VM
08-08 12:26:24.426  4038  4038 E AndroidRuntime: FATAL EXCEPTION: main
08-08 12:26:24.426  4038  4038 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4038
08-08 12:26:24.426  4038  4038 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-08 12:26:24.426  4038  4038 E AndroidRuntime: 	... 10 more
08-08 12:26:24.428   873  2063 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-08 12:26:24.429  4038  4038 I Process : Sending signal. PID: 4038 SIG: 9
08-08 12:26:24.430   873  4064 E DropBoxManagerService: Can't write: system_app_crash
08-08 12:26:24.430   873  4064 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 12:26:24.430   873  4064 E DropBoxManagerService: 	... 5 more
08-08 12:26:24.442  4050  4050 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.444  4006  4055 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-08 12:26:24.445  4006  4055 E AndroidRuntime: Process: android.process.acore, PID: 4006
08-08 12:26:24.445  4006  4055 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.445  4006  4055 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: Can't write: system_app_crash
08-08 12:26:24.447   873  4065 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 12:26:24.447   873  4065 E DropBoxManagerService: 	... 5 more
08-08 12:26:24.452  4006  4055 I Process : Sending signal. PID: 4006 SIG: 9
08-08 12:26:24.453  1732  4062 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-08 12:26:24.455  1732  4062 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-08 12:26:24.460   873  1718 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4038) has died
08-08 12:26:24.462   873  1718 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-08 12:26:24.476   873   886 I ActivityManager: Start proc 4068:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-08 12:26:24.477   279   279 E lowmemorykiller: Error writing /proc/4006/oom_score_adj; errno=22
08-08 12:26:24.479   279   279 E lowmemorykiller: Error writing /proc/4006/oom_score_adj; errno=22
08-08 12:26:24.483  1732  4062 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-08 12:26:24.485  1732  4062 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-08 12:26:24.489   873  1911 I ActivityManager: Killing 1833:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-08 12:26:24.496  1511  1511 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-08 12:26:24.496  1511  1511 D AndroidRuntime: Shutting down VM
08-08 12:26:24.497  1511  1511 E AndroidRuntime: FATAL EXCEPTION: main
08-08 12:26:24.497  1511  1511 E AndroidRuntime: Process: com.google.process.gapps, PID: 1511
08-08 12:26:24.497  1511  1511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-08 12:26:24.497  1511  1511 E AndroidRuntime: 	... 8 more

```
