#### Test 82912030c36b21a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
,09-08 14:00:17.620   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-08 14:00:18.302  3823  3823 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 14:00:18.307  3823  3823 D AndroidRuntime: CheckJNI is OFF
09-08 14:00:18.344  3823  3823 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 14:00:18.388  3823  3823 I Radio-JNI: register_android_hardware_Radio DONE
09-08 14:00:18.408  3823  3823 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 14:00:18.415   875  2044 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 14:00:18.464  2085  2097 W SearchService: Abort, client detached.
09-08 14:00:18.465  3823  3823 D AndroidRuntime: Shutting down VM
09-08 14:00:18.479  2085  2085 I HotwordDetector: Closing mic
09-08 14:00:18.479  2085  2332 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@69fa4d
09-08 14:00:18.479  2085  2339 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-08 14:00:18.512   875  1694 I ActivityManager: Start proc 3832:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 14:00:18.542   377  2341 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 14:00:18.543   377  2341 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-08 14:00:18.548   377  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 14:00:18.550  2085  2338 I MicroRecognitionRnrImpl: Detection finished
09-08 14:00:18.550  2085  2337 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-08 14:00:18.602  3832  3832 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 14:00:18.627  3832  3832 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 14:00:18.633  3832  3832 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4752-4755)
09-08 14:00:18.633  3832  3832 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:00:18.650  3832  3832 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {447d4b4}
09-08 14:00:18.652  3832  3832 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 14:00:18.654  3832  3832 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 14:00:18.676  3832  3832 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 14:00:18.679  3832  3832 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:00:18.697  3832  3832 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 14:00:18.711  3832  3832 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:00:18.711  3832  3832 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 14:00:18.711  3832  3832 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 14:00:18.711  3832  3832 I Adreno  : Build Date                       : 10/20/15
09-08 14:00:18.711  3832  3832 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 14:00:18.711  3832  3832 I Adreno  : Local Branch                     : M14
09-08 14:00:18.711  3832  3832 I Adreno  : Remote Branch                    : 
09-08 14:00:18.711  3832  3832 I Adreno  : Remote Branch                    : 
09-08 14:00:18.711  3832  3832 I Adreno  : Reconstruct Branch               : 
09-08 14:00:18.801   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c8be6ab:true
09-08 14:00:18.889  3832  3832 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 14:00:18.907  3832  3832 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-08 14:00:18.996  3832  3870 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-08 14:00:19.021  3832  3857 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-08 14:00:19.045  3832  3870 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 14:00:19.061  1897  1897 I Keyboard.Facilitator: onFinishInput()
09-08 14:00:19.100   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +608ms
09-08 14:00:19.178  3832  3832 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3832
09-08 14:00:19.349   875  2038 I ActivityManager: Killing 3254:com.google.android.gm/u0a78 (adj 15): empty #17
09-08 14:00:19.406  3832  3832 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-08 14:00:19.414   875  2038 I ActivityManager: Killing 3152:com.google.android.apps.maps/u0a65 (adj 15): empty #18
09-08 14:00:19.568  3832  3873 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1702889168
09-08 14:00:19.573  3832  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 14:00:19.573  3832  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 14:00:19.573  3832  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 14:00:19.573  3832  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 14:00:19.573  3832  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-08 14:00:19.574  3832  3873 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ea9dff8 added. We now have 1 listener(s)
09-08 14:00:19.577  3832  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-08 14:00:19.578  3832  3873 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:00:19.579  3832  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:00:19.579  3832  3873 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 14:00:19.582  3832  3873 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b1a237 added. We now have 1 listener(s)
09-08 14:00:19.582  3832  3873 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:00:19.586   875  1312 D WifiService: New client listening to asynchronous messages
09-08 14:00:19.587  3832  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 14:00:19.588  3832  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 14:00:19.589  3832  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 14:00:19.589  3832  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 14:00:19.589  3832  3873 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 14:00:19.593  3832  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:00:19.594  3832  3873 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-08 14:00:19.602  3832  3873 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:00:19.602  3832  3873 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:00:19.602  3832  3873 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 14:00:19.603  3832  3873 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:00:19.603  3832  3873 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 14:00:19.679  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:00:19.682  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:00:19.687  3832  3832 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 14:00:20.650   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 14:00:20.984  3832  3880 W jxcore-log: Initializing JXcore engine
09-08 14:00:20.984  3832  3880 W jxcore-log: JXcore engine is ready
,09-08 14:00:21.018  3880  3880 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-08 14:00:21.018  3880  3880 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12082]" dev="sockfs" ino=12082 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-08 14:00:21.018  3880  3880 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 14:00:21.018  3880  3880 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26981]" dev="sockfs" ino=26981 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 14:00:21.034  3832  3880 W jxcore-log: Starting JXcore engine
,09-08 14:00:21.117  3832  3880 W jxcore-log: Platform android
09-08 14:00:21.117  3832  3880 W jxcore-log: 
,09-08 14:00:21.117  3832  3880 W jxcore-log: Process ARCH arm
09-08 14:00:21.117  3832  3880 W jxcore-log: 
,09-08 14:00:21.313  3832  3880 I jxcore-log: JXcore Cordova bridge is ready!
09-08 14:00:21.313  3832  3880 I jxcore-log: 
09-08 14:00:21.313  3832  3880 W jxcore-log: JXcore engine is started
,09-08 14:00:21.325  3832  3873 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 14:00:21.331  3832  3832 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 14:00:23.689   875  1918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 14:00:26.907   875  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-08 14:00:28.719  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:28.729  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:28.732  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:28.785  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 14:00:28.785  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 14:00:28.786  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:00:28.786  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:00:28.811  3554  3554 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:00:28.811  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 14:00:28.812  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-08 14:00:35.083  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 14:00:35.083  3832  3880 I jxcore-log: 
,09-08 14:00:35.086  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 14:00:35.086  3832  3880 I jxcore-log: 
,09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:00:35.095  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:00:35.102  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:00:35.104  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 14:00:35.104  3832  3880 I jxcore-log: 
,09-08 14:00:35.106  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 14:00:35.106  3832  3880 I jxcore-log: 
,09-08 14:00:35.453  3832  3880 I jxcore-log: Running unit tests
09-08 14:00:35.453  3832  3880 I jxcore-log: 
,09-08 14:00:35.453  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:00:35.454  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7b9078 added. We now have 2 listener(s)
09-08 14:00:35.455  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:00:35.455  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:00:35.455  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:00:35.455  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:00:35.455  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1714351 added. We now have 2 listener(s)
09-08 14:00:35.455  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:00:35.456  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:00:35.459  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:00:35.472  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:00:35.478  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:00:35.478  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:00:35.478  3832  3880 D executeNativeTests: Running unit tests
,09-08 14:00:35.484  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:35.486  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:35.580  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:00:35.580  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 added. We now have 3 listener(s)
09-08 14:00:35.581  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:00:35.581  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:00:35.581  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:00:35.582  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:00:35.582  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 added. We now have 3 listener(s)
09-08 14:00:35.582  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:00:35.582  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:00:35.585  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:00:35.593  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:00:35.597  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:00:35.597  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:00:35.600  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 14:00:35.601  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
09-08 14:00:35.601  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:00:35.602  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 14:00:35.603  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:00:35.603  3832  3880 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-08 14:00:35.603  3832  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:00:35.603  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:00:35.604  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:00:35.604  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:00:35.604  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 14:00:35.604  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:00:35.605  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:00:35.605  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:35.605  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:35.605  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:35.605  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:00:35.605  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:00:35.605  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 removed from the list
09-08 14:00:35.605  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:35.606  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 removed from the list
,09-08 14:00:35.609  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:35.609  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:35.609  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:35.609  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:35.610  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:35.612  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:00:35.612  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:35.612  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:00:35.613  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:35.617  3832  3880 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 14:00:35.619  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:35.620  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:35.620  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:00:35.620  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:35.620  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:35.620  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:35.621  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:35.621  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:35.621  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:35.621  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:35.622  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:35.622  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:35.622  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:35.622  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:35.623  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:00:35.623  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:35.623  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:00:35.623  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:35.628  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 14:00:35.628  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:00:35.628  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:00:35.629  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:00:35.630  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:00:35.630  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:00:35.630  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:35.631  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:35.631  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:35.631  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:35.631  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:35.631  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:35.631  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:35.631  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:35.631  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:35.631  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:35.631  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:35.631  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:35.631  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:35.632  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:00:35.632  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:35.632  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:35.632  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:35.633  3832  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:00:35.634  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:00:35.640  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:00:35.643  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:00:35.643  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:00:35.643  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:00:35.643  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:00:35.643  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:00:35.643  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:00:35.643  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:00:35.646  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:35.647  3832  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 14:00:35.647  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:00:35.649  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:35.653  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:00:35.655  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 14:00:35.656  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:00:35.658  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 14:00:35.660  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-08 14:00:35.660  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 14:00:35.661  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 14:00:35.661  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 14:00:35.662  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:00:35.666  2719  2732 D BtGatt.GattService: registerClient() - UUID=5fa2910c-b288-407c-b2fe-37ffaa94860b
,09-08 14:00:35.667  2719  2771 D BtGatt.GattService: onClientRegistered() - UUID=5fa2910c-b288-407c-b2fe-37ffaa94860b, clientIf=5
,09-08 14:00:35.668  3832  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 14:00:35.669  2719  2928 D BtGatt.GattService: start scan with filters
,09-08 14:00:35.672  2719  2776 D BtGatt.ScanManager: handling starting scan
,09-08 14:00:35.672  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 14:00:35.672  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:00:35.672  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:00:35.673  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 14:00:35.673  2719  2776 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:00:35.675  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:00:35.675  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 14:00:35.676  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:00:35.677  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:00:35.681  3832  3880 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:00:35.681  2719  2771 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 14:00:35.681  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:35.681  2719  2776 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:00:35.687  2719  2771 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 14:00:35.687  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:35.687  2719  2776 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:00:35.688  2719  2776 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 14:00:35.696  2719  2771 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 14:00:35.696  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:35.701  2719  2771 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 14:00:35.702  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:35.777   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 14:00:35.811  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:35.812  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:35.857  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:00:35.857  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:00:35.858  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:00:35.858  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:00:35.885  3023  3893 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 14:00:35.885  3023  3893 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at blb.a(PG:3937)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at czp.a(PG:18188)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:00:35.885  3023  3893 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	... 12 more
09-08 14:00:35.885  3023  3893 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at fal.a(PG:38)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:00:35.885  3023  3893 E HttpOperation: 	... 14 more
,09-08 14:00:35.977  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:00:35.977  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 14:00:35.977  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:00:35.977  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:00:36.031  3023  3893 E HttpOperation: [getmobileexperiments] Unexpected exception,
09-08 14:00:36.031  3023  3893 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at hec.a(PG:42)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at hee.a(PG:102)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at czr.a(PG:65)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at kka.a(PG:108)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at czp.a(PG:19176)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:00:36.031  3023  3893 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	... 15 more
09-08 14:00:36.031  3023  3893 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at fal.a(PG:38)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:00:36.031  3023  3893 E HttpOperation: 	... 17 more
,09-08 14:00:36.034  3023  3893 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 14:00:36.034  3023  3893 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at hec.a(PG:42)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at hee.a(PG:102)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at czr.a(PG:65)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at kka.a(PG:108)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	... 15 more
09-08 14:00:36.034  3023  3893 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at fal.a(PG:38)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 14:00:36.034  3023  3893 E ExperimentLoader: 	... 17 more
,09-08 14:00:36.141   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 131655, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:00:36.177  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 14:00:36.178  3832  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:00:36.178  3832  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:00:36.204  2719  2719 D BtGatt.ScanManager: awakened up at time 132326
,09-08 14:00:36.212  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:36.246  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
09-08 14:00:36.246  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:36.247  2719  2771 D BtGatt.GattService: current time is 132369065643
,09-08 14:00:36.248  2719  2771 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -78, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 14:00:36.253  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 14:00:36.256  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 14:00:36.257  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 14:00:37.752  2719  2719 D BtGatt.ScanManager: awakened up at time 133874
,09-08 14:00:37.755  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:37.798  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-08 14:00:37.798  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:37.799  2719  2771 D BtGatt.GattService: current time is 133921050681
09-08 14:00:37.800  2719  2771 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,09-08 14:00:37.801  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 14:00:37.802  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 14:00:37.803  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:00:37.803  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 14:00:37.804  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,09-08 14:00:39.305  2719  2719 D BtGatt.ScanManager: awakened up at time 135427
,09-08 14:00:39.307  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:39.315  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 14:00:39.315  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:40.690  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:40.691  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:00:40.691  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:00:40.691  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:40.692  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:00:40.692  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:00:40.693  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:00:40.693  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 14:00:40.693  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:00:40.695  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:00:40.705  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 14:00:40.707  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:00:40.709  2719  2736 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:00:40.712  2719  2732 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:00:40.713  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:00:40.713  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:00:40.714  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 14:00:40.714  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:00:40.714  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 14:00:40.717  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:00:40.718  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 14:00:40.718  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:00:40.719  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:00:40.720  2719  2719 D BtGatt.ScanManager: awakened up at time 136842
,09-08 14:00:40.726  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:00:40.727  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:00:40.728  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:00:40.728  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:00:40.728  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:40.728  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:40.728  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:00:40.728  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
,09-08 14:00:40.729  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:40.729  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:40.729  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:40.729  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:40.735  2719  2771 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 14:00:40.736  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:40.736  2719  2776 D BtGatt.ScanManager: stopping BLe Batch
,09-08 14:00:40.751  2719  2771 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:00:40.751  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:40.751  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:40.767  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 14:00:40.767  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:41.229  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:00:44.873   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-08 14:00:45.730  3832  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 14:00:45.738  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:00:45.756  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:00:45.765  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:00:45.765  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:00:45.766  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:00:45.766  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 14:00:45.767  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 14:00:45.767  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:00:45.767  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:00:45.779  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:45.783  3832  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 14:00:45.783  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:00:45.789  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:45.800  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:00:45.803  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 14:00:45.803  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:00:45.816  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 14:00:45.817  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 14:00:45.817  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 14:00:45.820  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:00:45.828  2719  2920 D BtGatt.GattService: registerClient() - UUID=d09a08cd-c052-47ab-9609-85b9a30aec25
,09-08 14:00:45.830  2719  2771 D BtGatt.GattService: onClientRegistered() - UUID=d09a08cd-c052-47ab-9609-85b9a30aec25, clientIf=5
09-08 14:00:45.831  3832  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 14:00:45.832  2719  2732 D BtGatt.GattService: start scan with filters
,09-08 14:00:45.844  2719  2776 D BtGatt.ScanManager: handling starting scan
,09-08 14:00:45.845  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 14:00:45.845  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 14:00:45.845  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:00:45.846  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 14:00:45.856  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:00:45.857  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 14:00:45.857  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:00:45.863  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 14:00:45.866  2719  2771 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 14:00:45.866  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:45.866  2719  2776 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:00:45.871  3832  3880 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:00:45.891  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:45.892  3832  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 14:00:45.892  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:00:45.893  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:00:45.893  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:45.893  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:00:45.893  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 14:00:45.894  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:00:45.894  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:00:45.895  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:00:45.895  2719  2771 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 14:00:45.895  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:45.895  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:00:45.895  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 14:00:45.895  2719  2776 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 14:00:45.896  2719  2776 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 14:00:45.897  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:00:45.901  2719  2732 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:00:45.908  2719  2736 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:00:45.909  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:00:45.909  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:00:45.910  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 14:00:45.910  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 14:00:45.911  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 14:00:45.913  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:00:45.914  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:00:45.914  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 14:00:45.914  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:00:45.915  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:00:45.916  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:45.916  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:45.916  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:00:45.916  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:00:45.916  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:45.916  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:45.917  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:45.917  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:00:45.916  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:00:45.917  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:45.917  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:00:45.917  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:45.917  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:45.919  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:00:45.919  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:45.919  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:00:45.919  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:45.920  3832  3880 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 14:00:45.922  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:00:45.924  2719  2771 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 14:00:45.925  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:00:45.928  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:00:45.932  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:00:45.932  2719  2771 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 14:00:45.932  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:00:45.932  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:45.932  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:00:45.935  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 14:00:45.935  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:00:45.935  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:00:45.935  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:00:45.935  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:00:45.938  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:00:45.941  3832  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 14:00:45.941  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 14:00:45.944  2719  2771 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 14:00:45.944  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:45.944  2719  2776 D BtGatt.ScanManager: stopping BLe Batch
09-08 14:00:45.947  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:00:45.948  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 14:00:45.948  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:00:45.952  2719  2771 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:00:45.952  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:45.953  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:45.955  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 14:00:45.955  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-08 14:00:45.955  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:00:45.956  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:00:45.958  2719  2736 D BtGatt.GattService: registerClient() - UUID=6ed386f3-1c62-40b6-b34b-47e3e1b9130d
09-08 14:00:45.959  2719  2771 D BtGatt.GattService: onClientRegistered() - UUID=6ed386f3-1c62-40b6-b34b-47e3e1b9130d, clientIf=5
,09-08 14:00:45.959  3832  3844 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 14:00:45.959  2719  2732 D BtGatt.GattService: start scan with filters
09-08 14:00:45.959  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:00:45.959  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:45.964  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:00:45.964  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:00:45.964  2719  2776 D BtGatt.ScanManager: handling starting scan
09-08 14:00:45.964  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:00:45.964  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 14:00:45.967  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 14:00:45.967  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:00:45.967  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 14:00:45.969  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:00:45.970  2719  2771 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 14:00:45.970  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:45.971  2719  2776 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 14:00:45.972  3832  3880 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 14:00:45.976  2719  2771 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 14:00:45.976  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:45.977  2719  2776 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:00:45.977  2719  2776 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 14:00:45.988  2719  2771 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 14:00:45.988  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:45.995  2719  2771 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 14:00:45.995  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:46.468  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 14:00:46.469  3832  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:00:46.469  3832  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:00:47.502  2719  2719 D BtGatt.ScanManager: awakened up at time 143624
,09-08 14:00:47.505  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:47.536  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-08 14:00:47.536  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:47.537  2719  2771 D BtGatt.GattService: current time is 143658796001
,09-08 14:00:47.538  2719  2771 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -85, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -85, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 14:00:47.538  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 14:00:47.539  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:00:47.539  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 14:00:47.539  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 14:00:47.539  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 14:00:47.609   875  1918 D NetlinkSocketObserver: NeighborEvent{elapsedMs=143730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:00:49.042  2719  2719 D BtGatt.ScanManager: awakened up at time 145164
,09-08 14:00:49.046  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:49.170  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-08 14:00:49.171  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:00:49.171  2719  2771 D BtGatt.GattService: current time is 145293095108
09-08 14:00:49.171  2719  2771 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -77, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -88, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -69, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
09-08 14:00:49.172  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:00:49.172  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 14:00:49.173  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-08 14:00:49.173  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 14:00:49.174  2719  2771 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,09-08 14:00:49.417  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:49.433  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:49.439  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:00:49.517  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 14:00:49.517  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 14:00:49.518  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:00:49.518  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:00:49.580  3554  3554 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:00:49.582  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 14:00:49.584  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-08 14:00:50.674  2719  2719 D BtGatt.ScanManager: awakened up at time 146796
09-08 14:00:50.676  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:50.687  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:00:50.687  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:50.974  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:50.975  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:50.975  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:00:50.975  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:50.976  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 14:00:50.976  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:00:50.976  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 14:00:50.976  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:00:50.977  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:00:50.979  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:00:50.979  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 14:00:50.983  3832  3880 D BluetoothAdapter: STATE_ON
09-08 14:00:50.987  2719  2732 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:00:50.991  2719  2920 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 14:00:50.992  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:00:50.992  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:00:50.993  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 14:00:50.993  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:00:50.993  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 14:00:50.995  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:00:50.996  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 14:00:50.996  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 14:00:50.996  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:00:50.997  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:00:50.999  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:00:51.000  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:00:51.000  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:00:51.004  2719  2771 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 14:00:51.005  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:51.005  2719  2776 D BtGatt.ScanManager: stopping BLe Batch
,09-08 14:00:51.018  2719  2771 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:00:51.019  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:51.019  2719  2776 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:00:51.032  2719  2771 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:00:51.032  2719  2771 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:00:51.501  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:00:51.502  3832  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:51.502  3832  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:00:56.002  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,09-08 14:00:56.002  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:00:56.003  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:56.005  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:00:56.006  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.007  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:00:56.007  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
,09-08 14:00:56.007  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.008  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.008  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.009  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.010  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.011  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.014  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:00:56.014  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:56.015  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.015  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.017  3832  3880 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-08 14:00:56.019  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:00:56.020  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.020  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:00:56.021  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.021  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.021  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.022  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
,09-08 14:00:56.022  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.022  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.022  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.022  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.023  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.023  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.023  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.026  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:00:56.026  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:00:56.026  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.026  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.029  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 14:00:56.029  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:00:56.029  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.030  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:00:56.030  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.031  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.031  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.031  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.031  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:00:56.032  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.032  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.032  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.032  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.033  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.033  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.035  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:00:56.036  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:56.036  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.036  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.038  3832  3880 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 14:00:56.038  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:56.039  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.039  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:56.040  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.040  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.040  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.040  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.040  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.040  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.040  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:00:56.041  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.041  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.041  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.041  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.042  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:00:56.043  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:56.043  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.043  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.044  3832  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-08 14:00:56.044  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:00:56.044  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.045  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:56.045  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:00:56.045  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.045  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.045  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.046  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:00:56.046  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.046  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.046  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.046  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.046  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.046  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.048  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:00:56.048  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:56.048  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.048  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.049  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 14:00:56.050  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:00:56.050  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:00:56.050  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 14:00:56.050  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:00:56.050  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:00:56.050  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 14:00:56.051  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:00:56.051  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 14:00:56.051  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:00:56.051  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.051  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:00:56.051  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.052  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.052  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.053  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.053  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.054  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.055  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:00:56.056  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.056  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.058  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.059  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.060  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:00:56.060  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:00:56.060  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.061  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.062  3832  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:00:56.062  3832  3880 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 14:00:56.062  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-08 14:00:56.070  3832  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 14:00:56.070  3832  3880 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 14:00:56.070  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 14:00:56.070  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 14:00:56.070  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 14:00:56.070  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 14:00:56.071  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-08 14:00:56.072  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-08 14:00:56.072  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 14:00:56.072  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 14:00:56.072  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 14:00:56.073  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 14:00:56.073  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 14:00:56.073  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-08 14:00:56.074  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-08 14:00:56.075  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 14:00:56.075  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 14:00:56.076  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 14:00:56.076  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 14:00:56.077  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 14:00:56.077  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-08 14:00:56.077  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 14:00:56.077  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 14:00:56.077  3832  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 14:00:56.077  3832  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:00:56.078  3832  3880 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 14:00:56.078  3832  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:00:56.078  3832  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 14:00:56.078  3832  3880 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 14:00:56.078  3832  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 14:00:56.079  3832  3880 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 14:00:56.079  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-08 14:00:56.084  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-08 14:00:56.086  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-08 14:00:56.086  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 14:00:56.087  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 14:00:56.087  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 14:00:56.087  3832  3880 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 14:00:56.087  3832  3880 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 14:00:56.088  3832  3880 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 14:00:56.088  3832  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
,09-08 14:00:56.090  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:56.090  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.090  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:56.090  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.090  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.091  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.091  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-08 14:00:56.092  3832  3897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:00:56.092  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.092  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:00:56.092  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.092  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.092  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.092  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.092  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.092  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.094  3832  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
09-08 14:00:56.094  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:00:56.094  3832  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
09-08 14:00:56.094  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:56.095  3832  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
09-08 14:00:56.095  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.096  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.098  3832  3897 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
,09-08 14:00:56.099  3832  3880 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-08 14:00:56.100  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:00:56.100  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.100  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:56.100  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.100  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.100  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.100  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.100  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.100  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.100  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.101  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.101  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.101  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.101  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.102  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:00:56.102  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:00:56.103  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.103  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.103  3832  3880 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 14:00:56.104  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:56.104  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.104  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:56.104  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.104  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.104  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.104  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.104  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:00:56.104  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.104  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.105  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.105  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.105  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.105  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.106  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:00:56.106  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:56.106  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.106  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.107  3832  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 14:00:56.108  3832  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 14:00:56.108  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:00:56.108  3832  3880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,09-08 14:00:56.108  3832  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:00:56.108  3832  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 14:00:56.109  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:00:56.109  3832  3880 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 14:00:56.109  3832  3880 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 14:00:56.109  3832  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 14:00:56.109  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:00:56.109  3832  3880 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 14:00:56.110  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:00:56.110  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:00:56.110  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:00:56.110  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.110  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.110  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.110  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.111  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.111  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.111  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.111  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.111  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.111  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:00:56.111  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:00:56.113  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:00:56.113  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:00:56.113  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.113  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:00:56.114  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:00:56.114  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.114  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.115  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:00:56.115  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:00:56.115  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:00:56.115  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:00:56.115  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:00:56.115  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:00:56.712   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-08 14:00:56.724  1897  1897 I Keyboard.Facilitator: onFinishInput()
,09-08 14:00:56.727   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 14:00:56.727   875   895 I Adreno  : Build Date                       : 10/20/15
09-08 14:00:56.727   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 14:00:56.727   875   895 I Adreno  : Local Branch                     : M14
09-08 14:00:56.727   875   895 I Adreno  : Remote Branch                    : 
09-08 14:00:56.727   875   895 I Adreno  : Remote Branch                    : 
09-08 14:00:56.727   875   895 I Adreno  : Reconstruct Branch               : 
,09-08 14:00:56.754   280  2374 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (239 us)
,09-08 14:00:57.337  3832  3832 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 14:00:57.338  3832  3832 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-08 14:00:57.368   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-08 14:00:57.374  3832  3832 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b1563aa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e201916, 16908290=android.view.AbsSavedState$1@e201916}, android:focusedViewId=100}]}]
,09-08 14:00:57.375  3832  3832 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-08 14:00:57.375  3832  3832 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 14:00:57.375  3832  3832 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-08 14:00:57.375   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-08 14:00:57.378   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-08 14:00:57.380   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,09-08 14:00:57.380   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-08 14:00:57.427   875   884 I art     : Background partial concurrent mark sweep GC freed 15978(1121KB) AllocSpace objects, 4(92KB) LOS objects, 33% free, 28MB/43MB, paused 842us total 100.837ms
,09-08 14:00:57.614   280   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-08 14:00:57.618   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-08 14:00:57.624   875  1336 D SurfaceControl: Excessive delay in setPowerMode(): 245ms
09-08 14:00:57.628   875   895 I DreamManagerService: Entering dreamland.
09-08 14:00:57.629   875   895 I PowerManagerService: Dozing...
09-08 14:00:57.631   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-08 14:00:57.675   377  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-08 14:00:57.675   377  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-08 14:00:57.680   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:00:57.691   875  1311 E native  : do suspend false
,09-08 14:00:57.691  1994  3902 D NfcService: Discovery configuration equal, not updating.
,09-08 14:00:57.710   875  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 14:00:57.724   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:00:57.730   875  1311 E native  : do suspend true
,09-08 14:00:57.817   377  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-08 14:00:57.818   377  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-08 14:00:58.184   875  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-08 14:01:01.116  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:01:01.117  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.117  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:01:01.117  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:01:01.117  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.118  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:01:01.118  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:01:01.119  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:01:01.119  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:01:01.119  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:01:01.120  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.120  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.120  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:01:01.120  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.121  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.121  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:01:01.121  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.122  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.122  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.122  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:01.126  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:01:01.126  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:01:01.126  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.127  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:01:01.132  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 14:01:01.134  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:01:01.136  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 14:01:01.139  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 14:01:01.139  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 14:01:01.140  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 14:01:01.140  3832  3832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 14:01:01.140  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:01:01.142  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:01:01.142  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:01:01.142  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:01:01.143  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-08 14:01:01.143  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.143  3832  3907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:01:01.143  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:01:01.144  3832  3832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:01:01.144  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:01:01.144  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.144  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:01:01.144  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:01:01.145  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:01:01.145  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:01:01.145  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:01.150  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:01:01.150  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:01:01.151  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:01:01.151  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:01:01.151  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.151  3832  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 14:01:01.152  3832  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:01:01.152  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:01:01.152  3832  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:01:01.152  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:01:01.153  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:01:01.153  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:01:01.153  3832  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:01:01.153  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.153  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.154  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:01:01.154  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.155  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.155  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:01:01.155  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.156  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.156  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.156  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.159  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:01:01.159  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:01:01.160  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.160  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
,09-08 14:01:01.163  3832  3880 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 14:01:01.163  3832  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 14:01:01.164  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 14:01:01.168  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:01:01.168  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 14:01:01.168  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:01:01.169  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:01:01.170  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:01:01.172  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:01:01.173  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.173  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.173  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:01:01.173  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.173  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.174  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:01:01.174  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.174  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.174  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.174  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.176  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:01:01.177  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:01:01.177  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.177  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.184  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:01:01.184  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:01:01.184  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:01:01.185  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:01:01.185  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.185  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.185  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:01:01.185  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.186  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.186  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:01:01.186  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.186  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.186  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.187  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.188  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:01:01.189  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:01:01.189  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.189  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.192  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:01:01.192  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:01:01.192  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:01:01.193  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:01:01.193  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.193  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.193  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7a0f1a7 not in the list
09-08 14:01:01.194  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.194  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.194  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:01:01.195  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.195  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.195  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:01.195  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:01:01.198  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:01:01.198  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:01:01.198  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:01.198  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@751f654 not in the list
09-08 14:01:01.201  3832  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 14:01:01.202  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:01:01.202  3832  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 14:01:01.202  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 14:01:01.203  3832  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 14:01:01.203  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 14:01:01.210  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 14:01:01.210  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 14:01:01.212  3832  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 14:01:01.213  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:01:01.213  3832  3880 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 14:01:01.213  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 14:01:01.213  3832  3880 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 14:01:01.214  3832  3880 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-08 14:01:01.215  3832  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 14:01:01.216  3832  3880 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 14:01:01.216  3832  3880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 14:01:01.216  3832  3880 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 14:01:01.216  3832  3880 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 14:01:01.216  3832  3880 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-08 14:01:01.217  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:01:01.218  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8539297 added. We now have 3 listener(s)
09-08 14:01:01.218  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:01:01.219  2719  2910 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-08 14:01:01.219  2719  2918 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
09-08 14:01:01.221  3832  3880 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 14:01:01.222   875  1947 D WifiService: setWifiEnabled: true pid=3832, uid=10000
09-08 14:01:01.222   875  1947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:01:01.652  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:01:03.356  1864  2658 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 14:01:06.230  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:01:06.230  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a099c84 added. We now have 4 listener(s)
,09-08 14:01:06.231  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:01:06.248  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:01:06.248  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a099c84 removed from the list
09-08 14:01:06.249  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:01:06.249  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:06.249  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:06.252  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:01:06.252  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e00c6d added. We now have 4 listener(s)
09-08 14:01:06.252  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:01:06.256  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:01:06.256  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e00c6d removed from the list
09-08 14:01:06.257  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:01:06.257  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:06.257  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:06.260  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:01:06.260  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7cb0a2 added. We now have 4 listener(s)
,09-08 14:01:06.261  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:01:06.268   875  1394 D WifiService: setWifiEnabled: false pid=3832, uid=10000
,09-08 14:01:06.268   875  1394 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:01:06.281  2719  2767 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 14:01:06.281  2719  2767 D BluetoothAdapterProperties: Setting state to 13
09-08 14:01:06.282  2719  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 14:01:06.282  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:01:06.284  2719  2767 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 14:01:06.290  2719  2767 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:01:06.294  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:06.294  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:01:06.297  2719  2719 D BluetoothMapService: onReceive
,09-08 14:01:06.298  2719  2719 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:01:06.298  2719  2719 D BluetoothMapService: STATE_TURNING_OFF
,09-08 14:01:06.299  2719  2719 D BluetoothMapService: MAP Service closeService in
09-08 14:01:06.299  2719  2771 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:01:06.299  2719  2719 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 14:01:06.299  2719  2719 D ObexServerSockets0: shutdown(block = true)
09-08 14:01:06.300  2719  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 14:01:06.301  2719  2719 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 14:01:06.302  2719  2918 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 14:01:06.302  2719  2940 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 14:01:06.302  2719  2719 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 14:01:06.302  2719  2941 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 14:01:06.302  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.303  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:06.303  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:01:06.304  2719  2719 I BtOppRfcommListener: stopping Accept Thread
09-08 14:01:06.305  2719  3462 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 14:01:06.306  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:06.306  2719  3462 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 14:01:06.313  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:06.316  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:06.316  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:01:06.317  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.318  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:01:06.319   875   888 I ActivityManager: Start proc 3911:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 14:01:06.320  2719  2719 D HeadsetService: Received stop request...Stopping profile...
,09-08 14:01:06.320  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 14:01:06.322  2719  2719 V BluetoothAdapterState: isTurningOff()=true
,09-08 14:01:06.322  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:06.322  2008  2289 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:06.322  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:06.322  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:06.322   875   875 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:06.324  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:06.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:01:06.324   875  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 14:01:06.324   875  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 14:01:06.324   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:01:06.324  1365  1393 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:06.324   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 14:01:06.324   875   875 D BluetoothHeadset: Proxy object disconnected
,09-08 14:01:06.324  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.324   875   875 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:06.325  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:06.327  2719  2719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 14:01:06.327  2719  2719 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 14:01:06.328  2719  2910 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:06.328  2719  2910 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:06.328  2719  2910 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:06.328  2719  2771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 14:01:06.328  2719  2771 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 14:01:06.328  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:06.330  2719  2719 D A2dpService: Received stop request...Stopping profile...
09-08 14:01:06.330  2719  2923 D A2dpStateMachine: Exit Disconnected: -1
09-08 14:01:06.331  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:06.331   875  1311 E native  : do suspend true
09-08 14:01:06.333  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:06.334   875   875 D BluetoothA2dp: Proxy object disconnected
09-08 14:01:06.335  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:06.335  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:06.335  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:06.335  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:06.336  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:06.341  1365  1365 D HeadsetProfile: Bluetooth service disconnected
09-08 14:01:06.341  1365  1365 D BluetoothA2dp: Proxy object disconnected
,09-08 14:01:06.341  2719  2910 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:06.341  2719  2910 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:06.342  2719  2910 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:01:06.342  2719  2910 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 14:01:06.342  2719  2910 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:01:06.342  2719  2910 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:01:06.342  2719  2771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 14:01:06.343  2719  2719 D HidService: Received stop request...Stopping profile...
,09-08 14:01:06.343  2719  2719 D HidService: Stopping Bluetooth HidService
09-08 14:01:06.344  1365  1365 D BluetoothInputDevice: Proxy object disconnected
09-08 14:01:06.344  1365  1365 D HidProfile: Bluetooth service disconnected
,09-08 14:01:06.345  2719  2719 D HealthService: Received stop request...Stopping profile...
09-08 14:01:06.346   875  1919 D DhcpClient: Clearing IP address
09-08 14:01:06.347   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:01:06.347  2719  2719 D PanService: Received stop request...Stopping profile...
,09-08 14:01:06.349  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-08 14:01:06.349  2719  2719 D BluetoothMapService: Received stop request...Stopping profile...
09-08 14:01:06.349  1365  1365 D PanProfile: Bluetooth service disconnected
09-08 14:01:06.349   373   873 D CommandListener: Setting iface cfg
09-08 14:01:06.349  2719  2719 D BluetoothMapService: stop(),
09-08 14:01:06.350  2719  2719 D BluetoothMapAppObserver: deinitObservers()
,09-08 14:01:06.350  2719  2719 D BluetoothMapAppObserver: removeReceiver()
,09-08 14:01:06.351  1365  1365 D BluetoothMap: Proxy object disconnected
09-08 14:01:06.351  1365  1365 D MapProfile: Bluetooth service disconnected
09-08 14:01:06.351  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:06.351  2719  2719 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:01:06.351  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:06.352  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:06.352  2719  2719 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 14:01:06.352  2719  2771 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 14:01:06.352  2719  2719 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-08 14:01:06.352   875  1921 D DhcpClient: Receive thread stopped
09-08 14:01:06.352  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:06.352  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:06.352  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:01:06.352  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:06.353  2719  2719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 14:01:06.353  2719  2771 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 14:01:06.353  2719  2719 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:01:06.353  2719  2719 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:06.353  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:06.353  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:01:06.353  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:06.354  2719  2719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 14:01:06.354  2719  2719 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 14:01:06.354  2719  2719 D BluetoothMapService: MAP Service closeService in
09-08 14:01:06.355  2719  2719 V BluetoothAdapterState: isTurningOff()=true
,09-08 14:01:06.355  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:06.355  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:06.355  2719  2719 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:06.355  2719  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-08 14:01:06.355  2719  2767 D BluetoothAdapterProperties: Setting state to 15
09-08 14:01:06.355  2719  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 14:01:06.356  2719  2767 I BluetoothAdapterState: Entering BleOnState
09-08 14:01:06.356  1365  1395 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 14:01:06.356  2719  2719 D BluetoothMapService: cleanup()
09-08 14:01:06.356  2719  2719 D BluetoothMapService: MAP Service closeService in
09-08 14:01:06.356   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:06.356  1365  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 14:01:06.357  1365  2121 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 14:01:06.358  1365  1393 D BluetoothMap: onBluetoothStateChange: up=false
09-08 14:01:06.358   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:06.358  2008  2082 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:06.358   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:06.358   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 14:01:06.359  1499  2508 V NativeCrypto: Read error: ssl=0x9b13e800: I/O error during system call, Connection timed out
09-08 14:01:06.359  1365  1395 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:06.359  1365  1385 D BluetoothPan: onBluetoothStateChange on: false
09-08 14:01:06.359  2719  2767 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 14:01:06.360  2719  2767 D BluetoothAdapterProperties: Setting state to 16
09-08 14:01:06.360  2719  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 14:01:06.360  1499  2508 V NativeCrypto: SSL shutdown failed: ssl=0x9b13e800: I/O error during system call, Broken pipe
09-08 14:01:06.360  2719  2767 D BluetoothAdapterProperties: onBleDisable
09-08 14:01:06.360  2719  2767 I BluetoothAdapterState: Entering PendingCommandState
09-08 14:01:06.360  2719  2768 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 14:01:06.362  2719  2771 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:01:06.362  2719  2910 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-08 14:01:06.362  2719  2910 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:06.363   875  1931 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-08 14:01:06.363   875  1911 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-08 14:01:06.364   875  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 14:01:06.364  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:06.364   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:01:06.364   875  1311 E native  : do suspend true
09-08 14:01:06.365   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 14:01:06.365   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-08 14:01:06.371   403   403 E Parcel  : Reading a NULL string not supported here.
09-08 14:01:06.372  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.372  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:01:06.372  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.372  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:06.373   875  1911 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-08 14:01:06.374  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:01:06.374  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:06.374  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:06.376  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.376  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:01:06.377  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.377  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:06.377   875  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 14:01:06.378  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:06.380  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.380  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:06.396  3911  3911 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 14:01:06.403   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:06.405  3911  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:01:06.410  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:06.412   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee8ce7a:true
,09-08 14:01:06.422   875  1931 I ActivityManager: Start proc 3927:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-08 14:01:06.432   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:06.432   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:01:06.434   875  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-08 14:01:06.434   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:01:06.435   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:01:06.435   875  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 14:01:06.438  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.438  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:06.438  3450  3450 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@10fa65e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 14:01:06.441  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.441  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:06.442  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:06.452   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 14:01:06.454  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.454  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:06.454   875  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:01:06.455  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.455  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:06.455  1864  2316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 14:01:06.456  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.456  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:06.457  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.457  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:06.458  3911  3911 D LocalBluetoothProfileManager: Adding local MAP profile
09-08 14:01:06.458  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:06.458  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:06.459  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:06.459  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:06.464  3911  3911 D BluetoothMap: Create BluetoothMap proxy object
,09-08 14:01:06.470  3927  3927 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
09-08 14:01:06.474  3911  3911 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 14:01:06.484  3911  3911 D DockEventReceiver: finishStartingService: stopping service
09-08 14:01:06.484   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-08 14:01:06.485   875  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 14:01:06.496   875  1694 I ActivityManager: Killing 3007:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-08 14:01:06.564  2719  2771 I bt_hci  : shut_down
,09-08 14:01:06.565  2719  2777 D bt_hwcfg: hw_epilog_process
,09-08 14:01:06.567  2719  2777 I bt_vendor: low_power_mode_cb
,09-08 14:01:06.588  2719  2777 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 14:01:06.589  2719  2777 I bt_vendor: epilog_cb
09-08 14:01:06.589  2719  2777 I bt_hci  : epilog_finished_callback
,09-08 14:01:06.594  2719  2771 I bt_hci_h4: hal_close
,09-08 14:01:06.595  2719  2771 I bt_userial_vendor: device fd = 51 close
,09-08 14:01:06.673  3927  3927 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.673  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:01:06.674  3927  3927 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:01:06.674  3927  3927 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:01:06.674  3927  3927 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:01:06.674  3927  3927 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:01:06.674  3927  3927 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at an,droid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.674  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:01:06.678  3927  3927 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:01:06.678  3927  3927 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:01:06.678  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 14:01:06.687  3911  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:01:06.696  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:06.709  1689  1689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:01:06.711  2719  2768 D bt_stack_manager: event_shut_down_stack finished.
,09-08 14:01:06.712  2719  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-08 14:01:06.713  2719  2719 D BtGatt.DebugUtils: handleDebugAction() action=null
09-08 14:01:06.713  2719  2767 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 14:01:06.714  2719  2719 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 14:01:06.714  2719  2719 D BtGatt.GattService: stop()
09-08 14:01:06.714  2719  2719 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 14:01:06.715  1689  1689 D SystemUpdateService: onCreate
,09-08 14:01:06.715  2719  2719 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:01:06.715  2719  2719 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:06.715  2719  2719 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:06.715  2719  2719 V BluetoothAdapterState: isBleTurningOff()=true
09-08 14:01:06.715  2719  2767 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 14:01:06.716  2719  2767 D BluetoothAdapterProperties: Setting state to 10
09-08 14:01:06.716  2719  2767 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 14:01:06.716  2719  2767 I BluetoothAdapterState: Entering OffState
09-08 14:01:06.718   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 14:01:06.719  1689  1689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 14:01:06.736  2719  2719 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-08 14:01:06.736  2719  2719 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-08 14:01:06.736  2719  2719 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 14:01:06.738  2719  2768 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 14:01:06.742  2719  2719 I art     : System.exit called, status: 0
,09-08 14:01:06.742  2719  2719 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 14:01:06.743  1689  1689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 14:01:06.746  1689  2471 I iu.UploadsManager: num queued entries: 0
,09-08 14:01:06.746  1689  2471 I iu.UploadsManager: num updated entries: 0
,09-08 14:01:06.751  3911  3911 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:01:06.763  1689  1689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 14:01:06.765  1689  1689 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 14:01:06.772  1689  3963 I SystemUpdateService: active receiver: enabled
,09-08 14:01:06.776  1689  2471 I iu.SyncManager: NEXT; no task
,09-08 14:01:06.783   875  1931 I ActivityManager: Start proc 3966:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 14:01:06.786  1689  3963 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:01:06.793   875  2041 I ActivityManager: Process com.android.bluetooth (pid 2719) has died
,09-08 14:01:06.794  1689  3963 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 14:01:06.794  1689  3963 I SystemUpdateService: now status is 0 (complete)
,09-08 14:01:06.794  1689  3963 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 14:01:06.794  1689  3963 I SystemUpdateService: file has been verified
09-08 14:01:06.795  1689  3963 I SystemUpdateService: OTA package size = 12249756
,09-08 14:01:06.802  1689  3963 I SystemUpdateService: showing system update notification
,09-08 14:01:06.848  3966  3966 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 14:01:06.852  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:01:06.854  1689  1689 D SystemUpdateService: onDestroy
,09-08 14:01:06.857   875  1931 I ActivityManager: Killing 3450:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 14:01:06.870  3966  3966 D SprintDMHelper: simOperator: 
,09-08 14:01:06.870  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 14:01:06.960   875  1931 I ActivityManager: Start proc 3979:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-08 14:01:06.961   875  1931 I ActivityManager: Killing 3505:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 14:01:06.977  3927  3949 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 14:01:06.996   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ae8ffc9:true
,09-08 14:01:07.142   875  1948 I ActivityManager: Start proc 3995:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 14:01:07.145  3122  3994 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 14:01:07.170  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 14:01:07.218  3995  3995 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 14:01:07.218  3995  3995 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 14:01:07.218  3995  3995 I GAv4    :   adb logcat -s GAv4
,09-08 14:01:07.231  3995  3995 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:01:07.236  3995  3995 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:01:07.273  3995  4012 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 14:01:07.387  3995  3995 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 14:01:07.434  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 14:01:07.443  3995  3995 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3562-3565)
,09-08 14:01:07.443  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:01:07.456  3995  3995 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6513728}
,09-08 14:01:07.457  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 14:01:07.457  3995  3995 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 14:01:07.466  3995  3995 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 14:01:07.467  3995  3995 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 14:01:07.487  3995  3995 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 14:01:07.503  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 14:01:07.503  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 14:01:07.503  3995  3995 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 14:01:07.503  3995  3995 I Adreno  : Build Date                       : 10/20/15
09-08 14:01:07.503  3995  3995 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 14:01:07.503  3995  3995 I Adreno  : Local Branch                     : M14
09-08 14:01:07.503  3995  3995 I Adreno  : Remote Branch                    : 
09-08 14:01:07.503  3995  3995 I Adreno  : Remote Branch                    : 
09-08 14:01:07.503  3995  3995 I Adreno  : Reconstruct Branch               : 
,09-08 14:01:07.572  3995  3995 I NSApplication: Starting up...
,09-08 14:01:07.583  3995  4041 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 14:01:07.618   875   886 I ActivityManager: Start proc 4046:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 14:01:07.620   875   886 I ActivityManager: Killing 1712:android.process.acore/u0a5 (adj 15): empty #17
,09-08 14:01:07.716  4046  4046 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 14:01:07.907   875  2041 I ActivityManager: Killing 3666:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 14:01:08.021   875  1694 I ActivityManager: Start proc 4060:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 14:01:08.056  4060  4060 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 14:01:08.106  4060  4060 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 14:01:08.173   875  1597 I ActivityManager: Killing 3683:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 14:01:11.306   875  1394 D WifiService: setWifiEnabled: true pid=3832, uid=10000
,09-08 14:01:11.306   875  1394 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:01:11.313   875  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 14:01:11.320  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:11.321  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:11.321  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:11.321  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:11.324  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:11.324  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:11.324  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:11.325  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:11.327  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:11.327  3832  3832 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-08 14:01:11.327  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:11.328  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:11.329   875  1311 D WifiConfigStore: loaded 0 passpoint configs
09-08 14:01:11.330   875  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 14:01:11.331   875  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-08 14:01:11.332   875  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 14:01:11.332   875  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 14:01:11.332   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 14:01:11.332   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 14:01:11.347   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 14:01:11.348   875  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=21.50 delta 1000 -> 994
,09-08 14:01:11.349   373   873 D CommandListener: Setting iface cfg
,09-08 14:01:11.349   875  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 14:01:11.352   875  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 14:01:11.352   875  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 14:01:11.362   875  1311 E native  : do suspend true
,09-08 14:01:11.363   875  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 14:01:11.370   875  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 14:01:11.381   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 14:01:11.382   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:01:11.397   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 14:01:11.483   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 14:01:11.489  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 14:01:11.911  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:01:11.951  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-08 14:01:11.952  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 14:01:11.956   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:01:11.970   875  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 14:01:11.970   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 14:01:11.970   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:01:11.998   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:01:12.014   373   873 D CommandListener: Setting iface cfg
,09-08 14:01:12.015   875  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 14:01:12.022   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 14:01:12.067   875  4093 D DhcpClient: Receive thread started
,09-08 14:01:12.143   875  1394 I ActivityManager: Killing 3490:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 14:01:12.157   875  1311 E native  : do suspend false
,09-08 14:01:12.172   875  1919 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 14:01:12.224   875  4093 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172655, domain null
,09-08 14:01:12.224   875  1919 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172655 seconds
,09-08 14:01:12.226   875  1919 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 14:01:12.239   875  4093 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
09-08 14:01:12.239   875  1919 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 14:01:12.241   373   873 D CommandListener: Setting iface cfg
,09-08 14:01:12.245   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 14:01:12.247   875  1919 D DhcpClient: Scheduling renewal in 86399s
,09-08 14:01:12.249   875  1311 E native  : do suspend true
,09-08 14:01:12.266   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-08 14:01:12.269   875  1311 D WifiConfigStore: No blacklist allowed without epno enabled
09-08 14:01:12.272   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 14:01:12.274   875  1313 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 14:01:12.282   875  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 14:01:12.317   875  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 14:01:12.318   875  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 14:01:12.321   875  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 14:01:12.322   875  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 14:01:12.324   875  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 14:01:12.335   875  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 14:01:12.340   875  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-08 14:01:12.340   875  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 14:01:12.340   875  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 14:01:12.341   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:01:12.341   875  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-08 14:01:12.341   875  1313 D ConnectivityService:    accepting network in place of null
,09-08 14:01:12.342   875  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 14:01:12.362   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:12.368   875  4092 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168489, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:01:12.384   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:12.392   875  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 14:01:12.393   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:01:12.401   875  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 14:01:12.406   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-08 14:01:12.415  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:12.416  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:01:12.416  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:12.416  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:01:12.420  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:12.420  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:01:12.421  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:12.421  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:01:12.423  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:12.424  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 14:01:12.424  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:12.424  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-08 14:01:12.430  1689  1689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:01:12.432  1689  1689 D SystemUpdateService: onCreate
09-08 14:01:12.434   875  4091 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-08 14:01:12.438  1689  1689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 14:01:12.459  1689  1689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 14:01:12.462  1689  4103 I SystemUpdateService: active receiver: enabled
,09-08 14:01:12.467  1689  2471 I iu.UploadsManager: num queued entries: 0
,09-08 14:01:12.467  1689  2471 I iu.UploadsManager: num updated entries: 0
09-08 14:01:12.468  1689  2471 I iu.SyncManager: NEXT; no task
,09-08 14:01:12.472  1689  1689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 14:01:12.473  1689  1689 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 14:01:12.474  1689  4103 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:01:12.476  1689  4103 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 14:01:12.477  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:01:12.476  1689  4103 I SystemUpdateService: now status is 0 (complete)
,09-08 14:01:12.485  3966  3966 D SprintDMHelper: simOperator: 
09-08 14:01:12.485  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 14:01:12.487  1689  4107 I MDM     : [174] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 14:01:12.487  1689  4107 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 14:01:12.488  1689  4103 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 14:01:12.488  1689  4103 I SystemUpdateService: file has been verified
09-08 14:01:12.488  1689  4103 I SystemUpdateService: OTA package size = 12249756
,09-08 14:01:12.488  1689  4107 V GoogleAuthProtoRequest: [174] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:01:12.494   875  4091 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:01:12 GMT], X-Android-Received-Millis=[1473336072492], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473336072471]}
,09-08 14:01:12.501   875  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 14:01:12.502   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,09-08 14:01:12.502   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 14:01:12.503   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 14:01:12.510  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:12.513  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:12.526  1689  4103 I SystemUpdateService: showing system update notification
,09-08 14:01:12.527  3775  4112 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:01:12.604  1689  1689 D SystemUpdateService: onDestroy
,09-08 14:01:12.608  3775  4117 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:01:12.612  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 14:01:12.612  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 14:01:12.617  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:12.617  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:12.627  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:01:12.627  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:01:12.627  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:12.627  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:12.667  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:01:12.667  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 14:01:12.668  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:01:12.668  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:12.677  3775  4117 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:01:12.678  3775  4112 E BooksSync: Soft error
09-08 14:01:12.678  3775  4112 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:01:12.678  3775  4112 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:01:12.678  3775  4112 E BooksSync: Sync error
09-08 14:01:12.678  3775  4112 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:01:12.678  3775  4112 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:01:12.678  3775  4112 I BooksSync: Finished books sync
,09-08 14:01:12.683  3122  4113 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 14:01:12.690   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 164052, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:01:12.701  1689  4107 E MDM     : [174] SitrepService.a: Error sending sitrep.
,09-08 14:01:12.718  3763  4111 V KeepSync: Connecting to GoogleApiClient
,09-08 14:01:12.728   875  1947 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:01:12.809  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 14:01:12.809  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 14:01:12.809  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:12.809  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:12.824  1689  4121 V BaseAuthAsyncOperation: access token request failed
,09-08 14:01:12.825  3763  4111 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:01:12.972  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:13.048  1499  2998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 14:01:13.050  1499  2998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 14:01:13.051  1499  2998 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:13.052  1499  2998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:13.163  1499  4123 I VacuumService: Vacuum at: now=1473336073163 tag=VacuumService
,09-08 14:01:13.184  3763  4111 E KeepSync: IOException
09-08 14:01:13.184  3763  4111 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:01:13.184  3763  4111 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:01:13.184  3763  4111 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:01:13.184  3763  4111 E KeepSync: 	... 10 more
,09-08 14:01:13.184  3763  4111 W KeepSync: Sync result 2
,09-08 14:01:13.195   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 163983, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:01:13.324  1499  4124 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-08 14:01:13.329  1499  4124 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-08 14:01:13.381  1499  4124 W Uploader:  no longer exists, so no auth token.
,09-08 14:01:13.391   875  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 14:01:13.431  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:13.461  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 14:01:13.461  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 14:01:13.461  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:13.461  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:13.483  3554  3554 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 14:01:13.483  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-08 14:01:13.483  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-08 14:01:14.615  1499  4124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-08 14:01:14.615  1499  4124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-08 14:01:14.615  1499  4124 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:01:14.615  1499  4124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:14.628  1499  4124 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 14:01:14.628  1499  4124 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 14:01:14.628  1499  4124 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 14:01:15.188  1499  4124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-08 14:01:15.189  1499  4124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-08 14:01:15.189  1499  4124 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:15.189  1499  4124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:15.208  1499  4124 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 14:01:15.208  1499  4124 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-08 14:01:15.208  1499  4124 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-08 14:01:16.313   875  1948 D WifiService: setWifiEnabled: false pid=3832, uid=10000
,09-08 14:01:16.314   875  1948 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:01:16.351  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 14:01:16.355   875  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 14:01:16.356   875  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 14:01:16.356   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 14:01:16.356   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:01:16.376   875  1311 E native  : do suspend true
,09-08 14:01:16.387   875  1919 D DhcpClient: Clearing IP address
09-08 14:01:16.388   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-08 14:01:16.393   373   873 D CommandListener: Setting iface cfg
,09-08 14:01:16.402   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 14:01:16.402   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-08 14:01:16.410   403   403 E Parcel  : Reading a NULL string not supported here.
,09-08 14:01:16.398  1499  4119 V NativeCrypto: Read error: ssl=0x9b12c000: I/O error during system call, Connection timed out
,09-08 14:01:16.414   875  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 14:01:16.416  1499  4119 V NativeCrypto: SSL shutdown failed: ssl=0x9b12c000: I/O error during system call, Broken pipe
09-08 14:01:16.416   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 14:01:16.416   875  1311 E native  : do suspend true
09-08 14:01:16.418   875  4093 D DhcpClient: Receive thread stopped
,09-08 14:01:16.421   875  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 14:01:16.462   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:16.508   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:16.509   875  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 14:01:16.509   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:01:16.511   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-08 14:01:16.513   875   892 D Tethering: MasterInitialState.processMessage what=3
09-08 14:01:16.518  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:16.518  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:16.518  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.518  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:16.519  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:16.519  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:16.519  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.519  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:16.520  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:16.521  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:16.521  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.521  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:16.535  1689  1689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:01:16.541  1689  1689 D SystemUpdateService: onCreate
,09-08 14:01:16.544  1689  1689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 14:01:16.564  1689  1689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 14:01:16.570  1689  4143 I SystemUpdateService: active receiver: enabled
,09-08 14:01:16.573  1689  1689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 14:01:16.574  1689  1689 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 14:01:16.575  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:01:16.580  3966  3966 D SprintDMHelper: simOperator: 
,09-08 14:01:16.580  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 14:01:16.598  1689  2471 I iu.UploadsManager: num queued entries: 0
,09-08 14:01:16.603   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-08 14:01:16.606   875  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 14:01:16.613  1689  4143 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:01:16.615  3122  4148 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 14:01:16.626   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 14:01:16.629  1689  2471 I iu.UploadsManager: num updated entries: 0
,09-08 14:01:16.629   875  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 14:01:16.632  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.632  1689  2471 I iu.SyncManager: NEXT; no task
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:16.632  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:16.633  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:16.633  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:16.636  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:16.637  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:16.637  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.637  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:16.637  1864  2316 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 14:01:16.642  1689  4143 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-08 14:01:16.642  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.642  1689  4143 I SystemUpdateService: now status is 0 (complete)
09-08 14:01:16.642  1689  4143 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 14:01:16.642  1689  4143 I SystemUpdateService: file has been verified
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:16.642  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:16.642  1689  4143 I SystemUpdateService: OTA package size = 12249756
09-08 14:01:16.642  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:16.642  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:16.657  1689  4143 I SystemUpdateService: showing system update notification
,09-08 14:01:16.667  1689  1689 D SystemUpdateService: onDestroy
,09-08 14:01:20.343   875  1313 D ConnectivityService: handlePromptUnvalidated 101
,09-08 14:01:21.360   875   892 I ActivityManager: Start proc 4153:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 14:01:21.509  4153  4153 D AdapterServiceConfig: Adding HeadsetService
09-08 14:01:21.510  4153  4153 D AdapterServiceConfig: Adding A2dpService
09-08 14:01:21.510  4153  4153 D AdapterServiceConfig: Adding HidService
09-08 14:01:21.510  4153  4153 D AdapterServiceConfig: Adding HealthService
09-08 14:01:21.510  4153  4153 D AdapterServiceConfig: Adding PanService
09-08 14:01:21.511  4153  4153 D AdapterServiceConfig: Adding GattService
09-08 14:01:21.511  4153  4153 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 14:01:21.527  4153  4153 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 14:01:21.527   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@338b0c2:true
,09-08 14:01:21.532  4153  4153 I bt_bluedroid: init
,09-08 14:01:21.533  4153  4165 I BluetoothAdapterState: Entering OffState
,09-08 14:01:21.540  4153  4166 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 14:01:21.540  4153  4166 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 14:01:21.540  4153  4166 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 14:01:21.541  4153  4166 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 14:01:21.545  4153  4153 I bt_bluedroid: get_profile_interface socket
,09-08 14:01:21.547  4153  4153 I bt_bluedroid: get_profile_interface sdp
,09-08 14:01:21.550  4153  4169 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:01:21.552  4153  4164 I bt_bluedroid: config_hci_snoop_log
,09-08 14:01:21.553  4153  4169 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:01:21.556   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 14:01:21.565  4153  4165 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 14:01:21.565  4153  4165 D BluetoothAdapterProperties: Setting state to 14
09-08 14:01:21.566  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 14:01:21.570  4153  4165 D BluetoothBondStateMachine: make
,09-08 14:01:21.575  4153  4170 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 14:01:21.582  4153  4165 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:01:21.585  4153  4153 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 14:01:21.593  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:21.595  4153  4153 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 14:01:21.596  4153  4153 D BtGatt.GattService: Received start request. Starting profile...
,09-08 14:01:21.597  4153  4153 D BtGatt.GattService: start()
,09-08 14:01:21.597  4153  4153 I bt_bluedroid: get_profile_interface gatt
09-08 14:01:21.598  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:21.599  4153  4153 D BtGatt.AdvertiseManager: advertise manager created
,09-08 14:01:21.612  4153  4153 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:21.612  4153  4153 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:01:21.612  4153  4153 V BluetoothAdapterState: isBleTurningOn()=true
09-08 14:01:21.613  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:21.613  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 14:01:21.614  4153  4165 I bt_bluedroid: enable
09-08 14:01:21.615  4153  4166 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 14:01:21.616  4153  4166 I bt_hci  : start_up
,09-08 14:01:21.635  4153  4166 I bt_vendor: alloc value 0xb39e8189
,09-08 14:01:21.635  4153  4166 I bt_vendor: init
09-08 14:01:21.635  4153  4166 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 14:01:21.636  4153  4166 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 14:01:21.744  4153  4166 D bt_hci  : start_up starting async portion
,09-08 14:01:21.745  4153  4173 I bt_hci  : event_finish_startup
,09-08 14:01:21.747  4153  4173 I bt_hci_h4: hal_open
09-08 14:01:21.747  4153  4173 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 14:01:21.758  4153  4173 I bt_userial_vendor: device fd = 51 open
,09-08 14:01:21.785  4153  4173 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:01:21.817  4153  4173 D bt_hwcfg: Chipset BCM4354A2
,09-08 14:01:21.817  4153  4173 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 14:01:21.819  4153  4173 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 14:01:22.476  4153  4173 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 14:01:22.477  4153  4173 D bt_hwcfg: Settlement delay -- 100 ms
09-08 14:01:22.478  4153  4173 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 14:01:22.594  4153  4173 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:01:22.596  4153  4173 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 14:01:22.624  4153  4173 I bt_hwcfg: vendor lib fwcfg completed
09-08 14:01:22.624  4153  4173 I bt_vendor: firmware callback
,09-08 14:01:22.624  4153  4173 I bt_hci  : firmware_config_callback
,09-08 14:01:22.638  4153  4177 I bt_btu  : btu_task pending for preload complete event
,09-08 14:01:22.638  4153  4177 I bt_btu_task: Bluetooth chip preload is complete
09-08 14:01:22.638  4153  4177 I bt_btu  : btu_task received preload complete event
,09-08 14:01:22.648  4153  4177 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 14:01:22.649  4153  4177 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-08 14:01:22.649  4153  4177 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 14:01:22.649  4153  4177 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 14:01:22.650  4153  4177 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 14:01:22.650  4153  4177 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 14:01:22.650  4153  4177 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 14:01:22.650  4153  4177 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 14:01:22.651  4153  4177 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 14:01:22.651  4153  4177 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 14:01:22.651  4153  4177 I         : BTE_InitTraceLevels -- TRC_SDP
,09-08 14:01:22.651  4153  4177 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 14:01:22.652  4153  4177 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 14:01:22.652  4153  4177 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 14:01:22.652  4153  4177 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 14:01:22.787  4153  4177 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3965d9d
,09-08 14:01:22.788  4153  4177 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3965d9d 
,09-08 14:01:22.802  4153  4169 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 14:01:22.804  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 14:01:22.805  4153  4169 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:01:22.809  4153  4169 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:01:22.813  4153  4169 D BluetoothAdapterProperties: Scan Mode:20
,09-08 14:01:22.814  4153  4169 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:01:22.814  4153  4169 D bt_hci  : do_postload posting postload work item
09-08 14:01:22.814  4153  4173 I bt_hci  : event_postload
,09-08 14:01:22.815  4153  4173 I bt_vendor: sco_config_cb
,09-08 14:01:22.815  4153  4173 I bt_hci  : sco_config_callback postload finished.
,09-08 14:01:22.817  4153  4169 D bt_bte_conf: Device ID record 1 : primary
09-08 14:01:22.817  4153  4169 D bt_bte_conf:   vendorId            = 000f
,09-08 14:01:22.817  4153  4169 D bt_bte_conf:   vendorIdSource      = 0001
,09-08 14:01:22.817  4153  4169 D bt_bte_conf:   product             = 1200
,09-08 14:01:22.817  4153  4169 D bt_bte_conf:   version             = 1436
,09-08 14:01:22.817  4153  4169 D bt_bte_conf:   clientExecutableURL = 
,09-08 14:01:22.817  4153  4169 D bt_bte_conf:   serviceDescription  = 
09-08 14:01:22.818  4153  4169 D bt_bte_conf:   documentationURL    = 
,09-08 14:01:22.817  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:22.818  4153  4169 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 14:01:22.818  4153  4166 D bt_stack_manager: event_start_up_stack finished
09-08 14:01:22.819  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 14:01:22.819  4153  4165 D BluetoothAdapterProperties: Setting state to 15
09-08 14:01:22.819  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 14:01:22.823  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:22.823  4153  4165 I BluetoothAdapterState: Entering BleOnState
09-08 14:01:22.824  4153  4165 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 14:01:22.824  4153  4165 D BluetoothAdapterProperties: Setting state to 11
,09-08 14:01:22.824  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 14:01:22.825  4153  4173 I bt_vendor: low_power_mode_cb
09-08 14:01:22.825  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:22.831  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
09-08 14:01:22.833  4153  4153 D HeadsetService: Received start request. Starting profile...
09-08 14:01:22.835  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:22.837  4153  4153 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 14:01:22.838  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:22.838  4153  4153 D HeadsetStateMachine: make
09-08 14:01:22.840  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:22.841  4153  4165 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:01:22.849  4153  4153 D HeadsetStateMachine: max_hf_connections = 1
09-08 14:01:22.849  4153  4153 I bt_bluedroid: get_profile_interface handsfree
09-08 14:01:22.849  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 14:01:22.849  4153  4169 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-08 14:01:22.853  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:22.854  4153  4153 D A2dpService: Received start request. Starting profile...
,09-08 14:01:22.855  4153  4153 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 14:01:22.855  4153  4153 I bt_bluedroid: get_profile_interface avrcp
,09-08 14:01:22.861  4153  4153 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 14:01:22.861  4153  4153 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 14:01:22.861  4153  4153 D A2dpStateMachine: make
,09-08 14:01:22.863  4153  4153 I bt_bluedroid: get_profile_interface a2dp
,09-08 14:01:22.863  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 14:01:22.864  4153  4186 D A2dpStateMachine: Enter Disconnected: -2
,09-08 14:01:22.865  4153  4153 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 14:01:22.866  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:22.867  3911  3911 D BluetoothInputDevice: Proxy object connected
09-08 14:01:22.867  4153  4153 D HidService: Received start request. Starting profile...
09-08 14:01:22.867  4153  4153 I bt_bluedroid: get_profile_interface hidhost
09-08 14:01:22.868  4153  4153 D HidService: setHidService(): set to: null
09-08 14:01:22.868  4153  4169 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39473e5
09-08 14:01:22.868  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 14:01:22.868  4153  4153 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 14:01:22.869  3911  3911 D HidProfile: Bluetooth service connected
09-08 14:01:22.869  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:22.870  4153  4153 D HealthService: Received start request. Starting profile...
,09-08 14:01:22.871  4153  4153 I bt_bluedroid: get_profile_interface health
,09-08 14:01:22.872  4153  4153 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 14:01:22.873  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:22.874  3911  3911 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 14:01:22.874  4153  4153 D PanService: Received start request. Starting profile...
,09-08 14:01:22.875  4153  4153 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 14:01:22.875  4153  4153 I bt_bluedroid: get_profile_interface pan
,09-08 14:01:22.875  4153  4169 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 14:01:22.876  3911  3911 D PanProfile: Bluetooth service connected
09-08 14:01:22.877  4153  4153 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
09-08 14:01:22.879  3911  3911 D BluetoothMap: Proxy object connected
,09-08 14:01:22.879  4153  4153 D BluetoothMapService: Received start request. Starting profile...
09-08 14:01:22.879  4153  4153 D BluetoothMapService: start()
,09-08 14:01:22.879  3911  3911 D MapProfile: Bluetooth service connected
09-08 14:01:22.879  3911  3911 D BluetoothMap: getConnectedDevices()
09-08 14:01:22.880  3911  3911 D BluetoothMap: Bluetooth is Not enabled
09-08 14:01:22.881  4153  4153 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-08 14:01:22.882  4153  4153 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 14:01:22.882  4153  4153 D BluetoothMapAppObserver: createReceiver()
,09-08 14:01:22.883  4153  4153 D BluetoothMapAppObserver: initObservers()
09-08 14:01:22.883  4153  4153 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 14:01:22.892  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:22.894  4153  4184 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 14:01:22.895  4153  4153 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:22.895  4153  4153 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:22.895  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:01:22.895  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isTurningOn()=true
,09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:22.897  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:22.898  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:22.899  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 14:01:22.899  4153  4165 D BluetoothAdapterProperties: ScanMode =  20
09-08 14:01:22.899  4153  4165 D BluetoothAdapterProperties: State =  11
09-08 14:01:22.900  4153  4165 D BluetoothAdapterProperties: Setting state to 12
09-08 14:01:22.900  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 14:01:22.901  1365  2121 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 14:01:22.901  4153  4169 D BluetoothAdapterProperties: Scan Mode:21
09-08 14:01:22.901  4153  4169 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:01:22.902  4153  4165 I BluetoothAdapterState: Entering OnState
09-08 14:01:22.903  1365  1365 D BluetoothInputDevice: Proxy object connected
09-08 14:01:22.903   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:01:22.903  1365  1365 D HidProfile: Bluetooth service connected
09-08 14:01:22.904  1365  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:01:22.907  1365  1365 D BluetoothA2dp: Proxy object connected
09-08 14:01:22.907  1365  2121 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:22.907  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:22.910  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:22.910  4153  4153 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 14:01:22.911  4153  4153 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 14:01:22.912  1365  1395 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 14:01:22.913  4153  4153 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:01:22.914  1365  1365 D BluetoothMap: Proxy object connected
09-08 14:01:22.914   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 14:01:22.914  1365  1365 D MapProfile: Bluetooth service connected
09-08 14:01:22.914  1365  1365 D BluetoothMap: getConnectedDevices()
,09-08 14:01:22.914  2008  2082 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:22.914  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:22.915   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:01:22.915  3911  3923 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 14:01:22.915   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:01:22.916  4153  4153 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:01:22.916   875   875 D BluetoothA2dp: Proxy object connected
09-08 14:01:22.916  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:22.917  3911  3921 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 14:01:22.918  4153  4153 D ObexServerSockets: Succeed to create listening sockets 
09-08 14:01:22.918  4153  4153 D ObexServerSockets0: startAccept()
09-08 14:01:22.918  4153  4153 D ObexServerSockets0: prepareForNewConnect()
,09-08 14:01:22.918  3911  3923 D BluetoothPan: onBluetoothStateChange on: true
,09-08 14:01:22.919  3911  3921 D BluetoothMap: onBluetoothStateChange: up=true
09-08 14:01:22.919  1365  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:22.920  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:22.920  1365  2121 D BluetoothPan: onBluetoothStateChange on: true
09-08 14:01:22.921  4153  4153 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 14:01:22.921  4153  4153 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 14:01:22.922  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:22.922  4153  4192 D ObexServerSockets0: Accepting socket connection...
09-08 14:01:22.922  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 14:01:22.923  1365  1365 D PanProfile: Bluetooth service connected
09-08 14:01:22.924  4153  4193 D ObexServerSockets0: Accepting socket connection...
09-08 14:01:22.924  4153  4153 D BluetoothMapService: onReceive
09-08 14:01:22.924   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 14:01:22.925  4153  4153 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:01:22.925  4153  4153 D BluetoothMapService: STATE_ON
09-08 14:01:22.925  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:22.926  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:22.927  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:22.929  3911  3911 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-08 14:01:22.933  3911  3911 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 14:01:22.938  3911  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:01:22.940  3911  3911 D BluetoothA2dp: Proxy object connected
,09-08 14:01:22.948  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:22.955  3911  3911 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:01:22.956  4153  4153 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 14:01:22.956  4153  4153 D ObexServerSockets0: prepareForNewConnect()
,09-08 14:01:22.959  1365  1365 D BluetoothPbap: Proxy object connected
,09-08 14:01:22.959  1365  1365 D PbapServerProfile: Bluetooth service connected
09-08 14:01:22.959  3911  3911 D BluetoothPbap: Proxy object connected
09-08 14:01:22.960  3911  3911 D PbapServerProfile: Bluetooth service connected
,09-08 14:01:22.967  4153  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:01:22.982  4153  4202 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:01:22.988  4153  4202 I BtOppRfcommListener: Accept thread started.
,09-08 14:01:23.005  2008  2289 D BluetoothHeadset: Proxy object connected
,09-08 14:01:23.005   875   875 D BluetoothHeadset: Proxy object connected
09-08 14:01:23.006  1365  1395 D BluetoothHeadset: Proxy object connected
,09-08 14:01:23.006   875   875 D BluetoothHeadset: Proxy object connected
09-08 14:01:23.006  1365  1365 D HeadsetProfile: Bluetooth service connected
09-08 14:01:23.006   875   875 D BluetoothHeadset: Proxy object connected
,09-08 14:01:23.014   875   892 D BluetoothHeadset: Proxy object connected
,09-08 14:01:23.015  2008  2027 D BluetoothHeadset: Proxy object connected
09-08 14:01:23.015   875   892 D BluetoothHeadset: Proxy object connected
,09-08 14:01:23.019  1365  1385 D BluetoothHeadset: Proxy object connected
,09-08 14:01:23.019  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-08 14:01:23.036  3911  3923 D BluetoothHeadset: Proxy object connected
,09-08 14:01:23.039  3911  3911 D HeadsetProfile: Bluetooth service connected
,09-08 14:01:26.334  4153  4165 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 14:01:26.334  4153  4165 D BluetoothAdapterProperties: Setting state to 13
09-08 14:01:26.335  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 14:01:26.336  4153  4165 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 14:01:26.341  4153  4165 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:01:26.364  4153  4153 D BluetoothMapService: onReceive
09-08 14:01:26.365  4153  4153 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 14:01:26.365  4153  4153 D BluetoothMapService: STATE_TURNING_OFF
,09-08 14:01:26.365  4153  4153 D BluetoothMapService: MAP Service closeService in
,09-08 14:01:26.365  4153  4153 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 14:01:26.365  4153  4153 D ObexServerSockets0: shutdown(block = true)
09-08 14:01:26.366  4153  4153 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 14:01:26.366  4153  4192 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 14:01:26.366  4153  4153 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 14:01:26.366  4153  4179 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 14:01:26.367  4153  4193 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 14:01:26.368  4153  4153 I BtOppRfcommListener: stopping Accept Thread
,09-08 14:01:26.369  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:26.369  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:26.369  4153  4202 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-08 14:01:26.369  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:26.370  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:26.370  4153  4202 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 14:01:26.370  4153  4169 D BluetoothAdapterProperties: Scan Mode:20
,09-08 14:01:26.371  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 14:01:26.374  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:26.374  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:26.375  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:26.375  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:26.376  4153  4153 D HeadsetService: Received stop request...Stopping profile...
09-08 14:01:26.376  3911  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 14:01:26.378  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:26.378  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:26.379  3832  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 14:01:26.379  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:26.381  2008  2021 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:26.381  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:26.382   875   875 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:26.382  4153  4153 D A2dpService: Received stop request...Stopping profile...
09-08 14:01:26.382  1365  1385 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:26.383   875   875 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:26.383  3911  3921 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:26.383   875   875 D BluetoothHeadset: Proxy object disconnected
09-08 14:01:26.383  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:26.383  4153  4186 D A2dpStateMachine: Exit Disconnected: -1
,09-08 14:01:26.385  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:26.387   875   875 D BluetoothA2dp: Proxy object disconnected
09-08 14:01:26.387  4153  4153 D HidService: Received stop request...Stopping profile...
09-08 14:01:26.387  4153  4153 D HidService: Stopping Bluetooth HidService
,09-08 14:01:26.389  4153  4153 D HealthService: Received stop request...Stopping profile...
,09-08 14:01:26.390  4153  4153 D PanService: Received stop request...Stopping profile...
,09-08 14:01:26.392  4153  4153 D BluetoothMapService: Received stop request...Stopping profile...
09-08 14:01:26.392  1365  1365 D HeadsetProfile: Bluetooth service disconnected
09-08 14:01:26.392  4153  4153 D BluetoothMapService: stop()
09-08 14:01:26.392  1365  1365 D BluetoothA2dp: Proxy object disconnected
09-08 14:01:26.392  1365  1365 D BluetoothInputDevice: Proxy object disconnected
,09-08 14:01:26.392  1365  1365 D HidProfile: Bluetooth service disconnected
09-08 14:01:26.392  1365  1365 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 14:01:26.392  1365  1365 D PanProfile: Bluetooth service disconnected
09-08 14:01:26.392  4153  4153 D BluetoothMapAppObserver: deinitObservers()
09-08 14:01:26.392  4153  4153 D BluetoothMapAppObserver: removeReceiver()
09-08 14:01:26.393  3911  3911 D DockEventReceiver: finishStartingService: stopping service
09-08 14:01:26.393  1365  1365 D BluetoothMap: Proxy object disconnected
,09-08 14:01:26.393  3911  3911 D HeadsetProfile: Bluetooth service disconnected
,09-08 14:01:26.393  1365  1365 D MapProfile: Bluetooth service disconnected
09-08 14:01:26.394  3911  3911 D BluetoothA2dp: Proxy object disconnected
09-08 14:01:26.394  4153  4153 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:26.394  4153  4153 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:01:26.394  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:01:26.394  3911  3911 D BluetoothInputDevice: Proxy object disconnected
,09-08 14:01:26.394  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:26.394  3911  3911 D HidProfile: Bluetooth service disconnected
09-08 14:01:26.394  3911  3911 D BluetoothPan: BluetoothPAN Proxy object disconnected,
09-08 14:01:26.394  3911  3911 D PanProfile: Bluetooth service disconnected
09-08 14:01:26.395  3911  3911 D BluetoothMap: Proxy object disconnected
09-08 14:01:26.395  3911  3911 D MapProfile: Bluetooth service disconnected
09-08 14:01:26.396  4153  4153 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 14:01:26.396  4153  4153 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 14:01:26.397  4153  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 14:01:26.397  4153  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 14:01:26.397  4153  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:26.397  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 14:01:26.397  4153  4169 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 14:01:26.400  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:26.401  4153  4153 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:26.401  4153  4153 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:26.401  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:26.401  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:26.402  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 14:01:26.402  4153  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 14:01:26.403  4153  4153 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:26.403  4153  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:26.403  4153  4153 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:26.403  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:26.403  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:26.403  4153  4177 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 14:01:26.403  4153  4177 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:01:26.403  4153  4177 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 14:01:26.403  4153  4177 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 14:01:26.403  4153  4153 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 14:01:26.403  4153  4169 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 14:01:26.404  4153  4153 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 14:01:26.404  4153  4153 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:26.404  4153  4153 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:26.404  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:26.404  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:26.404  4153  4153 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 14:01:26.404  4153  4169 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 14:01:26.404  4153  4153 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 14:01:26.405  4153  4153 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:26.405  4153  4153 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:26.405  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:26.405  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:26.406  4153  4153 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 14:01:26.406  4153  4153 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 14:01:26.407  4153  4153 D BluetoothMapService: MAP Service closeService in
09-08 14:01:26.407  4153  4153 V BluetoothAdapterState: isTurningOff()=true
09-08 14:01:26.407  4153  4153 V BluetoothAdapterState: isTurningOn()=false
09-08 14:01:26.407  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:26.407  4153  4153 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:26.407  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 14:01:26.408  4153  4153 D BluetoothMapService: cleanup()
09-08 14:01:26.408  4153  4165 D BluetoothAdapterProperties: Setting state to 15
09-08 14:01:26.408  4153  4153 D BluetoothMapService: MAP Service closeService in
,09-08 14:01:26.408  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 14:01:26.408  4153  4165 I BluetoothAdapterState: Entering BleOnState
09-08 14:01:26.409  3911  3911 D BluetoothPbap: Proxy object disconnected
09-08 14:01:26.409  3911  3911 D PbapServerProfile: Bluetooth service disconnected
09-08 14:01:26.409  1365  2121 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 14:01:26.409   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:26.410  1365  1395 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:01:26.410  1365  1365 D BluetoothPbap: Proxy object disconnected
,09-08 14:01:26.410  1365  1365 D PbapServerProfile: Bluetooth service disconnected
09-08 14:01:26.411  1365  1385 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 14:01:26.415  1365  2121 D BluetoothMap: onBluetoothStateChange: up=false
09-08 14:01:26.415   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:26.415  2008  2082 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:26.415   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:26.416  3911  3923 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 14:01:26.416   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 14:01:26.416  3911  3921 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 14:01:26.417  3911  3921 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 14:01:26.418  3911  3923 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 14:01:26.419  3911  3921 D BluetoothPan: onBluetoothStateChange on: false
09-08 14:01:26.420  3911  3923 D BluetoothMap: onBluetoothStateChange: up=false
09-08 14:01:26.421  1365  1393 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 14:01:26.422  1365  1395 D BluetoothPan: onBluetoothStateChange on: false
09-08 14:01:26.423  4153  4165 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 14:01:26.423  4153  4165 D BluetoothAdapterProperties: Setting state to 16
,09-08 14:01:26.423  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-08 14:01:26.424  4153  4165 D BluetoothAdapterProperties: onBleDisable
09-08 14:01:26.425  4153  4165 I BluetoothAdapterState: Entering PendingCommandState
09-08 14:01:26.425  4153  4166 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 14:01:26.425  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:26.426  4153  4177 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 14:01:26.426  4153  4177 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 14:01:26.427  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:26.427  3911  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:01:26.427  4153  4169 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:01:26.428  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:26.430  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:26.431  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:26.432  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:26.435  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:26.439  3911  3911 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:01:26.633  4153  4169 I bt_hci  : shut_down
,09-08 14:01:26.651  4153  4173 I bt_vendor: low_power_mode_cb
,09-08 14:01:26.656  4153  4173 D bt_hwcfg: hw_epilog_process
,09-08 14:01:26.667  4153  4173 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 14:01:26.668  4153  4173 I bt_vendor: epilog_cb
09-08 14:01:26.668  4153  4173 I bt_hci  : epilog_finished_callback
,09-08 14:01:26.675  4153  4169 I bt_hci_h4: hal_close
,09-08 14:01:26.677  4153  4169 I bt_userial_vendor: device fd = 51 close
,09-08 14:01:26.802  4153  4166 D bt_stack_manager: event_shut_down_stack finished.
,09-08 14:01:26.804  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 14:01:26.814  4153  4153 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 14:01:26.814  4153  4165 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-08 14:01:26.815  4153  4153 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 14:01:26.816  4153  4153 D BtGatt.GattService: stop()
09-08 14:01:26.816  4153  4153 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 14:01:26.822  4153  4153 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:01:26.823  4153  4153 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:01:26.823  4153  4153 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:26.824  4153  4153 V BluetoothAdapterState: isBleTurningOff()=true
09-08 14:01:26.824  4153  4165 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 14:01:26.825  4153  4165 D BluetoothAdapterProperties: Setting state to 10
09-08 14:01:26.825  4153  4165 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 14:01:26.827  4153  4165 I BluetoothAdapterState: Entering OffState
09-08 14:01:26.828   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 14:01:26.852  4153  4153 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 14:01:26.852  4153  4153 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 14:01:26.853  4153  4166 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 14:01:26.859  4153  4166 D bt_stack_manager: event_clean_up_stack finished.
,09-08 14:01:26.860  4153  4153 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 14:01:26.865  4153  4153 I art     : System.exit called, status: 0
,09-08 14:01:26.866  4153  4153 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 14:01:26.917   875  2044 I ActivityManager: Process com.android.bluetooth (pid 4153) has died
,09-08 14:01:31.330  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:01:31.331  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:31.337  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:01:31.337  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7cb0a2 removed from the list
09-08 14:01:31.337  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:01:31.338  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:01:31.339  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:31.346  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 14:01:31.346  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c5fcf0 added. We now have 4 listener(s)
09-08 14:01:31.347  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:01:31.349  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:01:31.350  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c5fcf0 removed from the list
,09-08 14:01:31.350  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:01:31.350  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:01:31.350  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:31.352  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:01:31.353  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe0269 added. We now have 4 listener(s)
,09-08 14:01:31.353  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:01:36.365  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:36.415   875   892 I ActivityManager: Start proc 4215:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 14:01:36.571  4215  4215 D AdapterServiceConfig: Adding HeadsetService
,09-08 14:01:36.571  4215  4215 D AdapterServiceConfig: Adding A2dpService
09-08 14:01:36.571  4215  4215 D AdapterServiceConfig: Adding HidService
09-08 14:01:36.571  4215  4215 D AdapterServiceConfig: Adding HealthService
09-08 14:01:36.572  4215  4215 D AdapterServiceConfig: Adding PanService
,09-08 14:01:36.572  4215  4215 D AdapterServiceConfig: Adding GattService
,09-08 14:01:36.573  4215  4215 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 14:01:36.588   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ec01f7:true
,09-08 14:01:36.589  4215  4215 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 14:01:36.594  4215  4215 I bt_bluedroid: init
,09-08 14:01:36.595  4215  4227 I BluetoothAdapterState: Entering OffState
,09-08 14:01:36.601  4215  4228 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 14:01:36.601  4215  4228 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 14:01:36.602  4215  4228 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 14:01:36.602  4215  4228 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 14:01:36.605  4215  4215 I bt_bluedroid: get_profile_interface socket
,09-08 14:01:36.607  4215  4215 I bt_bluedroid: get_profile_interface sdp
,09-08 14:01:36.608  4215  4231 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:01:36.610  4215  4231 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:01:36.612  4215  4226 I bt_bluedroid: config_hci_snoop_log
,09-08 14:01:36.616   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 14:01:36.630  4215  4227 D BluetoothAdapterState: Current state: OFF, message: 0
09-08 14:01:36.630  4215  4227 D BluetoothAdapterProperties: Setting state to 14
09-08 14:01:36.631  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 14:01:36.636  4215  4227 D BluetoothBondStateMachine: make
,09-08 14:01:36.642  4215  4232 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 14:01:36.647  4215  4227 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:01:36.649  4215  4215 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 14:01:36.656  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:36.658  4215  4215 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 14:01:36.660  4215  4215 D BtGatt.GattService: Received start request. Starting profile...
,09-08 14:01:36.660  4215  4215 D BtGatt.GattService: start()
09-08 14:01:36.661  4215  4215 I bt_bluedroid: get_profile_interface gatt
,09-08 14:01:36.663  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:36.664  4215  4215 D BtGatt.AdvertiseManager: advertise manager created
,09-08 14:01:36.680  4215  4215 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:36.680  4215  4215 V BluetoothAdapterState: isTurningOn()=false
,09-08 14:01:36.681  4215  4215 V BluetoothAdapterState: isBleTurningOn()=true
09-08 14:01:36.681  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:36.682  4215  4227 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 14:01:36.683  4215  4227 I bt_bluedroid: enable
09-08 14:01:36.683  4215  4228 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 14:01:36.684  4215  4228 I bt_hci  : start_up
,09-08 14:01:36.704  4215  4228 I bt_vendor: alloc value 0xb39e8189
,09-08 14:01:36.705  4215  4228 I bt_vendor: init
09-08 14:01:36.705  4215  4228 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 14:01:36.705  4215  4228 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 14:01:36.813  4215  4228 D bt_hci  : start_up starting async portion
,09-08 14:01:36.814  4215  4235 I bt_hci  : event_finish_startup
09-08 14:01:36.814  4215  4235 I bt_hci_h4: hal_open
,09-08 14:01:36.814  4215  4235 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 14:01:36.824  4215  4235 I bt_userial_vendor: device fd = 51 open
,09-08 14:01:36.856  4215  4235 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:01:36.888  4215  4235 D bt_hwcfg: Chipset BCM4354A2
,09-08 14:01:36.888  4215  4235 D bt_hwcfg: Target name = [BCM4354A2]
09-08 14:01:36.889  4215  4235 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 14:01:37.760  4215  4235 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 14:01:37.762  4215  4235 D bt_hwcfg: Settlement delay -- 100 ms
09-08 14:01:37.762  4215  4235 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 14:01:37.880  4215  4235 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 14:01:37.881  4215  4235 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 14:01:37.911  4215  4235 I bt_hwcfg: vendor lib fwcfg completed
,09-08 14:01:37.911  4215  4235 I bt_vendor: firmware callback
,09-08 14:01:37.911  4215  4235 I bt_hci  : firmware_config_callback
,09-08 14:01:37.923  4215  4237 I bt_btu  : btu_task pending for preload complete event
,09-08 14:01:37.924  4215  4237 I bt_btu_task: Bluetooth chip preload is complete
09-08 14:01:37.924  4215  4237 I bt_btu  : btu_task received preload complete event
,09-08 14:01:37.937  4215  4237 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 14:01:37.937  4215  4237 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 14:01:37.937  4215  4237 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 14:01:37.938  4215  4237 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 14:01:37.938  4215  4237 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 14:01:37.938  4215  4237 I         : BTE_InitTraceLevels -- TRC_A2D
,09-08 14:01:37.939  4215  4237 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 14:01:37.940  4215  4237 I         : BTE_InitTraceLevels -- TRC_BTM
,09-08 14:01:37.940  4215  4237 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 14:01:37.941  4215  4237 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 14:01:37.942  4215  4237 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 14:01:37.942  4215  4237 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 14:01:37.944  4215  4237 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 14:01:37.945  4215  4237 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 14:01:37.946  4215  4237 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 14:01:38.094  4215  4237 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3965d9d
,09-08 14:01:38.095  4215  4237 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3965d9d 
,09-08 14:01:38.105  4215  4231 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-08 14:01:38.108  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 14:01:38.109  4215  4231 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 14:01:38.114  4215  4231 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 14:01:38.118  4215  4231 D BluetoothAdapterProperties: Scan Mode:20
09-08 14:01:38.119  4215  4231 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 14:01:38.119  4215  4231 D bt_hci  : do_postload posting postload work item
09-08 14:01:38.119  4215  4235 I bt_hci  : event_postload
09-08 14:01:38.120  4215  4235 I bt_vendor: sco_config_cb
,09-08 14:01:38.120  4215  4235 I bt_hci  : sco_config_callback postload finished.
09-08 14:01:38.123  4215  4231 D bt_bte_conf: Device ID record 1 : primary
09-08 14:01:38.123  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:38.124  4215  4231 D bt_bte_conf:   vendorId            = 000f
,09-08 14:01:38.124  4215  4231 D bt_bte_conf:   vendorIdSource      = 0001
09-08 14:01:38.124  4215  4231 D bt_bte_conf:   product             = 1200
09-08 14:01:38.125  4215  4231 D bt_bte_conf:   version             = 1436
09-08 14:01:38.125  4215  4231 D bt_bte_conf:   clientExecutableURL = 
09-08 14:01:38.125  4215  4231 D bt_bte_conf:   serviceDescription  = 
,09-08 14:01:38.125  4215  4231 D bt_bte_conf:   documentationURL    = 
09-08 14:01:38.127  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:01:38.126  4215  4231 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 14:01:38.127  4215  4228 D bt_stack_manager: event_start_up_stack finished
,09-08 14:01:38.128  4215  4235 I bt_vendor: low_power_mode_cb
09-08 14:01:38.130  4215  4227 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 14:01:38.130  4215  4227 D BluetoothAdapterProperties: Setting state to 15
09-08 14:01:38.131  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 14:01:38.132  4215  4227 I BluetoothAdapterState: Entering BleOnState
,09-08 14:01:38.137  4215  4227 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 14:01:38.137  4215  4227 D BluetoothAdapterProperties: Setting state to 11
,09-08 14:01:38.138  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-08 14:01:38.143  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:38.145  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:38.147  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:38.148  4215  4215 D HeadsetService: Received start request. Starting profile...
,09-08 14:01:38.153  4215  4215 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 14:01:38.153  4215  4215 D HeadsetStateMachine: make
,09-08 14:01:38.161  4215  4227 I BluetoothAdapterState: Entering PendingCommandState
,09-08 14:01:38.161  4215  4215 D HeadsetStateMachine: max_hf_connections = 1
09-08 14:01:38.161  4215  4215 I bt_bluedroid: get_profile_interface handsfree
09-08 14:01:38.162  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 14:01:38.162  4215  4231 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 14:01:38.166  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:38.167  4215  4215 D A2dpService: Received start request. Starting profile...
,09-08 14:01:38.167  4215  4215 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 14:01:38.168  4215  4215 I bt_bluedroid: get_profile_interface avrcp
,09-08 14:01:38.168  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:38.175  4215  4215 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 14:01:38.175  4215  4215 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 14:01:38.175  4215  4215 D A2dpStateMachine: make
,09-08 14:01:38.177  4215  4215 I bt_bluedroid: get_profile_interface a2dp
,09-08 14:01:38.177  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 14:01:38.179  4215  4246 D A2dpStateMachine: Enter Disconnected: -2
,09-08 14:01:38.180  4215  4215 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 14:01:38.180  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:38.183  4215  4215 D HidService: Received start request. Starting profile...
,09-08 14:01:38.183  4215  4215 I bt_bluedroid: get_profile_interface hidhost
,09-08 14:01:38.183  4215  4231 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39473e5
09-08 14:01:38.183  4215  4231 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 14:01:38.183  4215  4215 D HidService: setHidService(): set to: null
,09-08 14:01:38.184  4215  4215 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 14:01:38.185  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:38.185  4215  4215 D HealthService: Received start request. Starting profile...
,09-08 14:01:38.187  4215  4215 I bt_bluedroid: get_profile_interface health
,09-08 14:01:38.187  4215  4215 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 14:01:38.188  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:38.189  4215  4215 D PanService: Received start request. Starting profile...
,09-08 14:01:38.189  4215  4215 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 14:01:38.189  4215  4215 I bt_bluedroid: get_profile_interface pan
,09-08 14:01:38.190  4215  4231 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 14:01:38.193  4215  4215 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:01:38.194  4215  4215 D BluetoothMapService: Received start request. Starting profile...
09-08 14:01:38.194  4215  4215 D BluetoothMapService: start()
,09-08 14:01:38.196  4215  4215 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 14:01:38.197  4215  4215 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 14:01:38.197  4215  4215 D BluetoothMapAppObserver: createReceiver()
,09-08 14:01:38.198  4215  4215 D BluetoothMapAppObserver: initObservers()
,09-08 14:01:38.198  4215  4215 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 14:01:38.204  4215  4215 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:01:38.204  4215  4215 V BluetoothAdapterState: isTurningOn()=true
,09-08 14:01:38.204  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:38.204  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:38.206  4215  4244 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 14:01:38.207  4215  4215 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:38.207  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:38.207  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isTurningOff()=false
09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:38.208  4215  4215 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:01:38.209  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:38.209  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 14:01:38.209  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:38.209  4215  4215 V BluetoothAdapterState: isTurningOff()=false
,09-08 14:01:38.209  4215  4215 V BluetoothAdapterState: isTurningOn()=true
09-08 14:01:38.209  4215  4215 V BluetoothAdapterState: isBleTurningOn()=false
09-08 14:01:38.209  4215  4215 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 14:01:38.209  4215  4227 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 14:01:38.209  4215  4227 D BluetoothAdapterProperties: ScanMode =  20
09-08 14:01:38.209  4215  4227 D BluetoothAdapterProperties: State =  11
09-08 14:01:38.210  4215  4227 D BluetoothAdapterProperties: Setting state to 12
,09-08 14:01:38.210  4215  4227 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 14:01:38.210  4215  4227 I BluetoothAdapterState: Entering OnState
,09-08 14:01:38.210  1365  1395 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 14:01:38.211  4215  4231 D BluetoothAdapterProperties: Scan Mode:21
09-08 14:01:38.211  4215  4231 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 14:01:38.212   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 14:01:38.212  1365  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:01:38.213  1365  1365 D BluetoothInputDevice: Proxy object connected
09-08 14:01:38.213  1365  1365 D HidProfile: Bluetooth service connected
,09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:38.215  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:38.215  1365  1395 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 14:01:38.216  1365  1365 D BluetoothA2dp: Proxy object connected
,09-08 14:01:38.217  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:38.217  1365  2121 D BluetoothMap: onBluetoothStateChange: up=true
09-08 14:01:38.219   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:01:38.219  2008  2289 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:01:38.219   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 14:01:38.219  3911  3921 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 14:01:38.220  1365  1365 D BluetoothMap: Proxy object connected
09-08 14:01:38.220  1365  1365 D MapProfile: Bluetooth service connected
,09-08 14:01:38.220  1365  1365 D BluetoothMap: getConnectedDevices()
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:38.220  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 14:01:38.223   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:01:38.223   875   875 D BluetoothA2dp: Proxy object connected
09-08 14:01:38.223  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:38.223  3911  3921 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 14:01:38.224  4215  4215 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 14:01:38.225  4215  4215 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 14:01:38.225  3911  3923 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 14:01:38.227  4215  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:01:38.229  3911  3921 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 14:01:38.229  4215  4215 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:01:38.230  3911  3911 D BluetoothInputDevice: Proxy object connected
09-08 14:01:38.230  3911  3911 D HidProfile: Bluetooth service connected
,09-08 14:01:38.230  3911  3923 D BluetoothPan: onBluetoothStateChange on: true
09-08 14:01:38.230  4215  4215 D ObexServerSockets: Succeed to create listening sockets 
,09-08 14:01:38.230  4215  4215 D ObexServerSockets0: startAccept()
09-08 14:01:38.230  4215  4215 D ObexServerSockets0: prepareForNewConnect()
,09-08 14:01:38.232  3911  3921 D BluetoothMap: onBluetoothStateChange: up=true
09-08 14:01:38.233  4215  4215 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 14:01:38.233  4215  4215 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 14:01:38.234  4215  4254 D ObexServerSockets0: Accepting socket connection...
09-08 14:01:38.234  4215  4255 D ObexServerSockets0: Accepting socket connection...
,09-08 14:01:38.235  1365  1385 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 14:01:38.236  1365  1395 D BluetoothPan: onBluetoothStateChange on: true
,09-08 14:01:38.237  1365  1365 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 14:01:38.237  1365  1365 D PanProfile: Bluetooth service connected
09-08 14:01:38.238   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 14:01:38.239  4215  4215 D BluetoothMapService: onReceive
,09-08 14:01:38.239  4215  4215 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 14:01:38.239  4215  4215 D BluetoothMapService: STATE_ON
09-08 14:01:38.240  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:38.241  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:38.241  3911  3911 D BluetoothA2dp: Proxy object connected
,09-08 14:01:38.243  3911  3911 D BluetoothMap: Proxy object connected
,09-08 14:01:38.243  3911  3911 D MapProfile: Bluetooth service connected
09-08 14:01:38.243  3911  3911 D BluetoothMap: getConnectedDevices()
,09-08 14:01:38.245  3911  3911 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 14:01:38.245  3911  3911 D PanProfile: Bluetooth service connected
,09-08 14:01:38.249  3911  3911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 14:01:38.255  1499  1499 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 14:01:38.256  3911  3911 D DockEventReceiver: finishStartingService: stopping service
,09-08 14:01:38.260  3911  3911 D BluetoothPbap: Proxy object connected
,09-08 14:01:38.260  3911  3911 D PbapServerProfile: Bluetooth service connected
09-08 14:01:38.260  4215  4215 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 14:01:38.260  4215  4215 D ObexServerSockets0: prepareForNewConnect()
,09-08 14:01:38.262  4215  4257 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 14:01:38.265  1365  1365 D BluetoothPbap: Proxy object connected
09-08 14:01:38.265  1365  1365 D PbapServerProfile: Bluetooth service connected
,09-08 14:01:38.282  4215  4263 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:01:38.284  4215  4263 I BtOppRfcommListener: Accept thread started.
,09-08 14:01:38.314  2008  2027 D BluetoothHeadset: Proxy object connected
09-08 14:01:38.314   875   875 D BluetoothHeadset: Proxy object connected
09-08 14:01:38.314  1365  1395 D BluetoothHeadset: Proxy object connected
,09-08 14:01:38.315   875   875 D BluetoothHeadset: Proxy object connected
09-08 14:01:38.315  1365  1365 D HeadsetProfile: Bluetooth service connected
09-08 14:01:38.315  3911  3923 D BluetoothHeadset: Proxy object connected
,09-08 14:01:38.315   875   875 D BluetoothHeadset: Proxy object connected
09-08 14:01:38.315  3911  3911 D HeadsetProfile: Bluetooth service connected
,09-08 14:01:38.318   875   892 D BluetoothHeadset: Proxy object connected
,09-08 14:01:38.320  2008  2021 D BluetoothHeadset: Proxy object connected
,09-08 14:01:38.320   875   892 D BluetoothHeadset: Proxy object connected
,09-08 14:01:38.325  3911  4253 D BluetoothHeadset: Proxy object connected
,09-08 14:01:38.325  3911  3911 D HeadsetProfile: Bluetooth service connected
,09-08 14:01:38.336  1365  1393 D BluetoothHeadset: Proxy object connected
,09-08 14:01:38.336  1365  1365 D HeadsetProfile: Bluetooth service connected
,09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:41.386  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:41.393  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:41.395  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:01:41.395  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe0269 removed from the list
09-08 14:01:41.396  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:01:41.396  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:41.396  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:41.400  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 14:01:41.400  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@71934ee added. We now have 4 listener(s)
09-08 14:01:41.401  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 14:01:41.405   875  1947 D WifiService: setWifiEnabled: false pid=3832, uid=10000
,09-08 14:01:41.405   875  1947 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:01:42.687  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:42.699  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:42.703  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:42.755  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 14:01:42.755  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 14:01:42.756  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:42.756  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:42.809  3554  3554 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-08 14:01:42.810  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 14:01:42.810  3554  3554 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-08 14:01:46.419  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:01:46.421   875  2036 D WifiService: setWifiEnabled: true pid=3832, uid=10000
09-08 14:01:46.421   875  2036 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 14:01:46.433   875  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:46.455  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:46.462   875  1311 D WifiConfigStore: loaded 0 passpoint configs
,09-08 14:01:46.463   875  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 14:01:46.464   875  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 14:01:46.464  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 14:01:46.465   875  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 14:01:46.465   875  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 14:01:46.465   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 14:01:46.465   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 14:01:46.475  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 14:01:46.484  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 14:01:46.489   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 14:01:46.490   875  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 14:01:46.491   373   873 D CommandListener: Setting iface cfg
,09-08 14:01:46.541   875  1308 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-08 14:01:46.542   875  1308 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 14:01:46.553   875  1311 E native  : do suspend true
,09-08 14:01:46.554   875  1308 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 14:01:46.567   875  1308 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 14:01:46.587   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:01:47.856   875  1311 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 14:01:47.955   875  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=13.19 delta 1000 -> 994
,09-08 14:01:47.957   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 14:01:47.957   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:01:47.968   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 14:01:48.013   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 14:01:48.014  1459  1459 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 14:01:48.444  1459  1459 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 14:01:48.510  1459  1459 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 14:01:48.513  1459  1459 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 14:01:48.522   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 14:01:48.534   875  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 14:01:48.535   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:01:48.535   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 14:01:48.555   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 14:01:48.566   373   873 D CommandListener: Setting iface cfg
,09-08 14:01:48.567   875  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 14:01:48.580   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 14:01:48.612   875  4273 D DhcpClient: Receive thread started
,09-08 14:01:48.709   875  1311 E native  : do suspend false
,09-08 14:01:48.737   875  1919 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 14:01:48.753   875  4273 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172763, domain null
,09-08 14:01:48.754   875  1919 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172763 seconds
,09-08 14:01:48.758   875  1919 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 14:01:48.772   875  4273 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 14:01:48.774   875  1919 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 14:01:48.780   373   873 D CommandListener: Setting iface cfg
,09-08 14:01:48.791   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 14:01:48.793   875  1919 D DhcpClient: Scheduling renewal in 86399s
,09-08 14:01:48.794   875  1311 E native  : do suspend true
,09-08 14:01:48.813   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 14:01:48.814   875  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 14:01:48.815   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 14:01:48.817   875  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 14:01:48.817   875  1313 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 14:01:48.886   875  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 14:01:48.886   875  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-08 14:01:48.888   875  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 14:01:48.889   875  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-08 14:01:48.890   875  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 14:01:48.908   875  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 14:01:48.921   875  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 14:01:48.922   875  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-08 14:01:48.922   875  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-08 14:01:48.922   875  1313 D ConnectivityService:    accepting network in place of null
09-08 14:01:48.923   875  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 14:01:48.925   875  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 14:01:48.925   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 14:01:48.946   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205067, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:01:48.975   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:49.018   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 14:01:49.023   875  4271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:803::200e
,09-08 14:01:49.024   875  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-08 14:01:49.024   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 14:01:49.029   875   892 D Tethering: MasterInitialState.processMessage what=3
09-08 14:01:49.041   875  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:49.051  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:01:49.053  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:49.060  3832  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:01:49.063  3832  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:01:49.067  1689  1689 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 14:01:49.076  1689  1689 D SystemUpdateService: onCreate
,09-08 14:01:49.093  1689  1689 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 14:01:49.111  1689  4282 I SystemUpdateService: active receiver: enabled
,09-08 14:01:49.114  1689  1689 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 14:01:49.120   875  4271 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 12:01:49 GMT], X-Android-Received-Millis=[1473336109119], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473336109090]}
,09-08 14:01:49.121   875  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 14:01:49.121   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 14:01:49.121   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 14:01:49.126   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 14:01:49.129  1689  2471 I iu.UploadsManager: num queued entries: 0
,09-08 14:01:49.131  1689  1689 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 14:01:49.132  1689  1689 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 14:01:49.134  3966  3966 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 14:01:49.139  3966  3966 D SprintDMHelper: simOperator: 
,09-08 14:01:49.140  3966  3966 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 14:01:49.140  1689  4284 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 14:01:49.141  1689  4284 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 14:01:49.142  1689  4284 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:01:49.146  1689  4282 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 14:01:49.129  1689  2471 I iu.UploadsManager: num updated entries: 0
,09-08 14:01:49.160  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:49.171  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:01:49.188  1689  4282 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 14:01:49.188  1689  4282 I SystemUpdateService: now status is 0 (complete)
09-08 14:01:49.188  1689  4282 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 14:01:49.188  1689  4282 I SystemUpdateService: file has been verified
09-08 14:01:49.188  1689  4282 I SystemUpdateService: OTA package size = 12249756
,09-08 14:01:49.190  3775  4289 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:01:49.195  1689  2471 I iu.SyncManager: NEXT; no task
,09-08 14:01:49.235  1689  4282 I SystemUpdateService: showing system update notification
,09-08 14:01:49.283  1689  1689 D SystemUpdateService: onDestroy
,09-08 14:01:49.294  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 14:01:49.294  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 14:01:49.294  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:01:49.294  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:49.316  3122  4288 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 14:01:49.319  3775  4295 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:01:49.367  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:01:49.367  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:01:49.367  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:01:49.367  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:49.409  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:01:49.409  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:01:49.409  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:49.409  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:49.422  1689  4284 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-08 14:01:49.425  3763  4290 V KeepSync: Connecting to GoogleApiClient
09-08 14:01:49.425   875  1597 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:01:49.448  3775  4295 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:01:49.449  3775  4289 E BooksSync: Soft error
09-08 14:01:49.449  3775  4289 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:01:49.449  3775  4289 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:01:49.449  3775  4289 E BooksSync: Sync error
09-08 14:01:49.449  3775  4289 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:01:49.449  3775  4289 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:01:49.451  3775  4289 I BooksSync: Finished books sync
,09-08 14:01:49.467   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 201725, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:01:49.523  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 14:01:49.523  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 14:01:49.523  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:01:49.523  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:49.551  1689  4297 V BaseAuthAsyncOperation: access token request failed
,09-08 14:01:49.552  3763  4290 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:01:49.596  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 14:01:49.596  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 14:01:49.596  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:01:49.596  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:01:49.610  3763  4290 E KeepSync: IOException
09-08 14:01:49.610  3763  4290 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:01:49.610  3763  4290 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:01:49.610  3763  4290 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:01:49.610  3763  4290 E KeepSync: 	... 10 more
,09-08 14:01:49.610  3763  4290 W KeepSync: Sync result 2
,09-08 14:01:49.620   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 202133, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:01:50.025   875  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:01:51.447  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:01:51.455  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:01:51.456  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:01:51.457  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@71934ee removed from the list
,09-08 14:01:51.457  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 14:01:51.457  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:01:51.458  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:01:51.471  3832  4298 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 14:01:51.471  3832  4298 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 14:01:54.479  3832  4298 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 14:01:54.481  3832  4298 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:01:54.482  3832  4299 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-08 14:01:54.482  3832  4299 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:01:54.482  3832  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:01:54.483  3832  4299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:01:54.484  3832  4298 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:01:54.486  3832  4299 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:01:54.487  3832  4298 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 14:01:54.489  3832  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: OutgoingSocketThread/Sender)
09-08 14:01:54.491  3832  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Sender)
,09-08 14:01:54.491  3832  4299 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 14:01:54.493  3832  4304 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: IncomingSocketThread/Receiver)
09-08 14:01:54.494  3832  4304 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: IncomingSocketThread/Receiver)
09-08 14:01:54.494  3832  4304 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:01:54.494  3832  4304 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 14:01:54.496  3832  4303 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Receiver)
09-08 14:01:54.497  3832  4303 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: OutgoingSocketThread/Receiver)
09-08 14:01:54.497  3832  4303 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:01:54.497  3832  4303 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 14:01:56.765  1897  1957 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-08 14:01:56.766  1897  1957 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 14:01:56.803  1499  1499 I ConfigService: onCreate
,09-08 14:01:56.929   875  1313 D ConnectivityService: handlePromptUnvalidated 102
,09-08 14:01:57.477  3832  3880 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 14:01:57.479  3832  3880 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 14:01:57.487  3832  3880 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b1563aa Bundle[{}]
09-08 14:01:57.487  3832  3880 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 14:01:57.487  3832  3880 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 14:01:57.488  3832  3880 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 14:01:57.488  3832  3880 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 14:01:57.489  3832  3880 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 14:01:57.489  3832  3880 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 14:01:57.494  3832  3880 I System.out: Running OutgoingSocketThread
,09-08 14:01:57.497  3832  4306 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-08 14:01:57.497  3832  4306 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 14:02:00.507  3832  4308 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 14:02:00.507  3832  4308 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 14:02:00.508  3832  4306 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-08 14:02:00.508  3832  4308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:02:00.508  3832  4306 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-08 14:02:00.509  3832  4308 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:02:00.509  3832  4306 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:02:00.513  3832  4310 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Sender)
09-08 14:02:00.513  3832  4308 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 14:02:00.513  3832  4306 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 14:02:00.515  3832  4306 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-08 14:02:00.518  3832  4312 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Sender)
,09-08 14:02:00.521  3832  4311 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: IncomingSocketThread/Receiver)
,09-08 14:02:00.522  3832  4313 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: OutgoingSocketThread/Receiver)
09-08 14:02:00.523  3832  4313 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: OutgoingSocketThread/Receiver)
09-08 14:02:00.523  3832  4313 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 14:02:00.523  3832  4311 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: IncomingSocketThread/Receiver)
,09-08 14:02:00.524  3832  4313 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-08 14:02:00.524  3832  4311 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 14:02:00.524  3832  4311 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 14:02:01.873  1499  1499 I ConfigService: onDestroy
,09-08 14:02:03.509  3832  3880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,09-08 14:02:03.512  3832  3880 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-08 14:02:03.512  3832  3880 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,09-08 14:02:03.518  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 14:02:03.518  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f03d8f added. We now have 3 listener(s)
09-08 14:02:03.520  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:02:03.520  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 14:02:03.520  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:02:03.520  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:02:03.520  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a5f81c added. We now have 4 listener(s)
09-08 14:02:03.520  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:02:03.522  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:02:03.528  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:02:03.538  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:02:03.545  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:02:03.545  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:02:03.546  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:02:03.547  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:02:03.547  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 14:02:03.547  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:02:03.547  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:03.548  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:02:03.547  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:02:03.549  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:02:03.549  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f03d8f removed from the list
09-08 14:02:03.549  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:03.550  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a5f81c removed from the list
09-08 14:02:03.552  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:02:03.552  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:02:03.552  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:03.553  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:03.553  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:02:03.562  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:02:03.562  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:02:03.562  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:03.562  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a5f81c not in the list
,09-08 14:02:03.563  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:03.563  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:03.565  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:02:03.565  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:02:03.566  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:02:03.566  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a5f81c not in the list
09-08 14:02:03.566  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:02:03.566  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:03.567  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:03.567  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f03d8f not in the list
09-08 14:02:03.569  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:02:03.569  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7b1fa added. We now have 3 listener(s)
,09-08 14:02:03.574  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 14:02:03.575  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:02:03.575  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:02:03.575  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:02:03.576  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93d23ab added. We now have 4 listener(s)
,09-08 14:02:03.576  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:02:03.578  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:02:03.585  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:02:03.598  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:02:03.604  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 14:02:03.605  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:02:03.606  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:02:03.606  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 14:02:03.606  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 14:02:03.606  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:02:03.607  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 14:02:03.611  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:02:03.616  3832  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 14:02:03.616  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 14:02:03.617  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:02:03.630  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:02:03.632  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 14:02:03.633  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:02:03.644  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 14:02:03.644  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 14:02:03.644  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:02:03.646  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:02:03.653  4215  4225 D BtGatt.GattService: registerClient() - UUID=d2a33b72-2106-4b51-bc8c-90793a9e8b86
,09-08 14:02:03.655  4215  4231 D BtGatt.GattService: onClientRegistered() - UUID=d2a33b72-2106-4b51-bc8c-90793a9e8b86, clientIf=5
,09-08 14:02:03.657  3832  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 14:02:03.659  4215  4251 D BtGatt.GattService: start scan with filters
,09-08 14:02:03.667  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:02:03.667  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:02:03.668  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:02:03.668  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 14:02:03.668  4215  4234 D BtGatt.ScanManager: handling starting scan
,09-08 14:02:03.672  4215  4234 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf62b9e
,09-08 14:02:03.678  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:02:03.679  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 14:02:03.679  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:02:03.686  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:02:03.688  4215  4231 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 14:02:03.689  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:03.690  4215  4234 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:02:03.697  3832  3880 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 14:02:03.697  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:02:03.697  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:02:03.698  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:03.698  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:02:03.698  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:02:03.698  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:02:03.699  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 14:02:03.699  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 14:02:03.699  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:02:03.700  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 14:02:03.702  3832  3880 D BluetoothAdapter: STATE_ON
09-08 14:02:03.704  4215  4251 D BtGatt.GattService: stopScan() - queue size =1
09-08 14:02:03.706  4215  4252 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 14:02:03.706  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:02:03.707  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 14:02:03.707  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 14:02:03.707  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 14:02:03.707  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 14:02:03.708  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:02:03.708  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:02:03.708  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:02:03.709  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:02:03.709  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:02:03.710  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:02:03.710  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:02:03.711  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 14:02:03.711  4215  4231 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 14:02:03.711  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:02:03.712  4215  4234 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:02:03.712  4215  4234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 14:02:03.729  4215  4231 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 14:02:03.729  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:03.740  4215  4231 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 14:02:03.740  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:03.757  4215  4231 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 14:02:03.757  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:03.757  4215  4234 D BtGatt.ScanManager: stopping BLe Batch
,09-08 14:02:03.770  4215  4231 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:02:03.770  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:02:03.771  4215  4234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:02:03.790  4215  4231 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 14:02:03.790  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:04.212  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:02:04.212  3832  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:02:04.213  3832  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:02:06.712  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:02:06.713  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:02:06.713  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:02:06.714  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:02:06.715  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:06.715  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:02:06.715  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:02:06.716  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7b1fa removed from the list
09-08 14:02:06.716  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:06.716  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93d23ab removed from the list
,09-08 14:02:06.717  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:02:06.717  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:06.719  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:06.719  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:02:06.722  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:02:06.723  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:02:06.723  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:06.723  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93d23ab not in the list
,09-08 14:02:06.724  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:06.724  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:02:06.727  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:02:06.727  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:02:06.728  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:06.728  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93d23ab not in the list
09-08 14:02:06.728  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:02:06.729  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:06.729  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:02:06.729  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7b1fa not in the list
,09-08 14:02:06.732  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:02:06.733  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acf2eb4 added. We now have 3 listener(s)
,09-08 14:02:06.735  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:02:06.735  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 14:02:06.735  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:02:06.735  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:02:06.735  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da9eadd added. We now have 4 listener(s)
09-08 14:02:06.735  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:02:06.736  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:02:06.739  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:02:06.746  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:02:06.748  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:02:06.749  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:02:06.749  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:02:06.751  3832  3880 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-08 14:02:06.751  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 14:02:06.753  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 14:02:06.754  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,09-08 14:02:06.753  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:02:06.754  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 14:02:06.754  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:02:06.755  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 14:02:06.756  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 14:02:06.756  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 14:02:06.756  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 14:02:06.756  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 14:02:06.756  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:02:06.756  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:02:06.761  3832  4314 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 14:02:06.764  3832  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 14:02:06.764  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 14:02:06.765  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:02:06.766  3832  3832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 14:02:06.768  3832  4314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 14:02:06.774  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:02:06.775  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 14:02:06.775  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:02:06.777  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-08 14:02:06.778  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:02:06.778  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-08 14:02:06.780  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-08 14:02:06.780  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 14:02:06.780  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 14:02:06.781  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:02:06.784  4215  4251 D BtGatt.GattService: registerClient() - UUID=d9fe9d35-a80f-433f-ad8b-f8f10592e424
,09-08 14:02:06.785  4215  4231 D BtGatt.GattService: onClientRegistered() - UUID=d9fe9d35-a80f-433f-ad8b-f8f10592e424, clientIf=5
,09-08 14:02:06.785  3832  3843 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 14:02:06.788  4215  4233 D BtGatt.AdvertiseManager: message : 0
,09-08 14:02:06.792  4215  4233 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 14:02:06.810  4215  4231 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 14:02:06.824  4215  4231 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 14:02:06.825  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 14:02:06.825  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:02:06.828  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:02:06.830  3832  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 14:02:06.831  3832  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 14:02:06.831  3832  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 14:02:06.831  3832  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 14:02:06.832  3832  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 14:02:06.832  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 14:02:06.832  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 14:02:06.838  3832  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 14:02:06.838  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 14:02:07.340  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-08 14:02:07.340  3832  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 14:02:07.340  3832  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:02:09.833  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:02:09.834  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-08 14:02:09.835  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:02:09.835  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 14:02:09.835  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 14:02:09.835  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 14:02:09.836  3832  4314 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-08 14:02:09.836  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 14:02:09.836  3832  4314 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 14:02:09.837  3832  3880 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 14:02:09.837  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 14:02:09.837  3832  3832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 14:02:09.838  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:02:09.837  3832  4314 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 14:02:09.838  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 14:02:09.838  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:02:09.839  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 14:02:09.841  3832  3880 D BluetoothAdapter: STATE_ON
09-08 14:02:09.841  3832  3880 D BluetoothLeScanner: could not find callback wrapper
09-08 14:02:09.842  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 14:02:09.842  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 14:02:09.846  4215  4233 D BtGatt.AdvertiseManager: message : 1
,09-08 14:02:09.847  4215  4233 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 14:02:09.854  4215  4231 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-08 14:02:09.855  4215  4231 D BtGatt.GattService: Client app is not null!
,09-08 14:02:09.856  4215  4252 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 14:02:09.856  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 14:02:09.856  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-08 14:02:09.856  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-08 14:02:09.857  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 14:02:09.857  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 14:02:09.859  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:02:09.859  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:02:09.859  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 14:02:09.860  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 14:02:09.862  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:02:09.862  3832  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 14:02:09.862  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:09.862  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:02:09.862  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:02:09.862  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:02:09.862  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acf2eb4 removed from the list
,09-08 14:02:09.863  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:09.863  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 14:02:09.863  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da9eadd removed from the list
09-08 14:02:09.863  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:02:09.863  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:02:09.863  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:09.863  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:02:09.863  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:09.864  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:02:09.865  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:02:09.865  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:09.865  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da9eadd not in the list
09-08 14:02:09.865  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:09.865  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:09.866  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:02:09.866  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:02:09.866  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:09.866  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da9eadd not in the list
09-08 14:02:09.866  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:02:09.866  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:02:09.866  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:09.866  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@acf2eb4 not in the list
09-08 14:02:09.867  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:02:09.867  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d32b59e added. We now have 3 listener(s)
09-08 14:02:09.869  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:02:09.869  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 14:02:09.869  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:02:09.870  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:02:09.870  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@821a87f added. We now have 4 listener(s)
09-08 14:02:09.870  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:02:09.870  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:02:09.873  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:02:09.878  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:02:09.881  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:02:09.881  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 14:02:09.881  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:02:09.881  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 14:02:09.881  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 14:02:09.881  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 14:02:09.881  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 14:02:09.883  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:02:09.885  3832  3880 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 14:02:09.885  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 14:02:09.887  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 14:02:09.889  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 14:02:09.890  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 14:02:09.890  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 14:02:09.894  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 14:02:09.894  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 14:02:09.894  3832  3880 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 14:02:09.895  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:02:09.897  4215  4225 D BtGatt.GattService: registerClient() - UUID=23d2673b-a9dd-44b4-aec8-74eed8eb2abc
,09-08 14:02:09.898  4215  4231 D BtGatt.GattService: onClientRegistered() - UUID=23d2673b-a9dd-44b4-aec8-74eed8eb2abc, clientIf=5
09-08 14:02:09.898  3832  3843 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 14:02:09.899  4215  4252 D BtGatt.GattService: start scan with filters
,09-08 14:02:09.903  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 14:02:09.903  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 14:02:09.903  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 14:02:09.903  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 14:02:09.903  4215  4234 D BtGatt.ScanManager: handling starting scan
,09-08 14:02:09.906  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 14:02:09.906  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 14:02:09.906  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 14:02:09.908  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 14:02:09.914  4215  4231 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 14:02:09.914  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:09.915  4215  4234 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 14:02:09.929  4215  4231 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 14:02:09.929  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:02:09.929  4215  4234 D BtGatt.ScanManager: Starting BLE batch scan
09-08 14:02:09.930  4215  4234 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 14:02:09.955  4215  4231 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 14:02:09.956  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:09.973  4215  4231 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 14:02:09.973  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:10.364  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:02:10.407  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 14:02:10.407  3832  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 14:02:10.407  3832  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 14:02:11.478  4215  4215 D BtGatt.ScanManager: awakened up at time 227600
,09-08 14:02:11.481  4215  4234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:02:11.522  4215  4231 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
,09-08 14:02:11.522  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:02:11.522  4215  4231 D BtGatt.GattService: current time is 227644387308
09-08 14:02:11.523  4215  4231 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -94, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -77, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -117, 56, -16, 66, -20, 124, 1, -128, -36, 16, 0, 0, 0, 71, -122, -77, 84, 69, -12, 1, -128, -80, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -117, 56, -16, 66, -20, 124, 1, -128, -36, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96, 0, 35, 97, 126, -92, 22, -56, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -75, 112, 8, 38, 113, -28, 1, -128, -113, 2, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -63, 108, -6, 2, 2, -29, 23, 62, -13, 112, 113, 0]
,09-08 14:02:11.524  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 14:02:11.525  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 14:02:11.525  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 14:02:11.526  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 14:02:11.526  4215  4231 D BtGatt.GattService: ScanRecord : []
09-08 14:02:11.526  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 14:02:11.526  4215  4231 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 1, 124, -7, 14, 52, -118, -96]
09-08 14:02:11.527  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 14:02:11.527  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -63, 108, -6, 2, 2, -29, 23, 62, -13, 112, 113]
,09-08 14:02:11.532  3832  3832 V org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addOrUpdateDiscoveredPeer: New peer, [<no peer name> 7C:F9:0E:34:8A:A0 1], added - the peer count is 1
,09-08 14:02:11.534  3832  3832 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 7C:F9:0E:34:8A:A0 1], Bluetooth address: 7C:F9:0E:34:8A:A0, device name: '', device address: ''
,09-08 14:02:12.919  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 14:02:12.920  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:02:12.920  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 14:02:12.920  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:12.921  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 14:02:12.921  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 14:02:12.922  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 14:02:12.923  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 14:02:12.923  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 14:02:12.925  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 14:02:12.926  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 14:02:12.929  3832  3880 D BluetoothAdapter: STATE_ON
,09-08 14:02:12.931  4215  4226 D BtGatt.GattService: stopScan() - queue size =1
,09-08 14:02:12.934  4215  4225 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 14:02:12.935  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 14:02:12.936  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 14:02:12.936  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 14:02:12.936  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 14:02:12.937  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 14:02:12.940  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:02:12.940  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 14:02:12.942  3832  3880 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 14:02:12.942  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 14:02:12.942  4215  4215 D BtGatt.ScanManager: awakened up at time 229064
09-08 14:02:12.943  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:02:12.943  3832  3880 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
,09-08 14:02:12.946  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:02:12.947  3832  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 14:02:12.947  3832  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 14:02:12.948  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:02:12.949  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:02:12.949  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:02:12.949  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:02:12.949  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d32b59e removed from the list
,09-08 14:02:12.949  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:12.950  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@821a87f removed from the list
09-08 14:02:12.950  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:02:12.950  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:02:12.951  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:12.951  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:02:12.955  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:02:12.955  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:02:12.955  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:12.955  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@821a87f not in the list
09-08 14:02:12.955  4215  4231 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 14:02:12.955  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:12.955  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:12.955  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 14:02:12.956  4215  4234 D BtGatt.ScanManager: stopping BLe Batch
,09-08 14:02:12.957  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 14:02:12.957  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:02:12.957  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:12.957  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@821a87f not in the list
09-08 14:02:12.957  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:02:12.957  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:02:12.957  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:12.957  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d32b59e not in the list
09-08 14:02:12.958  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 14:02:12.958  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5432911 added. We now have 3 listener(s)
09-08 14:02:12.960  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 14:02:12.960  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 14:02:12.960  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 14:02:12.960  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 14:02:12.960  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@841da76 added. We now have 4 listener(s)
09-08 14:02:12.960  3832  3880 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 14:02:12.961  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 14:02:12.967  4215  4231 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 14:02:12.968  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:02:12.968  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 14:02:12.968  4215  4234 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 14:02:12.975  3832  3880 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 14:02:12.978  3832  3880 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 14:02:12.978  3832  3880 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 14:02:12.978  3832  3880 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 14:02:12.979  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 14:02:12.979  3832  3880 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 14:02:12.979  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 14:02:12.979  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:12.979  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 14:02:12.979  3832  3880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 14:02:12.979  3832  3880 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5432911 removed from the list
09-08 14:02:12.979  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:02:12.979  3832  3880 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@841da76 removed from the list
09-08 14:02:12.981  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:02:12.982  4215  4231 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-08 14:02:12.982  4215  4231 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 14:02:12.983  4215  4231 D BtGatt.GattService: current time is 229104889551
,09-08 14:02:12.983  4215  4231 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -88, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 14:02:12.983  4215  4231 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 14:02:12.985  3832  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 14:02:12.985  3832  3880 D io.jxcore.node.ConnectivityMonitor: stop
09-08 14:02:12.985  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:12.986  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 14:02:12.986  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:12.987  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 14:02:12.987  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:02:12.987  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 14:02:12.987  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@841da76 not in the list
09-08 14:02:12.987  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:12.988  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 14:02:12.989  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 14:02:12.989  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 14:02:12.989  3832  3880 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 14:02:12.989  3832  3880 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@841da76 not in the list
,09-08 14:02:12.989  3832  3880 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 14:02:12.989  3832  3880 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 14:02:12.989  3832  3880 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 14:02:12.990  3832  3880 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5432911 not in the list
,09-08 14:02:12.991  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 14:02:12.991  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 14:02:12.991  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 14:02:12.991  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 14:02:12.991  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 14:02:12.991  3832  3880 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 14:02:13.448  3832  3832 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 14:02:13.875   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:02:15.006  3832  4316 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
,09-08 14:02:17.004  3832  3880 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 462
,09-08 14:02:17.004  3832  3880 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 462, name: My test thread name)
,09-08 14:02:17.010  3832  4317 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,09-08 14:02:17.011  3832  4317 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: My test thread name)
09-08 14:02:17.011  3832  4317 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 14:02:17.016  3832  3880 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 14:02:17.024  3832  4318 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: My test thread name)
,09-08 14:02:17.025  3832  4318 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 467, thread name: My test thread name): Test exception.
,09-08 14:02:17.026  3832  4318 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 14:02:17.034  3832  3880 I jxcore-log: Total number of executed tests:  82
09-08 14:02:17.034  3832  3880 I jxcore-log: 
,09-08 14:02:17.035  3832  3880 I jxcore-log: Number of passed tests:  82
09-08 14:02:17.035  3832  3880 I jxcore-log: 
09-08 14:02:17.036  3832  3880 I jxcore-log: Number of failed tests:  0
09-08 14:02:17.036  3832  3880 I jxcore-log: 
09-08 14:02:17.036  3832  3880 I jxcore-log: Number of ignored tests:  0
09-08 14:02:17.036  3832  3880 I jxcore-log: 
09-08 14:02:17.037  3832  3880 I jxcore-log: Total duration:  101450
09-08 14:02:17.037  3832  3880 I jxcore-log: 
,09-08 14:02:17.046  3832  3880 I jxcore-log: Unit Test app is loaded
09-08 14:02:17.046  3832  3880 I jxcore-log: 
,09-08 14:02:17.065  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.065  3832  3880 I jxcore-log: 
,09-08 14:02:17.070  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.070  3832  3880 I jxcore-log: 
,09-08 14:02:17.072  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.072  3832  3880 I jxcore-log: 
,09-08 14:02:17.073  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.073  3832  3880 I jxcore-log: 
09-08 14:02:17.074  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 14:02:17.074  3832  3880 I jxcore-log: 
09-08 14:02:17.076  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:02:17.076  3832  3880 I jxcore-log: 
09-08 14:02:17.077  3832  3832 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 14:02:17.079  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.079  3832  3880 I jxcore-log: 
,09-08 14:02:17.082  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.082  3832  3880 I jxcore-log: 
,09-08 14:02:17.083  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 14:02:17.083  3832  3880 I jxcore-log: 
09-08 14:02:17.084  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:02:17.084  3832  3880 I jxcore-log: 
09-08 14:02:17.085  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:02:17.085  3832  3880 I jxcore-log: 
,09-08 14:02:17.086  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.086  3832  3880 I jxcore-log: 
09-08 14:02:17.086  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.086  3832  3880 I jxcore-log: 
09-08 14:02:17.087  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.087  3832  3880 I jxcore-log: 
09-08 14:02:17.088  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.088  3832  3880 I jxcore-log: 
,09-08 14:02:17.089  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.089  3832  3880 I jxcore-log: 
09-08 14:02:17.090  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.090  3832  3880 I jxcore-log: 
,09-08 14:02:17.091  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.091  3832  3880 I jxcore-log: 
09-08 14:02:17.092  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.092  3832  3880 I jxcore-log: 
,09-08 14:02:17.093  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.093  3832  3880 I jxcore-log: 
,09-08 14:02:17.094  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.094  3832  3880 I jxcore-log: 
,09-08 14:02:17.095  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.095  3832  3880 I jxcore-log: 
09-08 14:02:17.095  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.095  3832  3880 I jxcore-log: 
09-08 14:02:17.096  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.096  3832  3880 I jxcore-log: 
,09-08 14:02:17.097  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.097  3832  3880 I jxcore-log: 
09-08 14:02:17.098  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.098  3832  3880 I jxcore-log: 
09-08 14:02:17.099  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.099  3832  3880 I jxcore-log: 
,09-08 14:02:17.099  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.099  3832  3880 I jxcore-log: 
09-08 14:02:17.100  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.100  3832  3880 I jxcore-log: 
09-08 14:02:17.101  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.101  3832  3880 I jxcore-log: 
,09-08 14:02:17.102  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.102  3832  3880 I jxcore-log: 
09-08 14:02:17.103  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.103  3832  3880 I jxcore-log: 
,09-08 14:02:17.103  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.103  3832  3880 I jxcore-log: 
09-08 14:02:17.104  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.104  3832  3880 I jxcore-log: 
09-08 14:02:17.104  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.104  3832  3880 I jxcore-log: 
09-08 14:02:17.105  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.105  3832  3880 I jxcore-log: 
09-08 14:02:17.105  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.105  3832  3880 I jxcore-log: 
09-08 14:02:17.106  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.106  3832  3880 I jxcore-log: 
09-08 14:02:17.106  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.106  3832  3880 I jxcore-log: 
09-08 14:02:17.107  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.107  3832  3880 I jxcore-log: 
09-08 14:02:17.107  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 14:02:17.107  3832  3880 I jxcore-log: 
09-08 14:02:17.108  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.108  3832  3880 I jxcore-log: 
09-08 14:02:17.108  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 14:02:17.108  3832  3880 I jxcore-log: 
09-08 14:02:17.109  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.109  3832  3880 I jxcore-log: 
09-08 14:02:17.109  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.109  3832  3880 I jxcore-log: 
,09-08 14:02:17.110  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.110  3832  3880 I jxcore-log: 
09-08 14:02:17.110  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.110  3832  3880 I jxcore-log: 
09-08 14:02:17.111  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.111  3832  3880 I jxcore-log: 
,09-08 14:02:17.111  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:02:17.111  3832  3880 I jxcore-log: 
09-08 14:02:17.112  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.112  3832  3880 I jxcore-log: 
09-08 14:02:17.112  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 14:02:17.112  3832  3880 I jxcore-log: 
09-08 14:02:17.113  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.113  3832  3880 I jxcore-log: 
09-08 14:02:17.113  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:02:17.113  3832  3880 I jxcore-log: 
,09-08 14:02:17.114  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 14:02:17.114  3832  3880 I jxcore-log: 
09-08 14:02:17.115  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state
09-08 14:02:17.115  3832  3880 I jxcore-log: 
09-08 14:02:17.116  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 14:02:17.116  3832  3880 I jxcore-log: 
09-08 14:02:17.116  3832  3880 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 14:02:17.116  3832  3880 I jxcore-log: 
,09-08 14:02:17.119  3832  3880 I jxcore-log: My device name is: motorola-Nexus 6
09-08 14:02:17.119  3832  3880 I jxcore-log: 
,09-08 14:02:17.121  3832  3880 I jxcore-log: Running for WIFI network type
09-08 14:02:17.121  3832  3880 I jxcore-log: 
,09-08 14:02:17.226  3832  4316 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-08 14:02:19.602  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 14:02:19.602  3832  3880 I jxcore-log: 
,09-08 14:02:20.058  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 14:02:20.058  3832  3880 I jxcore-log: 
,09-08 14:02:20.091  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 14:02:20.091  3832  3880 I jxcore-log: 
,09-08 14:02:20.882  3763  4319 V KeepSync: Connecting to GoogleApiClient
,09-08 14:02:20.882   875  1694 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:02:20.927  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:02:20.929  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:02:20.963  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 14:02:20.963  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 14:02:20.963  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:02:20.963  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:02:20.986  1689  4320 V BaseAuthAsyncOperation: access token request failed
,09-08 14:02:20.987  3763  4319 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:02:21.053  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 14:02:21.054  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 14:02:21.054  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:02:21.054  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:02:21.078  3763  4319 E KeepSync: IOException
09-08 14:02:21.078  3763  4319 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:02:21.078  3763  4319 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:02:21.078  3763  4319 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:02:21.078  3763  4319 E KeepSync: 	... 10 more
09-08 14:02:21.078  3763  4319 W KeepSync: Sync result 2
,09-08 14:02:21.090   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 236810, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:02:21.514  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 14:02:21.514  3832  3880 I jxcore-log: 
,09-08 14:02:21.760  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 14:02:21.760  3832  3880 I jxcore-log: 
,09-08 14:02:21.765  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 14:02:21.765  3832  3880 I jxcore-log: 
,09-08 14:02:21.772  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 14:02:21.772  3832  3880 I jxcore-log: 
,09-08 14:02:22.038  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 14:02:22.038  3832  3880 I jxcore-log: 
,09-08 14:02:22.055  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 14:02:22.055  3832  3880 I jxcore-log: 
,09-08 14:02:22.059  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 14:02:22.059  3832  3880 I jxcore-log: 
,09-08 14:02:22.771  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 14:02:22.771  3832  3880 I jxcore-log: 
,09-08 14:02:22.939  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 14:02:22.939  3832  3880 I jxcore-log: 
,09-08 14:02:23.275  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 14:02:23.275  3832  3880 I jxcore-log: 
,09-08 14:02:23.286  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 14:02:23.286  3832  3880 I jxcore-log: 
,09-08 14:02:23.294  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 14:02:23.294  3832  3880 I jxcore-log: 
,09-08 14:02:23.300  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 14:02:23.300  3832  3880 I jxcore-log: 
,09-08 14:02:23.342  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 14:02:23.342  3832  3880 I jxcore-log: 
,09-08 14:02:23.389  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 14:02:23.389  3832  3880 I jxcore-log: 
,09-08 14:02:23.397  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 14:02:23.397  3832  3880 I jxcore-log: 
,09-08 14:02:23.404  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 14:02:23.404  3832  3880 I jxcore-log: 
,09-08 14:02:23.425  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 14:02:23.425  3832  3880 I jxcore-log: 
,09-08 14:02:23.430  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 14:02:23.430  3832  3880 I jxcore-log: 
,09-08 14:02:23.436  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 14:02:23.436  3832  3880 I jxcore-log: 
,09-08 14:02:23.452  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 14:02:23.452  3832  3880 I jxcore-log: 
,09-08 14:02:23.479  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 14:02:23.479  3832  3880 I jxcore-log: 
,09-08 14:02:23.491  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 14:02:23.491  3832  3880 I jxcore-log: 
,09-08 14:02:23.505  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 14:02:23.505  3832  3880 I jxcore-log: 
,09-08 14:02:23.516  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 14:02:23.516  3832  3880 I jxcore-log: 
,09-08 14:02:23.532  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 14:02:23.532  3832  3880 I jxcore-log: 
,09-08 14:02:23.543  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 14:02:23.543  3832  3880 I jxcore-log: 
,09-08 14:02:23.549  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 14:02:23.549  3832  3880 I jxcore-log: 
,09-08 14:02:23.579  3832  3880 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 14:02:23.579  3832  3880 I jxcore-log: ,
,09-08 14:02:23.592  3832  3880 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 14:02:23.593  3832  3880 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 14:02:23.593  3832  3880 I jxcore-log: 
,09-08 14:02:28.650   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 14:02:51.410  3775  4322 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:02:51.514  3775  4325 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:02:51.534  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:02:51.551  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:02:51.635  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:02:51.635  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 14:02:51.635  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:02:51.635  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:02:51.638  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:02:51.638  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:02:51.638  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:02:51.638  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:02:51.666  3023  4324 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 14:02:51.666  3023  4324 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at blb.a(PG:3937)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at czp.a(PG:18188)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:02:51.666  3023  4324 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	... 12 more
09-08 14:02:51.666  3023  4324 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at fal.a(PG:38)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:02:51.666  3023  4324 E HttpOperation: 	... 14 more
,09-08 14:02:51.730  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:02:51.730  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 14:02:51.731  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:02:51.731  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 14:02:51.732  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 14:02:51.732  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:02:51.732  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:02:51.732  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:02:51.756  3023  4324 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 14:02:51.756  3023  4324 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at hec.a(PG:42)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at hee.a(PG:102)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at czr.a(PG:65)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at kka.a(PG:108)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at czp.a(PG:19176)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:02:51.756  3023  4324 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	... 15 more
09-08 14:02:51.756  3023  4324 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at fal.a(PG:38)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:02:51.756  3023  4324 E HttpOperation: 	... 17 more
,09-08 14:02:51.756  3023  4324 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 14:02:51.756  3023  4324 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at hec.a(PG:42)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at hee.a(PG:102)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at czr.a(PG:65)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at kka.a(PG:108)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	... 15 more
09-08 14:02:51.756  3023  4324 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at fal.a(PG:38)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 14:02:51.756  3023  4324 E ExperimentLoader: 	... 17 more
,09-08 14:02:51.772  3775  4325 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:02:51.773  3775  4322 E BooksSync: Soft error
09-08 14:02:51.773  3775  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:02:51.773  3775  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:02:51.775  3775  4322 E BooksSync: Sync error
09-08 14:02:51.775  3775  4322 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:02:51.775  3775  4322 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:02:51.775  3775  4322 I BooksSync: Finished books sync
,09-08 14:02:51.793   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 238573, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:02:51.872   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 259783, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:02:52.516   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:03:02.142   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=278264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 14:03:22.967  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:03:22.972  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:03:23.010  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:03:23.010  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 14:03:23.010  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:03:23.010  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:03:23.029  3023  4333 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 14:03:23.029  3023  4333 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at blb.a(PG:3937)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at czp.a(PG:18188)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:03:23.029  3023  4333 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	... 12 more
09-08 14:03:23.029  3023  4333 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at fal.a(PG:38)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:03:23.029  3023  4333 E HttpOperation: 	... 14 more
,09-08 14:03:23.090  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 14:03:23.090  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 14:03:23.090  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:03:23.090  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:03:23.108  3023  4333 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 14:03:23.108  3023  4333 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jdm.a(PG:82)
,09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at hec.a(PG:42)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at hee.a(PG:102)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at czr.a(PG:65)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at kka.a(PG:108)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at czp.a(PG:19176)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:03:23.108  3023  4333 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	... 15 more
09-08 14:03:23.108  3023  4333 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at fal.a(PG:38)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:03:23.108  3023  4333 E HttpOperation: 	... 17 more
09-08 14:03:23.108  3023  4333 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 14:03:23.108  3023  4333 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at hec.a(PG:42)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at hee.a(PG:102)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at czr.a(PG:65)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at kka.a(PG:108)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	... 15 more
09-08 14:03:23.108  3023  4333 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 14:03:23.108  3023  4333 E Exper,imentLoader: 	at fal.a(PG:38)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 14:03:23.108  3023  4333 E ExperimentLoader: 	... 17 more
,09-08 14:03:23.259   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 298725, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:03:23.319  3763  4335 V KeepSync: Connecting to GoogleApiClient
,09-08 14:03:23.320   875  2038 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:03:23.395  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 14:03:23.395  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 14:03:23.395  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:03:23.395  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:03:23.412  1689  4336 V BaseAuthAsyncOperation: access token request failed
,09-08 14:03:23.414  3763  4335 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:03:23.467  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 14:03:23.467  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 14:03:23.467  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:03:23.467  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:03:23.488  3763  4335 E KeepSync: IOException
09-08 14:03:23.488  3763  4335 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:03:23.488  3763  4335 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:03:23.488  3763  4335 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:03:23.488  3763  4335 E KeepSync: 	... 10 more
,09-08 14:03:23.488  3763  4335 W KeepSync: Sync result 2
,09-08 14:03:23.494   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 299348, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:03:26.009   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=302131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:03:32.515   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:03:52.782   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=328904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:03:57.835   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=333956, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:03:57.892  3775  4347 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:03:57.927  3775  4348 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:03:57.941  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:03:57.944  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:03:57.972  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:03:57.972  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:03:57.972  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:03:57.972  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:03:58.003  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:03:58.005  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:03:58.030  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:03:58.030  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:03:58.030  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:03:58.030  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:03:58.051  3775  4348 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:03:58.052  3775  4347 E BooksSync: Soft error
09-08 14:03:58.052  3775  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:03:58.052  3775  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 14:03:58.053  3775  4347 E BooksSync: Sync error
09-08 14:03:58.053  3775  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:03:58.053  3775  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:03:58.053  3775  4347 I BooksSync: Finished books sync
,09-08 14:03:58.067   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 333883, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:04:08.188  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:04:08.201  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:04:08.207  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:04:08.273  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 14:04:08.273  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 14:04:08.273  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:04:08.273  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:04:08.312  1499  1510 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 14:04:08.312  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 14:04:08.312  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 14:04:08.312  1499  1510 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 14:04:08.312  1499  1510 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 14:04:08.312  1499  1510 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 14:04:08.312  1499  1510 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 14:04:08.324  3554  3586 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 14:04:08.324  3554  3586 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 14:04:08.324  3554  3586 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 14:04:08.324  3554  3586 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 14:04:08.324  3554  3586 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 14:04:08.324  3554  3586 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 14:04:08.324  3554  3586 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 14:04:28.483  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:04:28.485  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:04:28.542  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:04:28.542  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:04:28.543  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:04:28.543  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:04:28.579  3023  4355 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 14:04:28.579  3023  4355 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at blb.a(PG:3937)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at czp.a(PG:18188)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:04:28.579  3023  4355 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	... 12 more
09-08 14:04:28.579  3023  4355 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at fal.a(PG:38)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:04:28.579  3023  4355 E HttpOperation: 	... 14 more
,09-08 14:04:28.657  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:04:28.657  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:04:28.657  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:04:28.657  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:04:28.686  3023  4355 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 14:04:28.686  3023  4355 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at hec.a(PG:42)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at hee.a(PG:102)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at czr.a(PG:65)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at kka.a(PG:108)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at czp.a(PG:19176)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:04:28.686  3023  4355 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	... 15 more
09-08 14:04:28.686  3023  4355 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at fal.a(PG:38)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:04:28.686  3023  4355 E HttpOperation: 	... 17 more
,09-08 14:04:28.687  3023  4355 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 14:04:28.687  3023  4355 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at hec.a(PG:42)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at hee.a(PG:102)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at czr.a(PG:65)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at kka.a(PG:108)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	... 15 more
09-08 14:04:28.687  3023  4355 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at fal.a(PG:38)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 14:04:28.687  3023  4355 E ExperimentLoader: 	... 17 more
,09-08 14:04:28.828   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 360844, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:04:41.769   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=377890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:04:47.982   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:05:06.862   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=402984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:05:13.049   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:05:27.892  3763  4359 V KeepSync: Connecting to GoogleApiClient
09-08 14:05:27.893   875  2044 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 14:05:27.966  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:05:27.973  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:05:28.035  1689  4361 I EventLogService: Opted in for usage reporting
,09-08 14:05:28.037  1689  4361 I EventLogService: Aggregate from 1473335491503 (log), 1473334523382 (data)
,09-08 14:05:28.086  1689  4361 W EventLogAggregator: Unknown tag: snet_gcore
09-08 14:05:28.086  1689  4361 W EventLogAggregator: Unknown tag: snet_launch_service
,09-08 14:05:28.137   875  2044 I ActivityManager: Start proc 4363:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,09-08 14:05:28.156  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 14:05:28.156  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 14:05:28.156  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:05:28.156  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:05:28.176  1689  4360 V BaseAuthAsyncOperation: access token request failed
,09-08 14:05:28.179  3763  4359 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 14:05:28.194  1689  4361 I ServiceDumpSys: dumping service [account]
,09-08 14:05:28.207  4363  4363 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,09-08 14:05:28.290  4363  4376 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-08 14:05:28.445  4363  4376 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,09-08 14:05:28.494  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 14:05:28.495  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 14:05:28.495  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth,
09-08 14:05:28.495  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-08 14:05:28.536  4363  4376 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-08 14:05:28.586  3763  4359 E KeepSync: IOException
09-08 14:05:28.586  3763  4359 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 14:05:28.586  3763  4359 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 14:05:28.586  3763  4359 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 14:05:28.586  3763  4359 E KeepSync: 	... 10 more
,09-08 14:05:28.586  3763  4359 W KeepSync: Sync result 2
,09-08 14:05:28.597  4363  4363 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,09-08 14:05:28.601   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 423892, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:05:28.813  4363  4363 W InstanceID/Rpc: Found 10011
,09-08 14:05:28.940  4400  4400 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1287742404.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1287742404.dex
,09-08 14:05:28.959  4363  4434 E GoogleConversionReporter: Error sending ping
,09-08 14:05:28.998  4400  4400 I dex2oat : dex2oat took 59.298ms (threads: 4) arena alloc=372KB java alloc=37KB native alloc=1514KB free=1557KB
,09-08 14:05:31.929   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=428050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:05:37.369   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=433490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:05:43.148   875   888 I ActivityManager: Waited long enough for: ServiceRecord{e92802 u0 com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator}
,09-08 14:05:56.996   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=453117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:05:57.886   875  2041 I ActivityManager: Killing 3704:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-08 14:06:02.556   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=458677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:06:10.056  3775  4451 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 14:06:10.092  3775  4452 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 14:06:10.106  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:06:10.108  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:06:10.148  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 14:06:10.148  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:06:10.148  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:06:10.148  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:06:10.186  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:06:10.189  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:06:10.232  1499  2998 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 14:06:10.232  1499  2998 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 14:06:10.232  1499  2998 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:06:10.232  1499  2998 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:06:10.259  3775  4452 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 14:06:10.260  3775  4451 E BooksSync: Soft error
09-08 14:06:10.260  3775  4451 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:06:10.260  3775  4451 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:06:10.260  3775  4451 E BooksSync: Sync error
09-08 14:06:10.260  3775  4451 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 14:06:10.260  3775  4451 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 14:06:10.261  3775  4451 I BooksSync: Finished books sync
,09-08 14:06:10.272   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 466125, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:06:22.063   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=478184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:06:28.236   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=484357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:06:28.725  1499  2257 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 14:06:40.572  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:06:40.573  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:06:40.603  1499  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:06:40.603  1499  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:06:40.603  1499  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:06:40.603  1499  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:06:40.620  3023  4455 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 14:06:40.620  3023  4455 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at blb.a(PG:3937)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at czp.a(PG:18188)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:06:40.620  3023  4455 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	... 12 more
09-08 14:06:40.620  3023  4455 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at fal.a(PG:38)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:06:40.620  3023  4455 E HttpOperation: 	... 14 more
,09-08 14:06:40.712  1499  1510 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 14:06:40.712  1499  1510 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 14:06:40.712  1499  1510 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:06:40.712  1499  1510 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:06:40.728  3023  4455 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 14:06:40.728  3023  4455 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jdm.a(PG:82)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jcs.o(PG:406)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jcn.a(PG:1379)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jcs.i(PG:143)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at hec.a(PG:42)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at hee.a(PG:102)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at czr.a(PG:65)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at kka.a(PG:108)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at czp.a(PG:19176)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at czp.a(PG:9081)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at czq.run(PG:1686)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:06:40.728  3023  4455 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jdj.a(PG:4091)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jdj.a(PG:1125)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jdm.a(PG:77)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	... 15 more
09-08 14:06:40.728  3023  4455 E HttpOperation: Caused by: faj: BadAuthentication
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at fal.a(PG:38)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	at jdj.a(PG:4089)
09-08 14:06:40.728  3023  4455 E HttpOperation: 	... 17 more
09-08 14:06:40.728  3023  4455 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 14:06:40.728  3023  4455 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at hec.a(PG:42)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at hee.a(PG:102)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at czr.a(PG:65)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at kka.a(PG:108)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	... 15 more
09-08 14:06:40.728  3023  4455 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at fal.a(PG:38)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 14:06:40.728  3023  4455 E ExperimentLoader: 	... 17 more
,09-08 14:06:40.851   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 487874, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 14:06:47.129   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=503250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:06:53.315   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=509437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:07:12.196   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=528317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:07:18.409   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=534530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:07:37.316   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=553437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:07:43.502   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=559623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:08:02.383   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=578504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:08:08.569   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=584690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:08:27.449   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=603570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:08:33.635   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=609757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:08:52.516   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=628637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:08:58.702   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=634823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:09:17.849   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=653970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:09:24.009   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=660130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:09:42.863   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=678984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:09:49.062   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=685184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:10:07.929   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=704050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:10:14.129   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=710250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:10:32.996   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=729117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:10:39.182   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=735303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:10:58.062   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=754184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:11:04.249   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=760370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:11:23.129   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=779251, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:11:29.315   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=785437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:11:48.196   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=804317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:11:54.382   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=810503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:12:13.262   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=829384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:12:19.449   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=835570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:12:38.329   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=854450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:12:44.515   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=860636, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:13:03.396   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=879517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:13:09.569   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=885690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:13:12.402   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=888524, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:13:34.636   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=910757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:13:37.842   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=913963, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:14:00.062   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=936183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:14:02.909   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=939030, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:14:25.143   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=961264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:14:27.976   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=964097, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:14:50.209   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=986331, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:14:53.035   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=989157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:15:15.262   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1011384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:15:18.102   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1014223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:15:40.329   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1036451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:15:43.796   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1039917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:16:06.022   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1062143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:16:08.922   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1065043, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:16:31.155   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1087277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:16:33.982   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1090104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:16:49.770  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:16:49.773  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:16:49.814  4060  4486 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:16:49.862  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-08 14:16:49.862  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,09-08 14:16:49.862  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:16:49.862  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:16:49.887  4060  4486 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-08 14:16:49.888  4060  4486 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-08 14:16:54.782   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1110904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:16:59.036   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1115157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:17:20.090  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:17:20.093  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:17:20.115  4060  4488 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:17:20.156  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-08 14:17:20.156  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-08 14:17:20.156  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:17:20.156  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-08 14:17:20.176  4060  4488 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-08 14:17:21.262   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:17:24.108   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1140230, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:17:46.329   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1162450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:17:49.175   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1165296, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:18:11.396   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1187517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:18:17.102   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1193223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:18:20.335  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:18:20.337  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:18:20.349  4060  4492 V GoogleAuthProtoRequest: [352] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:18:20.370  1499  2269 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,09-08 14:18:20.370  1499  2269 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
09-08 14:18:20.370  1499  2269 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 14:18:20.370  1499  2269 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: [352] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: [352] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-08 14:18:20.393  4060  4492 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-08 14:18:20.577   875   884 I art     : Background partial concurrent mark sweep GC freed 45849(3MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 1.181ms total 155.922ms
,09-08 14:18:37.076   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1213197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:18:42.169   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1218290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:18:42.896   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,09-08 14:19:02.142   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1238264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:19:07.235   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1243356, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:19:27.209   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1263330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:19:32.302   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1268423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:19:52.289   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1288410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:19:57.368   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1293490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:20:17.356   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1313477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:20:20.404  1499  2257 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-08 14:20:20.609  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:20:20.614  1499  1499 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 14:20:20.627  4060  4501 V GoogleAuthProtoRequest: [353] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 14:20:20.669  1499  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
09-08 14:20:20.669  1499  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,09-08 14:20:20.669  1499  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 14:20:20.669  1499  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 14:20:20.703  4060  4501 W ExperimentUpdateService: [353] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: [353] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
09-08 14:20:20.705  4060  4501 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,09-08 14:20:22.436   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1318557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:20:42.409   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1338530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:20:48.128   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1344250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:21:08.102   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1364224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:21:13.195   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1369317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:21:33.156   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1389277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:21:38.262   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1394383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:21:58.249   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1414370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:22:03.342   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1419463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:22:23.316   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1439437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:22:28.409   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1444530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:22:48.383   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1464504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:22:53.462   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1469583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:23:13.449   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1489570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:23:21.955   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1498076, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 14:23:39.049   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1515170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 14:23:47.022   875  4272 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1523143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-08 14:23:50.705  4513  4513 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 14:23:50.710  4513  4513 D AndroidRuntime: CheckJNI is OFF
09-08 14:23:50.747  4513  4513 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 14:23:50.788  4513  4513 I Radio-JNI: register_android_hardware_Radio DONE
09-08 14:23:50.810  4513  4513 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 14:23:50.827   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-08 14:23:50.827   875   888 I ActivityManager: Killing 3832:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-08 14:23:50.941   875   885 I WindowState: WIN DEATH: Window{95b7976 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 14:23:50.943   875  1394 D GraphicsStats: Buffer count: 2
09-08 14:23:50.945   875  1312 D WifiService: Client connection lost with reason: 4
09-08 14:23:50.958   875   898 W PackageSettings: Skipping PackageSetting{2b8e1b3 com.example.hello/10273} due to missing metadata
09-08 14:23:50.988   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-08 14:23:50.988   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-08 14:23:50.988   875   888 E ActivityManager: Failure starting process com.test.thalitest
09-08 14:23:50.988   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-08 14:23:50.988   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:50.988   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:50.988   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:50.988   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 14:23:50.989   875   888 I ActivityManager:   Force finishing activity ActivityRecord{3c6419f u0 com.test.thalitest/.MainActivity t4}
09-08 14:23:50.990   875   898 I art     : Starting a blocking GC Explicit
09-08 14:23:51.007   875  1947 W ActivityManager: Spurious death for ProcessRecord{5558493 0:com.test.thalitest/u0a0}, curProc for 3832: null
09-08 14:23:51.030   875   898 I art     : Explicit concurrent mark sweep GC freed 23857(1877KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 673us total 40.125ms
09-08 14:23:51.052   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-08 14:23:51.054  4513  4513 I art     : System.exit called, status: 0
09-08 14:23:51.054  4513  4513 I AndroidRuntime: VM exiting with result code 0.
09-08 14:23:51.060   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-08 14:23:51.076   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-08 14:23:51.080  4215  4215 D BluetoothMapAppObserver: onReceive
09-08 14:23:51.080  4215  4215 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 14:23:51.083  1864  2261 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 14:23:51.085   875  1301 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 14:23:51.089  1897  1897 I Keyboard.Facilitator: resetDictionaries() : en_US
09-08 14:23:51.097  3652  3652 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-08 14:23:51.107  1897  4526 I Keyboard.Facilitator.DecoderInitializer: run()
09-08 14:23:51.110  1897  4526 I Decoder : createOrResetDecoder
09-08 14:23:51.137  2008  2008 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-08 14:23:51.145   875  2046 I ActivityManager: Start proc 4528:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-08 14:23:51.148  1499  1499 I ConfigService: onCreate
09-08 14:23:51.174  1499  4538 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
09-08 14:23:51.175  4528  4528 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-08 14:23:51.187   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 14:23:51.194  1897  4526 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-08 14:23:51.202   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-08 14:23:51.203   875   887 E PackageManager: Failed to write settings, restoring backup
09-08 14:23:51.203   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 14:23:51.203   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 14:23:51.203   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 14:23:51.203   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 14:23:51.203   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 14:23:51.203   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.203   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.203   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:51.205   875  1694 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3832 uid 10000
09-08 14:23:51.206  2022  2102 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-08 14:23:51.206   875   888 E DropBoxManagerService: Can't write: system_server_wtf
09-08 14:23:51.206   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 14:23:51.206   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 14:23:51.206   875   888 E DropBoxManagerService: 	... 13 more
09-08 14:23:51.206  1897  1897 I Keyboard.Facilitator: onFinishInput()
09-08 14:23:51.218   875  1931 I ActivityManager: Start proc 4541:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-08 14:23:51.219  2022  2102 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 14:23:51.219  2022  2102 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2022
09-08 14:23:51.219  2022  2102 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.219  2022  2102 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: Can't write: system_app_crash
09-08 14:23:51.221   875  4547 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 14:23:51.221   875  4547 E DropBoxManagerService: 	... 5 more
09-08 14:23:51.222   875  2038 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 14:23:51.228  2022  2102 I Process : Sending signal. PID: 2022 SIG: 9
09-08 14:23:51.236  1897  4526 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-08 14:23:51.238  1897  4526 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 14:23:51.238  1897  4526 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-08 14:23:51.240  1897  4526 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-08 14:23:51.240  1897  4526 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 14:23:51.241  1897  4526 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 14:23:51.241  1897  4526 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 14:23:51.243  1897  4526 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 14:23:51.243  1897  4526 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 14:23:51.244  1897  4526 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 14:23:51.244  1897  4526 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 14:23:51.244  1897  4526 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 14:23:51.245  1897  4526 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-08 14:23:51.269  4528  4528 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.280  4528  4556 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.281  4528  4556 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:51.284  4528  4558 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-08 14:23:51.288   875  1948 I ActivityManager: Start proc 4559:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-08 14:23:51.303   875  2036 I WindowState: WIN DEATH: Window{1b2f2d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-08 14:23:51.303   875  1694 D GraphicsStats: Buffer count: 1
09-08 14:23:51.312   875  1694 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2022) has died
09-08 14:23:51.315   875  1694 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-08 14:23:51.316   875  1694 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 14:23:51.333  4559  4559 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-08 14:23:51.337   875   888 I ActivityManager: Start proc 4571:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 14:23:51.378  1499  1499 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-08 14:23:51.378  1499  1499 D AndroidRuntime: Shutting down VM
09-08 14:23:51.379  1499  1499 E AndroidRuntime: FATAL EXCEPTION: main
09-08 14:23:51.379  1499  1499 E AndroidRuntime: Process: com.google.process.gapps, PID: 1499
09-08 14:23:51.379  1499  1499 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 14:23:51.379  1499  1499 E AndroidRuntime: 	... 8 more
09-08 14:23:51.384   875  1394 I ActivityManager: Killing 2085:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:23:51.386  4571  4571 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:23:51.387  4571  4571 D AndroidRuntime: Shutting down VM
09-08 14:23:51.411  4528  4556 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.416  4528  4558 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 14:23:51.416  4528  4558 E AndroidRuntime: Process: android.process.acore, PID: 4528
09-08 14:23:51.416  4528  4558 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.416  4528  4558 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 14:23:51.419   875  1312 D WifiService: Client connection lost with reason: 4
09-08 14:23:51.425  4528  4556 I Process : Sending signal. PID: 4528 SIG: 9
09-08 14:23:51.440   875  4587 E DropBoxManagerService: Can't write: system_app_crash
09-08 14:23:51.440   875  4587 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 14:23:51.440   875  4587 E DropBoxManagerService: 	... 5 more
09-08 14:23:51.448   875  1597 I ActivityManager: Process android.process.acore (pid 4528) has died
09-08 14:23:51.448   875  1597 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-08 14:23:51.452  4571  4571 E AndroidRuntime: FATAL EXCEPTION: main
09-08 14:23:51.452  4571  4571 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4571
09-08 14:23:51.452  4571  4571 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 14:23:51.452  4571  4571 E AndroidRuntime: 	... 10 more
09-08 14:23:51.465   875  2036 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 14:23:51.466   875  4589 E DropBoxManagerService: Can't write: system_app_crash
09-08 14:23:51.466   875  4589 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 14:23:51.466   875  4589 E DropBoxManagerService: 	... 5 more
09-08 14:23:51.467  4571  4571 I Process : Sending signal. PID: 4571 SIG: 9
09-08 14:23:51.467  1499  1499 I Process : Sending signal. PID: 1499 SIG: 9
09-08 14:23:51.473   875  4590 E DropBoxManagerService: Can't write: system_app_crash
09-08 14:23:51.473   875  4590 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 14:23:51.473   875  4590 E DropBoxManagerService: 	... 5 more
09-08 14:23:51.504   875  1948 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4571) has died
09-08 14:23:51.505   875  1948 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 14:23:51.531   875   888 I ActivityManager: Start proc 4592:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 14:23:51.538  1689  4591 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
09-08 14:23:51.538  1689  4591 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@b31f1e8
09-08 14:23:51.539   875  1694 I ActivityManager: Process com.google.process.gapps (pid 1499) early provider death
09-08 14:23:51.543   875  1312 D WifiService: Client connection lost with reason: 4

```
