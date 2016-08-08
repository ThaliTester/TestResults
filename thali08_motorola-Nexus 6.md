#### Test 79689775691c720_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-08 14:23:18.295  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:23:18.313  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 14:23:18.319  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 14:23:18.407  1487  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-08 14:23:18.407  1487  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-08 14:23:18.408  1487  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:23:18.408  1487  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 14:23:18.444  2575  2575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-08 14:23:18.445  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-08 14:23:18.445  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
08-08 14:23:18.979  3314  3314 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-08 14:23:18.984  3314  3314 D AndroidRuntime: CheckJNI is OFF
08-08 14:23:19.020  3314  3314 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-08 14:23:19.065  3314  3314 I Radio-JNI: register_android_hardware_Radio DONE
08-08 14:23:19.085  3314  3314 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-08 14:23:19.089   873  1780 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 14:23:19.126  1834  1846 W SearchService: Abort, client detached.
08-08 14:23:19.141  1834  2102 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5b80a40
08-08 14:23:19.141  1834  2115 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-08 14:23:19.141  1834  1834 I HotwordDetector: Closing mic
08-08 14:23:19.142  3314  3314 D AndroidRuntime: Shutting down VM
08-08 14:23:19.159   873  1794 I ActivityManager: Start proc 3324:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-08 14:23:19.177  1834  1834 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-08 14:23:19.203   377  2117 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-08 14:23:19.205   377  2117 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-08 14:23:19.215   377  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-08 14:23:19.217  1834  2114 I MicroRecognitionRnrImpl: Detection finished
08-08 14:23:19.218  1834  2108 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-08 14:23:19.287  3324  3324 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-08 14:23:19.318  3324  3324 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-08 14:23:19.329  3324  3324 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2044-2049)
08-08 14:23:19.329  3324  3324 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 14:23:19.348  3324  3324 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10bf90d}
08-08 14:23:19.349  3324  3324 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 14:23:19.349  3324  3324 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 14:23:19.357  3324  3324 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-08 14:23:19.359  3324  3324 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-08 14:23:19.389  3324  3339 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-08 14:23:19.404  3324  3324 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-08 14:23:19.421  3324  3324 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 14:23:19.421  3324  3324 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 14:23:19.421  3324  3324 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 14:23:19.421  3324  3324 I Adreno  : Build Date                       : 10/20/15
08-08 14:23:19.421  3324  3324 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 14:23:19.421  3324  3324 I Adreno  : Local Branch                     : M14
08-08 14:23:19.421  3324  3324 I Adreno  : Remote Branch                    : 
08-08 14:23:19.421  3324  3324 I Adreno  : Remote Branch                    : 
08-08 14:23:19.421  3324  3324 I Adreno  : Reconstruct Branch               : 
08-08 14:23:19.511   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f201c0b:true
08-08 14:23:19.576  3324  3324 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-08 14:23:19.598  3324  3324 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-08 14:23:19.687  3324  3361 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-08 14:23:19.698  3324  3348 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-08 14:23:19.737  3324  3361 I OpenGLRenderer: Initialized EGL, version 1.4
08-08 14:23:19.810   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +666ms
08-08 14:23:19.818  1651  1651 I Keyboard.Facilitator: onFinishInput()
08-08 14:23:19.865  3324  3324 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3324
08-08 14:23:19.969  3324  3324 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-08 14:23:20.044   873   884 I ActivityManager: Killing 2311:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
08-08 14:23:20.090   873   884 I ActivityManager: Killing 2991:com.qualcomm.telephony/1001 (adj 15): empty #18
08-08 14:23:20.209  3324  3364 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684862672
08-08 14:23:20.217  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 14:23:20.217  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 14:23:20.217  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 14:23:20.217  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 14:23:20.217  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-08 14:23:20.217  3324  3364 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@66ddfe8 added. We now have 1 listener(s)
08-08 14:23:20.221  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-08 14:23:20.225  3324  3364 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 14:23:20.226  3324  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 14:23:20.227  3324  3364 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-08 14:23:20.232  3324  3364 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@769d6e7 added. We now have 1 listener(s)
08-08 14:23:20.232  3324  3364 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 14:23:20.235   873  1304 D WifiService: New client listening to asynchronous messages
08-08 14:23:20.237  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 14:23:20.237  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-08 14:23:20.237  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-08 14:23:20.237  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-08 14:23:20.237  3324  3364 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-08 14:23:20.243  3324  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 14:23:20.243  3324  3364 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-08 14:23:20.248  3324  3364 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:20.248  3324  3364 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:20.248  3324  3364 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-08 14:23:20.248  3324  3364 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 14:23:20.249  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:20.249  3324  3364 I io.jxcore.node.LifeCycleMonitor: start: OK
08-08 14:23:20.504  3324  3324 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 14:23:21.377  3324  3371 W jxcore-log: Initializing JXcore engine
,08-08 14:23:21.377  3324  3371 W jxcore-log: JXcore engine is ready
,08-08 14:23:21.415  3371  3371 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8979 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-08 14:23:21.415  3371  3371 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9739]" dev="sockfs" ino=9739 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-08 14:23:21.415  3371  3371 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-08 14:23:21.415  3371  3371 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23201]" dev="sockfs" ino=23201 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-08 14:23:21.429  3324  3371 W jxcore-log: Starting JXcore engine
,08-08 14:23:21.560  3324  3371 W jxcore-log: Platform android
08-08 14:23:21.560  3324  3371 W jxcore-log: 
,08-08 14:23:21.560  3324  3371 W jxcore-log: Process ARCH arm
08-08 14:23:21.560  3324  3371 W jxcore-log: 
,08-08 14:23:21.793  3324  3371 I jxcore-log: JXcore Cordova bridge is ready!
08-08 14:23:21.793  3324  3371 I jxcore-log: 
,08-08 14:23:21.793  3324  3371 W jxcore-log: JXcore engine is started
,08-08 14:23:21.803  3324  3364 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-08 14:23:21.808  3324  3324 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-08 14:23:37.737  3324  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-08 14:23:37.737  3324  3371 I jxcore-log: 
,08-08 14:23:37.739  3324  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-08 14:23:37.739  3324  3371 I jxcore-log: 
,08-08 14:23:37.741  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:37.741  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:37.741  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:37.742  3324  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:37.744  3324  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-08 14:23:37.744  3324  3371 I jxcore-log: 
08-08 14:23:37.745  3324  3371 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-08 14:23:37.745  3324  3371 I jxcore-log: 
,08-08 14:23:38.091  3324  3371 D ExecuteNativeTests: Running unit tests
,08-08 14:23:38.159  3324  3371 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-08 14:23:38.160  3324  3371 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 added. We now have 2 listener(s)
,08-08 14:23:38.161  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-08 14:23:38.161  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 14:23:38.161  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-08 14:23:38.161  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 14:23:38.161  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 added. We now have 2 listener(s)
08-08 14:23:38.161  3324  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 14:23:38.162  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-08 14:23:38.166  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 14:23:38.168  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:38.169  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 14:23:38.169  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:38.169  3324  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:38.170  3324  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-08 14:23:38.172  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:38.178  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 14:23:38.178  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 14:23:38.178  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 14:23:38.179  3324  3371 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-08 14:23:38.180  3324  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 14:23:38.180  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 14:23:38.180  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 14:23:38.180  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 14:23:38.181  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.181  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.181  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.182  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.182  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.182  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 14:23:38.182  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-08 14:23:38.182  3324  3371 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 removed from the list
08-08 14:23:38.182  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.182  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 removed from the list
08-08 14:23:38.182  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.182  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.184  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.184  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.185  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.185  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.185  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.185  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.189  3324  3371 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-08 14:23:38.190  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 14:23:38.190  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.190  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.190  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.190  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.190  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.190  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.190  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.190  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.190  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.191  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.191  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.191  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.191  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.191  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.191  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.191  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.191  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 14:23:38.196  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-08 14:23:38.197  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-08 14:23:38.197  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 14:23:38.197  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.197  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.198  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.198  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.198  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.198  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.198  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.198  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.198  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.198  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.198  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.198  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.198  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.199  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.199  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.199  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.199  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.199  3324  3371 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 14:23:38.201  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 14:23:38.202  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:38.202  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:38.202  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.202  3324  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:38.202  3324  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 14:23:38.202  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 14:23:38.202  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 14:23:38.203  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-08 14:23:38.203  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 14:23:38.203  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-08 14:23:38.204  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:38.205  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 14:23:38.206  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-08 14:23:38.206  3324  3371 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-08 14:23:38.206  3324  3371 I io.jxcore.node.ConnectionHelper: start: OK
08-08 14:23:38.206  3324  3324 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 14:23:38.207  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.207  3324  3371 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,08-08 14:23:38.208  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.208  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.208  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-08 14:23:38.208  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.208  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-08 14:23:38.209  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 14:23:38.209  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 14:23:38.209  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-08 14:23:38.209  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 14:23:38.209  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-08 14:23:38.210  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-08 14:23:38.211  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 14:23:38.211  3324  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 14:23:38.211  3324  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 14:23:38.211  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 14:23:38.211  3324  3324 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 14:23:38.211  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.211  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-08 14:23:38.211  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.211  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.211  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.211  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.211  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.212  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.212  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.212  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.212  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.212  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.212  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.213  3324  3371 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-08 14:23:38.215  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 14:23:38.215  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:38.215  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:38.215  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.215  3324  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:38.216  3324  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 14:23:38.216  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-08 14:23:38.216  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-08 14:23:38.216  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-08 14:23:38.216  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 14:23:38.216  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-08 14:23:38.217  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:38.218  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-08 14:23:38.218  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-08 14:23:38.218  3324  3371 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-08 14:23:38.218  3324  3371 I io.jxcore.node.ConnectionHelper: start: OK
08-08 14:23:38.218  3324  3324 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-08 14:23:38.218  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 14:23:38.218  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.218  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-08 14:23:38.218  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.218  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-08 14:23:38.218  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 14:23:38.218  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-08 14:23:38.218  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 14:23:38.218  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 14:23:38.219  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-08 14:23:38.219  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 14:23:38.219  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 14:23:38.219  3324  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-08 14:23:38.219  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.219  3324  3371 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-08 14:23:38.219  3324  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 14:23:38.220  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 14:23:38.220  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.220  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.220  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-08 14:23:38.220  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-08 14:23:38.220  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
,08-08 14:23:38.220  3324  3324 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 14:23:38.220  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.220  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.220  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.220  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.220  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.220  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 14:23:38.221  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.221  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.221  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.221  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.221  3324  3371 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-08 14:23:38.221  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 14:23:38.221  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.221  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.222  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.222  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.222  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.222  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.222  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-08 14:23:38.222  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.222  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.222  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.222  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.222  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.222  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.222  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.222  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-08 14:23:38.222  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.222  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.223  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-08 14:23:38.223  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 14:23:38.223  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.223  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.223  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 14:23:38.223  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.223  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.223  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.223  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.223  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.224  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.224  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.224  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.224  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.225  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 14:23:38.225  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.225  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.225  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.225  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.226  3324  3371 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-08 14:23:38.226  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-08 14:23:38.226  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.226  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.226  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.226  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.226  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.226  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.226  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.226  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.226  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 14:23:38.226  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.226  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.227  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.227  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.227  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-08 14:23:38.227  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.227  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.227  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.227  3324  3371 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-08 14:23:38.227  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.227  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.227  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.228  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-08 14:23:38.228  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.228  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.228  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.228  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.228  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.228  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 14:23:38.228  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.228  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.228  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.228  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.228  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-08 14:23:38.228  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.228  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.228  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.229  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-08 14:23:38.229  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-08 14:23:38.229  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 14:23:38.229  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-08 14:23:38.229  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-08 14:23:38.229  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-08 14:23:38.229  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.229  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.229  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 14:23:38.229  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.229  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.229  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.229  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list,
08-08 14:23:38.230  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.230  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.230  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop,
08-08 14:23:38.230  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.230  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.230  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.230  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.230  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.230  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.230  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.230  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.231  3324  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 14:23:38.231  3324  3371 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 14:23:38.231  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-08 14:23:38.233  3324  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 14:23:38.233  3324  3371 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-08 14:23:38.233  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-08 14:23:38.233  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-08 14:23:38.233  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-08 14:23:38.233  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-08 14:23:38.233  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
08-08 14:23:38.233  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-08 14:23:38.233  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810],
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310],
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-08 14:23:38.234  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-08 14:23:38.235  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-08 14:23:38.235  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
,08-08 14:23:38.235  3324  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-08 14:23:38.235  3324  3371 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 14:23:38.235  3324  3371 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-08 14:23:38.235  3324  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-08 14:23:38.235  3324  3371 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-08 14:23:38.235  3324  3371 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-08 14:23:38.235  3324  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 14:23:38.235  3324  3371 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-08 14:23:38.235  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-08 14:23:38.236  3324  3371 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-08 14:23:38.236  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-08 14:23:38.237  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-08 14:23:38.237  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0,
08-08 14:23:38.237  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-08 14:23:38.237  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-08 14:23:38.238  3324  3371 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-08 14:23:38.238  3324  3371 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-08 14:23:38.238  3324  3371 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-08 14:23:38.238  3324  3379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 349)
08-08 14:23:38.238  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.238  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.238  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 14:23:38.238  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.238  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.238  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.239  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-08 14:23:38.239  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.239  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.239  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.239  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.239  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.239  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.239  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-08 14:23:38.239  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.240  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.240  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.240  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.240  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.240  3324  3380 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 349
08-08 14:23:38.240  3324  3371 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-08 14:23:38.241  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.241  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.241  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.241  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 14:23:38.241  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.241  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.241  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.241  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.241  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.241  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.241  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.241  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.241  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.241  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 14:23:38.241  3324  3379 E BluetoothDevice: Bluetooth is not enabled
08-08 14:23:38.241  3324  3379 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 349)
08-08 14:23:38.242  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.242  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.242  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.242  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.242  3324  3371 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-08 14:23:38.242  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.242  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.242  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-08 14:23:38.242  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.242  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.243  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.243  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.243  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.243  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.243  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.243  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.243  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.243  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.243  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-08 14:23:38.243  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.243  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.243  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.243  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.244  3324  3371 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-08 14:23:38.244  3324  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString,
08-08 14:23:38.244  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 14:23:38.244  3324  3371 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-08 14:23:38.244  3324  3371 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 14:23:38.244  3324  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-08 14:23:38.244  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
08-08 14:23:38.244  3324  3371 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-08 14:23:38.244  3324  3371 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-08 14:23:38.244  3324  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-08 14:23:38.244  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 14:23:38.244  3324  3371 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-08 14:23:38.244  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.245  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.245  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.245  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-08 14:23:38.245  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.245  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.245  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.245  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.245  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.245  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop,
08-08 14:23:38.245  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.245  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.245  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.245  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-08 14:23:38.245  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.245  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.245  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.245  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.246  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-08 14:23:38.246  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.246  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.246  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
,08-08 14:23:38.246  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.246  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.246  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.246  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.246  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.246  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.247  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.247  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.247  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.247  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 14:23:38.247  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.247  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.248  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.248  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.248  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.248  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.248  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.248  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.248  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.248  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.248  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.248  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.248  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.248  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.248  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.248  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.248  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.248  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.248  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.249  3324  3371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-08 14:23:38.250  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 14:23:38.250  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
08-08 14:23:38.250  3324  3371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 14:23:38.250  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-08 14:23:38.250  3324  3324 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-08 14:23:38.250  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.250  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-08 14:23:38.250  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.250  3324  3371 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
08-08 14:23:38.250  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.250  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.250  3324  3324 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-08 14:23:38.250  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-08 14:23:38.250  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-08 14:23:38.250  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-08 14:23:38.251  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.251  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.251  3324  3371 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-08 14:23:38.251  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.251  3324  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 14:23:38.251  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.251  3324  3324 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-08 14:23:38.251  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.251  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.251  3324  3324 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-08 14:23:38.251  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.251  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.251  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.251  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.251  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.251  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.252  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.252  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.252  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.252  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.252  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.252  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-08 14:23:38.252  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.252  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.252  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.253  3324  3371 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-08 14:23:38.253  3324  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-08 14:23:38.253  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-08 14:23:38.253  3324  3371 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-08 14:23:38.253  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.253  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.253  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.253  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.254  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.254  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.254  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.254  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.254  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.254  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.254  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.254  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.254  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.254  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.254  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.254  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.254  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-08 14:23:38.254  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.256  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.256  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-08 14:23:38.256  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.256  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.256  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.256  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.256  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.256  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.256  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
,08-08 14:23:38.256  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.256  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.256  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.256  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.256  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.257  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.257  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.257  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.257  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.257  3324  3371 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-08 14:23:38.257  3324  3371 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-08 14:23:38.257  3324  3371 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-08 14:23:38.258  3324  3371 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-08 14:23:38.258  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.258  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.258  3324  3371 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adee7a8 not in the list
08-08 14:23:38.258  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.258  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.258  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
08-08 14:23:38.258  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-08 14:23:38.258  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.258  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-08 14:23:38.258  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-08 14:23:38.258  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-08 14:23:38.258  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-08 14:23:38.258  3324  3371 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-08 14:23:38.258  3324  3371 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6e02c1 not in the list
08-08 14:23:38.259  3324  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-08 14:23:38.259  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 14:23:38.259  3324  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-08 14:23:38.259  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-08 14:23:38.259  3324  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-08 14:23:38.259  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-08 14:23:38.261  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming],
08-08 14:23:38.261  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-08 14:23:38.261  3324  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-08 14:23:38.261  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 14:23:38.261  3324  3371 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-08 14:23:38.261  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-08 14:23:38.262  3324  3371 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-08 14:23:38.262  3324  3371 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-08 14:23:38.262  3324  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed,
08-08 14:23:38.262  3324  3371 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-08 14:23:38.262  3324  3371 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-08 14:23:38.262  3324  3371 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-08 14:23:38.263  3324  3371 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-08 14:23:38.263  3324  3371 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-08 14:23:38.263  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 14:23:38.263  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7eb6143 added. We now have 2 listener(s)
08-08 14:23:38.263  3324  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 14:23:38.264   873  1691 D WifiService: setWifiEnabled: true pid=3324, uid=10000
08-08 14:23:38.265   873  1691 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-08 14:23:38.266  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 14:23:38.266  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ad03c0 added. We now have 3 listener(s)
08-08 14:23:38.267  3324  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 14:23:38.267  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.267  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.267  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-08 14:23:38.267  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e4f48f9 added. We now have 4 listener(s)
08-08 14:23:38.267  3324  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 14:23:38.268  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 14:23:38.268  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@994203e added. We now have 5 listener(s)
08-08 14:23:38.268  3324  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 14:23:38.269   873  1429 D WifiService: setWifiEnabled: false pid=3324, uid=10000
08-08 14:23:38.269   873  1429 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 14:23:38.279   873   890 I ActivityManager: Start proc 3383:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
08-08 14:23:38.280   873  1303 D WifiConfigStore: Loading config and enabling all networks 
08-08 14:23:38.283  3324  3371 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-08 14:23:38.284  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:38.284  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:38.284  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:38.284  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:38.284  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:38.284  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:38.284  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.284  3324  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:38.284  3324  3371 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 14:23:38.285  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:38.299   873   886 I ActivityManager: Start proc 3393:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-08 14:23:38.299   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-08 14:23:38.299   873  1303 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-08 14:23:38.300   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-08 14:23:38.301   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-08 14:23:38.302   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-08 14:23:38.303   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-08 14:23:38.303   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 14:23:38.303   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-08 14:23:38.328  3393  3393 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-08 14:23:38.366   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-08 14:23:38.367   373   871 D CommandListener: Setting iface cfg
,08-08 14:23:38.367   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
,08-08 14:23:38.368   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-08 14:23:38.372  3393  3393 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-08 14:23:38.374  3383  3383 D AdapterServiceConfig: Adding HeadsetService
,08-08 14:23:38.374  3383  3383 D AdapterServiceConfig: Adding A2dpService
08-08 14:23:38.374  3383  3383 D AdapterServiceConfig: Adding HidService
08-08 14:23:38.374  3383  3383 D AdapterServiceConfig: Adding HealthService
08-08 14:23:38.374  3383  3383 D AdapterServiceConfig: Adding PanService
,08-08 14:23:38.374  3383  3383 D AdapterServiceConfig: Adding GattService
08-08 14:23:38.374  3383  3383 D AdapterServiceConfig: Adding BluetoothMapService
08-08 14:23:38.375   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
08-08 14:23:38.375   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-08 14:23:38.390  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:38.390  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:38.390  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.390  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:38.390   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
08-08 14:23:38.391  1693  2047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 14:23:38.391  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:38.391  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:38.391  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:38.391  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:38.400   873  1429 I ActivityManager: Killing 2664:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-08 14:23:38.407   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d1b389:true
,08-08 14:23:38.408  3383  3383 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 14:23:38.410  3383  3383 I bt_bluedroid: init
08-08 14:23:38.410  3383  3420 I BluetoothAdapterState: Entering OffState
,08-08 14:23:38.412  3383  3421 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 14:23:38.413  3383  3421 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 14:23:38.413  3383  3421 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-08 14:23:38.413  3383  3421 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 14:23:38.414  3383  3383 I bt_bluedroid: get_profile_interface socket
,08-08 14:23:38.415  3383  3383 I bt_bluedroid: get_profile_interface sdp
,08-08 14:23:38.417  3383  3424 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 14:23:38.448  3383  3424 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 14:23:38.450  3383  3402 I bt_bluedroid: config_hci_snoop_log
,08-08 14:23:38.452   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-08 14:23:38.454  3383  3420 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 14:23:38.454  3383  3420 D BluetoothAdapterProperties: Setting state to 14
08-08 14:23:38.454  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 14:23:38.455  3383  3420 D BluetoothBondStateMachine: make
,08-08 14:23:38.457  3383  3425 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-08 14:23:38.458  3383  3420 I BluetoothAdapterState: Entering PendingCommandState
,08-08 14:23:38.460  3383  3383 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 14:23:38.464  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:38.464  3383  3383 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 14:23:38.465  3383  3383 D BtGatt.GattService: Received start request. Starting profile...
08-08 14:23:38.465  3383  3383 D BtGatt.GattService: start()
,08-08 14:23:38.465  3383  3383 I bt_bluedroid: get_profile_interface gatt
,08-08 14:23:38.466  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:38.466  3383  3383 D BtGatt.AdvertiseManager: advertise manager created
,08-08 14:23:38.472  3383  3383 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:38.472  3383  3383 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:38.472  3383  3383 V BluetoothAdapterState: isBleTurningOn()=true
08-08 14:23:38.472  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:38.473  3383  3420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-08 14:23:38.473  3383  3420 I bt_bluedroid: enable
08-08 14:23:38.473  3383  3421 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-08 14:23:38.473  3383  3421 I bt_hci  : start_up
,08-08 14:23:38.485  3383  3421 I bt_vendor: alloc value 0xb39e0189
,08-08 14:23:38.485  3383  3421 I bt_vendor: init
08-08 14:23:38.485  3383  3421 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-08 14:23:38.485  3383  3421 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 14:23:38.593  3383  3421 D bt_hci  : start_up starting async portion
,08-08 14:23:38.593  3383  3428 I bt_hci  : event_finish_startup
08-08 14:23:38.593  3383  3428 I bt_hci_h4: hal_open
,08-08 14:23:38.594  3383  3428 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 14:23:38.600  3383  3428 I bt_userial_vendor: device fd = 51 open
,08-08 14:23:38.635  3383  3428 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 14:23:38.666  3383  3428 D bt_hwcfg: Chipset BCM4354A2
08-08 14:23:38.666  3383  3428 D bt_hwcfg: Target name = [BCM4354A2]
,08-08 14:23:38.667  3383  3428 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 14:23:38.752  3324  3324 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-08 14:23:39.349  3383  3428 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 14:23:39.350  3383  3428 D bt_hwcfg: Settlement delay -- 100 ms
08-08 14:23:39.351  3383  3428 I bt_hwcfg: Setting fw settlement delay to 100 
08-08 14:23:39.467  3383  3428 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 14:23:39.469  3383  3428 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 14:23:39.498  3383  3428 I bt_hwcfg: vendor lib fwcfg completed
08-08 14:23:39.499  3383  3428 I bt_vendor: firmware callback
08-08 14:23:39.499  3383  3428 I bt_hci  : firmware_config_callback
,08-08 14:23:39.510  3383  3430 I bt_btu  : btu_task pending for preload complete event
,08-08 14:23:39.510  3383  3430 I bt_btu_task: Bluetooth chip preload is complete
,08-08 14:23:39.510  3383  3430 I bt_btu  : btu_task received preload complete event
,08-08 14:23:39.524  3383  3430 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 14:23:39.524  3383  3430 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-08 14:23:39.525  3383  3430 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-08 14:23:39.525  3383  3430 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-08 14:23:39.525  3383  3430 I         : BTE_InitTraceLevels -- TRC_AVRC
08-08 14:23:39.526  3383  3430 I         : BTE_InitTraceLevels -- TRC_A2D
,08-08 14:23:39.526  3383  3430 I         : BTE_InitTraceLevels -- TRC_BNEP
08-08 14:23:39.527  3383  3430 I         : BTE_InitTraceLevels -- TRC_BTM
08-08 14:23:39.527  3383  3430 I         : BTE_InitTraceLevels -- TRC_GAP
,08-08 14:23:39.527  3383  3430 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 14:23:39.528  3383  3430 I         : BTE_InitTraceLevels -- TRC_SDP
,08-08 14:23:39.528  3383  3430 I         : BTE_InitTraceLevels -- TRC_GATT
08-08 14:23:39.528  3383  3430 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 14:23:39.528  3383  3430 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 14:23:39.529  3383  3430 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 14:23:39.665  3383  3430 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb395dd9d
,08-08 14:23:39.665  3383  3430 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb395dd9d 
,08-08 14:23:39.688  3383  3424 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 14:23:39.689  3383  3424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
08-08 14:23:39.690  3383  3424 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-08 14:23:39.695  3383  3424 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 14:23:39.700  3383  3424 D BluetoothAdapterProperties: Scan Mode:20
,08-08 14:23:39.701  3383  3424 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-08 14:23:39.702  3383  3424 D bt_hci  : do_postload posting postload work item
,08-08 14:23:39.703  3383  3428 I bt_hci  : event_postload
08-08 14:23:39.703  3383  3428 I bt_vendor: sco_config_cb
08-08 14:23:39.703  3383  3428 I bt_hci  : sco_config_callback postload finished.
,08-08 14:23:39.705  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:39.710  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:39.712  3383  3424 D bt_bte_conf: Device ID record 1 : primary
,08-08 14:23:39.712  3383  3424 D bt_bte_conf:   vendorId            = 000f
08-08 14:23:39.713  3383  3424 D bt_bte_conf:   vendorIdSource      = 0001
08-08 14:23:39.713  3383  3424 D bt_bte_conf:   product             = 1200
08-08 14:23:39.713  3383  3424 D bt_bte_conf:   version             = 1436
08-08 14:23:39.713  3383  3424 D bt_bte_conf:   clientExecutableURL = 
08-08 14:23:39.713  3383  3424 D bt_bte_conf:   serviceDescription  = 
08-08 14:23:39.713  3383  3424 D bt_bte_conf:   documentationURL    = 
08-08 14:23:39.714  3383  3424 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-08 14:23:39.714  3383  3421 D bt_stack_manager: event_start_up_stack finished
,08-08 14:23:39.715  3383  3428 I bt_vendor: low_power_mode_cb
08-08 14:23:39.716  3383  3420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-08 14:23:39.716  3383  3420 D BluetoothAdapterProperties: Setting state to 15
08-08 14:23:39.716  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-08 14:23:39.719  3383  3420 I BluetoothAdapterState: Entering BleOnState
,08-08 14:23:39.723  3383  3420 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-08 14:23:39.724  3383  3420 D BluetoothAdapterProperties: Setting state to 11
08-08 14:23:39.724  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 14:23:39.729  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:39.729  3383  3383 D HeadsetService: Received start request. Starting profile...
,08-08 14:23:39.733  3383  3383 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-08 14:23:39.733  3383  3383 D HeadsetStateMachine: make
,08-08 14:23:39.742  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:39.746  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:39.766   873   886 I ActivityManager: Start proc 3437:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-08 14:23:39.769  3383  3383 D HeadsetStateMachine: max_hf_connections = 1
,08-08 14:23:39.769  3383  3383 I bt_bluedroid: get_profile_interface handsfree
08-08 14:23:39.769  3383  3424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-08 14:23:39.770  3383  3424 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-08 14:23:39.782  3383  3420 I BluetoothAdapterState: Entering PendingCommandState
,08-08 14:23:39.784  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:39.785   873   873 D BluetoothA2dp: Proxy object connected
,08-08 14:23:39.786  3383  3383 D A2dpService: Received start request. Starting profile...
,08-08 14:23:39.787  3383  3383 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-08 14:23:39.787  3383  3383 I bt_bluedroid: get_profile_interface avrcp
,08-08 14:23:39.793  3383  3383 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 14:23:39.793  3383  3383 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-08 14:23:39.793  3383  3383 D A2dpStateMachine: make
08-08 14:23:39.795  3383  3383 I bt_bluedroid: get_profile_interface a2dp
08-08 14:23:39.797  3383  3383 I BluetoothHidServiceJni: classInitNative: succeeds
,08-08 14:23:39.798  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
08-08 14:23:39.796  3383  3450 D A2dpStateMachine: Enter Disconnected: -2,
08-08 14:23:39.799  3383  3424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 14:23:39.799  1348  1348 D BluetoothInputDevice: Proxy object connected
08-08 14:23:39.799  1348  1348 D HidProfile: Bluetooth service connected
,08-08 14:23:39.800  3383  3383 D HidService: Received start request. Starting profile...
08-08 14:23:39.801  3383  3383 I bt_bluedroid: get_profile_interface hidhost
,08-08 14:23:39.801  3383  3383 D HidService: setHidService(): set to: null
08-08 14:23:39.801  3383  3424 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393f3e5
08-08 14:23:39.801  3383  3424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-08 14:23:39.803  3383  3383 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 14:23:39.803  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
08-08 14:23:39.804  3383  3383 D HealthService: Received start request. Starting profile...
,08-08 14:23:39.805  3383  3383 I bt_bluedroid: get_profile_interface health
,08-08 14:23:39.806  3383  3383 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-08 14:23:39.807  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:39.808  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
,08-08 14:23:39.809  1348  1348 D PanProfile: Bluetooth service connected
,08-08 14:23:39.808  3383  3383 D PanService: Received start request. Starting profile...
08-08 14:23:39.809  3383  3383 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-08 14:23:39.809  3383  3383 I bt_bluedroid: get_profile_interface pan
08-08 14:23:39.810  3383  3424 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-08 14:23:39.812  3383  3383 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:39.813  3383  3383 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:39.814  1348  1348 D BluetoothMap: Proxy object connected
08-08 14:23:39.814  1348  1348 D MapProfile: Bluetooth service connected
,08-08 14:23:39.814  1348  1348 D BluetoothMap: getConnectedDevices()
08-08 14:23:39.813  3383  3383 V BluetoothAdapterState: isTurningOn()=true
,08-08 14:23:39.814  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:39.815  1348  1348 D BluetoothMap: Bluetooth is Not enabled
08-08 14:23:39.814  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:39.817  3383  3383 D BluetoothMapService: Received start request. Starting profile...,
08-08 14:23:39.817  3383  3383 D BluetoothMapService: start()
,08-08 14:23:39.824  3383  3383 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-08 14:23:39.825  3383  3383 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-08 14:23:39.825  3383  3383 D BluetoothMapAppObserver: createReceiver()
,08-08 14:23:39.826  3383  3383 D BluetoothMapAppObserver: initObservers()
,08-08 14:23:39.826  3383  3383 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 14:23:39.833  3383  3383 V BluetoothAdapterState: isTurningOff()=false
08-08 14:23:39.833  3383  3383 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:39.833  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:39.833  3383  3436 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-08 14:23:39.833  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:39.833  3383  3383 V BluetoothAdapterState: isTurningOff()=false
08-08 14:23:39.833  3383  3383 V BluetoothAdapterState: isTurningOn()=true
,08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isTurningOff()=false
08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isTurningOn()=true,
08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:39.834  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:39.835  3383  3383 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:39.835  3383  3383 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:39.835  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 14:23:39.835  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:39.835  3383  3420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-08 14:23:39.835  3383  3420 D BluetoothAdapterProperties: ScanMode =  20
,08-08 14:23:39.835  3383  3420 D BluetoothAdapterProperties: State =  11
,08-08 14:23:39.836  3383  3420 D BluetoothAdapterProperties: Setting state to 12
08-08 14:23:39.836  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 14:23:39.838  3383  3424 D BluetoothAdapterProperties: Scan Mode:21
08-08 14:23:39.838  3383  3424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 14:23:39.838  1348  1360 D BluetoothPan: onBluetoothStateChange on: true
08-08 14:23:39.838   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 14:23:39.839  3383  3420 I BluetoothAdapterState: Entering OnState
08-08 14:23:39.841  1348  1859 D BluetoothMap: onBluetoothStateChange: up=true
08-08 14:23:39.841   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 14:23:39.841  1348  3323 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 14:23:39.842  3324  3324 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-08 14:23:39.842  1348  1359 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-08 14:23:39.843   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 14:23:39.843   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 14:23:39.843  1759  1777 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 14:23:39.845   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-08 14:23:39.845  3383  3383 D BluetoothMapService: onReceive
08-08 14:23:39.845  3383  3383 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-08 14:23:39.845  3383  3383 D BluetoothMapService: STATE_ON
08-08 14:23:39.845  3324  3324 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-08 14:23:39.849  3324  3324 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:39.853  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:39.854  3383  3383 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 14:23:39.854  3383  3383 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-08 14:23:39.855  3437  3437 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-08 14:23:39.856  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:39.856  3383  3383 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
08-08 14:23:39.859  3383  3383 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:39.859  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 14:23:39.860  3383  3383 D ObexServerSockets: Succeed to create listening sockets 
08-08 14:23:39.860  3383  3383 D ObexServerSockets0: startAccept()
,08-08 14:23:39.860  3383  3383 D ObexServerSockets0: prepareForNewConnect()
,08-08 14:23:39.861  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:39.862  3383  3383 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-08 14:23:39.862  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:39.862  3383  3383 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-08 14:23:39.863  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:39.865  3383  3458 D ObexServerSockets0: Accepting socket connection...
,08-08 14:23:39.865  3383  3457 D ObexServerSockets0: Accepting socket connection...
08-08 14:23:39.857  1348  1667 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-08 14:23:39.866  3383  3383 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 14:23:39.866  3383  3383 D ObexServerSockets0: prepareForNewConnect()
,08-08 14:23:39.868  1348  1667 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-08 14:23:39.868  1348  1348 D BluetoothA2dp: Proxy object connected
08-08 14:23:39.874   873  1385 I ActivityManager: Killing 2829:com.google.android.gm/u0a78 (adj 15): empty #17,
,08-08 14:23:39.910  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 14:23:39.926   873  1758 I ActivityManager: Start proc 3459:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-08 14:23:39.941   873   890 D BluetoothHeadset: Proxy object connected
,08-08 14:23:39.942   873   890 D BluetoothHeadset: Proxy object connected
,08-08 14:23:39.944   873   890 D BluetoothHeadset: Proxy object connected
,08-08 14:23:39.945  1759  1770 D BluetoothHeadset: Proxy object connected
,08-08 14:23:39.970  3459  3459 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-08 14:23:39.972  1348  1360 D BluetoothHeadset: Proxy object connected
08-08 14:23:39.973  1348  1348 D HeadsetProfile: Bluetooth service connected
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.k.d(PG:583)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.e.b(PG:170)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.File.exists(File.java:361)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.121  3459  3459 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:23:40.121  3459  3459 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-08 14:23:40.127  3437  3437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 14:23:40.140   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c153d9e:true
08-08 14:23:40.144  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 14:23:40.149  3437  3437 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-08 14:23:40.153  1348  1348 D BluetoothPbap: Proxy object connected
,08-08 14:23:40.153  1348  1348 D PbapServerProfile: Bluetooth service connected
,08-08 14:23:40.164  3383  3487 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 14:23:40.170  3437  3437 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-08 14:23:40.180  3383  3491 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 14:23:40.181  3437  3437 D LocalBluetoothProfileManager: Adding local MAP profile
,08-08 14:23:40.182  3383  3491 I BtOppRfcommListener: Accept thread started.
08-08 14:23:40.182  3437  3437 D BluetoothMap: Create BluetoothMap proxy object
,08-08 14:23:40.195  3437  3437 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-08 14:23:40.212  3437  3437 D DockEventReceiver: finishStartingService: stopping service
,08-08 14:23:40.213  3437  3437 D BluetoothA2dp: Proxy object connected
,08-08 14:23:40.215  3437  3437 D BluetoothInputDevice: Proxy object connected
,08-08 14:23:40.216  3437  3437 D HidProfile: Bluetooth service connected
,08-08 14:23:40.217  3437  3437 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 14:23:40.217  3437  3437 D PanProfile: Bluetooth service connected,
08-08 14:23:40.217  3437  3437 D BluetoothMap: Proxy object connected
,08-08 14:23:40.218  3437  3437 D MapProfile: Bluetooth service connected
,08-08 14:23:40.218  3437  3437 D BluetoothMap: getConnectedDevices()
08-08 14:23:40.220  3437  3437 D BluetoothPbap: Proxy object connected
,08-08 14:23:40.220  3437  3437 D PbapServerProfile: Bluetooth service connected
08-08 14:23:40.221   873  1758 I ActivityManager: Killing 3015:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-08 14:23:40.273  3437  3448 D BluetoothHeadset: Proxy object connected
,08-08 14:23:40.273  3437  3437 D HeadsetProfile: Bluetooth service connected
,08-08 14:23:40.372  3459  3480 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-08 14:23:40.389   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5cc2d75:true
,08-08 14:23:41.289   873  1385 D WifiService: setWifiEnabled: true pid=3324, uid=10000
,08-08 14:23:41.289   873  1385 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 14:23:41.303   873  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:41.321  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 14:23:41.327  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:41.331  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 14:23:41.333  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:41.335   873  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-08 14:23:41.335   873  1303 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-08 14:23:41.335   873  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-08 14:23:41.337   873  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-08 14:23:41.337   873  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-08 14:23:41.338   873  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-08 14:23:41.338   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-08 14:23:41.338   873  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-08 14:23:41.341  1452  1452 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-08 14:23:41.426   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-08 14:23:41.429   373   871 D CommandListener: Setting iface cfg
,08-08 14:23:41.431   873  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-08 14:23:41.432   873  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-08 14:23:41.439   873  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-08 14:23:41.439   873  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-08 14:23:41.477   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 14:23:41.480   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 14:23:41.803  1452  1452 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-08 14:23:41.847  1452  1452 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-08 14:23:41.848  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-08 14:23:41.857   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 14:23:41.878   873  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 14:23:41.879   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-08 14:23:41.879   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-08 14:23:41.907   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 14:23:41.921   373   871 D CommandListener: Setting iface cfg
,08-08 14:23:41.943   873  1303 D WifiStateMachine: Start Dhcp Watchdog 1
,08-08 14:23:41.970   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-08 14:23:41.971   873  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,08-08 14:23:41.975   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-08 14:23:41.983   873  3503 D DhcpClient: Receive thread started
,08-08 14:23:42.067   873  1303 E native  : do suspend false
,08-08 14:23:42.091   873  3502 D DhcpClient: Broadcasting DHCPDISCOVER
,08-08 14:23:42.106   873  3503 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 164373, domain null
,08-08 14:23:42.108   873  3502 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 164373 seconds
,08-08 14:23:42.113   873  3502 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-08 14:23:42.141   873  3503 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-08 14:23:42.142   873  3502 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-08 14:23:42.147   373   871 D CommandListener: Setting iface cfg
,08-08 14:23:42.159   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-08 14:23:42.160   873  3502 D DhcpClient: Scheduling renewal in 86399s
,08-08 14:23:42.174   873  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-08 14:23:42.176   873  1303 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-08 14:23:42.176   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-08 14:23:42.180   873  1305 D ConnectivityService: Adding iface wlan0 to network 100
08-08 14:23:42.183   873  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-08 14:23:42.256   873  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-08 14:23:42.257   873  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-08 14:23:42.259   873  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-08 14:23:42.261   873  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-08 14:23:42.262   873  1305 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-08 14:23:42.270   873  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-08 14:23:42.275   873  1305 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-08 14:23:42.275   873  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-08 14:23:42.275   873  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-08 14:23:42.276   873  1305 D ConnectivityService:    accepting network in place of null
,08-08 14:23:42.276   873  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-08 14:23:42.277   873  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-08 14:23:42.279   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-08 14:23:42.288   873  3501 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145004, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-08 14:23:42.324   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 14:23:42.354   873  3500 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:802::200e
,08-08 14:23:42.369   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 14:23:42.374   873  1305 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-08 14:23:42.388   873  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-08 14:23:42.388   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-08 14:23:42.399   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-08 14:23:42.403   873  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 14:23:42.412  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 14:23:42.414   873  1691 V BackupManagerService: Scheduling immediate backup pass
,08-08 14:23:42.418   873   873 V BackupManagerService: Running a backup pass
,08-08 14:23:42.421  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-08 14:23:42.422   873  1327 V BackupManagerService: clearing pending backups
08-08 14:23:42.425   873  1327 V PerformBackupTask: Beginning backup of 16 targets
,08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 14:23:42.427  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 14:23:42.432  1834  1834 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-08 14:23:42.448   873  1327 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-08 14:23:42.449  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-08 14:23:42.455  1810  1810 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 14:23:42.456   873  3500 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Aug 2016 12:23:42 GMT], X-Android-Received-Millis=[1470659022454], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470659022414]}
,08-08 14:23:42.459   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 14:23:42.459   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-08 14:23:42.459   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-08 14:23:42.461   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-08 14:23:42.465  1810  1810 D SystemUpdateService: onCreate
,08-08 14:23:42.471  1810  1810 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 14:23:42.472   873  1706 D AlarmManagerService: Setting time of day to sec=1470659022
08-08 14:23:42.111   873  1706 W AlarmManagerService: Unable to set rtc to 1470659022: Invalid argument
08-08 14:23:42.114  1810  3521 I SystemUpdateService: active receiver: enabled
,08-08 14:23:42.120  1810  3521 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-08 14:23:42.127   873  1327 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,08-08 14:23:42.128  1810  3521 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-08 14:23:42.128  1810  3521 I SystemUpdateService: now status is 0 (complete)
08-08 14:23:42.128  1810  3521 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-08 14:23:42.128  1810  3521 I SystemUpdateService: file has been verified
,08-08 14:23:42.129  1810  3521 I SystemUpdateService: OTA package size = 12249756
,08-08 14:23:42.137  1810  3521 I SystemUpdateService: showing system update notification
,08-08 14:23:42.143   873  1385 I ActivityManager: Start proc 3525:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-08 14:23:42.155   873  1327 I BackupRestoreController: Getting widget state for user: 0
,08-08 14:23:42.166  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:23:42.166  1810  1810 D SystemUpdateService: onDestroy
08-08 14:23:42.168  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-08 14:23:42.183  3525  3525 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
08-08 14:23:42.200  1810  3544 I iu.SyncManager: SYNC; picasa accounts
08-08 14:23:42.203   873  3546 D GpsLocationProvider: NTP server returned: 1470659022111 (Mon Aug 08 14:23:42 GMT+02:00 2016) reference: 145191 certainty: 6 system time offset: -92
08-08 14:23:42.203   873  3546 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-08 14:23:42.215  1810  1810 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-08 14:23:42.218  1810  1810 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-08 14:23:42.244  1810  1810 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-08 14:23:42.245  1810  1810 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 14:23:42.247  1810  3544 I iu.UploadsManager: num queued entries: 0
,08-08 14:23:42.250  1810  3544 I iu.UploadsManager: num updated entries: 0
,08-08 14:23:42.256   873  1429 I ActivityManager: Start proc 3553:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-08 14:23:42.259  3525  3547 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-08 14:23:42.263  1810  3543 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-08 14:23:42.263  1810  3543 W BaseAppContext: Using Auth Proxy for data requests.
08-08 14:23:42.270  1810  3543 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
08-08 14:23:42.266  1810  3544 I iu.SyncManager: NEXT; no task
08-08 14:23:42.271  3393  3520 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
,08-08 14:23:42.301  3553  3553 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-08 14:23:42.316  3553  3553 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 14:23:42.321  1810  3542 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
08-08 14:23:42.322  3525  3547 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-08 14:23:42.326  1693  1710 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-08 14:23:42.329  1693  1710 V GmsBackupTransport: starting performBackup for @pm@
,08-08 14:23:42.337  3553  3553 D SprintDMHelper: simOperator: 
,08-08 14:23:42.337  3553  3553 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 14:23:42.350   873  1712 I ActivityManager: Start proc 3576:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-08 14:23:42.365  1693  1710 V GmsBackupTransport: performBackup done for @pm@
08-08 14:23:42.371  3525  3547 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-08 14:23:42.375  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:23:42.377  1487  1830 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-08 14:23:42.377  1487  1830 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-08 14:23:42.377  1487  1830 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:23:42.377  1487  1830 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 14:23:42.378  1487  1497 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-08 14:23:42.378  1487  1497 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-08 14:23:42.379  1487  1497 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-08 14:23:42.379  1487  1497 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:42.402  1487  3570 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-08 14:23:42.402  1487  3570 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-08 14:23:42.402  1487  3570 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:23:42.403  1487  3570 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:42.410  1487  3570 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 14:23:42.410  1487  3570 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 14:23:42.410  1487  3570 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 14:23:42.410  1487  3570 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 14:23:42.410  1487  3570 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 14:23:42.410  1487  3570 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 14:23:42.410  1487  3570 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:23:42.412  1693  1708 W GmsBackupTransport: Error sending final backup to server: 
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 14:23:42.412  1693  1708 W GmsBackupTransport: 	... 1 more
,08-08 14:23:42.414  1693  3160 I GmsBackupTransport: Next backup will happen in 43199998 millis.
,08-08 14:23:42.414   873  1327 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-08 14:23:42.423  1810  3543 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-08 14:23:42.424  3393  3520 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-08 14:23:42.425  3393  3520 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-08 14:23:42.467  1810  1810 E ConnectivityChangeReceiver: Ignoring connectivity change
,08-08 14:23:42.474  3525  3525 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-08 14:23:42.481   873  1385 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1810 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-08 14:23:42.536  3594  3594 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-933096810.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-933096810.dex
,08-08 14:23:42.568   873  1327 I BackupManagerService: Backup pass finished.
,08-08 14:23:42.594  3594  3594 I dex2oat : dex2oat took 58.330ms (threads: 4) arena alloc=320KB java alloc=41KB native alloc=1656KB free=1671KB
,08-08 14:23:42.627   873   885 I ActivityManager: Start proc 3623:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-08 14:23:42.657  1810  3545 W DriveInitializer: Awaiting to be initialized
08-08 14:23:42.657  1810  3640 W DriveInitializer: Background init thread started
,08-08 14:23:42.660  3525  3525 W InstanceID/Rpc: Found 10011
,08-08 14:23:42.664  3623  3623 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-08 14:23:42.686  1487  2682 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-08 14:23:42.686  1487  2682 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-08 14:23:42.686  1487  2682 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:23:42.686  1487  2682 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:42.694   873  1429 I ActivityManager: Start proc 3652:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-08 14:23:42.762  1810  3640 W DriveInitializer: Background init thread ended
,08-08 14:23:42.788  1487  1487 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-08 14:23:42.788  3652  3652 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-08 14:23:42.810  3129  3567 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-08 14:23:42.810  3129  3567 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jdm.a(PG:82)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jcs.o(PG:406)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jcn.a(PG:1379)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jcs.i(PG:143)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at blb.a(PG:3937)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at czp.a(PG:18188)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at czp.a(PG:9081)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at czq.run(PG:1686)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 14:23:42.810  3129  3567 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jdj.a(PG:4091)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jdj.a(PG:1125)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jdm.a(PG:77)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	... 12 more
08-08 14:23:42.810  3129  3567 E HttpOperation: Caused by: faj: BadAuthentication
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at fal.a(PG:38)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	at jdj.a(PG:4089)
08-08 14:23:42.810  3129  3567 E HttpOperation: 	... 14 more
,08-08 14:23:42.851  1487  2682 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-08 14:23:42.851  1487  2682 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-08 14:23:42.851  1487  2682 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:23:42.851  1487  2682 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:42.871  3129  3567 E HttpOperation: [getmobileexperiments] Unexpected exception
08-08 14:23:42.871  3129  3567 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jdm.a(PG:82)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jcs.o(PG:406)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jcn.a(PG:1379)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jcs.i(PG:143)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at hec.a(PG:42)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at hee.a(PG:102)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at czr.a(PG:65)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at kka.a(PG:108)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at czp.a(PG:19176)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at czp.a(PG:9081)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at czq.run(PG:1686)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-08 14:23:42.871  3129  3567 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jdj.a(PG:4091)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jdj.a(PG:1125)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jdm.a(PG:77)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	... 15 more
08-08 14:23:42.871  3129  3567 E HttpOperation: Caused by: faj: BadAuthentication
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at fal.a(PG:38)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	at jdj.a(PG:4089)
08-08 14:23:42.871  3129  3567 E HttpOperation: 	... 17 more
,08-08 14:23:42.872  3129  3567 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-08 14:23:42.872  3129  3567 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jdm.a(PG:82)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jcs.o(PG:406)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jcn.a(PG:1379)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jcs.i(PG:143)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at hec.a(PG:42)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at hee.a(PG:102)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at czr.a(PG:65)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at kka.a(PG:108)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at czp.a(PG:19176)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at czp.a(PG:9081)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at czq.run(PG:1686)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jdj.a(PG:4091)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jdj.a(PG:1125)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jdm.a(PG:77)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	... 15 more
08-08 14:23:42.872  3129  3567 E ExperimentLoader: Caused by: faj: BadAuthentication
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at fal.a(PG:38)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	at jdj.a(PG:4089)
08-08 14:23:42.872  3129  3567 E ExperimentLoader: 	... 17 more
,08-08 14:23:42.874  3623  3623 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-08 14:23:42.882  3623  3623 I BooksApp: Created application version: 3.6.9 (30609)
,08-08 14:23:42.917  2345  3657 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-08 14:23:43.038   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 23023, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-08 14:23:43.061  3623  3706 I BooksSync: Starting books sync for 61035162, extras: ade
,08-08 14:23:43.129  1487  3691 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-08 14:23:43.197  2868  3710 V KeepSync: Connecting to GoogleApiClient
,08-08 14:23:43.198   873  1711 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-08 14:23:43.290  1487  2244 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-08 14:23:43.290  1487  2244 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-08 14:23:43.290  1487  2244 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:23:43.292  1487  2244 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-08 14:23:43.307  3652  3652 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-08 14:23:43.307  3652  3652 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-08 14:23:43.307  3652  3652 I GAv4    :   adb logcat -s GAv4
08-08 14:23:43.307  1810  3717 V BaseAuthAsyncOperation: access token request failed
08-08 14:23:43.309  2868  3710 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-08 14:23:43.323  3652  3652 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-08 14:23:43.351  3652  3652 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-08 14:23:43.384  3652  3723 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-08 14:23:43.536  3652  3652 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-08 14:23:43.612  3652  3652 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-08 14:23:43.645  3652  3652 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 6707-6726)
,08-08 14:23:43.645  3652  3652 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-08 14:23:43.670  3652  3652 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fc047d7}
,08-08 14:23:43.673  3652  3652 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-08 14:23:43.673  3652  3652 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-08 14:23:43.694  3652  3652 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-08 14:23:43.695  3652  3652 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-08 14:23:43.702  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:23:43.714  3623  3743 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-08 14:23:43.759  1487  3592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 14:23:43.759  1487  3592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 14:23:43.759  1487  3592 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:23:43.759  1487  3592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:43.766  3652  3652 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-08 14:23:43.786  3652  3652 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-08 14:23:43.787  3652  3652 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 14:23:43.787  3652  3652 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 14:23:43.787  3652  3652 I Adreno  : Build Date                       : 10/20/15
08-08 14:23:43.787  3652  3652 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 14:23:43.787  3652  3652 I Adreno  : Local Branch                     : M14
08-08 14:23:43.787  3652  3652 I Adreno  : Remote Branch                    : 
08-08 14:23:43.787  3652  3652 I Adreno  : Remote Branch                    : 
08-08 14:23:43.787  3652  3652 I Adreno  : Reconstruct Branch               : 
,08-08 14:23:43.805  2575  2575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 14:23:43.807  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 14:23:43.807  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-08 14:23:43.807  1487  2031 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-08 14:23:43.807  1487  2031 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-08 14:23:43.807  1487  2031 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:23:43.807  1487  2031 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:43.866  1487  3570 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-08 14:23:43.866  1487  3570 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-08 14:23:43.866  1487  3570 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:23:43.867  1487  3570 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:43.872  3652  3652 I NSApplication: Starting up...
,08-08 14:23:43.873  3652  3755 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-08 14:23:43.909   873  1790 I ActivityManager: Start proc 3760:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-08 14:23:43.911   873  1790 I ActivityManager: Killing 2457:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-08 14:23:43.934   873  1794 D WifiService: setWifiEnabled: false pid=3324, uid=10000
,08-08 14:23:43.935   873  1794 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-08 14:23:43.965  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-08 14:23:43.966  3623  3743 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-08 14:23:43.968   873  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-08 14:23:43.968   873  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-08 14:23:43.968   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-08 14:23:43.969   873  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-08 14:23:43.974  3623  3706 E BooksSync: Soft error
08-08 14:23:43.974  3623  3706 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 14:23:43.974  3623  3706 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-08 14:23:43.977  3623  3706 E BooksSync: Sync error
08-08 14:23:43.977  3623  3706 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-08 14:23:43.977  3623  3706 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-08 14:23:43.977  3623  3706 I BooksSync: Finished books sync
,08-08 14:23:43.982   873   884 I ActivityManager: Killing 2739:android.process.acore/u0a5 (adj 15): empty #17
,08-08 14:23:43.982   873  3502 D DhcpClient: Clearing IP address
,08-08 14:23:43.982   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 23031, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-08 14:23:43.983   373   871 D CommandListener: Setting iface cfg
08-08 14:23:43.985   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-08 14:23:43.990  1487  3575 V NativeCrypto: Read error: ssl=0x9a0be800: I/O error during system call, Connection timed out
08-08 14:23:43.991  1487  3575 V NativeCrypto: SSL shutdown failed: ssl=0x9a0be800: I/O error during system call, Broken pipe
08-08 14:23:43.993   873  1756 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,08-08 14:23:43.994   873  3500 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-08 14:23:43.996   873  3500 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-08 14:23:43.997   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,08-08 14:23:43.997   873  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-08 14:23:43.999   873  3503 D DhcpClient: Receive thread stopped
,08-08 14:23:44.002   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-08 14:23:44.007  3760  3760 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-08 14:23:44.070   873  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-08 14:23:44.070   873  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-08 14:23:44.075   396   396 E Parcel  : Reading a NULL string not supported here.
,08-08 14:23:44.077   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-08 14:23:44.079   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-08 14:23:44.079   873  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-08 14:23:44.085   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 14:23:44.086   873  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-08 14:23:44.096  1693  2047 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-08 14:23:44.096   873  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:44.099  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-08 14:23:44.101  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:44.104  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:44.107  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:44.121  1487  1830 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive,
08-08 14:23:44.122  1487  1830 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-08 14:23:44.122  1487  1830 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:23:44.122  1487  1830 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:44.140   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 14:23:44.152  2868  3710 E KeepSync: IOException
08-08 14:23:44.152  2868  3710 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-08 14:23:44.152  2868  3710 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-08 14:23:44.152  2868  3710 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-08 14:23:44.152  2868  3710 E KeepSync: 	... 10 more
,08-08 14:23:44.152  2868  3710 W KeepSync: Sync result 2
,08-08 14:23:44.157  3525  3716 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Scheduled config refresh failed
08-08 14:23:44.168   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-08 14:23:44.169   873  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-08 14:23:44.169   873  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-08 14:23:44.172   873   890 D Tethering: MasterInitialState.processMessage what=3
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:44.175  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:44.177  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:44.179  1834  1834 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-08 14:23:44.196   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 23031, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-08 14:23:44.197   873  1806 I ActivityManager: Killing 3213:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-08 14:23:44.242   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-08 14:23:44.243   873  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-08 14:23:44.245  3525  3664 E YouTube : libraries.youtube.net.gcm.service.YouTubeGcmTaskService.onRunTask:1033 Failed to fetch settings
,08-08 14:23:44.257   873  1758 I ActivityManager: Killing 3229:com.android.musicfx/u0a18 (adj 15): empty #17
,08-08 14:23:44.365  1487  3787 I VacuumService: Vacuum at: now=1470659024365 tag=VacuumService
,08-08 14:23:44.500   873  1429 I ActivityManager: Killing 3044:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-08 14:23:44.610  1810  1810 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-08 14:23:44.614  1810  1810 D SystemUpdateService: onCreate
,08-08 14:23:44.625  2345  3793 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-08 14:23:44.626  1810  1810 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-08 14:23:44.635  1810  3795 I SystemUpdateService: active receiver: enabled
,08-08 14:23:44.636  1810  1810 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-08 14:23:44.637  1810  3544 I iu.UploadsManager: num queued entries: 0
,08-08 14:23:44.637  1810  3544 I iu.UploadsManager: num updated entries: 0
08-08 14:23:44.638  1810  3544 I iu.SyncManager: NEXT; no task
08-08 14:23:44.641  1810  3795 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-08 14:23:44.642  1810  3795 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-08 14:23:44.642  1810  3795 I SystemUpdateService: now status is 0 (complete)
08-08 14:23:44.642  1810  3795 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-08 14:23:44.642  1810  3795 I SystemUpdateService: file has been verified
08-08 14:23:44.645  1810  3795 I SystemUpdateService: OTA package size = 12249756
08-08 14:23:44.646  1810  1810 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-08 14:23:44.647  1810  1810 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-08 14:23:44.650  1810  3795 I SystemUpdateService: showing system update notification
,08-08 14:23:44.654  3553  3553 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-08 14:23:44.657  3553  3553 D SprintDMHelper: simOperator: 
,08-08 14:23:44.657  3553  3553 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-08 14:23:44.661  1810  1810 D SystemUpdateService: onDestroy
,08-08 14:23:46.956  3383  3420 D BluetoothAdapterState: Current state: ON, message: 23
08-08 14:23:46.956  3383  3420 D BluetoothAdapterProperties: Setting state to 13
08-08 14:23:46.956  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-08 14:23:46.959  3383  3420 D BluetoothAdapterProperties: onBluetoothDisable()
,08-08 14:23:46.962  3383  3420 I BluetoothAdapterState: Entering PendingCommandState
,08-08 14:23:46.969  3383  3383 D BluetoothMapService: onReceive
,08-08 14:23:46.970  3383  3383 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-08 14:23:46.970  3383  3383 D BluetoothMapService: STATE_TURNING_OFF
08-08 14:23:46.970  3383  3383 D BluetoothMapService: MAP Service closeService in
,08-08 14:23:46.970  3383  3383 D BluetoothMapMasInstance0: MAP Service shutdown
08-08 14:23:46.970  3383  3383 D ObexServerSockets0: shutdown(block = true)
08-08 14:23:46.971  3383  3383 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 14:23:46.971  3383  3383 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-08 14:23:46.972  3383  3457 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-08 14:23:46.973  3383  3458 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-08 14:23:46.973  3383  3432 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-08 14:23:46.973  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:46.974  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:46.974  3383  3383 I BtOppRfcommListener: stopping Accept Thread
,08-08 14:23:46.975  3383  3491 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 14:23:46.975  3383  3491 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 14:23:46.976  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-08 14:23:46.976  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:46.981  3383  3424 D BluetoothAdapterProperties: Scan Mode:20
,08-08 14:23:46.983  3383  3420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-08 14:23:46.986  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:46.986  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 14:23:46.987  3383  3383 D HeadsetService: Received stop request...Stopping profile...
08-08 14:23:46.988  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:46.988  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:46.990  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:46.991   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:46.991  1348  1360 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:46.992  1759  1770 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:46.992  3383  3383 D A2dpService: Received stop request...Stopping profile...
,08-08 14:23:46.992   873   873 D BluetoothHeadset: Proxy object disconnected
,08-08 14:23:46.992   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:46.992  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:46.992  3383  3450 D A2dpStateMachine: Exit Disconnected: -1
08-08 14:23:46.992  3437  3449 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:46.994  3383  3383 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:46.994   873   873 D BluetoothA2dp: Proxy object disconnected
08-08 14:23:46.994  3383  3383 V BluetoothAdapterState: isTurningOn()=false
,08-08 14:23:46.994  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:46.994  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:46.995  3437  3437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 14:23:46.998  3437  3437 D HeadsetProfile: Bluetooth service disconnected
,08-08 14:23:46.999  3383  3383 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-08 14:23:46.999  3383  3424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-08 14:23:46.999  3383  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 14:23:47.000  3383  3383 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 14:23:47.000  3383  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 14:23:47.000  3383  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 14:23:47.000  3383  3424 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-08 14:23:47.000  3383  3383 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:46.999  3437  3437 D BluetoothA2dp: Proxy object disconnected
08-08 14:23:47.000  3383  3383 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:47.000  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false,
08-08 14:23:47.000  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:47.001  1348  1348 D HeadsetProfile: Bluetooth service disconnected
08-08 14:23:47.001  1348  1348 D BluetoothA2dp: Proxy object disconnected
08-08 14:23:47.002  3383  3424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-08 14:23:47.002  3383  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 14:23:47.002  3383  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 14:23:47.002  3383  3430 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 14:23:47.002  3383  3430 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 14:23:47.002  3383  3430 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 14:23:47.002  3383  3430 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-08 14:23:47.003  3383  3383 D HidService: Received stop request...Stopping profile...
08-08 14:23:47.003  3383  3383 D HidService: Stopping Bluetooth HidService
08-08 14:23:47.005  3383  3383 D HealthService: Received stop request...Stopping profile...
08-08 14:23:47.006  3383  3383 D PanService: Received stop request...Stopping profile...
08-08 14:23:47.008  3383  3383 D BluetoothMapService: Received stop request...Stopping profile...
,08-08 14:23:47.008  3383  3383 D BluetoothMapService: stop()
08-08 14:23:47.009  3383  3383 D BluetoothMapAppObserver: deinitObservers()
08-08 14:23:47.010  3383  3383 D BluetoothMapAppObserver: removeReceiver()
08-08 14:23:47.010  3437  3437 D DockEventReceiver: finishStartingService: stopping service
08-08 14:23:47.012  3437  3437 D BluetoothInputDevice: Proxy object disconnected
,08-08 14:23:47.012  3437  3437 D HidProfile: Bluetooth service disconnected
,08-08 14:23:47.012  3437  3437 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 14:23:47.012  3437  3437 D PanProfile: Bluetooth service disconnected
,08-08 14:23:47.013  3383  3383 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:47.013  3383  3383 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:47.013  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:47.013  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:47.013  3383  3383 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 14:23:47.013  3383  3424 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-08 14:23:47.014  3383  3383 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 14:23:47.014  3383  3383 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:47.014  3383  3383 V BluetoothAdapterState: isTurningOn()=false
,08-08 14:23:47.014  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:47.014  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:47.014  3383  3383 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-08 14:23:47.014  3383  3424 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-08 14:23:47.015  3383  3383 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-08 14:23:47.015  3383  3383 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:47.015  3383  3383 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:47.015  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:47.015  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:47.015  3383  3383 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-08 14:23:47.015  3383  3383 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-08 14:23:47.016  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 14:23:47.016  3383  3383 D BluetoothMapService: MAP Service closeService in
08-08 14:23:47.017  3383  3383 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:47.017  3383  3383 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:47.017  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:47.017  3383  3383 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:47.017  3383  3420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-08 14:23:47.017  3383  3420 D BluetoothAdapterProperties: Setting state to 15
08-08 14:23:47.017  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-08 14:23:47.018  3383  3420 I BluetoothAdapterState: Entering BleOnState
,08-08 14:23:47.018  3383  3383 D BluetoothMapService: cleanup()
08-08 14:23:47.018  3383  3383 D BluetoothMapService: MAP Service closeService in
08-08 14:23:47.019  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-08 14:23:47.019  1348  1348 D HidProfile: Bluetooth service disconnected
08-08 14:23:47.021  3437  3437 D BluetoothMap: Proxy object disconnected
08-08 14:23:47.021  1348  1359 D BluetoothPan: onBluetoothStateChange on: false
08-08 14:23:47.021  3437  3437 D MapProfile: Bluetooth service disconnected
08-08 14:23:47.022  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-08 14:23:47.022  1348  1348 D PanProfile: Bluetooth service disconnected
08-08 14:23:47.022  1348  1348 D BluetoothMap: Proxy object disconnected
08-08 14:23:47.022  1348  1348 D MapProfile: Bluetooth service disconnected
08-08 14:23:47.022  1348  1348 D BluetoothPbap: Proxy object disconnected
,08-08 14:23:47.022  1348  1348 D PbapServerProfile: Bluetooth service disconnected
08-08 14:23:47.023  3437  3437 D BluetoothPbap: Proxy object disconnected
08-08 14:23:47.023  3437  3437 D PbapServerProfile: Bluetooth service disconnected
08-08 14:23:47.025  1348  1360 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:47.025  3437  3449 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 14:23:47.026  3437  3448 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 14:23:47.027  3437  3805 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 14:23:47.027   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:47.027  3437  3449 D BluetoothMap: onBluetoothStateChange: up=false
,08-08 14:23:47.028  1348  1859 D BluetoothMap: onBluetoothStateChange: up=false
08-08 14:23:47.030  3437  3448 D BluetoothPan: onBluetoothStateChange on: false
08-08 14:23:47.030   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:47.031  3437  3805 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 14:23:47.033  1348  1360 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 14:23:47.035  1348  3323 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 14:23:47.036  1348  1359 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 14:23:47.036   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 14:23:47.036   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:47.037  1759  1891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:47.037  3383  3420 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-08 14:23:47.037  3383  3420 D BluetoothAdapterProperties: Setting state to 16
08-08 14:23:47.038  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-08 14:23:47.038  3383  3420 D BluetoothAdapterProperties: onBleDisable
08-08 14:23:47.040  3383  3420 I BluetoothAdapterState: Entering PendingCommandState
08-08 14:23:47.040  3383  3421 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-08 14:23:47.041  3383  3430 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-08 14:23:47.041  3383  3430 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 14:23:47.043  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:47.044  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:47.045  3383  3424 D BluetoothAdapterProperties: Scan Mode:20
08-08 14:23:47.046  3437  3437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 14:23:47.046  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:47.048  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:47.054   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-08 14:23:47.055  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 14:23:47.058  1651  1651 I Keyboard.Facilitator: onFinishInput()
,08-08 14:23:47.063   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-08 14:23:47.063   873   893 I Adreno  : Build Date                       : 10/20/15
08-08 14:23:47.063   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-08 14:23:47.063   873   893 I Adreno  : Local Branch                     : M14
08-08 14:23:47.063   873   893 I Adreno  : Remote Branch                    : 
08-08 14:23:47.063   873   893 I Adreno  : Remote Branch                    : 
08-08 14:23:47.063   873   893 I Adreno  : Reconstruct Branch               : 
,08-08 14:23:47.063  3437  3437 D DockEventReceiver: finishStartingService: stopping service
,08-08 14:23:47.077   280  2021 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (117 us)
,08-08 14:23:47.248  3383  3424 I bt_hci  : shut_down
,08-08 14:23:47.250  3383  3428 D bt_hwcfg: hw_epilog_process
,08-08 14:23:47.251  3383  3428 I bt_vendor: low_power_mode_cb
,08-08 14:23:47.280  3383  3428 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-08 14:23:47.281  3383  3428 I bt_vendor: epilog_cb
08-08 14:23:47.281  3383  3428 I bt_hci  : epilog_finished_callback
,08-08 14:23:47.287  3383  3424 I bt_hci_h4: hal_close
,08-08 14:23:47.287  3383  3424 I bt_userial_vendor: device fd = 51 close
,08-08 14:23:47.411  3383  3421 D bt_stack_manager: event_shut_down_stack finished.
,08-08 14:23:47.412  3383  3420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-08 14:23:47.415  3383  3383 D BtGatt.DebugUtils: handleDebugAction() action=null
08-08 14:23:47.416  3383  3383 D BtGatt.GattService: Received stop request...Stopping profile...
08-08 14:23:47.416  3383  3383 D BtGatt.GattService: stop()
08-08 14:23:47.416  3383  3383 D BtGatt.AdvertiseManager: advertise clients cleared
08-08 14:23:47.416  3383  3420 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-08 14:23:47.417  3383  3383 V BluetoothAdapterState: isTurningOff()=false
08-08 14:23:47.417  3383  3383 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:47.417  3383  3383 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:47.417  3383  3383 V BluetoothAdapterState: isBleTurningOff()=true
08-08 14:23:47.418  3383  3420 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-08 14:23:47.419  3383  3420 D BluetoothAdapterProperties: Setting state to 10
08-08 14:23:47.419  3383  3420 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-08 14:23:47.420  3383  3420 I BluetoothAdapterState: Entering OffState
08-08 14:23:47.421   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-08 14:23:47.436  3383  3383 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-08 14:23:47.437  3383  3383 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-08 14:23:47.437  3383  3383 I BluetoothServiceJni: cleanupNative: return from cleanup
08-08 14:23:47.437  3383  3421 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-08 14:23:47.446  3383  3421 D bt_stack_manager: event_clean_up_stack finished.
,08-08 14:23:47.448  3383  3383 I art     : System.exit called, status: 0
08-08 14:23:47.448  3383  3383 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-08 14:23:47.497   873  1806 I ActivityManager: Process com.android.bluetooth (pid 3383) has died
,08-08 14:23:47.625  3324  3324 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-08 14:23:47.625  3324  3324 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-08 14:23:47.664   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-08 14:23:47.666  3324  3324 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@621854b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@aae024a, 16908290=android.view.AbsSavedState$1@aae024a}, android:focusedViewId=100}]}]
,08-08 14:23:47.666  3324  3324 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-08 14:23:47.667  3324  3324 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-08 14:23:47.667  3324  3324 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-08 14:23:47.674   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-08 14:23:47.680   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-08 14:23:47.682   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-08 14:23:47.682   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-08 14:23:47.875  3623  3701 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-08 14:23:47.900   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-08 14:23:47.903   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-08 14:23:47.909   873  1328 D SurfaceControl: Excessive delay in setPowerMode(): 228ms
08-08 14:23:47.912   873   893 I DreamManagerService: Entering dreamland.
,08-08 14:23:47.914   873   893 I PowerManagerService: Dozing...
,08-08 14:23:47.917   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-08 14:23:47.977   377  1275 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-08 14:23:47.977   377  1275 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-08 14:23:47.987   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 14:23:47.997  1737  3817 D NfcService: Discovery configuration equal, not updating.
,08-08 14:23:47.998   873  1303 E native  : do suspend false
,08-08 14:23:48.037   873  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-08 14:23:48.043   873  1303 E native  : do suspend true
,08-08 14:23:48.111   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-08 14:23:48.112   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-08 14:23:49.919   873  1305 D ConnectivityService: handlePromptUnvalidated 100
,08-08 14:23:49.990   873   890 I ActivityManager: Start proc 3823:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-08 14:23:50.106  3823  3823 D AdapterServiceConfig: Adding HeadsetService
,08-08 14:23:50.107  3823  3823 D AdapterServiceConfig: Adding A2dpService
,08-08 14:23:50.107  3823  3823 D AdapterServiceConfig: Adding HidService
,08-08 14:23:50.108  3823  3823 D AdapterServiceConfig: Adding HealthService
08-08 14:23:50.109  3823  3823 D AdapterServiceConfig: Adding PanService
,08-08 14:23:50.109  3823  3823 D AdapterServiceConfig: Adding GattService
08-08 14:23:50.110  3823  3823 D AdapterServiceConfig: Adding BluetoothMapService
,08-08 14:23:50.126  3823  3823 D BluetoothAdapterState: make() - Creating AdapterState
,08-08 14:23:50.126   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c3f7b3:true
,08-08 14:23:50.131  3823  3823 I bt_bluedroid: init
,08-08 14:23:50.132  3823  3835 I BluetoothAdapterState: Entering OffState
,08-08 14:23:50.134  3823  3836 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-08 14:23:50.135  3823  3836 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-08 14:23:50.135  3823  3836 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-08 14:23:50.135  3823  3836 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-08 14:23:50.136  3823  3823 I bt_bluedroid: get_profile_interface socket
,08-08 14:23:50.138  3823  3823 I bt_bluedroid: get_profile_interface sdp
,08-08 14:23:50.141  3823  3834 I bt_bluedroid: config_hci_snoop_log
,08-08 14:23:50.143   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-08 14:23:50.143  3823  3839 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 14:23:50.146  3823  3839 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 14:23:50.154  3823  3835 D BluetoothAdapterState: Current state: OFF, message: 0
,08-08 14:23:50.155  3823  3835 D BluetoothAdapterProperties: Setting state to 14
08-08 14:23:50.155  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-08 14:23:50.160  3823  3835 D BluetoothBondStateMachine: make
,08-08 14:23:50.163  3823  3840 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-08 14:23:50.169  3823  3835 I BluetoothAdapterState: Entering PendingCommandState
,08-08 14:23:50.170  3823  3823 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-08 14:23:50.174  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:50.175  3823  3823 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 14:23:50.176  3823  3823 D BtGatt.GattService: Received start request. Starting profile...
,08-08 14:23:50.176  3823  3823 D BtGatt.GattService: start()
08-08 14:23:50.176  3823  3823 I bt_bluedroid: get_profile_interface gatt
,08-08 14:23:50.177  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
08-08 14:23:50.177  3823  3823 D BtGatt.AdvertiseManager: advertise manager created
,08-08 14:23:50.186  3823  3823 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:50.186  3823  3823 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:50.186  3823  3823 V BluetoothAdapterState: isBleTurningOn()=true
08-08 14:23:50.186  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:50.187  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-08 14:23:50.187  3823  3835 I bt_bluedroid: enable
,08-08 14:23:50.188  3823  3836 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-08 14:23:50.188  3823  3836 I bt_hci  : start_up
,08-08 14:23:50.198  3823  3836 I bt_vendor: alloc value 0xb39e0189
,08-08 14:23:50.198  3823  3836 I bt_vendor: init
,08-08 14:23:50.198  3823  3836 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-08 14:23:50.198  3823  3836 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-08 14:23:50.307  3823  3836 D bt_hci  : start_up starting async portion
,08-08 14:23:50.307  3823  3843 I bt_hci  : event_finish_startup
08-08 14:23:50.308  3823  3843 I bt_hci_h4: hal_open
08-08 14:23:50.308  3823  3843 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-08 14:23:50.318  3823  3843 I bt_userial_vendor: device fd = 51 open
,08-08 14:23:50.349  3823  3843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 14:23:50.381  3823  3843 D bt_hwcfg: Chipset BCM4354A2
,08-08 14:23:50.381  3823  3843 D bt_hwcfg: Target name = [BCM4354A2]
,08-08 14:23:50.382  3823  3843 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-08 14:23:51.004  3823  3843 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-08 14:23:51.005  3823  3843 D bt_hwcfg: Settlement delay -- 100 ms
,08-08 14:23:51.006  3823  3843 I bt_hwcfg: Setting fw settlement delay to 100 
,08-08 14:23:51.122  3823  3843 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-08 14:23:51.123  3823  3843 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-08 14:23:51.153  3823  3843 I bt_hwcfg: vendor lib fwcfg completed
,08-08 14:23:51.154  3823  3843 I bt_vendor: firmware callback
08-08 14:23:51.154  3823  3843 I bt_hci  : firmware_config_callback
,08-08 14:23:51.165  3823  3845 I bt_btu  : btu_task pending for preload complete event
,08-08 14:23:51.165  3823  3845 I bt_btu_task: Bluetooth chip preload is complete
08-08 14:23:51.166  3823  3845 I bt_btu  : btu_task received preload complete event
,08-08 14:23:51.177  3823  3845 I         : BTE_InitTraceLevels -- TRC_HCI
,08-08 14:23:51.177  3823  3845 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-08 14:23:51.178  3823  3845 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-08 14:23:51.178  3823  3845 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-08 14:23:51.178  3823  3845 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-08 14:23:51.179  3823  3845 I         : BTE_InitTraceLevels -- TRC_A2D
,08-08 14:23:51.179  3823  3845 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-08 14:23:51.179  3823  3845 I         : BTE_InitTraceLevels -- TRC_BTM
08-08 14:23:51.179  3823  3845 I         : BTE_InitTraceLevels -- TRC_GAP
08-08 14:23:51.180  3823  3845 I         : BTE_InitTraceLevels -- TRC_PAN
08-08 14:23:51.180  3823  3845 I         : BTE_InitTraceLevels -- TRC_SDP
08-08 14:23:51.180  3823  3845 I         : BTE_InitTraceLevels -- TRC_GATT
,08-08 14:23:51.180  3823  3845 I         : BTE_InitTraceLevels -- TRC_SMP
08-08 14:23:51.181  3823  3845 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-08 14:23:51.181  3823  3845 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-08 14:23:51.313  3823  3845 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb395dd9d
,08-08 14:23:51.313  3823  3845 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb395dd9d 
,08-08 14:23:51.364  3823  3839 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-08 14:23:51.365  3823  3839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 14:23:51.365  3823  3839 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-08 14:23:51.367  3823  3839 D BluetoothAdapterProperties: Name is: Nexus 6
,08-08 14:23:51.368  3823  3839 D BluetoothAdapterProperties: Scan Mode:20
,08-08 14:23:51.368  3823  3839 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 14:23:51.368  3823  3839 D bt_hci  : do_postload posting postload work item
,08-08 14:23:51.369  3823  3843 I bt_hci  : event_postload
08-08 14:23:51.369  3823  3843 I bt_vendor: sco_config_cb
08-08 14:23:51.369  3823  3843 I bt_hci  : sco_config_callback postload finished.
,08-08 14:23:51.370  3823  3839 D bt_bte_conf: Device ID record 1 : primary
,08-08 14:23:51.370  3823  3839 D bt_bte_conf:   vendorId            = 000f
,08-08 14:23:51.370  3823  3839 D bt_bte_conf:   vendorIdSource      = 0001
,08-08 14:23:51.370  3823  3839 D bt_bte_conf:   product             = 1200
08-08 14:23:51.371  3823  3839 D bt_bte_conf:   version             = 1436
08-08 14:23:51.371  3823  3839 D bt_bte_conf:   clientExecutableURL = 
08-08 14:23:51.371  3823  3839 D bt_bte_conf:   serviceDescription  = 
,08-08 14:23:51.371  3823  3839 D bt_bte_conf:   documentationURL    = 
08-08 14:23:51.371  3823  3839 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-08 14:23:51.371  3823  3836 D bt_stack_manager: event_start_up_stack finished
08-08 14:23:51.372  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-08 14:23:51.373  3823  3835 D BluetoothAdapterProperties: Setting state to 15
08-08 14:23:51.373  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-08 14:23:51.374  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:51.376  3823  3835 I BluetoothAdapterState: Entering BleOnState
08-08 14:23:51.379  3823  3843 I bt_vendor: low_power_mode_cb
,08-08 14:23:51.380  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:51.383  3823  3835 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-08 14:23:51.383  3823  3835 D BluetoothAdapterProperties: Setting state to 11
,08-08 14:23:51.383  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-08 14:23:51.393  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:51.397  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:51.398  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:51.398  3823  3823 D HeadsetService: Received start request. Starting profile...
08-08 14:23:51.401  3823  3823 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-08 14:23:51.401  3823  3823 D HeadsetStateMachine: make
,08-08 14:23:51.413  3823  3823 D HeadsetStateMachine: max_hf_connections = 1
,08-08 14:23:51.413  3823  3823 I bt_bluedroid: get_profile_interface handsfree
,08-08 14:23:51.414  3823  3839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-08 14:23:51.414  3823  3839 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-08 14:23:51.415  3823  3835 I BluetoothAdapterState: Entering PendingCommandState
,08-08 14:23:51.420  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:51.421  3823  3823 D A2dpService: Received start request. Starting profile...
,08-08 14:23:51.422  3823  3823 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-08 14:23:51.422  3823  3823 I bt_bluedroid: get_profile_interface avrcp
,08-08 14:23:51.428  3823  3823 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-08 14:23:51.429  3823  3823 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-08 14:23:51.429  3823  3823 D A2dpStateMachine: make
,08-08 14:23:51.430  3823  3823 I bt_bluedroid: get_profile_interface a2dp
,08-08 14:23:51.430  3823  3839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-08 14:23:51.431  3823  3855 D A2dpStateMachine: Enter Disconnected: -2
,08-08 14:23:51.432  3823  3823 I BluetoothHidServiceJni: classInitNative: succeeds
08-08 14:23:51.433  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
08-08 14:23:51.433  3823  3823 D HidService: Received start request. Starting profile...
08-08 14:23:51.433  3823  3823 I bt_bluedroid: get_profile_interface hidhost
,08-08 14:23:51.433  3823  3823 D HidService: setHidService(): set to: null
08-08 14:23:51.433  3823  3839 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393f3e5
08-08 14:23:51.434  3823  3839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-08 14:23:51.434  3823  3823 I BluetoothHealthServiceJni: classInitNative: succeeds
08-08 14:23:51.434  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:51.436  3823  3823 D HealthService: Received start request. Starting profile...
08-08 14:23:51.437  3823  3823 I bt_bluedroid: get_profile_interface health
,08-08 14:23:51.439  3823  3823 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-08 14:23:51.440  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
08-08 14:23:51.440  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 14:23:51.440  3823  3823 D PanService: Received start request. Starting profile...
08-08 14:23:51.440  3823  3823 D BluetoothPanServiceJni: initializeNative(L110): pan
08-08 14:23:51.440  3823  3823 I bt_bluedroid: get_profile_interface pan
,08-08 14:23:51.441  3823  3839 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-08 14:23:51.443  3823  3823 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@693c52f
,08-08 14:23:51.444  3823  3823 D BluetoothMapService: Received start request. Starting profile...
08-08 14:23:51.444  3823  3823 D BluetoothMapService: start()
,08-08 14:23:51.446  3823  3823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-08 14:23:51.447  3823  3823 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-08 14:23:51.447  3823  3823 D BluetoothMapAppObserver: createReceiver()
08-08 14:23:51.448  3823  3823 D BluetoothMapAppObserver: initObservers()
08-08 14:23:51.448  3823  3823 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-08 14:23:51.453  3823  3853 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-08 14:23:51.454  3823  3823 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:51.454  3823  3823 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:51.454  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 14:23:51.454  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:51.456  3823  3823 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:51.456  3823  3823 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:51.456  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:51.456  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:51.456  3823  3823 V BluetoothAdapterState: isTurningOff()=false
08-08 14:23:51.456  3823  3823 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:51.456  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:51.457  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:51.457  3823  3823 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:51.457  3823  3823 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:51.457  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:51.457  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:51.457  3823  3823 V BluetoothAdapterState: isTurningOff()=false
08-08 14:23:51.457  3823  3823 V BluetoothAdapterState: isTurningOn()=true
08-08 14:23:51.458  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:51.458  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:51.458  3823  3823 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:51.458  3823  3823 V BluetoothAdapterState: isTurningOn()=true
,08-08 14:23:51.459  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:51.459  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:51.459  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-08 14:23:51.459  3823  3835 D BluetoothAdapterProperties: ScanMode =  20
08-08 14:23:51.459  3823  3835 D BluetoothAdapterProperties: State =  11
08-08 14:23:51.460  3823  3835 D BluetoothAdapterProperties: Setting state to 12
08-08 14:23:51.460  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-08 14:23:51.460  3823  3835 I BluetoothAdapterState: Entering OnState
08-08 14:23:51.460  1348  1359 D BluetoothPan: onBluetoothStateChange on: true
08-08 14:23:51.461  3823  3839 D BluetoothAdapterProperties: Scan Mode:21
08-08 14:23:51.462  3823  3839 D BluetoothAdapterProperties: Discoverable Timeout:120
08-08 14:23:51.463  1348  1859 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 14:23:51.464  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
08-08 14:23:51.464  1348  1348 D PanProfile: Bluetooth service connected
08-08 14:23:51.464  3437  3448 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:51.465  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:51.466  3437  3805 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 14:23:51.467  3437  3449 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 14:23:51.467  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:51.469   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 14:23:51.469  3437  3805 D BluetoothMap: onBluetoothStateChange: up=true
,08-08 14:23:51.470  1348  1359 D BluetoothMap: onBluetoothStateChange: up=true
08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:51.471  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-08 14:23:51.472  1348  1348 D BluetoothMap: Proxy object connected
08-08 14:23:51.472  1348  1348 D MapProfile: Bluetooth service connected
,08-08 14:23:51.472  1348  1348 D BluetoothMap: getConnectedDevices()
08-08 14:23:51.472  3437  3449 D BluetoothPan: onBluetoothStateChange on: true
,08-08 14:23:51.474  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:51.474  3823  3823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-08 14:23:51.475  3823  3823 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-08 14:23:51.477   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 14:23:51.477  3437  3448 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 14:23:51.477  3823  3823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 14:23:51.477  1348  3323 D BluetoothPbap: onBluetoothStateChange: up=true
08-08 14:23:51.479  1348  1859 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-08 14:23:51.479  3823  3823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-08 14:23:51.480  3823  3823 D ObexServerSockets: Succeed to create listening sockets 
,08-08 14:23:51.480  3823  3823 D ObexServerSockets0: startAccept()
,08-08 14:23:51.481  1348  1348 D BluetoothA2dp: Proxy object connected
,08-08 14:23:51.481  3823  3823 D ObexServerSockets0: prepareForNewConnect()
,08-08 14:23:51.481  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-08 14:23:51.483   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-08 14:23:51.483  3823  3823 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-08 14:23:51.483  3823  3823 D BluetoothSdpJni: SDP Create record success - handle: 0
08-08 14:23:51.483  1348  1348 D BluetoothInputDevice: Proxy object connected
,08-08 14:23:51.483   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-08 14:23:51.483  1348  1348 D HidProfile: Bluetooth service connected
,08-08 14:23:51.483   873   873 D BluetoothA2dp: Proxy object connected
08-08 14:23:51.484  1759  1777 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-08 14:23:51.485  3437  3437 D BluetoothInputDevice: Proxy object connected
08-08 14:23:51.486  3823  3861 D ObexServerSockets0: Accepting socket connection...
,08-08 14:23:51.487  3823  3823 D BluetoothMapService: onReceive
08-08 14:23:51.487  3823  3823 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-08 14:23:51.487  3823  3823 D BluetoothMapService: STATE_ON
08-08 14:23:51.487   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-08 14:23:51.488  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:51.485  3437  3437 D HidProfile: Bluetooth service connected
,08-08 14:23:51.489  3823  3860 D ObexServerSockets0: Accepting socket connection...
08-08 14:23:51.490  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:51.491  3437  3437 D BluetoothA2dp: Proxy object connected
,08-08 14:23:51.492  3437  3437 D BluetoothMap: Proxy object connected
08-08 14:23:51.493  3437  3437 D MapProfile: Bluetooth service connected
08-08 14:23:51.493  3437  3437 D BluetoothMap: getConnectedDevices()
08-08 14:23:51.494  3437  3437 D BluetoothPan: BluetoothPAN Proxy object connected
,08-08 14:23:51.494  3437  3437 D PanProfile: Bluetooth service connected
,08-08 14:23:51.499  3437  3437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 14:23:51.505  3437  3437 D DockEventReceiver: finishStartingService: stopping service
,08-08 14:23:51.506  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 14:23:51.514  3437  3437 D BluetoothPbap: Proxy object connected
,08-08 14:23:51.514  3437  3437 D PbapServerProfile: Bluetooth service connected
08-08 14:23:51.514  3823  3823 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-08 14:23:51.514  3823  3823 D ObexServerSockets0: prepareForNewConnect()
08-08 14:23:51.514  1348  1348 D BluetoothPbap: Proxy object connected
08-08 14:23:51.514  1348  1348 D PbapServerProfile: Bluetooth service connected
,08-08 14:23:51.527  3823  3865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 14:23:51.544  3823  3869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-08 14:23:51.546  3823  3869 I BtOppRfcommListener: Accept thread started.
,08-08 14:23:51.566   873   873 D BluetoothHeadset: Proxy object connected
,08-08 14:23:51.567  1348  1359 D BluetoothHeadset: Proxy object connected
08-08 14:23:51.567  1348  1348 D HeadsetProfile: Bluetooth service connected
08-08 14:23:51.568  1759  1770 D BluetoothHeadset: Proxy object connected
08-08 14:23:51.568   873   873 D BluetoothHeadset: Proxy object connected
,08-08 14:23:51.568   873   873 D BluetoothHeadset: Proxy object connected
,08-08 14:23:51.569  3437  3449 D BluetoothHeadset: Proxy object connected
,08-08 14:23:51.569   873   890 D BluetoothHeadset: Proxy object connected
,08-08 14:23:51.569  3437  3437 D HeadsetProfile: Bluetooth service connected
,08-08 14:23:51.577   873   890 D BluetoothHeadset: Proxy object connected
08-08 14:23:51.578  3437  3448 D BluetoothHeadset: Proxy object connected
,08-08 14:23:51.579  3437  3437 D HeadsetProfile: Bluetooth service connected
,08-08 14:23:51.584   873   890 D BluetoothHeadset: Proxy object connected
,08-08 14:23:51.584  1759  1891 D BluetoothHeadset: Proxy object connected
,08-08 14:23:52.293  1693  2310 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-08 14:23:52.931  2575  2586 D Finsky  : [177] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-08 14:23:52.948  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:23:52.955  3324  3371 D io.jxcore.node.ConnectivityMonitor: stop
,08-08 14:23:52.956  3324  3371 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-08 14:23:52.962  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:23:52.967  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:23:53.034  1487  2244 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 14:23:53.034  1487  2244 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 14:23:53.035  1487  2244 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:23:53.035  1487  2244 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:23:53.102  2575  2586 D Finsky  : [177] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-08 14:23:55.964  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-08 14:23:55.964  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5b5bb added. We now have 6 listener(s)
08-08 14:23:55.965  3324  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 14:23:55.971  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-08 14:23:55.971  3324  3371 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96f8ad8 added. We now have 7 listener(s)
08-08 14:23:55.971  3324  3371 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-08 14:23:55.976  3324  3371 I System.out: IsBluetoothEnabled
,08-08 14:23:55.987  3823  3835 D BluetoothAdapterState: Current state: ON, message: 23
,08-08 14:23:55.988  3823  3835 D BluetoothAdapterProperties: Setting state to 13
08-08 14:23:55.988  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-08 14:23:55.990  3823  3835 D BluetoothAdapterProperties: onBluetoothDisable()
08-08 14:23:55.993  3823  3835 I BluetoothAdapterState: Entering PendingCommandState
,08-08 14:23:56.008  3823  3823 D BluetoothMapService: onReceive
,08-08 14:23:56.008  3823  3823 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-08 14:23:56.008  3823  3823 D BluetoothMapService: STATE_TURNING_OFF
08-08 14:23:56.008  3823  3823 D BluetoothMapService: MAP Service closeService in
,08-08 14:23:56.009  3823  3823 D BluetoothMapMasInstance0: MAP Service shutdown
,08-08 14:23:56.009  3823  3823 D ObexServerSockets0: shutdown(block = true)
,08-08 14:23:56.010  3823  3823 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-08 14:23:56.010  3823  3823 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-08 14:23:56.010  3823  3860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-08 14:23:56.010  3823  3847 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-08 14:23:56.011  3823  3839 D BluetoothAdapterProperties: Scan Mode:20
08-08 14:23:56.011  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:56.011  3823  3861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:56.011  3324  3371 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 14:23:56.012  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-08 14:23:56.013  3324  3371 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:56.013  3324  3371 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-08 14:23:56.014  3823  3823 I BtOppRfcommListener: stopping Accept Thread
,08-08 14:23:56.014  3823  3869 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-08 14:23:56.017  3823  3869 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-08 14:23:56.019  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-08 14:23:56.019  3324  3324 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-08 14:23:56.019  3823  3823 D HeadsetService: Received stop request...Stopping profile...
08-08 14:23:56.020  3324  3324 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-08 14:23:56.020  3324  3324 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-08 14:23:56.021   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:56.021  1348  1859 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:56.022  1759  1777 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:56.022   873   873 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:56.022  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:56.022   873   873 D BluetoothHeadset: Proxy object disconnected
,08-08 14:23:56.022  3437  3448 D BluetoothHeadset: Proxy object disconnected
08-08 14:23:56.022  3823  3823 D A2dpService: Received stop request...Stopping profile...
08-08 14:23:56.024  3823  3855 D A2dpStateMachine: Exit Disconnected: -1
08-08 14:23:56.026  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-08 14:23:56.026  3823  3835 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
,08-08 14:23:56.026   873   873 D BluetoothA2dp: Proxy object disconnected
08-08 14:23:56.029  3823  3823 D HidService: Received stop request...Stopping profile...
08-08 14:23:56.030  3823  3823 D HidService: Stopping Bluetooth HidService
08-08 14:23:56.031  3437  3437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 14:23:56.031  3823  3823 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:56.031  3823  3823 V BluetoothAdapterState: isTurningOn()=false
,08-08 14:23:56.031  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:56.031  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:56.033  3823  3823 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-08 14:23:56.033  3823  3823 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-08 14:23:56.033  3823  3839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-08 14:23:56.033  3823  3845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 14:23:56.033  3823  3845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-08 14:23:56.033  3823  3845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 14:23:56.033  3823  3839 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-08 14:23:56.033  3823  3823 D HealthService: Received stop request...Stopping profile...
,08-08 14:23:56.036  1348  1348 D HeadsetProfile: Bluetooth service disconnected
08-08 14:23:56.036  1348  1348 D BluetoothA2dp: Proxy object disconnected
,08-08 14:23:56.037  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-08 14:23:56.037  1348  1348 D HidProfile: Bluetooth service disconnected
,08-08 14:23:56.039  3437  3437 D HeadsetProfile: Bluetooth service disconnected
,08-08 14:23:56.039  3437  3437 D BluetoothA2dp: Proxy object disconnected
,08-08 14:23:56.040  3437  3437 D BluetoothInputDevice: Proxy object disconnected
,08-08 14:23:56.040  3437  3437 D HidProfile: Bluetooth service disconnected
,08-08 14:23:56.040  3823  3823 D PanService: Received stop request...Stopping profile...
,08-08 14:23:56.041  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-08 14:23:56.041  1348  1348 D PanProfile: Bluetooth service disconnected
,08-08 14:23:56.041  3823  3823 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:56.041  3823  3823 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:56.042  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:56.042  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:56.042  3823  3823 D BluetoothMapService: Received stop request...Stopping profile...
08-08 14:23:56.042  3823  3823 D BluetoothMapService: stop()
,08-08 14:23:56.043  3823  3823 D BluetoothMapAppObserver: deinitObservers()
08-08 14:23:56.043  3823  3823 D BluetoothMapAppObserver: removeReceiver()
08-08 14:23:56.045  1348  1348 D BluetoothMap: Proxy object disconnected
08-08 14:23:56.045  1348  1348 D MapProfile: Bluetooth service disconnected
,08-08 14:23:56.046  3823  3845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 14:23:56.046  3823  3839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-08 14:23:56.046  3823  3823 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:56.046  3823  3823 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:56.046  3823  3845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 14:23:56.046  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 14:23:56.046  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:56.046  3823  3845 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 14:23:56.046  3823  3845 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-08 14:23:56.046  3823  3845 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-08 14:23:56.046  3823  3845 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-08 14:23:56.046  3823  3823 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-08 14:23:56.046  3823  3823 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-08 14:23:56.046  3823  3839 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-08 14:23:56.047  3823  3823 V BluetoothAdapterState: isTurningOff()=true
,08-08 14:23:56.047  3823  3823 V BluetoothAdapterState: isTurningOn()=false
,08-08 14:23:56.047  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:56.047  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
,08-08 14:23:56.048  3823  3823 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-08 14:23:56.048  3823  3839 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-08 14:23:56.048  3823  3823 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-08 14:23:56.048  3823  3823 V BluetoothAdapterState: isTurningOff()=true
,08-08 14:23:56.049  3823  3823 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:56.049  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:56.049  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:56.049  3823  3823 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-08 14:23:56.049  3823  3823 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-08 14:23:56.050  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 14:23:56.051  3823  3823 D BluetoothMapService: MAP Service closeService in
08-08 14:23:56.051  3823  3823 V BluetoothAdapterState: isTurningOff()=true
08-08 14:23:56.051  3823  3823 V BluetoothAdapterState: isTurningOn()=false
,08-08 14:23:56.051  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
08-08 14:23:56.051  3823  3823 V BluetoothAdapterState: isBleTurningOff()=false
08-08 14:23:56.051  3437  3437 D DockEventReceiver: finishStartingService: stopping service
08-08 14:23:56.051  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-08 14:23:56.051  3823  3835 D BluetoothAdapterProperties: Setting state to 15
,08-08 14:23:56.051  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-08 14:23:56.052  3823  3835 I BluetoothAdapterState: Entering BleOnState
,08-08 14:23:56.052  3823  3835 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-08 14:23:56.052  1348  3323 D BluetoothPan: onBluetoothStateChange on: false
,08-08 14:23:56.052  3823  3823 D BluetoothMapService: cleanup()
08-08 14:23:56.052  3823  3823 D BluetoothMapService: MAP Service closeService in
08-08 14:23:56.053  3437  3437 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-08 14:23:56.053  3437  3437 D PanProfile: Bluetooth service disconnected
08-08 14:23:56.053  3437  3437 D BluetoothMap: Proxy object disconnected
08-08 14:23:56.053  3437  3437 D MapProfile: Bluetooth service disconnected
08-08 14:23:56.055  1348  1348 D BluetoothPbap: Proxy object disconnected
08-08 14:23:56.056  1348  1348 D PbapServerProfile: Bluetooth service disconnected
,08-08 14:23:56.056  1348  1859 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:56.056  3437  3437 D BluetoothPbap: Proxy object disconnected
08-08 14:23:56.056  3437  3437 D PbapServerProfile: Bluetooth service disconnected
08-08 14:23:56.056  3437  3449 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 14:23:56.058  3437  3448 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 14:23:56.059  3437  3448 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 14:23:56.060   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 14:23:56.060  3437  3805 D BluetoothMap: onBluetoothStateChange: up=false
08-08 14:23:56.063  1348  3323 D BluetoothMap: onBluetoothStateChange: up=false
08-08 14:23:56.063  3437  3449 D BluetoothPan: onBluetoothStateChange on: false
08-08 14:23:56.063   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 14:23:56.064  3437  3448 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-08 14:23:56.064  1348  1359 D BluetoothPbap: onBluetoothStateChange: up=false
08-08 14:23:56.064  1348  1360 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 14:23:56.065  1348  1859 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-08 14:23:56.066   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-08 14:23:56.066   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:56.066  1759  1770 D BluetoothHeadset: onBluetoothStateChange: up=false
08-08 14:23:56.066  3823  3835 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-08 14:23:56.066  3823  3835 D BluetoothAdapterProperties: Setting state to 16
08-08 14:23:56.066  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-08 14:23:56.067  3823  3835 D BluetoothAdapterProperties: onBleDisable
08-08 14:23:56.067  3823  3835 I BluetoothAdapterState: Entering PendingCommandState
08-08 14:23:56.067  3823  3836 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-08 14:23:56.068  3823  3845 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-08 14:23:56.068  3823  3845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-08 14:23:56.069  3823  3839 D BluetoothAdapterProperties: Scan Mode:20
08-08 14:23:56.069  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:56.071  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 14:23:56.073  3437  3437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-08 14:23:56.078  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-08 14:23:56.087  3437  3437 D DockEventReceiver: finishStartingService: stopping service
,08-08 14:23:56.270  3823  3839 I bt_hci  : shut_down
,08-08 14:23:56.282  3823  3843 D bt_hwcfg: hw_epilog_process
,08-08 14:23:56.283  3823  3843 I bt_vendor: low_power_mode_cb
,08-08 14:23:56.309  3823  3843 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-08 14:23:56.309  3823  3843 I bt_vendor: epilog_cb
,08-08 14:23:56.310  3823  3843 I bt_hci  : epilog_finished_callback
,08-08 14:23:56.315  3823  3839 I bt_hci_h4: hal_close
,08-08 14:23:56.316  3823  3839 I bt_userial_vendor: device fd = 51 close
,08-08 14:23:56.440  3823  3836 D bt_stack_manager: event_shut_down_stack finished.
,08-08 14:23:56.442  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-08 14:23:56.447  3823  3835 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-08 14:23:56.448  3823  3823 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-08 14:23:56.450  3823  3823 D BtGatt.GattService: Received stop request...Stopping profile...
,08-08 14:23:56.450  3823  3823 D BtGatt.GattService: stop()
,08-08 14:23:56.450  3823  3823 D BtGatt.AdvertiseManager: advertise clients cleared
,08-08 14:23:56.459  3823  3823 V BluetoothAdapterState: isTurningOff()=false
,08-08 14:23:56.459  3823  3823 V BluetoothAdapterState: isTurningOn()=false
08-08 14:23:56.459  3823  3823 V BluetoothAdapterState: isBleTurningOn()=false
,08-08 14:23:56.459  3823  3823 V BluetoothAdapterState: isBleTurningOff()=true
,08-08 14:23:56.460  3823  3835 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-08 14:23:56.461  3823  3835 D BluetoothAdapterProperties: Setting state to 10
,08-08 14:23:56.461  3823  3835 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-08 14:23:56.463  3823  3835 I BluetoothAdapterState: Entering OffState
08-08 14:23:56.473  3324  3324 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-08 14:23:56.477  3437  3437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-08 14:23:56.484  1487  1487 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-08 14:23:56.484  3437  3437 D DockEventReceiver: finishStartingService: stopping service
,08-08 14:23:56.874   873  1758 I ActivityManager: Killing 3173:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-08 14:24:04.054  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:04.067  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:04.071  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:04.135  1487  2682 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-08 14:24:04.135  1487  2682 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 14:24:04.135  1487  2682 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:24:04.136  1487  2682 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:24:04.182  2575  2575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 14:24:04.183  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 14:24:04.183  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-08 14:24:27.461  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:27.475  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:27.477  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:27.532  1487  1830 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 14:24:27.532  1487  1830 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 14:24:27.532  1487  1830 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:24:27.532  1487  1830 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:24:27.606  2575  2575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 14:24:27.607  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-08 14:24:27.608  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-08 14:24:27.658   873   882 I art     : Background partial concurrent mark sweep GC freed 27384(1997KB) AllocSpace objects, 9(268KB) LOS objects, 33% free, 28MB/43MB, paused 1.169ms total 108.621ms
,08-08 14:24:44.192   873  1305 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-08 14:24:47.099  1651  1721 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-08 14:24:47.099  1651  1721 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-08 14:24:47.149  1487  1487 I ConfigService: onCreate
,08-08 14:24:47.850  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:47.861  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:47.864  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:24:47.912  1487  1499 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-08 14:24:47.912  1487  1499 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-08 14:24:47.913  1487  1499 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:24:47.913  1487  1499 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:24:47.956  2575  2575 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-08 14:24:47.957  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-08 14:24:47.958  2575  2575 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-08 14:24:52.224  1487  1487 I ConfigService: onDestroy
,08-08 14:26:48.396  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:26:48.409  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:26:48.412  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:26:48.477  1487  1499 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 14:26:48.477  1487  1499 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 14:26:48.478  1487  1499 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:26:48.478  1487  1499 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:26:48.517  1487  1499 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 14:26:48.517  1487  1499 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 14:26:48.517  1487  1499 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 14:26:48.517  1487  1499 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 14:26:48.517  1487  1499 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 14:26:48.517  1487  1499 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 14:26:48.517  1487  1499 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:26:48.526  2575  2608 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 14:26:48.526  2575  2608 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 14:26:48.526  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 14:26:48.526  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 14:26:48.526  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 14:26:48.526  2575  2608 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 14:26:48.526  2575  2608 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:31:48.699  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:31:48.714  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:31:48.720  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:31:48.820  1487  1499 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 14:31:48.820  1487  1499 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 14:31:48.821  1487  1499 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:31:48.821  1487  1499 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:31:48.877  1487  1499 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 14:31:48.877  1487  1499 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 14:31:48.877  1487  1499 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 14:31:48.877  1487  1499 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 14:31:48.877  1487  1499 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 14:31:48.877  1487  1499 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 14:31:48.877  1487  1499 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:31:48.891  2575  2608 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 14:31:48.891  2575  2608 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 14:31:48.891  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 14:31:48.891  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 14:31:48.891  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 14:31:48.891  2575  2608 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 14:31:48.891  2575  2608 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:36:49.036  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:36:49.053  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:36:49.058  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:36:49.155  1487  3592 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 14:36:49.156  1487  3592 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 14:36:49.156  1487  3592 I GLSUser : [GLSUser] Extracting token using key: Auth
08-08 14:36:49.156  1487  3592 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:36:49.212  1487  3592 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 14:36:49.212  1487  3592 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 14:36:49.212  1487  3592 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 14:36:49.212  1487  3592 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 14:36:49.212  1487  3592 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 14:36:49.212  1487  3592 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 14:36:49.212  1487  3592 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:36:49.226  2575  2608 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 14:36:49.226  2575  2608 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 14:36:49.226  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 14:36:49.226  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 14:36:49.226  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 14:36:49.226  2575  2608 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 14:36:49.226  2575  2608 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:41:35.241   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-08 14:41:49.374  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:41:49.390  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:41:49.396  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:41:49.484  1487  1497 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 14:41:49.485  1487  1497 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-08 14:41:49.485  1487  1497 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:41:49.485  1487  1497 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:41:49.533  1487  1497 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 14:41:49.533  1487  1497 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 14:41:49.533  1487  1497 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 14:41:49.533  1487  1497 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 14:41:49.533  1487  1497 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 14:41:49.533  1487  1497 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 14:41:49.533  1487  1497 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:41:49.543  2575  2608 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 14:41:49.543  2575  2608 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 14:41:49.543  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 14:41:49.543  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 14:41:49.543  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 14:41:49.543  2575  2608 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 14:41:49.543  2575  2608 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:46:49.686  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:46:49.709  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:46:49.713  1487  1487 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-08 14:46:49.773  1487  2682 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-08 14:46:49.773  1487  2682 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-08 14:46:49.774  1487  2682 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-08 14:46:49.774  1487  2682 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-08 14:46:49.807  1487  2682 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-08 14:46:49.807  1487  2682 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-08 14:46:49.807  1487  2682 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-08 14:46:49.807  1487  2682 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-08 14:46:49.807  1487  2682 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-08 14:46:49.807  1487  2682 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-08 14:46:49.807  1487  2682 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-08 14:46:49.819  2575  2608 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-08 14:46:49.819  2575  2608 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-08 14:46:49.819  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-08 14:46:49.819  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-08 14:46:49.819  2575  2608 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-08 14:46:49.819  2575  2608 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-08 14:46:49.819  2575  2608 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-08 14:46:51.068  3967  3967 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-08 14:46:51.073  3967  3967 D AndroidRuntime: CheckJNI is OFF
08-08 14:46:51.116  3967  3967 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-08 14:46:51.163  3967  3967 I Radio-JNI: register_android_hardware_Radio DONE
08-08 14:46:51.186  3967  3967 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-08 14:46:51.203   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-08 14:46:51.204   873   886 I ActivityManager: Killing 3324:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-08 14:46:51.317   873  1385 D GraphicsStats: Buffer count: 2
08-08 14:46:51.317   873  1790 I WindowState: WIN DEATH: Window{4741dfb u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-08 14:46:51.318   873  1304 D WifiService: Client connection lost with reason: 4
08-08 14:46:51.321   873   896 W PackageSettings: Skipping PackageSetting{9555960 com.example.hello/10273} due to missing metadata
08-08 14:46:51.364   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-08 14:46:51.365   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-08 14:46:51.365   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-08 14:46:51.365   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-08 14:46:51.365   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:46:51.365   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.365   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 14:46:51.365   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-08 14:46:51.366   873   886 I ActivityManager:   Force finishing activity ActivityRecord{46e70a0 u0 com.test.thalitest/.MainActivity t2}
08-08 14:46:51.368   873   896 I art     : Starting a blocking GC Explicit
08-08 14:46:51.379   873  1385 W ActivityManager: Spurious death for ProcessRecord{277ef3 0:com.test.thalitest/u0a0}, curProc for 3324: null
08-08 14:46:51.435   873   896 I art     : Explicit concurrent mark sweep GC freed 32671(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 1.063ms total 66.056ms
08-08 14:46:51.476   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-08 14:46:51.478  3967  3967 I art     : System.exit called, status: 0
08-08 14:46:51.478  3967  3967 I AndroidRuntime: VM exiting with result code 0.
08-08 14:46:51.531   873   896 I ActivityManager: Start proc 3981:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-08 14:46:51.547   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-08 14:46:51.563   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-08 14:46:51.570   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-08 14:46:51.595  1693  2006 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-08 14:46:51.599  3199  3199 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-08 14:46:51.603   873  1794 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3324 uid 10000
08-08 14:46:51.621  1651  1651 I Keyboard.Facilitator: resetDictionaries() : en_US
08-08 14:46:51.633   873  1691 I ActivityManager: Start proc 3998:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-08 14:46:51.634  1759  1759 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-08 14:46:51.635  1651  1651 I Keyboard.Facilitator: onFinishInput()
08-08 14:46:51.638   873  1301 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-08 14:46:51.640  1651  3997 I Keyboard.Facilitator.DecoderInitializer: run()
08-08 14:46:51.645  1651  3997 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-08 14:46:51.645  1651  3997 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-08 14:46:51.645  1651  3997 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-08 14:46:51.642   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-08 14:46:51.657   873   885 E PackageManager: Failed to write settings, restoring backup
08-08 14:46:51.657   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-08 14:46:51.657   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-08 14:46:51.657   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-08 14:46:51.657   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-08 14:46:51.657   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-08 14:46:51.657   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:46:51.657   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.657   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 14:46:51.662   873  1780 I ActivityManager: Killing 3252:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-08 14:46:51.668   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-08 14:46:51.668   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-08 14:46:51.668   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 14:46:51.668   873   886 E DropBoxManagerService: 	... 13 more
08-08 14:46:51.673   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-08 14:46:51.648  1651  3997 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-08 14:46:51.673  1651  3997 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-08 14:46:51.673  1651  3997 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-08 14:46:51.674  1651  3997 I Decoder : createOrResetDecoder
08-08 14:46:51.701  3998  3998 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.736  3998  4011 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.737  3998  4011 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 14:46:51.755  3998  4011 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
--------- beginning of crash
08-08 14:46:51.759  3998  4011 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-08 14:46:51.759  3998  4011 E AndroidRuntime: Process: android.process.acore, PID: 3998
08-08 14:46:51.759  3998  4011 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.759  3998  4011 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 14:46:51.766  1773  1856 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-08 14:46:51.766   873  4013 E DropBoxManagerService: Can't write: system_app_crash
08-08 14:46:51.766   873  4013 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 14:46:51.766   873  4013 E DropBoxManagerService: 	... 5 more
08-08 14:46:51.767  1487  1487 I ConfigService: onCreate
08-08 14:46:51.777   873   886 I ActivityManager: Start proc 4015:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-08 14:46:51.788  3998  3998 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-08 14:46:51.790   873  1385 I ActivityManager: Start proc 4027:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-08 14:46:51.791  1773  1856 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-08 14:46:51.791  1773  1856 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1773
08-08 14:46:51.791  1773  1856 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.791  1773  1856 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-08 14:46:51.792   873   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-08 14:46:51.796   873   883 I ActivityManager: Killing 1834:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-08 14:46:51.798   873  4034 E DropBoxManagerService: Can't write: system_app_crash
08-08 14:46:51.798   873  4034 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 14:46:51.798   873  4034 E DropBoxManagerService: 	... 5 more
08-08 14:46:51.805  3998  4011 I Process : Sending signal. PID: 3998 SIG: 9
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-08 14:46:51.819  1487  4014 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-08 14:46:51.819  1487  4014 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-08 14:46:51.821  1487  4014 W SQLiteOpenHelper: Opened config.db in read-only mode
08-08 14:46:51.843   873  1304 D WifiService: Client connection lost with reason: 4
08-08 14:46:51.848  1773  1856 I Process : Sending signal. PID: 1773 SIG: 9
08-08 14:46:51.856  1651  3997 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-08 14:46:51.873   873  1780 I ActivityManager: Process android.process.acore (pid 3998) has died
08-08 14:46:51.881  4015  4015 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-08 14:46:51.902  1651  3997 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-08 14:46:51.903  1651  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-08 14:46:51.903  1651  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-08 14:46:51.912  1651  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-08 14:46:51.912  1651  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-08 14:46:51.913  1651  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-08 14:46:51.913  1651  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-08 14:46:51.913  1651  3997 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-08 14:46:51.914  1651  3997 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-08 14:46:51.914  1651  3997 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-08 14:46:51.914  1651  3997 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-08 14:46:51.914  1651  3997 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-08 14:46:51.914  1651  3997 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-08 14:46:51.922  1487  1487 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-08 14:46:51.923   278   278 E lowmemorykiller: Error writing /proc/1773/oom_score_adj; errno=22
08-08 14:46:51.924   278   278 E lowmemorykiller: Error writing /proc/1773/oom_score_adj; errno=22
08-08 14:46:51.925  1487  1487 D AndroidRuntime: Shutting down VM
08-08 14:46:51.926  1487  1487 E AndroidRuntime: FATAL EXCEPTION: main
08-08 14:46:51.926  1487  1487 E AndroidRuntime: Process: com.google.process.gapps, PID: 1487
08-08 14:46:51.926  1487  1487 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-08 14:46:51.926  1487  1487 E AndroidRuntime: 	... 8 more
08-08 14:46:51.928   873  4047 E DropBoxManagerService: Can't write: system_app_crash
08-08 14:46:51.928   873  4047 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-08 14:46:51.928   873  4047 E DropBoxManagerService: 	... 5 more
08-08 14:46:51.930  1487  1487 I Process : Sending signal. PID: 1487 SIG: 9
08-08 14:46:51.968  1810  4048 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
08-08 14:46:51.968  1810  4048 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@905ed0e
08-08 14:46:51.968   873  1806 I ActivityManager: Process com.google.process.gapps (pid 1487) early provider death
08-08 14:46:51.977   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
