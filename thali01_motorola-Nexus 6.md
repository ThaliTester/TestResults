#### Test 830701771a7aee8_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 18:23:37.392   875  1311 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-08 18:23:38.149  3760  3760 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 18:23:38.154  3760  3760 D AndroidRuntime: CheckJNI is OFF
09-08 18:23:38.197  3760  3760 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 18:23:38.247  3760  3760 I Radio-JNI: register_android_hardware_Radio DONE
09-08 18:23:38.268  3760  3760 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 18:23:38.273   875  2028 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 18:23:38.328  1998  2013 W SearchService: Abort, client detached.
09-08 18:23:38.332  3760  3760 D AndroidRuntime: Shutting down VM
09-08 18:23:38.332  1998  1998 I HotwordDetector: Closing mic
09-08 18:23:38.333  1998  2360 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2c81718
09-08 18:23:38.334  1998  2367 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-08 18:23:38.349   875  2264 I ActivityManager: Start proc 3769:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 18:23:38.398   377  2369 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-08 18:23:38.399   377  2369 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-08 18:23:38.404   377  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 18:23:38.405  1998  2366 I MicroRecognitionRnrImpl: Detection finished
09-08 18:23:38.405  1998  2364 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-08 18:23:38.428  3769  3769 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 18:23:38.449  3769  3769 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 18:23:38.455  3769  3769 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4176-4179)
09-08 18:23:38.455  3769  3769 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:23:38.469  3769  3769 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cdface}
09-08 18:23:38.471  3769  3769 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:23:38.471  3769  3769 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 18:23:38.478  3769  3769 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 18:23:38.480  3769  3769 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 18:23:38.495  3769  3769 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-08 18:23:38.506  3769  3769 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 18:23:38.506  3769  3769 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 18:23:38.506  3769  3769 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 18:23:38.506  3769  3769 I Adreno  : Build Date                       : 10/20/15
09-08 18:23:38.506  3769  3769 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 18:23:38.506  3769  3769 I Adreno  : Local Branch                     : M14
09-08 18:23:38.506  3769  3769 I Adreno  : Remote Branch                    : 
09-08 18:23:38.506  3769  3769 I Adreno  : Remote Branch                    : 
09-08 18:23:38.506  3769  3769 I Adreno  : Reconstruct Branch               : 
09-08 18:23:38.566   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37b3be6:true
,09-08 18:23:38.599  3769  3769 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 18:23:38.611  3769  3769 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 18:23:38.676  3769  3807 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 18:23:38.687  3769  3794 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 18:23:38.711  3769  3807 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 18:23:38.785   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +453ms
,09-08 18:23:38.787  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-08 18:23:38.852  3769  3769 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3769
,09-08 18:23:38.951  3769  3769 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 18:23:39.147   875  2028 I ActivityManager: Killing 3204:com.google.android.gm/u0a78 (adj 15): empty #17
,09-08 18:23:39.153  3769  3809 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1681524432
,09-08 18:23:39.161  3769  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 18:23:39.161  3769  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 18:23:39.161  3769  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 18:23:39.161  3769  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 18:23:39.161  3769  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 18:23:39.161  3769  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24a94f2 added. We now have 1 listener(s)
,09-08 18:23:39.165  3769  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 18:23:39.167  3769  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:23:39.167  3769  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:23:39.167  3769  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 18:23:39.174  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 18:23:39.175  3769  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54b2ef9 added. We now have 1 listener(s)
09-08 18:23:39.175  3769  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:23:39.179   875  1312 D WifiService: New client listening to asynchronous messages
,09-08 18:23:39.181  3769  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:23:39.182  3769  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 18:23:39.183  3769  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 18:23:39.184  3769  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-08 18:23:39.184  3769  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 18:23:39.215   875  2028 I ActivityManager: Killing 3103:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-08 18:23:39.245  3769  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:39.245  3769  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 18:23:39.250  3769  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:39.251  3769  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:39.251  3769  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 18:23:39.251  3769  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:39.252  3769  3809 I io.jxcore.node.LifeCycleMonitor: start: OK,
,09-08 18:23:39.275  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:39.278  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:39.302  3769  3769 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 18:23:40.173  3769  3820 W jxcore-log: Initializing JXcore engine
09-08 18:23:40.173  3769  3820 W jxcore-log: JXcore engine is ready
09-08 18:23:40.212  3820  3820 W Thread-323: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8989 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-08 18:23:40.212  3820  3820 W Thread-323: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10845]" dev="sockfs" ino=10845 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 18:23:40.212  3820  3820 W Thread-323: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 18:23:40.212  3820  3820 W Thread-323: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27006]" dev="sockfs" ino=27006 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-08 18:23:40.225  3769  3820 W jxcore-log: Starting JXcore engine
09-08 18:23:40.273   875  2066 D NetlinkSocketObserver: NeighborEvent{elapsedMs=105996, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
09-08 18:23:40.307  3769  3820 W jxcore-log: Platform android
09-08 18:23:40.307  3769  3820 W jxcore-log: 
09-08 18:23:40.307  3769  3820 W jxcore-log: Process ARCH arm
09-08 18:23:40.307  3769  3820 W jxcore-log: 
09-08 18:23:40.566  3769  3820 I jxcore-log: JXcore Cordova bridge is ready!
09-08 18:23:40.566  3769  3820 I jxcore-log: 
09-08 18:23:40.567  3769  3820 W jxcore-log: JXcore engine is started
09-08 18:23:40.582  3769  3809 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-08 18:23:40.590  3769  3769 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-08 18:23:40.870  1508  1508 I ConfigService: onDestroy
,09-08 18:23:49.829   875   888 I ActivityManager: Waited long enough for: ServiceRecord{8f006dd u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,09-08 18:23:50.326  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:23:50.335  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:23:50.337  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:23:50.367  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 18:23:50.367  3769  3820 I jxcore-log: 
,09-08 18:23:50.368  1508  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 18:23:50.368  1508  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-08 18:23:50.368  1508  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 18:23:50.368  1508  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:23:50.369  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 18:23:50.369  3769  3820 I jxcore-log: 
,09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:50.376  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:50.383  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:50.387  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 18:23:50.387  3769  3820 I jxcore-log: 
,09-08 18:23:50.390  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 18:23:50.390  3769  3820 I jxcore-log: 
,09-08 18:23:50.393  3500  3500 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 18:23:50.393  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 18:23:50.394  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-08 18:23:50.879  3769  3820 D executeNativeTests: Running unit tests
,09-08 18:23:50.937  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:23:50.938  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 added. We now have 2 listener(s)
09-08 18:23:50.939  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:23:50.939  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:23:50.939  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:23:50.939  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:50.939  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 added. We now have 2 listener(s)
09-08 18:23:50.939  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:50.940  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:23:50.946  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:50.958  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:50.963  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:50.963  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:50.965  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:50.965  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:50.965  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:50.968  3769  3820 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 18:23:50.968  3769  3820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:50.968  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:50.968  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 18:23:50.968  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:50.969  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:50.969  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:50.969  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:50.969  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:50.969  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:50.969  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:50.969  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:50.970  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:23:50.970  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 removed from the list
09-08 18:23:50.970  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:50.970  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 removed from the list
,09-08 18:23:50.975  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:50.975  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:50.975  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:50.976  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:50.976  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:50.977  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:50.977  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:50.978  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:50.978  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
,09-08 18:23:50.980  3769  3820 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-08 18:23:50.980  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:50.980  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:50.980  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:50.980  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:23:50.981  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:50.981  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:50.981  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
,09-08 18:23:50.981  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:50.981  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
,09-08 18:23:50.981  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:23:50.981  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:50.981  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:50.981  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:50.981  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:50.982  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:50.982  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:50.983  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:50.983  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 18:23:50.988  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 18:23:50.989  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:50.989  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:50.990  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:50.990  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:50.990  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:50.990  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:50.990  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:50.990  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:50.990  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:50.990  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:50.990  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:50.990  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:50.990  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:50.990  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:50.990  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:50.993  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:50.993  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:50.993  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:50.993  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:50.994  3769  3820 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 18:23:50.995  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:51.004  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:51.007  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:51.008  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:51.008  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:51.008  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:51.009  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:51.009  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:51.013  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:51.021  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.023  3769  3820 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:23:51.023  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:23:51.029  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.030  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:23:51.033  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:23:51.033  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 18:23:51.037  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-08 18:23:51.040  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-08 18:23:51.040  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:23:51.041  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:23:51.042  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:23:51.043  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:23:51.048  2697  2889 D BtGatt.GattService: registerClient() - UUID=280cd356-c228-437e-a960-3113053986a2
09-08 18:23:51.048  2697  2735 D BtGatt.GattService: onClientRegistered() - UUID=280cd356-c228-437e-a960-3113053986a2, clientIf=5
09-08 18:23:51.049  3769  3816 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 18:23:51.050  2697  2711 D BtGatt.GattService: start scan with filters
09-08 18:23:51.053  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:23:51.053  2697  2756 D BtGatt.ScanManager: handling starting scan
09-08 18:23:51.053  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:23:51.054  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:23:51.054  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 18:23:51.055  2697  2756 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
09-08 18:23:51.056  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:23:51.057  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 18:23:51.057  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:23:51.060  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 18:23:51.063  3769  3820 I io.jxcore.node.ConnectionHelper: start: OK
09-08 18:23:51.065  2697  2735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 18:23:51.065  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.066  2697  2756 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 18:23:51.068  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.068  3769  3820 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:23:51.068  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.068  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:23:51.068  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.068  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:23:51.069  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:51.069  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:51.069  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:51.069  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:51.070  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:51.070  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:23:51.071  3769  3820 D BluetoothAdapter: STATE_ON
09-08 18:23:51.071  2697  2709 D BtGatt.GattService: stopScan() - queue size =1
09-08 18:23:51.073  2697  2889 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 18:23:51.073  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:51.073  2697  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 18:23:51.073  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:23:51.073  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:51.073  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.073  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:23:51.073  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 18:23:51.074  2697  2756 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:23:51.074  2697  2756 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 18:23:51.075  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:51.075  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:23:51.075  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:23:51.075  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:23:51.076  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:51.077  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.077  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.077  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:51.077  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:51.077  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.077  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.077  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.077  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:51.077  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop,
09-08 18:23:51.077  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.077  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:51.078  3769  3820 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 18:23:51.080  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:51.087  2697  2735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:51.087  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:51.087  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:23:51.090  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:51.091  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:51.093  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:23:51.093  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:51.093  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:51.093  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:51.093  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:51.093  2697  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 18:23:51.093  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.094  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.096  3769  3820 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 18:23:51.096  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:23:51.097  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.101  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:23:51.102  2697  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:23:51.102  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:23:51.102  2697  2756 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:23:51.102  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:23:51.103  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:23:51.109  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:23:51.109  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:23:51.109  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:23:51.113  2697  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:23:51.113  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.114  2697  2756 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 18:23:51.114  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:23:51.117  2697  2891 D BtGatt.GattService: registerClient() - UUID=76c0e45d-88a9-47e4-8b66-586fc248a5fb
,09-08 18:23:51.118  2697  2735 D BtGatt.GattService: onClientRegistered() - UUID=76c0e45d-88a9-47e4-8b66-586fc248a5fb, clientIf=5
,09-08 18:23:51.119  3769  3816 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 18:23:51.119  2697  2901 D BtGatt.GattService: start scan with filters
,09-08 18:23:51.124  2697  2735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 18:23:51.124  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.125  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:23:51.125  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:23:51.125  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:23:51.125  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 18:23:51.126  2697  2756 D BtGatt.ScanManager: handling starting scan
,09-08 18:23:51.130  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:51.130  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 18:23:51.130  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:51.133  2697  2735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 18:23:51.133  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.133  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 18:23:51.133  2697  2756 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:23:51.138  3769  3820 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 18:23:51.141  2697  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 18:23:51.141  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.142  2697  2756 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:23:51.142  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.142  3769  3820 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 18:23:51.142  2697  2756 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 18:23:51.142  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.142  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:23:51.142  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.142  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:23:51.142  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:23:51.142  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:51.142  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:51.143  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:23:51.143  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:51.143  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:23:51.143  3769  3820 D BluetoothAdapter: STATE_ON
09-08 18:23:51.144  2697  2709 D BtGatt.GattService: stopScan() - queue size =1
09-08 18:23:51.145  2697  2891 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 18:23:51.146  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:23:51.146  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:23:51.146  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:23:51.146  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:23:51.146  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:51.148  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:51.148  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:23:51.148  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:23:51.148  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:23:51.149  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:51.150  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:51.150  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:51.150  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:51.151  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.151  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.151  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:51.151  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.151  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.151  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.151  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.151  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.152  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.152  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.153  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.153  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.153  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.153  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.154  3769  3820 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 18:23:51.154  2697  2735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 18:23:51.154  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.156  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:51.160  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:51.161  2697  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 18:23:51.161  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.163  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:51.164  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:23:51.166  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.166  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:23:51.166  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:23:51.166  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:23:51.168  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.166  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:23:51.169  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:23:51.169  2697  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:23:51.169  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.169  2697  2756 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:23:51.173  3769  3820 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:23:51.173  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 18:23:51.175  2697  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:23:51.176  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.176  2697  2756 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 18:23:51.177  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:23:51.178  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:23:51.178  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 18:23:51.183  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 18:23:51.183  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:23:51.183  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:23:51.183  2697  2735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 18:23:51.183  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.184  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:23:51.188  2697  2891 D BtGatt.GattService: registerClient() - UUID=0449f03c-5ed1-4b63-a550-4ddb43538f37
,09-08 18:23:51.188  2697  2735 D BtGatt.GattService: onClientRegistered() - UUID=0449f03c-5ed1-4b63-a550-4ddb43538f37, clientIf=5
09-08 18:23:51.189  3769  3816 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 18:23:51.189  2697  2889 D BtGatt.GattService: start scan with filters
,09-08 18:23:51.194  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:23:51.194  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:23:51.194  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:23:51.194  2697  2756 D BtGatt.ScanManager: handling starting scan
09-08 18:23:51.194  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:23:51.197  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:23:51.197  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:23:51.197  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:23:51.199  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:23:51.200  2697  2735 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 18:23:51.200  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.201  2697  2756 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:23:51.202  3769  3820 I io.jxcore.node.ConnectionHelper: start: OK
09-08 18:23:51.202  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:23:51.202  3769  3820 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 18:23:51.202  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.202  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:23:51.202  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.202  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:23:51.202  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 18:23:51.202  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 18:23:51.202  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:51.202  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:23:51.203  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:23:51.203  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 18:23:51.203  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:23:51.204  2697  2709 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:23:51.205  2697  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 18:23:51.205  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 18:23:51.205  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 18:23:51.205  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 18:23:51.205  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 18:23:51.205  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:23:51.206  2697  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 18:23:51.206  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:23:51.206  2697  2756 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:23:51.206  2697  2756 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 18:23:51.208  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:51.208  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:23:51.208  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,09-08 18:23:51.208  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:23:51.208  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:51.209  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:51.209  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:23:51.209  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:23:51.210  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.210  3769  3820 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:23:51.210  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:51.210  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.210  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:23:51.210  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.210  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:23:51.210  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.210  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.210  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.210  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.211  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.211  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.211  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.212  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.212  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:23:51.212  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.212  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.212  3769  3820 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-08 18:23:51.213  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.213  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:51.213  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.213  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.213  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.213  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.214  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
,09-08 18:23:51.214  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.214  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.214  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.214  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.214  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.214  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.214  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.215  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.215  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.215  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.215  2697  2735 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 18:23:51.215  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:23:51.215  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.216  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 18:23:51.216  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.216  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:51.217  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.217  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.217  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.217  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.217  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.217  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.217  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
,09-08 18:23:51.217  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.217  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.217  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.217  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.218  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.218  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:51.218  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.218  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.218  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.219  3769  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 18:23:51.219  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.219  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:51.219  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.220  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.220  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.220  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.220  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.220  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.220  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.220  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:23:51.220  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.220  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.220  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.220  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.221  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:23:51.223  2697  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 18:23:51.223  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.221  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.224  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.224  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.224  3769  3820 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-08 18:23:51.224  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.224  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.224  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.225  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.225  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.225  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.225  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.225  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.225  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.225  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.225  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.225  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.225  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.225  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.226  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.226  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.226  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.226  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.227  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:51.228  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:51.228  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:51.228  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 18:23:51.228  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 18:23:51.228  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 18:23:51.228  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.229  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:51.229  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.229  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.230  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.230  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.230  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.230  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.230  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.230  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop,
09-08 18:23:51.230  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.230  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.230  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.231  2697  2735 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:23:51.232  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.230  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.232  2697  2756 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:23:51.233  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-08 18:23:51.233  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.233  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.234  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
,09-08 18:23:51.236  3769  3820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 18:23:51.236  3769  3820 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 18:23:51.237  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 18:23:51.239  2697  2735 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:23:51.239  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:23:51.239  2697  2756 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 18:23:51.241  3769  3820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:51.241  3769  3820 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-08 18:23:51.241  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 18:23:51.242  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 18:23:51.243  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 18:23:51.243  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 18:23:51.243  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-08 18:23:51.243  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 18:23:51.243  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-08 18:23:51.243  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 18:23:51.243  3769  3820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-08 18:23:51.243  3769  3820 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:51.243  3769  3820 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 18:23:51.243  3769  3820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55,
09-08 18:23:51.244  3769  3820 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:51.244  3769  3820 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 18:23:51.244  3769  3820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:51.244  3769  3820 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 18:23:51.244  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-08 18:23:51.244  2697  2735 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 18:23:51.244  2697  2735 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:23:51.248  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 18:23:51.248  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 18:23:51.248  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-08 18:23:51.249  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 18:23:51.249  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-08 18:23:51.249  3769  3820 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-08 18:23:51.249  3769  3820 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 18:23:51.249  3769  3820 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-08 18:23:51.250  3769  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 387)
09-08 18:23:51.250  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.250  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.250  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:23:51.250  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.250  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.250  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.251  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 18:23:51.251  3769  3829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:23:51.251  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.251  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.251  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.251  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.251  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.251  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.252  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.252  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.252  3769  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 387
09-08 18:23:51.252  3769  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 387)
09-08 18:23:51.252  3769  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 387)
09-08 18:23:51.253  3769  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 387)
09-08 18:23:51.254  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.254  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.254  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.255  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.255  3769  3820 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-08 18:23:51.255  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.255  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.256  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.256  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.256  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.256  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.256  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.256  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.256  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.256  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.256  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.256  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.256  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.256  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.257  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.257  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.257  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.257  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.258  3769  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 18:23:51.258  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.258  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:51.258  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.258  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.258  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.258  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.258  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.258  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.259  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.259  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:23:51.259  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.259  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.259  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.259  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-08 18:23:51.260  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.260  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.260  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:23:51.260  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.260  3769  3820 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 18:23:51.260  3769  3820 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,09-08 18:23:51.260  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:51.260  3769  3820 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 18:23:51.260  3769  3820 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:51.260  3769  3820 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-08 18:23:51.260  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:51.261  3769  3820 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 18:23:51.261  3769  3820 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 18:23:51.261  3769  3820 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 18:23:51.261  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 18:23:51.261  3769  3820 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 18:23:51.261  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.261  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.261  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.261  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.261  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.261  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.261  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.261  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.261  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.261  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.262  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.262  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.262  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.262  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.263  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.263  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.263  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-08 18:23:51.263  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.263  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.263  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.263  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.264  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.264  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.264  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.264  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:23:51.264  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.264  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.264  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.264  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list,
09-08 18:23:51.264  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.264  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.264  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.264  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.264  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.264  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.264  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:23:51.264  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.265  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.265  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.265  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list,
09-08 18:23:51.265  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.265  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.265  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop,
09-08 18:23:51.265  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.265  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.265  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.265  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.266  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.266  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.266  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-08 18:23:51.266  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.267  3769  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 18:23:51.267  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:51.268  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-08 18:23:51.269  3769  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 18:23:51.269  3769  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 18:23:51.269  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 18:23:51.269  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 18:23:51.269  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 18:23:51.270  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.270  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 18:23:51.270  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...,
09-08 18:23:51.270  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 18:23:51.270  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.270  3769  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
09-08 18:23:51.270  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 18:23:51.270  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.270  3769  3831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:23:51.270  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.270  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:23:51.270  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:23:51.270  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-08 18:23:51.271  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.271  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.271  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:51.272  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:51.272  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:23:51.272  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:23:51.272  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.272  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.272  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:23:51.272  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.272  3769  3831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 18:23:51.272  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:23:51.272  3769  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 18:23:51.272  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.272  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-08 18:23:51.272  3769  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 18:23:51.272  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list,
09-08 18:23:51.272  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.273  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
09-08 18:23:51.272  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.273  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.273  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:23:51.273  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.273  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.273  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:23:51.274  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.274  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.274  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.274  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
,09-08 18:23:51.275  3769  3820 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 18:23:51.275  3769  3820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 18:23:51.275  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 18:23:51.276  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-08 18:23:51.276  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.276  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.276  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.277  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.277  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.277  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.277  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.277  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.277  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.277  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.277  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.277  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.277  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.277  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.279  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.279  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.279  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.279  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.282  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.282  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.282  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.282  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.282  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.282  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.283  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.283  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.283  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.283  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.283  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.283  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.283  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.283  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.284  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.284  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.284  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.284  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.285  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:23:51.285  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:23:51.285  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:23:51.285  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:23:51.285  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.285  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.285  3769  3820 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2834b42 not in the list
09-08 18:23:51.285  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.285  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.285  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:23:51.285  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.285  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.285  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:23:51.285  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:23:51.286  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:23:51.286  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:23:51.286  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:23:51.286  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e15753 not in the list
09-08 18:23:51.287  3769  3820 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 18:23:51.287  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:51.287  3769  3820 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 18:23:51.287  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 18:23:51.287  3769  3820 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-08 18:23:51.287  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 18:23:51.289  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 18:23:51.289  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-08 18:23:51.290  3769  3820 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 18:23:51.290  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:23:51.290  3769  3820 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-08 18:23:51.290  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 18:23:51.290  3769  3820 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 18:23:51.290  3769  3820 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-08 18:23:51.291  3769  3820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 18:23:51.291  3769  3820 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-08 18:23:51.291  3769  3820 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 18:23:51.291  3769  3820 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 18:23:51.291  3769  3820 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 18:23:51.292  3769  3820 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 18:23:51.292  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:51.292  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ca053fd added. We now have 2 listener(s)
09-08 18:23:51.293  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:51.294  3769  3820 D BluetoothAdapter: enable(): BT is already enabled..!
09-08 18:23:51.295   875  2028 D WifiService: setWifiEnabled: true pid=3769, uid=10000
09-08 18:23:51.295   875  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:51.295  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:51.295  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c8908f2 added. We now have 3 listener(s)
09-08 18:23:51.295  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:51.303  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:51.303  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43ebb43 added. We now have 4 listener(s)
09-08 18:23:51.303  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:51.305  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:23:51.305  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@49655c0 added. We now have 5 listener(s)
09-08 18:23:51.305  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:23:51.307   875  1700 D WifiService: setWifiEnabled: false pid=3769, uid=10000
09-08 18:23:51.307   875  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:51.312  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:23:51.312  2697  2722 D BluetoothAdapterState: Current state: ON, message: 23
09-08 18:23:51.312  2697  2722 D BluetoothAdapterProperties: Setting state to 13
,09-08 18:23:51.312  2697  2722 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 18:23:51.313  2697  2722 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:23:51.313  2697  2722 I BluetoothAdapterState: Entering PendingCommandState
09-08 18:23:51.314  2697  2735 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:23:51.314  2697  2722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 18:23:51.317  2697  2697 D HeadsetService: Received stop request...Stopping profile...
,09-08 18:23:51.317  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:51.317  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:51.318  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.318  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:51.318  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:23:51.320  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.322  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.326  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:51.326  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:51.326  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.326  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:51.329  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.330  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-08 18:23:51.331  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.332   875  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-08 18:23:51.332   875  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 18:23:51.332   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:23:51.332   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:23:51.334  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:23:51.343   875  2103 D DhcpClient: Clearing IP address
,09-08 18:23:51.344   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:51.346   373   873 D CommandListener: Setting iface cfg
,09-08 18:23:51.349  1508  2543 V NativeCrypto: Read error: ssl=0x9acbf000: I/O error during system call, Connection timed out
,09-08 18:23:51.350   875   888 I ActivityManager: Start proc 3834:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-08 18:23:51.350  1508  2543 V NativeCrypto: SSL shutdown failed: ssl=0x9acbf000: I/O error during system call, Broken pipe
,09-08 18:23:51.351   875   875 D BluetoothHeadset: Proxy object disconnected
,09-08 18:23:51.352  2697  2697 V BluetoothAdapterState: isTurningOff()=true
,09-08 18:23:51.352  2697  2697 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:23:51.352  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:23:51.352  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:23:51.352  2697  2697 D BluetoothMapService: onReceive
09-08 18:23:51.352  2697  2697 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:23:51.352  2697  2697 D BluetoothMapService: STATE_TURNING_OFF
,09-08 18:23:51.353  1952  1976 D BluetoothHeadset: Proxy object disconnected
09-08 18:23:51.353  1367  1386 D BluetoothHeadset: Proxy object disconnected
,09-08 18:23:51.353  1367  1367 D HeadsetProfile: Bluetooth service disconnected
09-08 18:23:51.353   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 18:23:51.354   875   875 D BluetoothHeadset: Proxy object disconnected
,09-08 18:23:51.354   875   875 D BluetoothHeadset: Proxy object disconnected
,09-08 18:23:51.354   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-08 18:23:51.357   402   402 E Parcel  : Reading a NULL string not supported here.
,09-08 18:23:51.360  2697  2697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 18:23:51.360  2697  2697 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 18:23:51.360  2697  2697 D BluetoothMapService: MAP Service closeService in
09-08 18:23:51.360   875  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 18:23:51.360  2697  2697 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 18:23:51.360   875  1311 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-08 18:23:51.360  2697  2697 D ObexServerSockets0: shutdown(block = true)
09-08 18:23:51.361  2697  2697 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 18:23:51.361   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:23:51.361  2697  2697 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 18:23:51.361  2697  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 18:23:51.361  2697  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:23:51.361  2697  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:23:51.361  2697  2735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 18:23:51.363  2697  2735 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 18:23:51.363  2697  2905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 18:23:51.363  2697  2886 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 18:23:51.363  2697  2904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 18:23:51.364  2697  2697 I BtOppRfcommListener: stopping Accept Thread
,09-08 18:23:51.364  2697  3434 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:23:51.364  2697  3434 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-08 18:23:51.366   373   873 D CommandListener: Clearing all IP addresses on wlan0
09-08 18:23:51.368  2697  2697 D A2dpService: Received stop request...Stopping profile...
,09-08 18:23:51.368  2697  2894 D A2dpStateMachine: Exit Disconnected: -1
09-08 18:23:51.370   875   875 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:51.371  2697  2697 D HidService: Received stop request...Stopping profile...
,09-08 18:23:51.371  2697  2697 D HidService: Stopping Bluetooth HidService
09-08 18:23:51.372  2697  2697 D HealthService: Received stop request...Stopping profile...
09-08 18:23:51.373  2697  2697 D PanService: Received stop request...Stopping profile...
09-08 18:23:51.374   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:23:51.374  2697  2697 D BluetoothMapService: Received stop request...Stopping profile...
09-08 18:23:51.375  2697  2697 D BluetoothMapService: stop()
,09-08 18:23:51.375  2697  2697 D BluetoothMapAppObserver: deinitObservers()
09-08 18:23:51.375  2697  2697 D BluetoothMapAppObserver: removeReceiver()
09-08 18:23:51.378  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-08 18:23:51.378  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-08 18:23:51.378  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:23:51.378  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:23:51.378   875  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 18:23:51.380  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:51.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:51.380  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.380  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:51.382  2697  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 18:23:51.382  2697  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:23:51.383  2697  2864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 18:23:51.383  2697  2864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:51.383  2697  2864 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:23:51.383  2697  2864 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:23:51.383  2697  2735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 18:23:51.383  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:51.383  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:51.384  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:51.384  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:51.384  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-08 18:23:51.385  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-08 18:23:51.385  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:23:51.385  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:23:51.385  2697  2697 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 18:23:51.385  2697  2735 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 18:23:51.385  2697  2697 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-08 18:23:51.386  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-08 18:23:51.386  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-08 18:23:51.386  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:23:51.387  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:23:51.387  2697  2697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 18:23:51.387  2697  2735 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-08 18:23:51.387  2697  2697 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-08 18:23:51.387  2697  2697 V BluetoothAdapterState: isTurningOff()=true
09-08 18:23:51.388  2697  2697 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:23:51.388  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:23:51.388  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:23:51.388  2697  2697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-08 18:23:51.388  2697  2697 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 18:23:51.390   875  2111 D DhcpClient: Receive thread stopped
,09-08 18:23:51.394  2697  2697 D BluetoothMapService: MAP Service closeService in
09-08 18:23:51.394  2697  2697 V BluetoothAdapterState: isTurningOff()=true
,09-08 18:23:51.394  2697  2697 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:23:51.393  1367  1367 D BluetoothA2dp: Proxy object disconnected
09-08 18:23:51.394  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:23:51.395  2697  2697 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:23:51.395  1367  1367 D BluetoothInputDevice: Proxy object disconnected
09-08 18:23:51.395  1367  1367 D HidProfile: Bluetooth service disconnected
,09-08 18:23:51.396  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:23:51.396  1367  1367 D PanProfile: Bluetooth service disconnected
,09-08 18:23:51.396  1367  1367 D BluetoothMap: Proxy object disconnected
09-08 18:23:51.396  1367  1367 D MapProfile: Bluetooth service disconnected
,09-08 18:23:51.396  2697  2722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 18:23:51.396  2697  2722 D BluetoothAdapterProperties: Setting state to 15
,09-08 18:23:51.396  2697  2722 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 18:23:51.397  1367  1383 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:23:51.398  2697  2722 I BluetoothAdapterState: Entering BleOnState,
09-08 18:23:51.399  1367  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:23:51.400  1952  2114 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:23:51.400  1367  2032 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:23:51.400   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:23:51.400  1367  1383 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 18:23:51.401   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:23:51.401   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 18:23:51.401   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:23:51.401  1367  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-08 18:23:51.402  1367  2032 D BluetoothPan: onBluetoothStateChange on: false
,09-08 18:23:51.402  2697  2722 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-08 18:23:51.402  2697  2722 D BluetoothAdapterProperties: Setting state to 16
,09-08 18:23:51.402  2697  2722 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 18:23:51.403  2697  2722 D BluetoothAdapterProperties: onBleDisable
09-08 18:23:51.403  2697  2722 I BluetoothAdapterState: Entering PendingCommandState
09-08 18:23:51.404  2697  2697 D BluetoothMapService: cleanup()
09-08 18:23:51.404  2697  2697 D BluetoothMapService: MAP Service closeService in
09-08 18:23:51.404  2697  2728 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 18:23:51.405  2697  2735 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:23:51.405  2697  2864 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 18:23:51.405  2697  2864 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:23:51.405  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.403  1897  2325 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 18:23:51.407  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.409  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.411  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.420   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 18:23:51.425  3834  3834 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-08 18:23:51.437  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 18:23:51.442  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:23:51.453   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@576b4f5:true
09-08 18:23:51.454   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-08 18:23:51.455   875  2080 I ActivityManager: Start proc 3850:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-08 18:23:51.455   875  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 18:23:51.455   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 18:23:51.458   875   892 D Tethering: MasterInitialState.processMessage what=3
09-08 18:23:51.460  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.461  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:23:51.464  3383  3383 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@24a94f2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-08 18:23:51.481  3834  3834 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 18:23:51.483  3834  3834 D BluetoothMap: Create BluetoothMap proxy object
,09-08 18:23:51.490  3834  3834 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 18:23:51.495  3850  3850 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 18:23:51.505  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:51.516   875   886 I ActivityManager: Killing 2986:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-08 18:23:51.519   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-08 18:23:51.520   875  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 18:23:51.608  2697  2735 I bt_hci  : shut_down
09-08 18:23:51.608  2697  2757 D bt_hwcfg: hw_epilog_process
,09-08 18:23:51.611  2697  2757 I bt_vendor: low_power_mode_cb
,09-08 18:23:51.631  2697  2757 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 18:23:51.631  2697  2757 I bt_vendor: epilog_cb
09-08 18:23:51.631  2697  2757 I bt_hci  : epilog_finished_callback
,09-08 18:23:51.637  2697  2735 I bt_hci_h4: hal_close
,09-08 18:23:51.637  2697  2735 I bt_userial_vendor: device fd = 51 close
,09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:23:51.682  3850  3850 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:23:51.682  3850  3850 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 18:23:51.730   875  2084 I ActivityManager: Start proc 3884:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-08 18:23:51.731   875  2084 I ActivityManager: Killing 3383:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 18:23:51.772  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:23:51.807  3850  3878 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 18:23:51.820   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2460806:true
,09-08 18:23:51.861  3884  3884 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 18:23:51.874  2697  2728 D bt_stack_manager: event_shut_down_stack finished.
,09-08 18:23:51.874  2697  2722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 18:23:51.875  2697  2722 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 18:23:51.876  2697  2697 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:23:51.877  2697  2697 D BtGatt.GattService: Received stop request...Stopping profile...
09-08 18:23:51.877  2697  2697 D BtGatt.GattService: stop()
,09-08 18:23:51.878  2697  2697 D BtGatt.AdvertiseManager: advertise clients cleared
09-08 18:23:51.881  2697  2697 V BluetoothAdapterState: isTurningOff()=false
09-08 18:23:51.881  2697  2697 V BluetoothAdapterState: isTurningOn()=false
09-08 18:23:51.882  2697  2697 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:23:51.882  2697  2697 V BluetoothAdapterState: isBleTurningOff()=true
09-08 18:23:51.882  2697  2722 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 18:23:51.882  2697  2722 D BluetoothAdapterProperties: Setting state to 10
09-08 18:23:51.882  2697  2722 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 18:23:51.883   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-08 18:23:51.883  2697  2722 I BluetoothAdapterState: Entering OffState
,09-08 18:23:51.910  2697  2697 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-08 18:23:51.910  2697  2697 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 18:23:51.910  2697  2697 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 18:23:51.911  2697  2728 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 18:23:51.914  2697  2728 D bt_stack_manager: event_clean_up_stack finished.
,09-08 18:23:51.914  3884  3884 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 18:23:51.931  2697  2697 I art     : System.exit called, status: 0
09-08 18:23:51.931  2697  2697 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 18:23:51.954  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:23:51.959   875   886 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,09-08 18:23:51.960   875   886 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
,09-08 18:23:51.961   875   886 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-08 18:23:51.961   875   886 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-08 18:23:51.961   875   886 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 18:23:52.024   875   886 I ActivityManager: Start proc 3912:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-08 18:23:52.027  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:23:52.030   875  2083 W ActivityManager: Spurious death for ProcessRecord{96a7f24 3912:com.android.bluetooth/1002}, curProc for 2697: null
,09-08 18:23:52.090  3912  3912 D AdapterServiceConfig: Adding HeadsetService
,09-08 18:23:52.091  3912  3912 D AdapterServiceConfig: Adding A2dpService
09-08 18:23:52.091  3912  3912 D AdapterServiceConfig: Adding HidService
09-08 18:23:52.091  3912  3912 D AdapterServiceConfig: Adding HealthService
09-08 18:23:52.091  3912  3912 D AdapterServiceConfig: Adding PanService
,09-08 18:23:52.091  3912  3912 D AdapterServiceConfig: Adding GattService
09-08 18:23:52.091  3912  3912 D AdapterServiceConfig: Adding BluetoothMapService
09-08 18:23:52.093   875  2263 I ActivityManager: Killing 3454:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 18:23:52.133  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:23:52.157  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 18:23:52.162  1724  1724 D SystemUpdateService: onCreate
,09-08 18:23:52.169  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 18:23:52.172  1724  3924 I SystemUpdateService: active receiver: enabled
,09-08 18:23:52.174  1724  3924 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:23:52.175  1724  3924 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 18:23:52.176  1724  3924 I SystemUpdateService: now status is 0 (complete)
,09-08 18:23:52.176  1724  3924 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 18:23:52.176  1724  3924 I SystemUpdateService: file has been verified
09-08 18:23:52.176  1724  3924 I SystemUpdateService: OTA package size = 12249756
,09-08 18:23:52.181  1724  3924 I SystemUpdateService: showing system update notification
,09-08 18:23:52.195  1724  1724 D SystemUpdateService: onDestroy
,09-08 18:23:52.206  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 18:23:52.213  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 18:23:52.214  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 18:23:52.213  1724  2520 I iu.UploadsManager: num queued entries: 0
,09-08 18:23:52.218  1724  2520 I iu.UploadsManager: num updated entries: 0
,09-08 18:23:52.219  1724  2520 I iu.SyncManager: NEXT; no task
,09-08 18:23:52.235   875  2083 I ActivityManager: Start proc 3926:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 18:23:52.277  3926  3926 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 18:23:52.279  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:52.284  3926  3926 D SprintDMHelper: simOperator: 
09-08 18:23:52.285  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 18:23:52.302   875  1915 I ActivityManager: Start proc 3938:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-08 18:23:52.303   875  1915 I ActivityManager: Killing 3580:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-08 18:23:52.435   875  2083 I ActivityManager: Start proc 3953:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-08 18:23:52.443   875  2083 I ActivityManager: Killing 1702:android.process.acore/u0a5 (adj 15): empty #17
,09-08 18:23:52.511  3953  3953 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 18:23:52.576  3953  3953 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 18:23:52.576  3953  3953 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 18:23:52.576  3953  3953 I GAv4    :   adb logcat -s GAv4
,09-08 18:23:52.592  3953  3953 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:52.599  3953  3953 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:52.632  3953  3970 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 18:23:52.735  3953  3953 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 18:23:52.782  3953  3953 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 18:23:52.795  3953  3953 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 8511-8518)
09-08 18:23:52.795  3953  3953 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 18:23:52.807  3953  3953 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {54e1ea2}
09-08 18:23:52.808  3953  3953 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 18:23:52.808  3953  3953 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 18:23:52.816  3953  3953 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 18:23:52.818  3953  3953 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 18:23:52.832  3953  3953 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 18:23:52.845  3953  3953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 18:23:52.845  3953  3953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 18:23:52.845  3953  3953 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 18:23:52.845  3953  3953 I Adreno  : Build Date                       : 10/20/15
09-08 18:23:52.845  3953  3953 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 18:23:52.845  3953  3953 I Adreno  : Local Branch                     : M14
09-08 18:23:52.845  3953  3953 I Adreno  : Remote Branch                    : 
09-08 18:23:52.845  3953  3953 I Adreno  : Remote Branch                    : 
09-08 18:23:52.845  3953  3953 I Adreno  : Reconstruct Branch               : 
,09-08 18:23:52.908  3953  3953 I NSApplication: Starting up...
,09-08 18:23:52.919  3953  4000 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 18:23:52.959   875  1700 I ActivityManager: Start proc 4005:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 18:23:52.964   875  1700 I ActivityManager: Killing 3660:com.google.android.partnersetup/u0a16 (adj 15): empty #17,
,09-08 18:23:53.056  4005  4005 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 18:23:53.274   875  2080 I ActivityManager: Killing 3675:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 18:23:54.321   875  2083 D WifiService: setWifiEnabled: true pid=3769, uid=10000
,09-08 18:23:54.321   875  2083 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:54.336   875  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 18:23:54.343  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:54.344  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:54.344  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:54.344  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:54.348  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:54.348  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:54.348  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:54.349  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:23:54.370   875  1311 D WifiConfigStore: loaded 0 passpoint configs
,09-08 18:23:54.371   875  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 18:23:54.372   875  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 18:23:54.373   875  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-08 18:23:54.373   875  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 18:23:54.373   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 18:23:54.373   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 18:23:54.395   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 18:23:54.396   373   873 D CommandListener: Setting iface cfg
,09-08 18:23:54.397   875  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.88 rxSuccessRate=11.00 delta 1000 -> 994
,09-08 18:23:54.397   875  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 18:23:54.397   875  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 18:23:54.400   875  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 18:23:54.401   875  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 18:23:54.422   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 18:23:54.423   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:54.428   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 18:23:54.472   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 18:23:54.475  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 18:23:54.900  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 18:23:54.938  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 18:23:54.939  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 18:23:54.944   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 18:23:54.961   875  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 18:23:54.962   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 18:23:54.964   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:54.999   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:55.019   373   873 D CommandListener: Setting iface cfg
,09-08 18:23:55.020   875  1311 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 18:23:55.042   875  1313 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-08 18:23:55.046   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 18:23:55.078   875  4028 D DhcpClient: Receive thread started
,09-08 18:23:55.161   875  1311 E native  : do suspend false
,09-08 18:23:55.182   875  2103 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 18:23:55.195   875  4028 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172703, domain null
,09-08 18:23:55.196   875  2103 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172703 seconds
,09-08 18:23:55.199   875  2103 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 18:23:55.214   875  4028 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 18:23:55.217   875  2103 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 18:23:55.222   373   873 D CommandListener: Setting iface cfg
,09-08 18:23:55.234   875  2103 D DhcpClient: Scheduling renewal in 86399s
,09-08 18:23:55.235   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 18:23:55.246   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 18:23:55.247   875  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 18:23:55.247   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:55.247   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 18:23:55.255   875  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 18:23:55.251   875  1313 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 18:23:55.302   875  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 18:23:55.302   875  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-08 18:23:55.306   875  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 18:23:55.309   875  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-08 18:23:55.311   875  1313 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 18:23:55.325   875  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 18:23:55.331   875  1313 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 18:23:55.332   875  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 18:23:55.332   875  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 18:23:55.332   875  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:55.332   875  1313 D ConnectivityService:    accepting network in place of null
09-08 18:23:55.333   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:23:55.334   875  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 18:23:55.353   875  4027 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121076, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:23:55.375   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:23:55.428   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:23:55.435   875  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 18:23:55.435   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:55.443   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:23:55.444   875  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-08 18:23:55.448  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:55.448  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:23:55.448  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:55.448  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:55.452  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:23:55.452  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:55.452  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:55.453  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:23:55.463   875  4026 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 18:23:55.469  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 18:23:55.472  1724  1724 D SystemUpdateService: onCreate
,09-08 18:23:55.476  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 18:23:55.479  1724  4038 I SystemUpdateService: active receiver: enabled
,09-08 18:23:55.482  1724  4038 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:23:55.485  1724  4038 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 18:23:55.485  1724  4038 I SystemUpdateService: now status is 0 (complete)
09-08 18:23:55.485  1724  4038 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 18:23:55.485  1724  4038 I SystemUpdateService: file has been verified
09-08 18:23:55.486  1724  4038 I SystemUpdateService: OTA package size = 12249756
,09-08 18:23:55.491  1724  4038 I SystemUpdateService: showing system update notification
,09-08 18:23:55.495  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 18:23:55.498  1724  2520 I iu.UploadsManager: num queued entries: 0
09-08 18:23:55.498  1724  2520 I iu.UploadsManager: num updated entries: 0
09-08 18:23:55.499  1724  2520 I iu.SyncManager: NEXT; no task
,09-08 18:23:55.501  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:23:55.503  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 18:23:55.504  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:55.505  1724  1724 D SystemUpdateService: onDestroy
,09-08 18:23:55.507  1724  4042 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 18:23:55.507  1724  4042 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:23:55.508  1724  4042 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 18:23:55.509  3926  3926 D SprintDMHelper: simOperator: 
09-08 18:23:55.509  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 18:23:55.514  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:23:55.516  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:23:55.545  1508  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 18:23:55.545  1508  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-08 18:23:55.545  1508  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:23:55.545  1508  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:23:55.568  1724  4042 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-08 18:23:55.577   875  4026 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:23:55 GMT], X-Android-Received-Millis=[1473351835576], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473351835509]}
,09-08 18:23:55.578   875  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 18:23:55.578   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 18:23:55.578   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 18:23:55.579   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 18:23:55.641  2278  4044 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 18:23:55.674  1508  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:23:55.674  1508  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:23:55.674  1508  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:23:55.674  1508  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:23:55.684  3540  4052 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 18:23:55.684  3540  4052 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at blb.a(PG:3937)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at czp.a(PG:18188)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at czp.a(PG:9087)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:23:55.684  3540  4052 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	... 12 more
09-08 18:23:55.684  3540  4052 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at fal.a(PG:38)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:23:55.684  3540  4052 E HttpOperation: 	... 14 more
,09-08 18:23:55.847  1508  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 18:23:55.847  1508  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-08 18:23:55.847  1508  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:23:55.847  1508  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:23:55.887  3540  4059 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 18:23:55.887  3540  4059 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at blb.a(PG:3937)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at czp.a(PG:18188)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:23:55.887  3540  4059 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	... 12 more
09-08 18:23:55.887  3540  4059 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at fal.a(PG:38)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:23:55.887  3540  4059 E HttpOperation: 	... 14 more
,09-08 18:23:55.916  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 18:23:55.916  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 18:23:55.916  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 18:23:55.916  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:23:55.929  3540  4059 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 18:23:55.929  3540  4059 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jdm.a(PG:82)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jcs.o(PG:406)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jcn.a(PG:1379)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jcs.i(PG:143)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at hec.a(PG:42)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at hee.a(PG:102)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at czr.a(PG:65)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at kka.a(PG:108)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at czp.a(PG:19176)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at czp.a(PG:9081)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at czq.run(PG:1686)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:23:55.929  3540  4059 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jdj.a(PG:4091)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jdj.a(PG:1125)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jdm.a(PG:77)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	... 15 more
09-08 18:23:55.929  3540  4059 E HttpOperation: Caused by: faj: BadAuthentication
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at fal.a(PG:38)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	at jdj.a(PG:4089)
09-08 18:23:55.929  3540  4059 E HttpOperation: 	... 17 more
,09-08 18:23:55.930  3540  4059 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 18:23:55.930  3540  4059 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at hec.a(PG:42)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at hee.a(PG:102)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at czr.a(PG:65)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at kka.a(PG:108)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	... 15 more
09-08 18:23:55.930  3540  4059 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at fal.a(PG:38)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 18:23:55.930  3540  4059 E ExperimentLoader: 	,... 17 more
,09-08 18:23:56.053   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 66503, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:23:56.437   875  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 18:23:57.079   875  1384 I ActivityManager: Killing 2125:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 18:23:57.330   875  1701 D WifiService: setWifiEnabled: false pid=3769, uid=10000
,09-08 18:23:57.330   875  1701 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:23:57.364  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 18:23:57.373   875  1311 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 18:23:57.373   875  1311 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-08 18:23:57.374   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:23:57.374   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:23:57.396   875  2103 D DhcpClient: Clearing IP address
,09-08 18:23:57.397   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:57.400   373   873 D CommandListener: Setting iface cfg
,09-08 18:23:57.404  1508  4056 V NativeCrypto: Read error: ssl=0x9acbf000: I/O error during system call, Connection timed out
,09-08 18:23:57.406  1508  4056 V NativeCrypto: SSL shutdown failed: ssl=0x9acbf000: I/O error during system call, Broken pipe
,09-08 18:23:57.408   875  2028 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-08 18:23:57.408   875  4026 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,09-08 18:23:57.409   875  4026 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 18:23:57.412   875  4028 D DhcpClient: Receive thread stopped
,09-08 18:23:57.418   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 18:23:57.419   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-08 18:23:57.424   875  1311 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-08 18:23:57.424   875  4026 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-08 18:23:57.425   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 18:23:57.425   402   402 E Parcel  : Reading a NULL string not supported here.
09-08 18:23:57.428   373   873 D CommandListener: Clearing all IP addresses on wlan0
,09-08 18:23:57.433   875  1313 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 18:23:57.434   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 18:23:57.436  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:57.437  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:57.437  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:57.437  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-08 18:23:57.438  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:57.438  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:23:57.438  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:57.438  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:23:57.440  1897  2325 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 18:23:57.452   875  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 18:23:57.468   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:23:57.493   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:23:57.495   875  1313 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 18:23:57.495   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:57.497   875   892 D Tethering: MasterInitialState.processMessage what=3
,09-08 18:23:57.501  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:57.501  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:23:57.503  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:23:57.503  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:23:57.508  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 18:23:57.511  1724  1724 D SystemUpdateService: onCreate
,09-08 18:23:57.514  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 18:23:57.521  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-08 18:23:57.527  1724  2520 I iu.UploadsManager: num queued entries: 0
,09-08 18:23:57.528  1724  4070 I SystemUpdateService: active receiver: enabled
,09-08 18:23:57.531  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:23:57.532  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 18:23:57.535  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:23:57.543  3926  3926 D SprintDMHelper: simOperator: 
,09-08 18:23:57.543  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 18:23:57.558   373   873 E Netd    : netlink response contains error (No such file or directory)
,09-08 18:23:57.559   875  1313 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 18:23:57.559   875  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 18:23:57.559  1724  2520 I iu.UploadsManager: num updated entries: 0
09-08 18:23:57.560  1724  2520 I iu.SyncManager: NEXT; no task
,09-08 18:23:57.563  1724  4070 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:23:57.563  2278  4074 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 18:23:57.571  1724  4070 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 18:23:57.571  1724  4070 I SystemUpdateService: now status is 0 (complete)
,09-08 18:23:57.572  1724  4070 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 18:23:57.572  1724  4070 I SystemUpdateService: file has been verified
09-08 18:23:57.572  1724  4070 I SystemUpdateService: OTA package size = 12249756
,09-08 18:23:57.592  3953  3953 I art     : Waiting for a blocking GC DisableMovingGc
,09-08 18:23:57.595  3953  3953 I art     : Starting a blocking GC DisableMovingGc
,09-08 18:23:57.600  1724  4070 I SystemUpdateService: showing system update notification
,09-08 18:23:57.628  1724  1724 D SystemUpdateService: onDestroy
,09-08 18:24:00.382   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f8085b:true
09-08 18:24:00.382  3912  3912 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 18:24:00.387  3912  3912 I bt_bluedroid: init
,09-08 18:24:00.388  3912  4077 I BluetoothAdapterState: Entering OffState
,09-08 18:24:00.392  3912  4078 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 18:24:00.392  3912  4078 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 18:24:00.392  3912  4078 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 18:24:00.392  3912  4078 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 18:24:00.393  3912  3912 I bt_bluedroid: get_profile_interface socket
,09-08 18:24:00.396  3912  3912 I bt_bluedroid: get_profile_interface sdp
,09-08 18:24:00.399  3912  4081 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-08 18:24:00.399  3912  3923 I bt_bluedroid: config_hci_snoop_log
,09-08 18:24:00.401   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-08 18:24:00.402  3912  4081 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:24:00.410  3912  4077 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 18:24:00.410  3912  4077 D BluetoothAdapterProperties: Setting state to 14
,09-08 18:24:00.411  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 18:24:00.415  3912  4077 D BluetoothBondStateMachine: make
,09-08 18:24:00.420  3912  4082 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 18:24:00.427  3912  4077 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:24:00.428  3912  3912 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 18:24:00.431  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:00.432  3912  3912 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:24:00.433  3912  3912 D BtGatt.GattService: Received start request. Starting profile...
,09-08 18:24:00.433  3912  3912 D BtGatt.GattService: start()
09-08 18:24:00.433  3912  3912 I bt_bluedroid: get_profile_interface gatt
09-08 18:24:00.434  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
09-08 18:24:00.435  3912  3912 D BtGatt.AdvertiseManager: advertise manager created
,09-08 18:24:00.446  3912  3912 V BluetoothAdapterState: isTurningOff()=false
09-08 18:24:00.446  3912  3912 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:24:00.446  3912  3912 V BluetoothAdapterState: isBleTurningOn()=true
09-08 18:24:00.446  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:00.447  3912  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 18:24:00.448  3912  4077 I bt_bluedroid: enable
,09-08 18:24:00.448  3912  4078 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 18:24:00.448  3912  4078 I bt_hci  : start_up
,09-08 18:24:00.457  3912  4078 I bt_vendor: alloc value 0xb3996189
,09-08 18:24:00.457  3912  4078 I bt_vendor: init
,09-08 18:24:00.458  3912  4078 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 18:24:00.458  3912  4078 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 18:24:00.568  3912  4078 D bt_hci  : start_up starting async portion
,09-08 18:24:00.569  3912  4085 I bt_hci  : event_finish_startup
09-08 18:24:00.569  3912  4085 I bt_hci_h4: hal_open
,09-08 18:24:00.569  3912  4085 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 18:24:00.579  3912  4085 I bt_userial_vendor: device fd = 51 open
,09-08 18:24:00.611  3912  4085 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:24:00.642  3912  4085 D bt_hwcfg: Chipset BCM4354A2
,09-08 18:24:00.643  3912  4085 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 18:24:00.643  3912  4085 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 18:24:01.311  3912  4085 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 18:24:01.312  3912  4085 D bt_hwcfg: Settlement delay -- 100 ms
,09-08 18:24:01.312  3912  4085 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 18:24:01.429  3912  4085 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:24:01.430  3912  4085 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 18:24:01.460  3912  4085 I bt_hwcfg: vendor lib fwcfg completed
,09-08 18:24:01.460  3912  4085 I bt_vendor: firmware callback
09-08 18:24:01.461  3912  4085 I bt_hci  : firmware_config_callback
,09-08 18:24:01.472  3912  4089 I bt_btu  : btu_task pending for preload complete event
,09-08 18:24:01.472  3912  4089 I bt_btu_task: Bluetooth chip preload is complete
09-08 18:24:01.473  3912  4089 I bt_btu  : btu_task received preload complete event
,09-08 18:24:01.482  3912  4089 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 18:24:01.483  3912  4089 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 18:24:01.483  3912  4089 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 18:24:01.483  3912  4089 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 18:24:01.484  3912  4089 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 18:24:01.484  3912  4089 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 18:24:01.484  3912  4089 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 18:24:01.485  3912  4089 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 18:24:01.485  3912  4089 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 18:24:01.485  3912  4089 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 18:24:01.485  3912  4089 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 18:24:01.486  3912  4089 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 18:24:01.486  3912  4089 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 18:24:01.486  3912  4089 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 18:24:01.487  3912  4089 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 18:24:01.622  3912  4089 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3913d9d
,09-08 18:24:01.623  3912  4089 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3913d9d 
,09-08 18:24:01.635  3912  4081 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 18:24:01.636  3912  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 18:24:01.637  3912  4081 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 18:24:01.642  3912  4081 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:24:01.647  3912  4081 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:24:01.647  3912  4081 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 18:24:01.648  3912  4081 D bt_hci  : do_postload posting postload work item
09-08 18:24:01.648  3912  4085 I bt_hci  : event_postload
09-08 18:24:01.648  3912  4085 I bt_vendor: sco_config_cb
,09-08 18:24:01.648  3912  4085 I bt_hci  : sco_config_callback postload finished.
,09-08 18:24:01.651  3912  4081 D bt_bte_conf: Device ID record 1 : primary
,09-08 18:24:01.651  3912  4081 D bt_bte_conf:   vendorId            = 000f
,09-08 18:24:01.651  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.651  3912  4081 D bt_bte_conf:   vendorIdSource      = 0001
09-08 18:24:01.652  3912  4081 D bt_bte_conf:   product             = 1200
09-08 18:24:01.652  3912  4081 D bt_bte_conf:   version             = 1436
09-08 18:24:01.652  3912  4081 D bt_bte_conf:   clientExecutableURL = 
,09-08 18:24:01.652  3912  4081 D bt_bte_conf:   serviceDescription  = 
09-08 18:24:01.652  3912  4081 D bt_bte_conf:   documentationURL    = 
09-08 18:24:01.653  3912  4081 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 18:24:01.653  3912  4078 D bt_stack_manager: event_start_up_stack finished
09-08 18:24:01.655  3912  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 18:24:01.656  3912  4077 D BluetoothAdapterProperties: Setting state to 15
09-08 18:24:01.656  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-08 18:24:01.659  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.660  3912  4085 I bt_vendor: low_power_mode_cb
,09-08 18:24:01.661  3912  4077 I BluetoothAdapterState: Entering BleOnState
,09-08 18:24:01.667  3912  4077 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 18:24:01.667  3912  4077 D BluetoothAdapterProperties: Setting state to 11
,09-08 18:24:01.667  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 18:24:01.674  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:01.675  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.676  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.677  3912  3912 D HeadsetService: Received start request. Starting profile...
,09-08 18:24:01.681  3912  3912 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 18:24:01.681  3912  3912 D HeadsetStateMachine: make
,09-08 18:24:01.688  3912  4077 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:24:01.689  3912  3912 D HeadsetStateMachine: max_hf_connections = 1
,09-08 18:24:01.689  3912  3912 I bt_bluedroid: get_profile_interface handsfree
09-08 18:24:01.690  3912  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 18:24:01.690  3912  4081 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-08 18:24:01.694  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:01.694  3912  3912 D A2dpService: Received start request. Starting profile...
,09-08 18:24:01.695  3912  3912 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-08 18:24:01.695  3912  3912 I bt_bluedroid: get_profile_interface avrcp
,09-08 18:24:01.701  3912  3912 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 18:24:01.702  3912  3912 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:24:01.702  3912  3912 D A2dpStateMachine: make
09-08 18:24:01.703  3912  3912 I bt_bluedroid: get_profile_interface a2dp
,09-08 18:24:01.703  3912  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 18:24:01.705  3912  4098 D A2dpStateMachine: Enter Disconnected: -2
,09-08 18:24:01.706  3912  3912 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 18:24:01.707  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
09-08 18:24:01.708  3912  3912 D HidService: Received start request. Starting profile...
09-08 18:24:01.708  3912  3912 I bt_bluedroid: get_profile_interface hidhost
09-08 18:24:01.708  3834  3834 D BluetoothInputDevice: Proxy object connected
09-08 18:24:01.708  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:24:01.709  3912  4081 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38f53e5
,09-08 18:24:01.709  3912  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 18:24:01.709  3912  3912 D HidService: setHidService(): set to: null
09-08 18:24:01.709  3834  3834 D HidProfile: Bluetooth service connected
,09-08 18:24:01.709  3912  3912 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 18:24:01.710  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
09-08 18:24:01.711  3912  3912 D HealthService: Received start request. Starting profile...
,09-08 18:24:01.712  3912  3912 I bt_bluedroid: get_profile_interface health
,09-08 18:24:01.713  3912  3912 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 18:24:01.713  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:01.714  3912  3912 D PanService: Received start request. Starting profile...
,09-08 18:24:01.714  3834  3834 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:24:01.714  3912  3912 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 18:24:01.714  3912  3912 I bt_bluedroid: get_profile_interface pan
,09-08 18:24:01.715  3834  3834 D PanProfile: Bluetooth service connected
09-08 18:24:01.715  3912  4081 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 18:24:01.718  3912  3912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:01.719  3834  3834 D BluetoothMap: Proxy object connected
,09-08 18:24:01.719  3912  3912 D BluetoothMapService: Received start request. Starting profile...
09-08 18:24:01.719  3912  3912 D BluetoothMapService: start()
09-08 18:24:01.720  3834  3834 D MapProfile: Bluetooth service connected
,09-08 18:24:01.720  3834  3834 D BluetoothMap: getConnectedDevices()
09-08 18:24:01.721  3834  3834 D BluetoothMap: Bluetooth is Not enabled
09-08 18:24:01.721  3912  3912 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 18:24:01.722  3912  3912 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 18:24:01.722  3912  3912 D BluetoothMapAppObserver: createReceiver()
,09-08 18:24:01.723  3912  3912 D BluetoothMapAppObserver: initObservers()
,09-08 18:24:01.723  3912  3912 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 18:24:01.729  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:01.729  3912  3912 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:01.729  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:01.729  3912  4096 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 18:24:01.729  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:01.730  3912  3912 V BluetoothAdapterState: isTurningOff()=false
09-08 18:24:01.731  3912  3912 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:01.731  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:24:01.731  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:01.731  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:01.731  3912  3912 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:24:01.731  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:01.731  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:01.733  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:01.733  3912  3912 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:01.733  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:01.733  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:01.734  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false,
09-08 18:24:01.734  3912  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 18:24:01.734  3912  4077 D BluetoothAdapterProperties: ScanMode =  20,
,09-08 18:24:01.734  3912  4077 D BluetoothAdapterProperties: State =  11
09-08 18:24:01.736  3912  4081 D BluetoothAdapterProperties: Scan Mode:21
,09-08 18:24:01.737  3912  4077 D BluetoothAdapterProperties: Setting state to 12
,09-08 18:24:01.737  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-08 18:24:01.737  3912  4081 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:24:01.737  3834  3845 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:24:01.738  3912  4077 I BluetoothAdapterState: Entering OnState
,09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:01.739  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:01.739  1367  2032 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:24:01.740  3834  3846 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:24:01.740  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:01.740  1367  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:01.741  1952  2171 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:01.742  1367  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:01.743  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 18:24:01.743   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:01.744  1367  2032 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:24:01.744  1367  1367 D BluetoothA2dp: Proxy object connected
09-08 18:24:01.745  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:01.745   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:01.746   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:01.746  1367  1367 D BluetoothMap: Proxy object connected
09-08 18:24:01.746  1367  1367 D MapProfile: Bluetooth service connected
09-08 18:24:01.746  1367  1367 D BluetoothMap: getConnectedDevices()
09-08 18:24:01.746   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:01.746   875   875 D BluetoothA2dp: Proxy object connected
09-08 18:24:01.746  3834  3845 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 18:24:01.747  3834  3846 D BluetoothPan: onBluetoothStateChange on: true
09-08 18:24:01.747  1367  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 18:24:01.749  1367  1367 D BluetoothInputDevice: Proxy object connected
09-08 18:24:01.749  3912  3912 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 18:24:01.749  1367  1367 D HidProfile: Bluetooth service connected
09-08 18:24:01.749  3912  3912 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 18:24:01.750  1367  2032 D BluetoothPan: onBluetoothStateChange on: true
09-08 18:24:01.751  3912  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:24:01.751  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:24:01.751  1367  1367 D PanProfile: Bluetooth service connected
09-08 18:24:01.752   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 18:24:01.754  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.755  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:01.755  3912  3912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 18:24:01.757  3834  3834 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 18:24:01.757  3912  3912 D ObexServerSockets: Succeed to create listening sockets 
09-08 18:24:01.757  3912  3912 D ObexServerSockets0: startAccept()
09-08 18:24:01.758  3912  3912 D ObexServerSockets0: prepareForNewCo,nnect()
09-08 18:24:01.760  3834  3834 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-08 18:24:01.760  3912  3912 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 18:24:01.761  3912  3912 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 18:24:01.761  3912  4104 D ObexServerSockets0: Accepting socket connection...
09-08 18:24:01.761  3912  3912 D BluetoothMapService: onReceive
09-08 18:24:01.761  3912  3912 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:01.761  3912  3912 D BluetoothMapService: STATE_ON
09-08 18:24:01.762  3912  4105 D ObexServerSockets0: Accepting socket connection...
09-08 18:24:01.766  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:24:01.772  3834  3834 D BluetoothA2dp: Proxy object connected
,09-08 18:24:01.776  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:24:01.782  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:24:01.789  3834  3834 D BluetoothPbap: Proxy object connected
,09-08 18:24:01.789  1367  1367 D BluetoothPbap: Proxy object connected
09-08 18:24:01.789  1367  1367 D PbapServerProfile: Bluetooth service connected
09-08 18:24:01.789  3834  3834 D PbapServerProfile: Bluetooth service connected
,09-08 18:24:01.795  3912  3912 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 18:24:01.796  3912  3912 D ObexServerSockets0: prepareForNewConnect()
,09-08 18:24:01.799  3912  4109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:01.819  3912  4113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:01.821  3912  4113 I BtOppRfcommListener: Accept thread started.
,09-08 18:24:01.842   875   875 D BluetoothHeadset: Proxy object connected
,09-08 18:24:01.842  1952  1976 D BluetoothHeadset: Proxy object connected
,09-08 18:24:01.843  1367  1383 D BluetoothHeadset: Proxy object connected
,09-08 18:24:01.843  1367  1367 D HeadsetProfile: Bluetooth service connected
09-08 18:24:01.843   875   875 D BluetoothHeadset: Proxy object connected
09-08 18:24:01.843   875   875 D BluetoothHeadset: Proxy object connected
09-08 18:24:01.843   875   892 D BluetoothHeadset: Proxy object connected
,09-08 18:24:01.846   875   892 D BluetoothHeadset: Proxy object connected
,09-08 18:24:01.847   875   892 D BluetoothHeadset: Proxy object connected
,09-08 18:24:01.863  3834  3845 D BluetoothHeadset: Proxy object connected
,09-08 18:24:01.865  3834  3834 D HeadsetProfile: Bluetooth service connected
,09-08 18:24:03.338   875  1313 D ConnectivityService: handlePromptUnvalidated 101
,09-08 18:24:03.348  3912  4077 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 18:24:03.348  3912  4077 D BluetoothAdapterProperties: Setting state to 13
,09-08 18:24:03.348  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-08 18:24:03.351  3912  4077 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 18:24:03.353  3912  4077 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:24:03.363  3912  3912 D BluetoothMapService: onReceive
,09-08 18:24:03.363  3912  3912 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 18:24:03.364  3912  3912 D BluetoothMapService: STATE_TURNING_OFF
,09-08 18:24:03.365  3912  3912 D BluetoothMapService: MAP Service closeService in
09-08 18:24:03.365  3912  3912 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 18:24:03.366  3912  3912 D ObexServerSockets0: shutdown(block = true)
,09-08 18:24:03.367  3912  4104 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 18:24:03.367  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:03.367  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:03.370  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:24:03.370  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:03.370  3912  3912 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 18:24:03.371  3912  4105 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-08 18:24:03.376  3912  4081 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:24:03.377  3912  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-08 18:24:03.378  3912  4091 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-08 18:24:03.379  3912  3912 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 18:24:03.380  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:03.380  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:03.380  3912  3912 I BtOppRfcommListener: stopping Accept Thread
09-08 18:24:03.381  3912  4113 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 18:24:03.381  3912  4113 I BtOppRfcommListener: BluetoothSocket listen thread finished,
09-08 18:24:03.382  3769  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 18:24:03.382  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:03.383  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:24:03.385  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:03.387  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:03.390  3912  3912 D HeadsetService: Received stop request...Stopping profile...
,09-08 18:24:03.391   875   875 D BluetoothHeadset: Proxy object disconnected
09-08 18:24:03.391  1952  2114 D BluetoothHeadset: Proxy object disconnected
,09-08 18:24:03.392  1367  2032 D BluetoothHeadset: Proxy object disconnected
,09-08 18:24:03.392  1367  1367 D HeadsetProfile: Bluetooth service disconnected
09-08 18:24:03.392   875   875 D BluetoothHeadset: Proxy object disconnected
,09-08 18:24:03.392  3912  3912 D A2dpService: Received stop request...Stopping profile...
,09-08 18:24:03.393  3912  4098 D A2dpStateMachine: Exit Disconnected: -1
09-08 18:24:03.394  3834  3845 D BluetoothHeadset: Proxy object disconnected,
,09-08 18:24:03.395   875   875 D BluetoothHeadset: Proxy object disconnected
09-08 18:24:03.395   875   875 D BluetoothA2dp: Proxy object disconnected
09-08 18:24:03.395  1367  1367 D BluetoothA2dp: Proxy object disconnected
09-08 18:24:03.396  3912  3912 D HidService: Received stop request...Stopping profile...
,09-08 18:24:03.396  3912  3912 D HidService: Stopping Bluetooth HidService
09-08 18:24:03.397  1367  1367 D BluetoothInputDevice: Proxy object disconnected
,09-08 18:24:03.397  1367  1367 D HidProfile: Bluetooth service disconnected
09-08 18:24:03.400  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 18:24:03.402  3912  3912 D HealthService: Received stop request...Stopping profile...
,09-08 18:24:03.403  3834  3834 D DockEventReceiver: finishStartingService: stopping service
09-08 18:24:03.403  3912  3912 V BluetoothAdapterState: isTurningOff()=true
09-08 18:24:03.403  3912  3912 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:24:03.403  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:03.403  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:03.404  3834  3834 D HeadsetProfile: Bluetooth service disconnected
09-08 18:24:03.404  3834  3834 D BluetoothA2dp: Proxy object disconnected
,09-08 18:24:03.405  3834  3834 D BluetoothInputDevice: Proxy object disconnected
09-08 18:24:03.405  3912  3912 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 18:24:03.405  3834  3834 D HidProfile: Bluetooth service disconnected
,09-08 18:24:03.405  3912  3912 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-08 18:24:03.405  3912  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-08 18:24:03.405  3912  4089 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 18:24:03.405  3912  4089 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:24:03.405  3912  3912 D PanService: Received stop request...Stopping profile...
,09-08 18:24:03.405  3912  4089 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:24:03.406  3912  4081 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885,
,09-08 18:24:03.408  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:24:03.408  1367  1367 D PanProfile: Bluetooth service disconnected
09-08 18:24:03.408  3912  3912 D BluetoothMapService: Received stop request...Stopping profile...
09-08 18:24:03.408  3912  3912 D BluetoothMapService: stop()
,09-08 18:24:03.409  3834  3834 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 18:24:03.409  3834  3834 D PanProfile: Bluetooth service disconnected
,09-08 18:24:03.409  3912  3912 D BluetoothMapAppObserver: deinitObservers()
09-08 18:24:03.409  3912  3912 D BluetoothMapAppObserver: removeReceiver()
09-08 18:24:03.411  1367  1367 D BluetoothMap: Proxy object disconnected
09-08 18:24:03.411  1367  1367 D MapProfile: Bluetooth service disconnected
,09-08 18:24:03.411  3912  3912 V BluetoothAdapterState: isTurningOff()=true
09-08 18:24:03.411  3912  3912 V BluetoothAdapterState: isTurningOn()=false
09-08 18:24:03.411  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:03.411  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:03.411  3834  3834 D BluetoothMap: Proxy object disconnected
09-08 18:24:03.411  3834  3834 D MapProfile: Bluetooth service disconnected
09-08 18:24:03.412  3912  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-08 18:24:03.412  3912  4089 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:24:03.412  3912  4089 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:24:03.412  3912  4089 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 18:24:03.412  3912  3912 V BluetoothAdapterState: isTurningOff()=true
,09-08 18:24:03.412  3912  4089 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:24:03.412  3912  3912 V BluetoothAdapterState: isTurningOn()=false
09-08 18:24:03.412  3912  4089 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-08 18:24:03.412  3912  4089 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 18:24:03.412  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:03.413  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:03.413  3912  3912 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...,
09-08 18:24:03.413  3912  4081 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 18:24:03.413  3912  3912 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 18:24:03.416  1367  1367 D BluetoothPbap: Proxy object disconnected
09-08 18:24:03.416  1367  1367 D PbapServerProfile: Bluetooth service disconnected
09-08 18:24:03.419  3912  3912 V BluetoothAdapterState: isTurningOff()=true
,09-08 18:24:03.419  3912  3912 V BluetoothAdapterState: isTurningOn()=false
09-08 18:24:03.419  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:03.419  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:03.419  3912  3912 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-08 18:24:03.419  3912  4081 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 18:24:03.420  3912  3912 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 18:24:03.420  3912  3912 V BluetoothAdapterState: isTurningOff()=true
09-08 18:24:03.420  3912  3912 V BluetoothAdapterState: isTurningOn()=false
09-08 18:24:03.420  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:24:03.420  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:03.421  3912  3912 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 18:24:03.421  3912  3912 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 18:24:03.422  3912  3912 D BluetoothMapService: MAP Service closeService in
09-08 18:24:03.422  3912  3912 V BluetoothAdapterState: isTurningOff()=true
,09-08 18:24:03.422  3912  3912 V BluetoothAdapterState: isTurningOn()=false
09-08 18:24:03.422  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:03.422  3912  3912 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:03.422  3912  3912 D BluetoothMapService: cleanup()
,09-08 18:24:03.422  3912  3912 D BluetoothMapService: MAP Service closeService in
09-08 18:24:03.423  3912  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 18:24:03.423  3912  4077 D BluetoothAdapterProperties: Setting state to 15
,09-08 18:24:03.423  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 18:24:03.423  3912  4077 I BluetoothAdapterState: Entering BleOnState
09-08 18:24:03.425  3834  3845 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 18:24:03.425  1367  2032 D BluetoothPbap: onBluetoothStateChange: up=false
,09-08 18:24:03.426  3834  3846 D BluetoothMap: onBluetoothStateChange: up=false
09-08 18:24:03.427  1367  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:24:03.427  1952  1969 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:24:03.427  1367  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:24:03.427   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:24:03.428  1367  2032 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 18:24:03.428   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:24:03.428   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:24:03.428   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 18:24:03.428  3834  3845 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 18:24:03.429  3834  3846 D BluetoothPan: onBluetoothStateChange on: false
,09-08 18:24:03.429  1367  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 18:24:03.430  1367  1383 D BluetoothPan: onBluetoothStateChange on: false
09-08 18:24:03.430  3834  3845 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 18:24:03.431  3834  3846 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 18:24:03.431  3912  4077 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 18:24:03.431  3912  4077 D BluetoothAdapterProperties: Setting state to 16
09-08 18:24:03.431  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 18:24:03.432  3912  4077 D BluetoothAdapterProperties: onBleDisable
09-08 18:24:03.434  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.434  3912  4078 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 18:24:03.435  3912  4077 I BluetoothAdapterState: Entering PendingCommandState
09-08 18:24:03.435  3912  4081 D BluetoothAdapterProperties: Scan Mode:20
09-08 18:24:03.435  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.435  3912  4089 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 18:24:03.435  3912  4089 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 18:24:03.436  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:24:03.438  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:03.439  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:03.442  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:24:03.446  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:24:03.636  3912  4081 I bt_hci  : shut_down
,09-08 18:24:03.651  3912  4085 D bt_hwcfg: hw_epilog_process
,09-08 18:24:03.652  3912  4085 I bt_vendor: low_power_mode_cb
,09-08 18:24:03.678  3912  4085 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 18:24:03.679  3912  4085 I bt_vendor: epilog_cb
,09-08 18:24:03.679  3912  4085 I bt_hci  : epilog_finished_callback
,09-08 18:24:03.688  3912  4081 I bt_hci_h4: hal_close
,09-08 18:24:03.689  3912  4081 I bt_userial_vendor: device fd = 51 close
,09-08 18:24:03.813  3912  4078 D bt_stack_manager: event_shut_down_stack finished.
,09-08 18:24:03.814  3912  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 18:24:03.819  3912  4077 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 18:24:03.821  3912  3912 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:24:03.822  3912  3912 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 18:24:03.822  3912  3912 D BtGatt.GattService: stop()
09-08 18:24:03.823  3912  3912 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 18:24:03.828  3912  3912 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:03.828  3912  3912 V BluetoothAdapterState: isTurningOn()=false
,09-08 18:24:03.829  3912  3912 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:24:03.829  3912  3912 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 18:24:03.830  3912  4077 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 18:24:03.831  3912  4077 D BluetoothAdapterProperties: Setting state to 10
09-08 18:24:03.831  3912  4077 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-08 18:24:03.833  3912  4077 I BluetoothAdapterState: Entering OffState
09-08 18:24:03.834   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 18:24:03.853  3912  3912 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 18:24:03.853  3912  3912 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-08 18:24:03.853  3912  4078 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-08 18:24:03.854  3912  3912 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 18:24:03.857  3912  4078 D bt_stack_manager: event_clean_up_stack finished.
,09-08 18:24:03.859  3912  3912 I art     : System.exit called, status: 0
,09-08 18:24:03.859  3912  3912 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 18:24:03.895   875  2085 I ActivityManager: Process com.android.bluetooth (pid 3912) has died
,09-08 18:24:06.345  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:24:06.345  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:09.354  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:09.354  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@89ac23e added. We now have 6 listener(s)
,09-08 18:24:09.355  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:09.360  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:09.361  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b07c89f added. We now have 7 listener(s)
,09-08 18:24:09.362  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:09.363  3769  3820 I System.out: IsBluetoothEnabled
,09-08 18:24:09.377  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:09.404   875   892 I ActivityManager: Start proc 4124:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 18:24:09.542  4124  4124 D AdapterServiceConfig: Adding HeadsetService
09-08 18:24:09.543  4124  4124 D AdapterServiceConfig: Adding A2dpService
,09-08 18:24:09.543  4124  4124 D AdapterServiceConfig: Adding HidService
09-08 18:24:09.543  4124  4124 D AdapterServiceConfig: Adding HealthService
09-08 18:24:09.543  4124  4124 D AdapterServiceConfig: Adding PanService
09-08 18:24:09.543  4124  4124 D AdapterServiceConfig: Adding GattService
09-08 18:24:09.544  4124  4124 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 18:24:09.560   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6bbbaff:true
,09-08 18:24:09.561  4124  4124 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 18:24:09.565  4124  4124 I bt_bluedroid: init
,09-08 18:24:09.565  4124  4136 I BluetoothAdapterState: Entering OffState
,09-08 18:24:09.571  4124  4137 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 18:24:09.572  4124  4137 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 18:24:09.572  4124  4137 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 18:24:09.572  4124  4137 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 18:24:09.574  4124  4124 I bt_bluedroid: get_profile_interface socket
,09-08 18:24:09.577  4124  4124 I bt_bluedroid: get_profile_interface sdp
,09-08 18:24:09.581  4124  4135 I bt_bluedroid: config_hci_snoop_log
,09-08 18:24:09.585  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 18:24:09.586   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 18:24:09.586  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:24:09.595  4124  4136 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 18:24:09.595  4124  4136 D BluetoothAdapterProperties: Setting state to 14
09-08 18:24:09.596  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 18:24:09.598  4124  4136 D BluetoothBondStateMachine: make
,09-08 18:24:09.602  4124  4142 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 18:24:09.609  4124  4124 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-08 18:24:09.609  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:24:09.614  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:09.615  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 18:24:09.616  4124  4124 D BtGatt.GattService: Received start request. Starting profile...
09-08 18:24:09.616  4124  4124 D BtGatt.GattService: start()
09-08 18:24:09.616  4124  4124 I bt_bluedroid: get_profile_interface gatt
,09-08 18:24:09.617  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
09-08 18:24:09.617  4124  4124 D BtGatt.AdvertiseManager: advertise manager created
,09-08 18:24:09.624  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:09.625  4124  4124 V BluetoothAdapterState: isTurningOn()=false
09-08 18:24:09.625  4124  4124 V BluetoothAdapterState: isBleTurningOn()=true
,09-08 18:24:09.625  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:09.625  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 18:24:09.628  4124  4136 I bt_bluedroid: enable
,09-08 18:24:09.628  4124  4137 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 18:24:09.629  4124  4137 I bt_hci  : start_up
,09-08 18:24:09.642  4124  4137 I bt_vendor: alloc value 0xb39a6189
,09-08 18:24:09.642  4124  4137 I bt_vendor: init
09-08 18:24:09.642  4124  4137 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-08 18:24:09.643  4124  4137 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 18:24:09.751  4124  4137 D bt_hci  : start_up starting async portion
,09-08 18:24:09.752  4124  4145 I bt_hci  : event_finish_startup
09-08 18:24:09.752  4124  4145 I bt_hci_h4: hal_open
09-08 18:24:09.752  4124  4145 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 18:24:09.760  4124  4145 I bt_userial_vendor: device fd = 51 open
,09-08 18:24:09.793  4124  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:24:09.825  4124  4145 D bt_hwcfg: Chipset BCM4354A2
09-08 18:24:09.826  4124  4145 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 18:24:09.826  4124  4145 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 18:24:10.506  4124  4145 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 18:24:10.507  4124  4145 D bt_hwcfg: Settlement delay -- 100 ms
,09-08 18:24:10.507  4124  4145 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 18:24:10.624  4124  4145 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 18:24:10.625  4124  4145 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 18:24:10.655  4124  4145 I bt_hwcfg: vendor lib fwcfg completed
,09-08 18:24:10.655  4124  4145 I bt_vendor: firmware callback
,09-08 18:24:10.656  4124  4145 I bt_hci  : firmware_config_callback
,09-08 18:24:10.669  4124  4147 I bt_btu  : btu_task pending for preload complete event
,09-08 18:24:10.669  4124  4147 I bt_btu_task: Bluetooth chip preload is complete
09-08 18:24:10.670  4124  4147 I bt_btu  : btu_task received preload complete event
,09-08 18:24:10.680  4124  4147 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 18:24:10.680  4124  4147 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 18:24:10.681  4124  4147 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-08 18:24:10.681  4124  4147 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-08 18:24:10.681  4124  4147 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 18:24:10.682  4124  4147 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 18:24:10.682  4124  4147 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-08 18:24:10.682  4124  4147 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 18:24:10.682  4124  4147 I         : BTE_InitTraceLevels -- TRC_GAP
,09-08 18:24:10.683  4124  4147 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 18:24:10.683  4124  4147 I         : BTE_InitTraceLevels -- TRC_SDP
,09-08 18:24:10.683  4124  4147 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 18:24:10.683  4124  4147 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 18:24:10.684  4124  4147 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 18:24:10.684  4124  4147 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 18:24:10.819  4124  4147 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3923d9d
,09-08 18:24:10.820  4124  4147 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3923d9d 
,09-08 18:24:10.830  4124  4140 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 18:24:10.832  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 18:24:10.833  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 18:24:10.836  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 18:24:10.840  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
,09-08 18:24:10.840  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:24:10.840  4124  4140 D bt_hci  : do_postload posting postload work item
,09-08 18:24:10.841  4124  4145 I bt_hci  : event_postload
09-08 18:24:10.841  4124  4145 I bt_vendor: sco_config_cb
09-08 18:24:10.841  4124  4145 I bt_hci  : sco_config_callback postload finished.
09-08 18:24:10.845  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:10.847  4124  4145 I bt_vendor: low_power_mode_cb
,09-08 18:24:10.848  4124  4140 D bt_bte_conf: Device ID record 1 : primary
,09-08 18:24:10.848  4124  4140 D bt_bte_conf:   vendorId            = 000f
09-08 18:24:10.848  4124  4140 D bt_bte_conf:   vendorIdSource      = 0001
09-08 18:24:10.848  4124  4140 D bt_bte_conf:   product             = 1200
,09-08 18:24:10.849  4124  4140 D bt_bte_conf:   version             = 1436
,09-08 18:24:10.849  4124  4140 D bt_bte_conf:   clientExecutableURL = 
09-08 18:24:10.849  4124  4140 D bt_bte_conf:   serviceDescription  = 
09-08 18:24:10.849  4124  4140 D bt_bte_conf:   documentationURL    = 
,09-08 18:24:10.850  4124  4140 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-08 18:24:10.850  4124  4137 D bt_stack_manager: event_start_up_stack finished
09-08 18:24:10.852  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 18:24:10.853  4124  4136 D BluetoothAdapterProperties: Setting state to 15
09-08 18:24:10.853  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 18:24:10.854  4124  4136 I BluetoothAdapterState: Entering BleOnState
,09-08 18:24:10.862  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 18:24:10.863  4124  4136 D BluetoothAdapterProperties: Setting state to 11
,09-08 18:24:10.863  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 18:24:10.870  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:10.874  4124  4124 D HeadsetService: Received start request. Starting profile...
,09-08 18:24:10.879  4124  4124 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 18:24:10.879  4124  4124 D HeadsetStateMachine: make
09-08 18:24:10.880  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:10.891  4124  4124 D HeadsetStateMachine: max_hf_connections = 1
,09-08 18:24:10.891  4124  4124 I bt_bluedroid: get_profile_interface handsfree
,09-08 18:24:10.892  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 18:24:10.892  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 18:24:10.894  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,09-08 18:24:10.899  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:10.899  4124  4124 D A2dpService: Received start request. Starting profile...
,09-08 18:24:10.901  4124  4124 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 18:24:10.901  4124  4124 I bt_bluedroid: get_profile_interface avrcp
,09-08 18:24:10.910  4124  4124 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 18:24:10.910  4124  4124 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 18:24:10.910  4124  4124 D A2dpStateMachine: make
,09-08 18:24:10.912  4124  4124 I bt_bluedroid: get_profile_interface a2dp
,09-08 18:24:10.913  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 18:24:10.916  4124  4124 I BluetoothHidServiceJni: classInitNative: succeeds
09-08 18:24:10.917  4124  4155 D A2dpStateMachine: Enter Disconnected: -2
09-08 18:24:10.917  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:10.918  4124  4124 D HidService: Received start request. Starting profile...
09-08 18:24:10.918  4124  4124 I bt_bluedroid: get_profile_interface hidhost
09-08 18:24:10.918  4124  4140 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39053e5
09-08 18:24:10.918  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-08 18:24:10.919  4124  4124 D HidService: setHidService(): set to: null
09-08 18:24:10.920  4124  4124 I BluetoothHealthServiceJni: classInitNative: succeeds
09-08 18:24:10.921  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
09-08 18:24:10.922  4124  4124 D HealthService: Received start request. Starting profile...
,09-08 18:24:10.925  4124  4124 I bt_bluedroid: get_profile_interface health
,09-08 18:24:10.929  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:24:10.931  4124  4124 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 18:24:10.932  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:10.933  4124  4124 D PanService: Received start request. Starting profile...
,09-08 18:24:10.934  4124  4124 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-08 18:24:10.934  4124  4124 I bt_bluedroid: get_profile_interface pan
,09-08 18:24:10.935  4124  4140 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
,09-08 18:24:10.941  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:10.943  4124  4124 D BluetoothMapService: Received start request. Starting profile...
,09-08 18:24:10.943  4124  4124 D BluetoothMapService: start()
,09-08 18:24:10.947  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 18:24:10.948  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 18:24:10.949  4124  4124 D BluetoothMapAppObserver: createReceiver()
,09-08 18:24:10.950  4124  4124 D BluetoothMapAppObserver: initObservers()
,09-08 18:24:10.951  4124  4124 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 18:24:10.962  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:10.962  4124  4124 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:10.962  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:10.962  4124  4153 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 18:24:10.962  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:10.964  4124  4124 V BluetoothAdapterState: isTurningOff()=false
09-08 18:24:10.964  4124  4124 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:10.964  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:10.964  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isTurningOff()=false
09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isTurningOff()=false
09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isTurningOn()=true
09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:10.965  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:10.967  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,09-08 18:24:10.967  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:24:10.968  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 18:24:10.968  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
09-08 18:24:10.968  4124  4124 V BluetoothAdapterState: isTurningOff()=false
09-08 18:24:10.968  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,09-08 18:24:10.968  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
09-08 18:24:10.968  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 18:24:10.968  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 18:24:10.968  4124  4136 D BluetoothAdapterProperties: ScanMode =  20
09-08 18:24:10.969  4124  4136 D BluetoothAdapterProperties: State =  11
09-08 18:24:10.971  4124  4140 D BluetoothAdapterProperties: Scan Mode:21
,09-08 18:24:10.971  4124  4136 D BluetoothAdapterProperties: Setting state to 12
,09-08 18:24:10.972  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 18:24:10.972  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 18:24:10.972  4124  4136 I BluetoothAdapterState: Entering OnState
09-08 18:24:10.972  3834  3846 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:24:10.974  1367  2032 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:10.975  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:10.976  3834  3845 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:24:10.977  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 18:24:10.977  1367  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:10.978  1952  2171 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:10.979  1367  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:10.981   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:10.981  1367  2032 D BluetoothMap: onBluetoothStateChange: up=true
09-08 18:24:10.982  3834  3834 D BluetoothMap: Proxy object connected
09-08 18:24:10.982  3834  3834 D MapProfile: Bluetooth service connected
09-08 18:24:10.982  1367  1367 D BluetoothA2dp: Proxy object connected
09-08 18:24:10.982  3834  3834 D BluetoothMap: getConnectedDevices()
09-08 18:24:10.984   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:10.984  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 18:24:10.984   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:10.984  1367  1367 D BluetoothMap: Proxy object connected
09-08 18:24:10.984  1367  1367 D MapProfile: Bluetooth service connected
09-08 18:24:10.984  1367  1367 D BluetoothMap: getConnectedDevices()
09-08 18:24:10.984   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:10.984   875   875 D BluetoothA2dp: Proxy object connected
09-08 18:24:10.984  4124  4124 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-08 18:24:10.985  3834  3845 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-08 18:24:10.987  3834  3846 D BluetoothPan: onBluetoothStateChange on: true
,09-08 18:24:10.989  1367  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 18:24:10.989  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback,
,09-08 18:24:10.990  1367  1383 D BluetoothPan: onBluetoothStateChange on: true
,09-08 18:24:10.993  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:10.993  3834  3845 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 18:24:10.994  4124  4124 D ObexServerSockets: Succeed to create listening sockets 
,09-08 18:24:10.994  4124  4124 D ObexServerSockets0: startAccept()
09-08 18:24:10.994  4124  4124 D ObexServerSockets0: prepareForNewConnect()
,09-08 18:24:10.995  3834  3846 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 18:24:10.996   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,09-08 18:24:10.998  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:10.996  3834  3834 D BluetoothA2dp: Proxy object connected
09-08 18:24:10.999  4124  4124 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 18:24:10.999  4124  4124 D BluetoothSdpJni: SDP Create record success - handle: 0,
09-08 18:24:11.000  4124  4162 D ObexServerSockets0: Accepting socket connection...
,09-08 18:24:11.001  4124  4163 D ObexServerSockets0: Accepting socket connection...
09-08 18:24:11.002  1367  1367 D BluetoothInputDevice: Proxy object connected
09-08 18:24:11.002  1367  1367 D HidProfile: Bluetooth service connected
,09-08 18:24:11.003  4124  4124 D BluetoothMapService: onReceive
09-08 18:24:11.003  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 18:24:11.003  4124  4124 D BluetoothMapService: STATE_ON
,09-08 18:24:11.005  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 18:24:11.005  1367  1367 D PanProfile: Bluetooth service connected
,09-08 18:24:11.009  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 18:24:11.013  3834  3834 D BluetoothInputDevice: Proxy object connected
,09-08 18:24:11.013  3834  3834 D HidProfile: Bluetooth service connected
,09-08 18:24:11.022  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 18:24:11.026  3834  3834 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 18:24:11.028  3834  3834 D PanProfile: Bluetooth service connected
,09-08 18:24:11.029  1367  1367 D BluetoothPbap: Proxy object connected
09-08 18:24:11.029  1367  1367 D PbapServerProfile: Bluetooth service connected
09-08 18:24:11.029  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 18:24:11.030  4124  4124 D ObexServerSockets0: prepareForNewConnect()
,09-08 18:24:11.035  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-08 18:24:11.035  3834  3834 D BluetoothPbap: Proxy object connected
,09-08 18:24:11.035  3834  3834 D PbapServerProfile: Bluetooth service connected
09-08 18:24:11.044  4124  4168 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:11.058  4124  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 18:24:11.059  4124  4172 I BtOppRfcommListener: Accept thread started.
,09-08 18:24:11.079   875   875 D BluetoothHeadset: Proxy object connected
,09-08 18:24:11.080  1952  1976 D BluetoothHeadset: Proxy object connected
09-08 18:24:11.080  1367  1383 D BluetoothHeadset: Proxy object connected
09-08 18:24:11.080  1367  1367 D HeadsetProfile: Bluetooth service connected
09-08 18:24:11.080   875   875 D BluetoothHeadset: Proxy object connected
,09-08 18:24:11.081  3834  3846 D BluetoothHeadset: Proxy object connected
09-08 18:24:11.081   875   875 D BluetoothHeadset: Proxy object connected
09-08 18:24:11.082   875   892 D BluetoothHeadset: Proxy object connected
09-08 18:24:11.082  3834  3834 D HeadsetProfile: Bluetooth service connected
09-08 18:24:11.084   875   892 D BluetoothHeadset: Proxy object connected
09-08 18:24:11.084   875   892 D BluetoothHeadset: Proxy object connected
,09-08 18:24:11.095  3834  3845 D BluetoothHeadset: Proxy object connected
,09-08 18:24:11.095  3834  3834 D HeadsetProfile: Bluetooth service connected
,09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:11.397  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:11.405  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:11.409  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 18:24:11.410  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6b0dec added. We now have 8 listener(s)
,09-08 18:24:11.410  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:11.416   875  1701 D WifiService: setWifiEnabled: false pid=3769, uid=10000
,09-08 18:24:11.417   875  1701 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:24:11.429  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:11.431   875  2083 D WifiService: setWifiEnabled: true pid=3769, uid=10000
,09-08 18:24:11.431   875  2083 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 18:24:11.443   875  1311 D WifiConfigStore: Loading config and enabling all networks 
,09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 18:24:11.465  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 18:24:11.471  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 18:24:11.473   875  1311 D WifiConfigStore: loaded 0 passpoint configs
,09-08 18:24:11.474   875  1311 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-08 18:24:11.475   875  1311 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-08 18:24:11.476   875  1311 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 18:24:11.476   875  1311 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 18:24:11.476   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 18:24:11.476   875  1311 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 18:24:11.490   373   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 18:24:11.492   373   873 D CommandListener: Setting iface cfg
,09-08 18:24:11.492   875  1311 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.66 rxSuccessRate=0.89 delta 1000 -> 1000,
,09-08 18:24:11.493   875  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-08 18:24:11.493   875  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-08 18:24:11.495   875  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 18:24:11.496   875  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 18:24:11.510   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 18:24:11.510   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:24:11.516   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 18:24:11.555   875  1311 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 18:24:11.557  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 18:24:12.030  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 18:24:12.072  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 18:24:12.074  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
09-08 18:24:12.078   875  1311 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 18:24:12.085   875  1311 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 18:24:12.085   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-08 18:24:12.086   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 18:24:12.107   875  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 18:24:12.117   373   873 D CommandListener: Setting iface cfg
,09-08 18:24:12.119   875  1311 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 18:24:12.131   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 18:24:12.131   875  1313 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-08 18:24:12.132   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 18:24:12.157   875  4180 D DhcpClient: Receive thread started
,09-08 18:24:12.240   875  1311 E native  : do suspend false
,09-08 18:24:12.260   875  2103 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 18:24:12.295   875  4180 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-08 18:24:12.296   875  2103 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-08 18:24:12.300   875  2103 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 18:24:12.312   875  4180 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 18:24:12.314   875  2103 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 18:24:12.319   373   873 D CommandListener: Setting iface cfg
,09-08 18:24:12.330   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 18:24:12.333   875  2103 D DhcpClient: Scheduling renewal in 86399s
,09-08 18:24:12.341   875  1311 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 18:24:12.342   875  1311 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 18:24:12.342   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 18:24:12.348   875  1313 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 18:24:12.350   875  1311 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 18:24:12.402   875  1313 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 18:24:12.402   875  1313 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-08 18:24:12.403   875  1313 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 18:24:12.404   875  1313 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 18:24:12.406   875  1313 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 18:24:12.416   875  1313 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 18:24:12.422   875  1313 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 18:24:12.422   875  1313 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-08 18:24:12.423   875  1313 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 18:24:12.423   875  1311 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 18:24:12.423   875  1313 D ConnectivityService:    accepting network in place of null
,09-08 18:24:12.424   875  1311 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 18:24:12.424   875  1313 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -45]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 18:24:12.437   875  4179 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138161, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:12.448  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:12.451  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:12.454  3769  3820 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 18:24:12.455  3769  3820 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 18:24:12.460  3769  3820 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@baa1301 Bundle[{}]
,09-08 18:24:12.464  3769  3820 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 18:24:12.464  3769  3820 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 18:24:12.465  3769  3820 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-08 18:24:12.466  3769  3820 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 18:24:12.467  3769  3820 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 18:24:12.468  3769  3820 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-08 18:24:12.474  3769  3820 I System.out: Running OutgoingSocketThread
,09-08 18:24:12.476  3769  4186 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 417)
,09-08 18:24:12.478  3769  4186 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38169
,09-08 18:24:12.478  3769  4186 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 18:24:12.496   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,09-08 18:24:12.514   875  4178 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 18:24:12.543   373   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 18:24:12.552   875  1313 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 18:24:12.554   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:12.561   875  1313 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 18:24:12.563   875   892 D Tethering: MasterInitialState.processMessage what=3
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:12.581  3769  3769 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:24:12.584  3769  3769 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:12.596  1724  1724 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 18:24:12.596   875  4178 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 16:24:12 GMT], X-Android-Received-Millis=[1473351852595], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473351852552]}
09-08 18:24:12.597   875  1313 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 18:24:12.597   875  1313 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 18:24:12.597   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 18:24:12.598   875  1313 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-08 18:24:12.602  1724  1724 D SystemUpdateService: onCreate
,09-08 18:24:12.605  1724  1724 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 18:24:12.627  1724  4191 I SystemUpdateService: active receiver: enabled
,09-08 18:24:12.634  1724  1724 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 18:24:12.639  1724  2520 I iu.UploadsManager: num queued entries: 0
,09-08 18:24:12.639  1724  2520 I iu.UploadsManager: num updated entries: 0
,09-08 18:24:12.640  1724  2520 I iu.SyncManager: NEXT; no task,
,09-08 18:24:12.645  1724  1724 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 18:24:12.646  1724  1724 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 18:24:12.647  3926  3926 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 18:24:12.649  1724  4191 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 18:24:12.654  1724  4194 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 18:24:12.654  1724  4194 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 18:24:12.663  3926  3926 D SprintDMHelper: simOperator: 
,09-08 18:24:12.663  3926  3926 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-08 18:24:12.665  1724  4194 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 18:24:12.667  1724  4191 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-08 18:24:12.667  1724  4191 I SystemUpdateService: now status is 0 (complete)
09-08 18:24:12.667  1724  4191 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 18:24:12.667  1724  4191 I SystemUpdateService: file has been verified
09-08 18:24:12.667  1724  4191 I SystemUpdateService: OTA package size = 12249756
,09-08 18:24:12.672  1724  4191 I SystemUpdateService: showing system update notification
,09-08 18:24:12.704   875   887 I ActivityManager: Start proc 4196:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-08 18:24:12.730  4196  4196 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-08 18:24:12.740  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:24:12.743  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:24:12.775  1724  1724 D SystemUpdateService: onDestroy
,09-08 18:24:12.784  1508  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-08 18:24:12.784  1508  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 18:24:12.784  1508  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:24:12.784  1508  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:24:12.795  3028  4208 V KeepSync: Connecting to GoogleApiClient
,09-08 18:24:12.796   875  1384 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 18:24:12.799  1724  4194 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-08 18:24:12.807  4196  4196 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-08 18:24:12.816  4196  4196 I BooksApp: Created application version: 3.6.9 (30609)
,09-08 18:24:12.841  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-08 18:24:12.841  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 18:24:12.841  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:24:12.841  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:24:12.850  2278  4209 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 18:24:12.857  1724  4219 V BaseAuthAsyncOperation: access token request failed
,09-08 18:24:12.858  3028  4208 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 18:24:12.917  4196  4220 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 18:24:12.961  1508  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 18:24:12.962  1508  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-08 18:24:12.962  1508  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:24:12.962  1508  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:24:12.988  3028  4208 E KeepSync: IOException
09-08 18:24:12.988  3028  4208 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 18:24:12.988  3028  4208 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 18:24:12.988  3028  4208 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 18:24:12.988  3028  4208 E KeepSync: 	... 10 more
,09-08 18:24:12.989  3028  4208 W KeepSync: Sync result 2
,09-08 18:24:12.994   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130126, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:24:13.077  4196  4228 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 18:24:13.176  1508  1928 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 18:24:13.177  1508  1928 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 18:24:13.177  1508  1928 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:24:13.177  1508  1928 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:24:13.211  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 18:24:13.254  1508  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 18:24:13.255  1508  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 18:24:13.255  1508  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 18:24:13.255  1508  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-08 18:24:13.262  1508  3093 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-08 18:24:13.262  1508  3093 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-08 18:24:13.263  1508  3093 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 18:24:13.263  1508  3093 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 18:24:13.268  4196  4228 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 18:24:13.270  4196  4220 E BooksSync: Soft error
09-08 18:24:13.270  4196  4220 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:24:13.270  4196  4220 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 18:24:13.270  4196  4220 E BooksSync: Sync error
09-08 18:24:13.270  4196  4220 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 18:24:13.270  4196  4220 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 18:24:13.270  4196  4220 I BooksSync: Finished books sync
,09-08 18:24:13.280   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 132083, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 18:24:13.289  3500  3500 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-08 18:24:13.290  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-08 18:24:13.290  3500  3500 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-08 18:24:13.477  3769  3820 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 418)
,09-08 18:24:13.477  3769  3820 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 418)
,09-08 18:24:13.487  3769  3820 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,09-08 18:24:13.489  3769  3820 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 18:24:13.489  3769  3820 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 424)
,09-08 18:24:13.495  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:13.495  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5b05b5 added. We now have 2 listener(s)
,09-08 18:24:13.497  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:24:13.497  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.497  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.497  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.497  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc44a added. We now have 9 listener(s)
09-08 18:24:13.498  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.498  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:13.501  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:13.510  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:13.513  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:13.513  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:24:13.514  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:13.514  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff11cd8 added. We now have 3 listener(s)
,09-08 18:24:13.516  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:13.519  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:13.523  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:24:13.524  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.524  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.525  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.525  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7834831 added. We now have 10 listener(s)
09-08 18:24:13.525  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.526  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:13.526  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:13.526  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:13.526  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.527  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:13.527  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:13.527  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 18:24:13.528  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5b05b5 removed from the list
09-08 18:24:13.528  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:13.528  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc44a removed from the list
09-08 18:24:13.528  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:13.528  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:13.530  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:13.530  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.532  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:13.532  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.533  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.533  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc44a not in the list
,09-08 18:24:13.533  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.533  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:13.535  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 18:24:13.535  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:13.535  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.536  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7834831 removed from the list
,09-08 18:24:13.536  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.536  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:13.536  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.537  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.537  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ff11cd8 removed from the list
,09-08 18:24:13.539  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:13.539  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cadb16 added. We now have 2 listener(s)
,09-08 18:24:13.541  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:24:13.541  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 18:24:13.541  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.542  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.542  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3242c97 added. We now have 9 listener(s)
09-08 18:24:13.542  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.542  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:13.545  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:13.549  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:13.551   875  1313 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-08 18:24:13.551  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:13.551  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:13.552  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:13.552  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@613366d added. We now have 3 listener(s)
,09-08 18:24:13.554  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:24:13.554  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:13.554  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.554  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.555  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.555  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61192a2 added. We now have 10 listener(s)
09-08 18:24:13.555  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.555  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:24:13.555  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:13.555  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:13.555  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:13.555  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:24:13.558  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:13.559  3769  3820 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:24:13.559  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:13.563  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 18:24:13.564  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 18:24:13.564  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:13.568  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:24:13.568  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:13.568  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:24:13.568  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:24:13.572  4124  4164 D BtGatt.GattService: registerClient() - UUID=2ac322d7-9828-45b3-9f8b-d64759f7af3a
,09-08 18:24:13.573  4124  4140 D BtGatt.GattService: onClientRegistered() - UUID=2ac322d7-9828-45b3-9f8b-d64759f7af3a, clientIf=5
,09-08 18:24:13.574  3769  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 18:24:13.575  4124  4141 D BtGatt.GattService: start scan with filters
,09-08 18:24:13.579  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:13.579  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 18:24:13.579  4124  4144 D BtGatt.ScanManager: handling starting scan
09-08 18:24:13.579  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:13.579  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 18:24:13.581  4124  4144 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fbc10e8
,09-08 18:24:13.584  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:13.584  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:24:13.584  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:13.585  4124  4140 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 18:24:13.586  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.586  4124  4144 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:24:13.588  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:13.591  3769  3820 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-08 18:24:13.591  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:13.591  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 18:24:13.591  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.591  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:24:13.591  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 18:24:13.591  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:24:13.591  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 18:24:13.591  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 18:24:13.592  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 18:24:13.592  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:13.598  4124  4140 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 18:24:13.601  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.602  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:24:13.603  4124  4144 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 18:24:13.603  4124  4144 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 18:24:13.603  4124  4164 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:13.604  4124  4141 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 18:24:13.604  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 18:24:13.604  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 18:24:13.604  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 18:24:13.604  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 18:24:13.604  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:13.605  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:13.605  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 18:24:13.605  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 18:24:13.606  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 18:24:13.606  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:13.608  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:13.608  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:13.608  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:13.612  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:13.612  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:13.612  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:13.612  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.613  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.613  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:13.613  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.613  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9cadb16 removed from the list
09-08 18:24:13.613  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.613  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3242c97 removed from the list
09-08 18:24:13.613  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 18:24:13.614  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.614  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.614  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.616  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:13.616  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.616  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.616  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3242c97 not in the list
09-08 18:24:13.616  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.617  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:13.618  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.618  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:13.618  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.618  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61192a2 removed from the list
09-08 18:24:13.619  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.619  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.619  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.619  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.619  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@613366d removed from the list
09-08 18:24:13.620  4124  4140 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 18:24:13.620  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.620  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:13.620  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11a36ee added. We now have 2 listener(s)
09-08 18:24:13.623  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:24:13.623  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.624  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.624  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.624  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa178f added. We now have 9 listener(s)
09-08 18:24:13.624  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.625  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:13.625  4124  4140 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 18:24:13.626  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.628  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:13.633  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:13.635  4124  4140 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:24:13.635  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.635  4124  4144 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:24:13.635  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:13.636  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 18:24:13.636  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 18:24:13.638  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:13.638  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@119c625 added. We now have 3 listener(s)
,09-08 18:24:13.640  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:13.640  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:24:13.640  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.640  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:13.640  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.640  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f6d3fa added. We now have 10 listener(s)
09-08 18:24:13.640  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:13.640  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:13.641  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:13.641  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 18:24:13.641  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:13.641  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:13.641  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 18:24:13.642  4124  4140 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 18:24:13.642  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.642  4124  4144 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 18:24:13.644  3769  3820 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:24:13.644  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:13.647  4124  4140 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 18:24:13.647  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.647  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:24:13.648  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 18:24:13.648  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:13.650  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:24:13.650  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:13.650  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 18:24:13.651  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:24:13.652  4124  4135 D BtGatt.GattService: registerClient() - UUID=294ecd91-2dc2-40d5-9c49-4c65b447377b
,09-08 18:24:13.653  4124  4140 D BtGatt.GattService: onClientRegistered() - UUID=294ecd91-2dc2-40d5-9c49-4c65b447377b, clientIf=5
09-08 18:24:13.653  3769  3780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 18:24:13.653  4124  4134 D BtGatt.GattService: start scan with filters
,09-08 18:24:13.655  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 18:24:13.655  4124  4144 D BtGatt.ScanManager: handling starting scan
09-08 18:24:13.655  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:24:13.655  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:13.655  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:13.657  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:13.658  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 18:24:13.658  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:13.659  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:13.660  4124  4140 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 18:24:13.660  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.661  4124  4144 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 18:24:13.661  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 18:24:13.661  3769  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-08 18:24:13.662  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 18:24:13.662  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:13.662  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 18:24:13.662  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.662  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.662  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:24:13.662  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.662  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11a36ee removed from the list
,09-08 18:24:13.663  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.663  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa178f removed from the list
09-08 18:24:13.663  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:13.663  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:13.663  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.663  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-08 18:24:13.663  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.663  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:13.664  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:13.664  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.664  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.664  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa178f not in the list
,09-08 18:24:13.664  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 18:24:13.664  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:24:13.664  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:24:13.665  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:24:13.665  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:13.665  3769  3820 D BluetoothAdapter: STATE_ON
09-08 18:24:13.665  4124  4140 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 18:24:13.665  4124  4141 D BtGatt.GattService: stopScan() - queue size =1
09-08 18:24:13.666  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.666  4124  4144 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:13.666  4124  4144 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 18:24:13.666  4124  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 18:24:13.666  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:13.666  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:13.666  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:13.666  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:24:13.666  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 18:24:13.667  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:13.667  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 18:24:13.668  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:13.668  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:13.668  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:13.669  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:13.669  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:13.669  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 18:24:13.669  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.669  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:13.669  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.669  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f6d3fa removed from the list
09-08 18:24:13.669  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 18:24:13.669  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.669  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.669  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.670  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@119c625 removed from the list
09-08 18:24:13.670  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:13.670  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ce35c6 added. We now have 2 listener(s)
,09-08 18:24:13.671  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:24:13.672  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.672  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.672  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.672  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d536987 added. We now have 9 listener(s)
09-08 18:24:13.672  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 18:24:13.672  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 18:24:13.678  4124  4140 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 18:24:13.678  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.679  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:13.684  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 18:24:13.684  4124  4140 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 18:24:13.684  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.686  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:13.686  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:13.686  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:13.686  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfb94dd added. We now have 3 listener(s)
09-08 18:24:13.688  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:24:13.688  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.688  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.688  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.688  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b67e852 added. We now have 10 listener(s)
09-08 18:24:13.688  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.689  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:13.689  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 18:24:13.689  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 18:24:13.689  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:13.689  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 18:24:13.690  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:13.691  4124  4140 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:24:13.691  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.691  4124  4144 D BtGatt.ScanManager: stopping BLe Batch
09-08 18:24:13.693  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:13.694  3769  3820 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 18:24:13.694  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 18:24:13.698  4124  4140 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:24:13.698  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.698  4124  4144 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 18:24:13.699  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 18:24:13.700  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 18:24:13.700  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 18:24:13.704  4124  4140 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 18:24:13.704  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.706  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 18:24:13.706  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 18:24:13.706  3769  3820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 18:24:13.707  3769  3820 D BluetoothAdapter: STATE_ON
,09-08 18:24:13.709  4124  4164 D BtGatt.GattService: registerClient() - UUID=38feaa19-ed51-49c4-8296-e07d694a4099
,09-08 18:24:13.709  4124  4140 D BtGatt.GattService: onClientRegistered() - UUID=38feaa19-ed51-49c4-8296-e07d694a4099, clientIf=5
09-08 18:24:13.710  3769  3781 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 18:24:13.710  4124  4141 D BtGatt.GattService: start scan with filters
,09-08 18:24:13.713  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 18:24:13.713  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 18:24:13.713  4124  4144 D BtGatt.ScanManager: handling starting scan
,09-08 18:24:13.714  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 18:24:13.714  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 18:24:13.717  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:13.717  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 18:24:13.717  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 18:24:13.719  4124  4140 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 18:24:13.719  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.720  4124  4144 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 18:24:13.720  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 18:24:13.724  4124  4140 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 18:24:13.724  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.724  4124  4144 D BtGatt.ScanManager: Starting BLE batch scan
09-08 18:24:13.724  4124  4144 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 18:24:13.728  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:24:13.728  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 18:24:13.728  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:13.728  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.728  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:13.728  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 18:24:13.728  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.728  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ce35c6 removed from the list
09-08 18:24:13.729  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.729  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d536987 removed from the list
09-08 18:24:13.729  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:13.729  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:13.729  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:13.729  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-08 18:24:13.729  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.729  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 18:24:13.730  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:13.730  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.730  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.730  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d536987 not in the list
09-08 18:24:13.730  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 18:24:13.730  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 18:24:13.730  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 18:24:13.730  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 18:24:13.730  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 18:24:13.730  3769  3820 D BluetoothAdapter: STATE_ON
09-08 18:24:13.731  4124  4135 D BtGatt.GattService: stopScan() - queue size =1
,09-08 18:24:13.731  4124  4141 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 18:24:13.731  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 18:24:13.731  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 18:24:13.731  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 18:24:13.731  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 18:24:13.731  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-08 18:24:13.732  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:13.732  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 18:24:13.732  3769  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 18:24:13.732  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 18:24:13.732  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.733  4124  4140 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 18:24:13.733  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.733  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.733  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:13.733  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:13.733  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b67e852 removed from the list
09-08 18:24:13.733  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 18:24:13.733  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.734  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.734  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 18:24:13.734  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.734  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.734  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dfb94dd removed from the list
09-08 18:24:13.734  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 18:24:13.734  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:13.734  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@278379e added. We now have 2 listener(s)
09-08 18:24:13.735  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 18:24:13.735  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.735  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 18:24:13.735  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.735  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56027f added. We now have 9 listener(s)
,09-08 18:24:13.735  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.736  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 18:24:13.737  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 18:24:13.737  4124  4140 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 18:24:13.737  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 18:24:13.740  3769  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 18:24:13.741  3769  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 18:24:13.742  3769  3820 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 18:24:13.742  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 18:24:13.742  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7018295 added. We now have 3 listener(s)
,09-08 18:24:13.743  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 18:24:13.743  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 18:24:13.743  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 18:24:13.743  4124  4140 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 18:24:13.743  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.743  4124  4144 D BtGatt.ScanManager: stopping BLe Batch
,09-08 18:24:13.743  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 18:24:13.743  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ac2faa added. We now have 10 listener(s)
09-08 18:24:13.743  3769  3820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 18:24:13.743  3769  3820 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 18:24:13.744  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:13.744  3769  3820 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 18:24:13.744  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.744  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 18:24:13.744  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 18:24:13.744  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.744  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@278379e removed from the list
09-08 18:24:13.744  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 18:24:13.744  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 18:24:13.744  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56027f removed from the list
09-08 18:24:13.745  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 18:24:13.745  3769  3820 D io.jxcore.node.ConnectivityMonitor: stop
09-08 18:24:13.745  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.746  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.746  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:13.747  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 18:24:13.747  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.747  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.747  3769  3820 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@56027f not in the list
,09-08 18:24:13.747  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.747  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 18:24:13.747  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 18:24:13.747  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 18:24:13.747  3769  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 18:24:13.748  4124  4140 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 18:24:13.748  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.748  3769  3820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5ac2faa removed from the list
,09-08 18:24:13.748  3769  3820 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 18:24:13.748  4124  4144 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 18:24:13.748  3769  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 18:24:13.748  3769  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-08 18:24:13.748  3769  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 18:24:13.748  3769  3820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7018295 removed from the list
09-08 18:24:13.748  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-08 18:24:13.749  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 18:24:13.749  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 18:24:13.749  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 18:24:13.749  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 18:24:13.749  3769  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 18:24:13.754  3769  4229 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
09-08 18:24:13.754  3769  4229 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: My test thread name)
09-08 18:24:13.754  3769  4229 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122,
,09-08 18:24:13.756  4124  4140 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 18:24:13.756  4124  4140 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 18:24:13.756  3769  4230 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: My test thread name)
09-08 18:24:13.756  3769  4230 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: My test thread name)
,09-08 18:24:13.756  3769  4230 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-08 18:24:13.758  3769  3820 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-08 18:24:13.758  3769  3820 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-08 18:24:13.758  3769  3820 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-08 18:24:13.758  3769  3820 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-08 18:24:13.758  3769  3820 D com.test.thalitest.ThaliTestRunner: Total duration: 22822 ms
,09-08 18:24:13.760  3769  3820 I jxcore-log: *Native tests were executed*
09-08 18:24:13.760  3769  3820 I jxcore-log: 
,09-08 18:24:13.760  3769  3820 I jxcore-log: Total number of executed tests:  80
09-08 18:24:13.760  3769  3820 I jxcore-log: 
09-08 18:24:13.760  3769  3820 I jxcore-log: Number of passed tests:  80
09-08 18:24:13.760  3769  3820 I jxcore-log: 
09-08 18:24:13.760  3769  3820 I jxcore-log: Number of failed tests:  0
09-08 18:24:13.760  3769  3820 I jxcore-log: 
09-08 18:24:13.760  3769  3820 I jxcore-log: Number of ignored tests:  0
09-08 18:24:13.760  3769  3820 I jxcore-log: 
,09-08 18:24:13.761  3769  3820 I jxcore-log: Total duration:  22822
09-08 18:24:13.761  3769  3820 I jxcore-log: 
09-08 18:24:13.761  3769  3820 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-08 18:24:13.761  3769  3820 I jxcore-log: 
,09-08 18:24:13.763  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.763  3769  3820 I jxcore-log: 
09-08 18:24:13.766  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.766  3769  3820 I jxcore-log: 
09-08 18:24:13.767  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.767  3769  3820 I jxcore-log: 
09-08 18:24:13.768  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.768  3769  3820 I jxcore-log: 
09-08 18:24:13.769  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.769  3769  3820 I jxcore-log: 
09-08 18:24:13.770  3769  3769 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-08 18:24:13.770  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.770  3769  3820 I jxcore-log: 
09-08 18:24:13.773  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.773  3769  3820 I jxcore-log: 
09-08 18:24:13.774  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.774  3769  3820 I jxcore-log: 
09-08 18:24:13.775  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.775  3769  3820 I jxcore-log: 
09-08 18:24:13.775  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:13.775  3769  3820 I jxcore-log: 
09-08 18:24:13.776  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:13.776  3769  3820 I jxcore-log: 
,09-08 18:24:13.777  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 18:24:13.777  3769  3820 I jxcore-log: 
09-08 18:24:13.778  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.778  3769  3820 I jxcore-log: 
,09-08 18:24:13.778  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.778  3769  3820 I jxcore-log: 
,09-08 18:24:13.779  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.779  3769  3820 I jxcore-log: 
,09-08 18:24:13.780  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.780  3769  3820 I jxcore-log: 
09-08 18:24:13.780  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.780  3769  3820 I jxcore-log: 
,09-08 18:24:13.781  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.781  3769  3820 I jxcore-log: 
09-08 18:24:13.781  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.781  3769  3820 I jxcore-log: 
,09-08 18:24:13.782  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.782  3769  3820 I jxcore-log: 
,09-08 18:24:13.783  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.783  3769  3820 I jxcore-log: 
09-08 18:24:13.783  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 18:24:13.783  3769  3820 I jxcore-log: 
,09-08 18:24:13.784  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 18:24:13.784  3769  3820 I jxcore-log: 
,09-08 18:24:13.784  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.784  3769  3820 I jxcore-log: 
09-08 18:24:13.785  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.785  3769  3820 I jxcore-log: 
,09-08 18:24:13.786  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.786  3769  3820 I jxcore-log: 
,09-08 18:24:13.786  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.786  3769  3820 I jxcore-log: 
,09-08 18:24:13.787  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.787  3769  3820 I jxcore-log: 
,09-08 18:24:13.787  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.787  3769  3820 I jxcore-log: 
09-08 18:24:13.788  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 18:24:13.788  3769  3820 I jxcore-log: 
,09-08 18:24:14.109  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:24:14.112  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:14.112  3769  3820 I jxcore-log: 
,09-08 18:24:14.170  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:24:14.173  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:14.173  3769  3820 I jxcore-log: 
,09-08 18:24:14.235  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 18:24:14.238  3769  3820 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 18:24:14.238  3769  3820 I jxcore-log: 
,09-08 18:24:14.433  4231  4231 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-08 18:24:14.438  4231  4231 D AndroidRuntime: CheckJNI is OFF
,09-08 18:24:14.481  4231  4231 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-08 18:24:14.529  4231  4231 I Radio-JNI: register_android_hardware_Radio DONE
,09-08 18:24:14.552  4231  4231 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-08 18:24:14.563   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-08 18:24:14.564   875   888 I ActivityManager: Killing 3769:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-08 18:24:14.662   875  1913 D GraphicsStats: Buffer count: 2
,09-08 18:24:14.662   875  1915 I WindowState: WIN DEATH: Window{a006a96 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 18:24:14.663   875  1312 D WifiService: Client connection lost with reason: 4
,09-08 18:24:14.711   875   888 W ActivityManager: Force removing ActivityRecord{9c4a83f u0 com.test.thalitest/.MainActivity t4}: app died, no saved state
,09-08 18:24:14.713   875   898 W PackageSettings: Skipping PackageSetting{298b995 com.example.hello/10273} due to missing metadata
,09-08 18:24:14.742   875   898 I art     : Starting a blocking GC Explicit
,09-08 18:24:14.761   875  1384 W ActivityManager: Spurious death for ProcessRecord{53680e0 0:com.test.thalitest/u0a0}, curProc for 3769: null
,09-08 18:24:14.782   875   886 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3769 uid 10000
,09-08 18:24:14.783  1881  1881 I Keyboard.Facilitator: onFinishInput()
,09-08 18:24:14.795   875   898 I art     : Explicit concurrent mark sweep GC freed 14272(947KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.184ms total 52.241ms
,09-08 18:24:14.824   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-08 18:24:14.825  4231  4231 I art     : System.exit called, status: 0
,09-08 18:24:14.825  4231  4231 I AndroidRuntime: VM exiting with result code 0.
,09-08 18:24:14.844   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-08 18:24:14.848  1998  4245 I MicroRecognitionRnrImpl: Starting detection.
09-08 18:24:14.849  1998  4246 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@316a1c9
,09-08 18:24:14.853   377  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-08 18:24:14.854   377  4249 I AudioFlinger: AudioFlinger's thread 0xb3400000 ready to run
09-08 18:24:14.855  1998  4246 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@316a1c9
,09-08 18:24:14.865   377  4249 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,09-08 18:24:14.865   377  4249 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
09-08 18:24:14.865   377  4249 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,09-08 18:24:14.870  1881  1881 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-08 18:24:14.872   377  4249 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
09-08 18:24:14.874   875  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 18:24:14.878  4124  4124 D BluetoothMapAppObserver: onReceive
,09-08 18:24:14.878  4124  4124 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 18:24:14.879  1897  2292 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 18:24:14.887  1881  4250 I Keyboard.Facilitator.DecoderInitializer: run()
,09-08 18:24:14.889  1881  4250 I Decoder : createOrResetDecoder
,09-08 18:24:14.919  1952  1952 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-08 18:24:14.941  3646  3646 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-08 18:24:14.951  1998  1998 I HotwordWorkerImpl: onReady
,09-08 18:24:14.960   875   886 I ActivityManager: Start proc 4254:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-08 18:24:14.965  1508  1508 I ConfigService: onCreate
,09-08 18:24:14.968  1508  4266 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 18:24:14.968  1508  4266 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-08 18:24:14.969  1508  4266 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-08 18:24:14.970  1508  4266 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-08 18:24:14.982  1881  4250 I Keyboard.Facilitator.MainLanguageModelLoader: run(),
,09-08 18:24:14.984   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-08 18:24:15.001  4254  4254 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-08 18:24:15.008  1881  4250 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-08 18:24:15.009  1881  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-08 18:24:15.010  1881  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-08 18:24:15.010  1970  2042 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-08 18:24:15.011   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-08 18:24:15.011   875   887 E PackageManager: Failed to write settings, restoring backup
09-08 18:24:15.011   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml,
09-08 18:24:15.011   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 18:24:15.011   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 18:24:15.011   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 18:24:15.011   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 18:24:15.011   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:15.011   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.011   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 18:24:15.015   875   888 E DropBoxManagerService: Can't write: system_server_wtf
09-08 18:24:15.015   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 18:24:15.015   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:24:15.015   875   888 E DropBoxManagerService: 	... 13 more
,09-08 18:24:15.021  1881  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-08 18:24:15.021  1881  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 18:24:15.022  1881  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 18:24:15.022  1881  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-08 18:24:15.023   875  1915 I ActivityManager: Start proc 4268:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-08 18:24:15.023  1970  2042 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 18:24:15.023  1970  2042 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1970
09-08 18:24:15.023  1970  2042 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.023  1970  2042 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 18:24:15.025   875  2264 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-08 18:24:15.026   875  4278 E DropBoxManagerService: Can't write: system_app_crash
09-08 18:24:15.026   875  4278 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:24:15.026   875  4278 E DropBoxManagerService: 	... 5 more
09-08 18:24:15.028  1998  2013 W SearchService: Abort, client detached.
09-08 18:24:15.030  1998  1998 I HotwordDetector: Closing mic
09-08 18:24:15.030  1998  2360 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@316a1c9
09-08 18:24:15.030  1998  4246 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-08 18:24:15.042  1881  4250 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-08 18:24:15.042   875  4281 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-08 18:24:15.042  1881  4250 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 18:24:15.042  1881  4250 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 18:24:15.042  1881  4250 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-08 18:24:15.051  1998  4282 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,09-08 18:24:15.063   875  4281 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 18:24:15.063   875  4281 I Adreno  : Build Date                       : 10/20/15
09-08 18:24:15.063   875  4281 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 18:24:15.063   875  4281 I Adreno  : Local Branch                     : M14
09-08 18:24:15.063   875  4281 I Adreno  : Remote Branch                    : 
09-08 18:24:15.063   875  4281 I Adreno  : Remote Branch                    : 
09-08 18:24:15.063   875  4281 I Adreno  : Reconstruct Branch               : 
,09-08 18:24:15.068   875  4281 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 18:24:15.070  1881  4250 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-08 18:24:15.070  1881  4250 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-08 18:24:15.091   377  4249 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-08 18:24:15.092   377  4249 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
,09-08 18:24:15.095   377  1282 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-08 18:24:15.098  1998  4245 I MicroRecognitionRnrImpl: Detection finished
,09-08 18:24:15.098  1998  2364 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-08 18:24:15.125  4254  4254 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-08 18:24:15.146   875  1313 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 18:24:15.148   875   886 I ActivityManager: Start proc 4292:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-08 18:24:15.176  4254  4291 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest,
09-08 18:24:15.178  1724  4304 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-08 18:24:15.179  1724  4304 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,09-08 18:24:15.193  4292  4292 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-08 18:24:15.197  4254  4291 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.197  4254  4291 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 18:24:15.198  4254  4291 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 18:24:15.198  4254  4291 E AndroidRuntime: Process: android.process.acore, PID: 4254
09-08 18:24:15.198  4254  4291 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.198  4254  4291 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 18:24:15.217  1508  1508 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-08 18:24:15.222   875  4308 E DropBoxManagerService: Can't write: system_app_crash
09-08 18:24:15.222   875  4308 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:24:15.222   875  4308 E DropBoxManagerService: 	... 5 more
09-08 18:24:15.223  1508  1508 D AndroidRuntime: Shutting down VM
,09-08 18:24:15.224  1508  1508 E AndroidRuntime: FATAL EXCEPTION: main
09-08 18:24:15.224  1508  1508 E AndroidRuntime: Process: com.google.process.gapps, PID: 1508
09-08 18:24:15.224  1508  1508 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 18:24:15.224  1508  1508 E AndroidRuntime: 	... 8 more
,09-08 18:24:15.201  4254  4287 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.201  4254  4287 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.o,penInner(SQLiteDatabase.java:806)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 18:24:15.236  4254  4287 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 18:24:15.261   875  4309 E DropBoxManagerService: Can't write: system_app_crash
09-08 18:24:15.261   875  4309 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 18:24:15.261   875  4309 E DropBoxManagerService: 	... 5 more
,09-08 18:24:15.267  4254  4287 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-08 18:24:15.273  4254  4287 I Process : Sending signal. PID: 4254 SIG: 9
,09-08 18:24:15.302   875  1311 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 12 -> obsolete
,09-08 18:24:15.318   875  2085 I ActivityManager: Process android.process.acore (pid 4254) has died
,09-08 18:24:15.319   875  2085 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-08 18:24:15.347   282   282 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,09-08 18:24:15.347   282   282 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
09-08 18:24:15.348   282   282 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
09-08 18:24:15.348   282   282 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
09-08 18:24:15.348   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
09-08 18:24:15.348   282   282 E qdoverlay: MdpCtrl close error in unset
,09-08 18:24:15.613   282   339 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
