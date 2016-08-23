#### Test 82203060884b823_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-23 12:38:37.588   872  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=110664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-23 12:38:38.254  3770  3770 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-23 12:38:38.259  3770  3770 D AndroidRuntime: CheckJNI is OFF
08-23 12:38:38.300  3770  3770 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-23 12:38:38.343  3770  3770 I Radio-JNI: register_android_hardware_Radio DONE
08-23 12:38:38.364  3770  3770 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 12:38:38.371   872  1952 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 12:38:38.407  1987  2000 W SearchService: Abort, client detached.
08-23 12:38:38.413  3770  3770 D AndroidRuntime: Shutting down VM
08-23 12:38:38.419  1987  2297 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f19ac29
08-23 12:38:38.419  1987  2318 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-23 12:38:38.420  1987  1987 I HotwordDetector: Closing mic
08-23 12:38:38.428   872  1955 I ActivityManager: Start proc 3779:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-23 12:38:38.476   375  2320 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-23 12:38:38.476   375  2320 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 12:38:38.481   375  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 12:38:38.483  1987  2306 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 12:38:38.484  1987  2317 I MicroRecognitionRnrImpl: Detection finished
08-23 12:38:38.512  3779  3779 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-23 12:38:38.542  3779  3779 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-23 12:38:38.552  3779  3779 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1623-1627)
08-23 12:38:38.552  3779  3779 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:38:38.569  3779  3779 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5a3a67}
08-23 12:38:38.569  3779  3779 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:38:38.570  3779  3779 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 12:38:38.575  3779  3779 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 12:38:38.576  3779  3779 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 12:38:38.588  3779  3779 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 12:38:38.597  3779  3779 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 12:38:38.597  3779  3779 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 12:38:38.598  3779  3779 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 12:38:38.598  3779  3779 I Adreno  : Build Date                       : 10/20/15
08-23 12:38:38.598  3779  3779 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 12:38:38.598  3779  3779 I Adreno  : Local Branch                     : M14
08-23 12:38:38.598  3779  3779 I Adreno  : Remote Branch                    : 
08-23 12:38:38.598  3779  3779 I Adreno  : Remote Branch                    : 
08-23 12:38:38.598  3779  3779 I Adreno  : Reconstruct Branch               : 
08-23 12:38:38.637   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e6b316:true
,08-23 12:38:38.705  3779  3779 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 12:38:38.720  3779  3779 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-23 12:38:38.761  3779  3817 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 12:38:38.771  3779  3804 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-23 12:38:38.796  3779  3817 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 12:38:38.883   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +471ms
,08-23 12:38:38.897  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-23 12:38:38.987  3779  3779 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3779
,08-23 12:38:39.091  3779  3779 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 12:38:39.240  3779  3819 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684014800
,08-23 12:38:39.242   872  1927 I ActivityManager: Killing 3195:com.google.android.gm/u0a78 (adj 15): empty #17
08-23 12:38:39.245  3779  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:38:39.245  3779  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:38:39.245  3779  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:38:39.245  3779  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:38:39.245  3779  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 12:38:39.246  3779  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36190ca added. We now have 1 listener(s)
08-23 12:38:39.250  3779  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-23 12:38:39.252  3779  3819 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 12:38:39.252  3779  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:38:39.252  3779  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 12:38:39.258  3779  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f5deb1 added. We now have 1 listener(s)
08-23 12:38:39.259  3779  3819 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:39.262  3779  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:38:39.262  3779  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 12:38:39.262   872  1301 D WifiService: New client listening to asynchronous messages
08-23 12:38:39.262  3779  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 12:38:39.262  3779  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:38:39.262  3779  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 12:38:39.311   872  1927 I ActivityManager: Killing 2959:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-23 12:38:39.377  3779  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:39.377  3779  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-23 12:38:39.384  3779  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:39.385  3779  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:38:39.385  3779  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 12:38:39.385  3779  3819 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:38:39.386  3779  3819 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 12:38:39.587  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:39.590  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:39.592  3779  3779 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 12:38:40.251  3779  3829 W jxcore-log: Initializing JXcore engine
08-23 12:38:40.251  3779  3829 W jxcore-log: JXcore engine is ready
,08-23 12:38:40.290  3829  3829 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8944 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-23 12:38:40.290  3829  3829 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9677]" dev="sockfs" ino=9677 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-23 12:38:40.290  3829  3829 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 12:38:40.290  3829  3829 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[23443]" dev="sockfs" ino=23443 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-23 12:38:40.305  3779  3829 W jxcore-log: Starting JXcore engine
,08-23 12:38:40.390  3779  3829 W jxcore-log: Platform android
08-23 12:38:40.390  3779  3829 W jxcore-log: 
,08-23 12:38:40.391  3779  3829 W jxcore-log: Process ARCH arm
08-23 12:38:40.391  3779  3829 W jxcore-log: 
,08-23 12:38:40.668  3779  3829 I jxcore-log: JXcore Cordova bridge is ready!
08-23 12:38:40.668  3779  3829 I jxcore-log: 
,08-23 12:38:40.668  3779  3829 W jxcore-log: JXcore engine is started
,08-23 12:38:40.679  3779  3819 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 12:38:40.682  3779  3779 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:38:48.659  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:38:48.665  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:38:48.666  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:38:48.685  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-23 12:38:48.685  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-23 12:38:48.685  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 12:38:48.685  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:48.698  3486  3486 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 12:38:48.698  3486  3486 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-23 12:38:48.699  3486  3486 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-23 12:38:49.710   872  1300 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-23 12:38:50.364  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 12:38:50.364  3779  3829 I jxcore-log: 
,08-23 12:38:50.367  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 12:38:50.367  3779  3829 I jxcore-log: 
,08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:50.374  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:50.379  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:50.381  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 12:38:50.381  3779  3829 I jxcore-log: 
,08-23 12:38:50.383  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 12:38:50.383  3779  3829 I jxcore-log: 
,08-23 12:38:50.872  3779  3829 D ExecuteNativeTests: Running unit tests
,08-23 12:38:50.928  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:38:50.929  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b added. We now have 2 listener(s)
,08-23 12:38:50.930  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 12:38:50.930  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:38:50.930  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:38:50.930  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:50.930  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 added. We now have 2 listener(s)
08-23 12:38:50.930  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:38:50.931  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:38:50.933  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:50.946  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:50.947  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:50.947  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:50.949  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-23 12:38:50.951  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 12:38:50.951  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 12:38:50.952  3779  3829 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-23 12:38:50.953  3779  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-23 12:38:50.953  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-23 12:38:50.953  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-23 12:38:50.953  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:38:50.953  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:50.953  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:50.954  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:50.954  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:50.954  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:50.954  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:50.954  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:50.954  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:38:50.954  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b removed from the list
,08-23 12:38:50.954  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:50.955  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 removed from the list
08-23 12:38:50.958  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:50.959  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:50.959  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:50.961  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:50.961  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:50.962  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:50.962  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:50.962  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:50.962  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:50.964  3779  3829 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-23 12:38:50.964  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:50.964  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:38:50.964  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:50.965  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:50.965  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:50.965  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:50.965  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:50.965  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:50.965  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:50.965  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:50.965  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:50.965  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:50.965  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:50.965  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:50.966  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:50.966  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:50.966  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:50.966  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:50.974  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 12:38:50.974  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-23 12:38:50.974  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410],
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 12:38:50.975  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 12:38:50.976  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 12:38:50.976  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:50.976  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:50.976  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:50.976  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:50.976  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:50.977  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:50.977  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:50.977  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:50.977  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:50.977  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:50.977  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:50.977  3779  3829 D org.thaliproject.p2p.bt,connectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:50.977  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:50.977  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:50.978  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:50.978  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:50.978  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:50.978  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:50.979  3779  3829 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-23 12:38:50.980  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:50.983  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:50.984  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:50.984  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:50.985  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 12:38:50.986  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:50.986  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 12:38:50.988  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:50.988  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:38:50.988  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:50.989  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 12:38:50.992  3779  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 12:38:50.992  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:38:50.996  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:38:50.997  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 12:38:50.998  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 12:38:50.999  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-23 12:38:51.003  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-23 12:38:51.003  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 12:38:51.005  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-23 12:38:51.005  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 12:38:51.007  3779  3829 D BluetoothAdapter: STATE_ON
,08-23 12:38:51.010  2641  2747 D BtGatt.GattService: registerClient() - UUID=f7901bde-40a8-4bb9-a8b9-945ba73303a1
,08-23 12:38:51.011  2641  2660 D BtGatt.GattService: onClientRegistered() - UUID=f7901bde-40a8-4bb9-a8b9-945ba73303a1, clientIf=5
,08-23 12:38:51.011  3779  3791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 12:38:51.012  2641  2770 D BtGatt.GattService: start scan with filters
,08-23 12:38:51.014  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:38:51.014  2641  2666 D BtGatt.ScanManager: handling starting scan
,08-23 12:38:51.014  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:38:51.015  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 12:38:51.015  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:38:51.016  2641  2666 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:38:51.017  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:38:51.018  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 12:38:51.018  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:38:51.019  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:38:51.021  3779  3829 I io.jxcore.node.ConnectionHelper: start: OK
08-23 12:38:51.022  2641  2660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 12:38:51.022  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:38:51.023  2641  2666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 12:38:51.023  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:38:51.023  3779  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 12:38:51.023  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.023  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 12:38:51.023  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.023  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 12:38:51.023  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 12:38:51.023  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 12:38:51.023  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:38:51.023  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 12:38:51.024  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:38:51.024  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:38:51.024  3779  3829 D BluetoothAdapter: STATE_ON
08-23 12:38:51.025  2641  2747 D BtGatt.GattService: stopScan() - queue size =1
08-23 12:38:51.025  2641  2770 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-23 12:38:51.025  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:38:51.025  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 12:38:51.025  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 12:38:51.025  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:38:51.026  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:38:51.027  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:38:51.028  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 12:38:51.028  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:38:51.028  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:38:51.028  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-23 12:38:51.029  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.029  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 12:38:51.029  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:51.029  2641  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 12:38:51.029  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:51.030  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.030  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:51.030  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:51.030  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
,08-23 12:38:51.030  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.030  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.030  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.030  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.030  3779  3829 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 12:38:51.030  2641  2666 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 12:38:51.031  2641  2666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 12:38:51.032  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:51.037  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:38:51.039  2641  2660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 12:38:51.039  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.040  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.040  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:38:51.040  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 12:38:51.040  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:38:51.040  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 12:38:51.040  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:51.040  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:38:51.041   872   881 I art     : Background partial concurrent mark sweep GC freed 50003(3MB) AllocSpace objects, 17(420KB) LOS objects, 33% free, 29MB/43MB, paused 1.254ms total 106.087ms
08-23 12:38:51.043  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.044  2641  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 12:38:51.044  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.045  3779  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 12:38:51.045  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.045  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-23 12:38:51.049  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:38:51.049  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 12:38:51.050  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:38:51.051  2641  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 12:38:51.052  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:38:51.052  2641  2666 D BtGatt.ScanManager: stopping BLe Batch
,08-23 12:38:51.053  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 12:38:51.053  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:38:51.053  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 12:38:51.053  3779  3829 D BluetoothAdapter: STATE_ON
,08-23 12:38:51.056  2641  2770 D BtGatt.GattService: registerClient() - UUID=1bc6ddaa-71c6-43df-b5dc-c5b4376677c7
,08-23 12:38:51.056  2641  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 12:38:51.056  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.056  2641  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-23 12:38:51.056  2641  2660 D BtGatt.GattService: onClientRegistered() - UUID=1bc6ddaa-71c6-43df-b5dc-c5b4376677c7, clientIf=5
08-23 12:38:51.057  3779  3790 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 12:38:51.057  2641  2652 D BtGatt.GattService: start scan with filters
,08-23 12:38:51.059  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:38:51.059  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:38:51.060  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 12:38:51.060  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 12:38:51.061  2641  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 12:38:51.061  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:38:51.062  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:38:51.062  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:38:51.062  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 12:38:51.062  2641  2666 D BtGatt.ScanManager: handling starting scan
,08-23 12:38:51.063  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-23 12:38:51.066  3779  3829 I io.jxcore.node.ConnectionHelper: start: OK
,08-23 12:38:51.067  2641  2660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 12:38:51.067  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.067  2641  2666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 12:38:51.068  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.068  3779  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 12:38:51.068  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.068  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 12:38:51.068  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.068  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 12:38:51.068  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:38:51.068  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:38:51.068  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:38:51.068  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 12:38:51.069  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:38:51.069  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 12:38:51.069  3779  3829 D BluetoothAdapter: STATE_ON
08-23 12:38:51.070  2641  2770 D BtGatt.GattService: stopScan() - queue size =1
08-23 12:38:51.071  2641  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 12:38:51.071  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.071  2641  2652 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 12:38:51.071  2641  2666 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:38:51.071  2641  2666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 12:38:51.071  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 12:38:51.071  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:38:51.071  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:38:51.071  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:38:51.072  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:38:51.072  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:51.073  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 12:38:51.073  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-23 12:38:51.073  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:38:51.073  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:38:51.074  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:51.074  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:51.074  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:51.075  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:38:51.075  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.075  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:51.075  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.075  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.075  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:51.075  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.075  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.075  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.075  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:51.076  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.076  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.076  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.076  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:51.077  3779  3829 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-23 12:38:51.078  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:51.078  2641  2660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 12:38:51.078  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:38:51.082  2641  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 12:38:51.082  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:51.083  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:51.085  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.085  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:51.086  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 12:38:51.086  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:38:51.086  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:38:51.086  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:51.087  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:38:51.087  2641  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 12:38:51.087  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.087  2641  2666 D BtGatt.ScanManager: stopping BLe Batch
,08-23 12:38:51.088  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:51.090  3779  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 12:38:51.090  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:38:51.090  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:51.092  2641  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 12:38:51.092  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.092  2641  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 12:38:51.094  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:38:51.094  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 12:38:51.095  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:38:51.096  2641  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 12:38:51.096  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:38:51.098  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 12:38:51.098  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:38:51.098  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 12:38:51.099  3779  3829 D BluetoothAdapter: STATE_ON
,08-23 12:38:51.101  2641  2652 D BtGatt.GattService: registerClient() - UUID=16a383b4-7e8b-4804-b95d-e72d978fc747
,08-23 12:38:51.101  2641  2660 D BtGatt.GattService: onClientRegistered() - UUID=16a383b4-7e8b-4804-b95d-e72d978fc747, clientIf=5
08-23 12:38:51.102  3779  3791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 12:38:51.102  2641  2747 D BtGatt.GattService: start scan with filters
,08-23 12:38:51.106  2641  2666 D BtGatt.ScanManager: handling starting scan
,08-23 12:38:51.106  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 12:38:51.106  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:38:51.106  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 12:38:51.106  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:38:51.108  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:38:51.108  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 12:38:51.109  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:38:51.110  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-23 12:38:51.110  2641  2660 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 12:38:51.110  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.110  2641  2666 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 12:38:51.112  3779  3829 I io.jxcore.node.ConnectionHelper: start: OK
08-23 12:38:51.112  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.112  3779  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 12:38:51.112  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.112  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-23 12:38:51.113  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.113  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 12:38:51.113  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:38:51.113  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:38:51.113  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:38:51.113  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:38:51.113  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:38:51.113  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:38:51.114  3779  3829 D BluetoothAdapter: STATE_ON
,08-23 12:38:51.114  2641  2747 D BtGatt.GattService: stopScan() - queue size =1
08-23 12:38:51.114  2641  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 12:38:51.115  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:38:51.115  2641  2666 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:38:51.115  2641  2666 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 12:38:51.115  2641  2653 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 12:38:51.115  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:38:51.115  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:38:51.115  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:38:51.115  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 12:38:51.116  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:38:51.117  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:51.118  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 12:38:51.118  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:38:51.118  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:38:51.118  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-23 12:38:51.119  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.119  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:51.119  3779  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-23 12:38:51.119  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:51.119  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:38:51.119  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:51.119  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.119  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.119  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.119  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:38:51.120  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.120  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.120  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:51.120  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.120  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.120  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.120  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.121  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:38:51.121  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.121  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.121  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:51.122  3779  3829 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-23 12:38:51.122  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.122  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:38:51.122  2641  2660 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 12:38:51.122  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.122  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.122  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:38:51.123  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.123  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.123  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.123  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:51.123  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.123  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:38:51.123  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.123  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:51.123  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.123  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.124  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.124  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.124  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:51.124  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.125  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-23 12:38:51.125  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:38:51.125  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:38:51.125  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 12:38:51.125  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.125  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.125  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:51.126  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
,08-23 12:38:51.126  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:38:51.126  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.126  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:38:51.126  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:51.126  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.126  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:38:51.126  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:51.126  2641  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 12:38:51.126  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.128  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.128  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:38:51.128  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.128  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list,
08-23 12:38:51.128  3779  3829 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-23 12:38:51.129  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.129  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:38:51.129  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 12:38:51.129  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-23 12:38:51.129  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.129  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.129  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
,08-23 12:38:51.129  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.129  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.129  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.129  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.129  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:51.130  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.130  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.130  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.130  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:38:51.130  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.131  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.131  3779  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-23 12:38:51.131  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.131  2641  2660 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 12:38:51.131  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.131  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.131  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.131  2641  2666 D BtGatt.ScanManager: stopping BLe Batch
08-23 12:38:51.131  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:38:51.131  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.131  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.132  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.132  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.132  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
,08-23 12:38:51.132  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.132  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.132  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.132  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.132  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:38:51.133  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.133  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.133  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.133  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.134  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:38:51.135  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 12:38:51.135  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:38:51.135  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:38:51.135  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-23 12:38:51.135  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-23 12:38:51.135  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.136  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.136  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.136  2641  2660 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 12:38:51.136  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.136  2641  2666 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 12:38:51.137  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.137  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.137  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.137  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.137  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.137  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.137  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:38:51.137  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.137  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.137  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.137  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.138  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.138  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:38:51.138  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.138  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.139  3779  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:51.139  3779  3829 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-23 12:38:51.139  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-23 12:38:51.141  2641  2660 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 12:38:51.141  2641  2660 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:38:51.142  3779  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:51.142  3779  3829 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-23 12:38:51.142  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-23 12:38:51.143  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-23 12:38:51.143  3779  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-23 12:38:51.144  3779  3829 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:38:51.144  3779  3829 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-23 12:38:51.144  3779  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:51.144  3779  3829 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:38:51.144  3779  3829 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-23 12:38:51.145  3779  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:51.145  3779  3829 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-23 12:38:51.145  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-23 12:38:51.148  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-23 12:38:51.149  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-23 12:38:51.149  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-23 12:38:51.150  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-23 12:38:51.150  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-23 12:38:51.150  3779  3829 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-23 12:38:51.150  3779  3829 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-23 12:38:51.150  3779  3829 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-23 12:38:51.151  3779  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
08-23 12:38:51.151  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.151  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.151  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.151  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.151  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.151  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.152  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-23 12:38:51.152  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.152  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.152  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.152  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.152  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.152  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.152  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.152  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.153  3779  3840 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-23 12:38:51.153  3779  3839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:38:51.153  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.153  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.153  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.153  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.154  3779  3829 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-23 12:38:51.154  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.155  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.155  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.155  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.155  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.155  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.155  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.155  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.155  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.155  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.155  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.155  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.155  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.155  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.156  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.156  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.156  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.156  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.157  3779  3829 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-23 12:38:51.157  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.157  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.157  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.157  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.158  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.158  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.158  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.158  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.158  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.158  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.158  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.158  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.158  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.158  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.159  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.159  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.159  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.159  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.160  3779  3829 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-23 12:38:51.160  3779  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-23 12:38:51.160  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:38:51.160  3779  3829 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-23 12:38:51.160  3779  3829 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 12:38:51.160  3779  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-23 12:38:51.160  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:38:51.160  3779  3829 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-23 12:38:51.160  3779  3829 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-23 12:38:51.160  3779  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-23 12:38:51.161  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:38:51.161  3779  3829 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-23 12:38:51.161  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.161  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.161  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.161  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.161  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.161  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.161  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.161  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.161  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.161  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.161  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.161  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.161  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.161  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.162  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.162  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.162  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.162  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.163  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.163  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.163  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.163  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.163  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.163  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.163  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.163  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.163  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.163  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.163  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.163  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.163  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.164  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.164  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.164  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.164  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.164  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.164  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.164  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.164  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.164  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.164  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.164  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.164  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.164  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.164  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.165  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.165  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.165  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.165  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.166  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.166  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.167  3779  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-23 12:38:51.167  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:51.167  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-23 12:38:51.168  3779  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-23 12:38:51.168  3779  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-23 12:38:51.168  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-23 12:38:51.168  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-23 12:38:51.168  3779  3779 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-23 12:38:51.168  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.168  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-23 12:38:51.168  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-23 12:38:51.168  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-23 12:38:51.169  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.169  3779  3829 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-23 12:38:51.169  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.169  3779  3779 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-23 12:38:51.169  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.169  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:38:51.169  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:38:51.169  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:38:51.169  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.169  3779  3841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:38:51.169  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.170  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:51.170  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.170  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.170  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:51.170  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.170  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:38:51.170  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 12:38:51.170  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.170  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:38:51.170  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.170  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.170  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.170  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.170  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.170  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.170  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.170  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.171  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.171  3779  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-23 12:38:51.171  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.171  3779  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-23 12:38:51.171  3779  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-23 12:38:51.171  3779  3779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-23 12:38:51.171  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.171  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.171  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.171  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.172  3779  3829 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-23 12:38:51.172  3779  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-23 12:38:51.172  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-23 12:38:51.173  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-23 12:38:51.173  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.173  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.173  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.173  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.173  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.173  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.173  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.173  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.173  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.173  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.173  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.173  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.173  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.173  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.174  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.174  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.174  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.174  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.177  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.177  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.177  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.177  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.177  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.177  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.177  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.177  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.177  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.177  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.177  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.177  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.177  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.177  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.178  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.178  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.178  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.178  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.179  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:38:51.179  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:38:51.179  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:38:51.179  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:38:51.179  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.179  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.179  3779  3829 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269b44b not in the list
08-23 12:38:51.179  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.179  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.179  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:38:51.179  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.179  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.179  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:38:51.180  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:38:51.180  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:38:51.180  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:38:51.180  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:38:51.180  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f2ce28 not in the list
08-23 12:38:51.181  3779  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-23 12:38:51.181  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:38:51.181  3779  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-23 12:38:51.181  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-23 12:38:51.181  3779  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-23 12:38:51.181  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-23 12:38:51.183  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-23 12:38:51.183  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-23 12:38:51.183  3779  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-23 12:38:51.183  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 12:38:51.183  3779  3829 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-23 12:38:51.183  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-23 12:38:51.183  3779  3829 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-23 12:38:51.183  3779  3829 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-23 12:38:51.184  3779  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-23 12:38:51.184  3779  3829 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-23 12:38:51.184  3779  3829 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-23 12:38:51.184  3779  3829 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-23 12:38:51.184  3779  3829 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-23 12:38:51.185  3779  3829 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-23 12:38:51.185  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:51.185  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f7284ca added. We now have 2 listener(s)
08-23 12:38:51.185  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:38:51.186  3779  3829 D BluetoothAdapter: enable(): BT is already enabled..!
,08-23 12:38:51.186   872  1952 D WifiService: setWifiEnabled: true pid=3779, uid=10000
08-23 12:38:51.186   872  1952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
08-23 12:38:51.187  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:51.187  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@674463b added. We now have 3 listener(s),
08-23 12:38:51.187  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:51.191  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:38:51.191  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@98a1158 added. We now have 4 listener(s)
,08-23 12:38:51.191  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:38:51.192  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:38:51.192  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32262b1 added. We now have 5 listener(s)
,08-23 12:38:51.192  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:38:51.193   872  1686 D WifiService: setWifiEnabled: false pid=3779, uid=10000
08-23 12:38:51.193   872  1686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-23 12:38:51.197  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:38:51.198  2641  2656 D BluetoothAdapterState: Current state: ON, message: 23
08-23 12:38:51.198  2641  2656 D BluetoothAdapterProperties: Setting state to 13
08-23 12:38:51.198  2641  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-23 12:38:51.199  2641  2656 D BluetoothAdapterProperties: onBluetoothDisable()
08-23 12:38:51.199  2641  2656 I BluetoothAdapterState: Entering PendingCommandState
08-23 12:38:51.200  2641  2641 D BluetoothMapService: onReceive
08-23 12:38:51.200  2641  2641 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:38:51.200  2641  2641 D BluetoothMapService: STATE_TURNING_OFF
,08-23 12:38:51.200  2641  2641 D BluetoothMapService: MAP Service closeService in
,08-23 12:38:51.200  2641  2641 D BluetoothMapMasInstance0: MAP Service shutdown
,08-23 12:38:51.200  2641  2641 D ObexServerSockets0: shutdown(block = true)
08-23 12:38:51.201  2641  2641 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 12:38:51.201  2641  2641 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 12:38:51.201  2641  2785 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-23 12:38:51.201  2641  2786 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-23 12:38:51.201  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:51.201  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:38:51.202  2641  2744 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-23 12:38:51.202  2641  2641 I BtOppRfcommListener: stopping Accept Thread
,08-23 12:38:51.202  2641  3407 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-23 12:38:51.202  2641  3407 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-23 12:38:51.203  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:51.203  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.203  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:38:51.209  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:51.211  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-23 12:38:51.211  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.214  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:51.214  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:38:51.214  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:51.214  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:51.216  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.217   872   885 I ActivityManager: Start proc 3844:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-23 12:38:51.217   872  1300 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-23 12:38:51.217   872  1300 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-23 12:38:51.217  2641  2660 D BluetoothAdapterProperties: Scan Mode:20
08-23 12:38:51.217   872  1300 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 12:38:51.217  2641  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-23 12:38:51.217   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 12:38:51.221  2641  2641 D HeadsetService: Received stop request...Stopping profile...
08-23 12:38:51.223  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.225   872  1872 D DhcpClient: Clearing IP address
08-23 12:38:51.225  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.225   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:38:51.226   872   872 D BluetoothHeadset: Proxy object disconnected
,08-23 12:38:51.226   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 12:38:51.226   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 12:38:51.226  1912  2058 D BluetoothHeadset: Proxy object disconnected
08-23 12:38:51.227  2641  2641 D A2dpService: Received stop request...Stopping profile...
08-23 12:38:51.227  1353  1384 D BluetoothHeadset: Proxy object disconnected
08-23 12:38:51.227  2641  2752 D A2dpStateMachine: Exit Disconnected: -1
08-23 12:38:51.228   371   870 D CommandListener: Setting iface cfg
,08-23 12:38:51.229   872   872 D BluetoothA2dp: Proxy object disconnected
08-23 12:38:51.229  1519  2087 V NativeCrypto: Read error: ssl=0xaeb6ae00: I/O error during system call, Connection timed out
,08-23 12:38:51.229  2641  2641 V BluetoothAdapterState: isTurningOff()=true
,08-23 12:38:51.229  2641  2641 V BluetoothAdapterState: isTurningOn()=false
08-23 12:38:51.230  2641  2641 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:38:51.230  2641  2641 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:38:51.230  2641  2641 D HidService: Received stop request...Stopping profile...
08-23 12:38:51.230  2641  2641 D HidService: Stopping Bluetooth HidService
08-23 12:38:51.230  1519  2087 V NativeCrypto: SSL shutdown failed: ssl=0xaeb6ae00: I/O error during system call, Broken pipe
08-23 12:38:51.232  2641  2641 D HealthService: Received stop request...Stopping profile...
,08-23 12:38:51.232   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 12:38:51.232   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-23 12:38:51.232   872  1300 D WifiStateMachine: Start Disconnecting Watchdog 1
08-23 12:38:51.233   872  1300 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 12:38:51.235   394   394 E Parcel  : Reading a NULL string not supported here.
08-23 12:38:51.236  1353  1353 D HeadsetProfile: Bluetooth service disconnected
08-23 12:38:51.236  1353  1353 D BluetoothA2dp: Proxy object disconnected
,08-23 12:38:51.236  1353  1353 D BluetoothInputDevice: Proxy object disconnected
08-23 12:38:51.236  1353  1353 D HidProfile: Bluetooth service disconnected
08-23 12:38:51.236  2641  2641 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 12:38:51.236  2641  2641 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:38:51.237  2641  2660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-23 12:38:51.237  2641  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:38:51.237  2641  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:38:51.237  2641  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-23 12:38:51.237  2641  2641 D PanService: Received stop request...Stopping profile...
08-23 12:38:51.238  2641  2660 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-23 12:38:51.238  2641  2641 D BluetoothMapService: Received stop request...Stopping profile...
08-23 12:38:51.238  2641  2641 D BluetoothMapService: stop()
08-23 12:38:51.239  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 12:38:51.239  1353  1353 D PanProfile: Bluetooth service disconnected
08-23 12:38:51.239  2641  2641 D BluetoothMapAppObserver: deinitObservers()
,08-23 12:38:51.239  2641  2641 D BluetoothMapAppObserver: removeReceiver()
08-23 12:38:51.240   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-23 12:38:51.241  1353  1353 D BluetoothMap: Proxy object disconnected
08-23 12:38:51.241  1353  1353 D MapProfile: Bluetooth service disconnected
08-23 12:38:51.241  2641  2641 V BluetoothAdapterState: isTurningOff()=true
08-23 12:38:51.241  2641  2641 V BluetoothAdapterState: isTurningOn()=false
08-23 12:38:51.241  2641  2641 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 12:38:51.241  2641  2641 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:38:51.242   872  1302 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-23 12:38:51.244  2641  2660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-23 12:38:51.244  2641  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:38:51.244  2641  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:38:51.244  2641  2732 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:38:51.244  2641  2732 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:38:51.244  2641  2732 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-23 12:38:51.244  2641  2732 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:38:51.244  2641  2641 V BluetoothAdapterState: isTurningOff()=true
08-23 12:38:51.244  2641  2641 V BluetoothAdapterState: isTurningOn()=false
08-23 12:38:51.244  2641  2641 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:38:51.244  2641  2641 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:38:51.244  2641  2641 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 12:38:51.245  2641  2660 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 12:38:51.245  2641  2641 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 12:38:51.245  2641  2641 V BluetoothAdapterState: isTurningOff()=true
08-23 12:38:51.245  2641  2641 V BluetoothAdapterState: isTurningOn()=false
08-23 12:38:51.246  2641  2641 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:38:51.246  2641  2641 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:38:51.246  2641  2641 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 12:38:51.246  2641  2660 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-23 12:38:51.246  2641  2641 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-23 12:38:51.246  2641  2641 V BluetoothAdapterState: isTurningOff()=true
08-23 12:38:51.246  2641  2641 V BluetoothAdapterState: isTurningOn()=false
08-23 12:38:51.247  2641  2641 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:38:51.247  2641  2641 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:38:51.247  2641  2641 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 12:38:51.247  2641  2641 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-23 12:38:51.251   872  1300 D WifiConfigStore: Retrieve network priorities after PNO.
08-23 12:38:51.252  2641  2641 D BluetoothMapService: MAP Service closeService in
08-23 12:38:51.252  2641  2641 V BluetoothAdapterState: isTurningOff()=true
08-23 12:38:51.252  2641  2641 V BluetoothAdapterState: isTurningOn()=false
08-23 12:38:51.252  2641  2641 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:38:51.252  2641  2641 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:38:51.252  2641  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 12:38:51.252  2641  2656 D BluetoothAdapterProperties: Setting state to 15
08-23 12:38:51.252  2641  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-23 12:38:51.253  2641  2656 I BluetoothAdapterState: Entering BleOnState
08-23 12:38:51.253  2641  2641 D BluetoothMapService: cleanup()
08-23 12:38:51.253  2641  2641 D BluetoothMapService: MAP Service closeService in
08-23 12:38:51.253  1353  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 12:38:51.256   872  1300 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-23 12:38:51.258   872  1881 D DhcpClient: Receive thread stopped
08-23 12:38:51.259   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:38:51.259  1912  1930 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:38:51.259   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:38:51.259  1353  2009 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:38:51.260  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:51.260  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:51.260  1353  1384 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 12:38:51.261  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:51.261  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:38:51.261  1353  1375 D BluetoothMap: onBluetoothStateChange: up=false
08-23 12:38:51.262  1353  2009 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:38:51.262   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:38:51.262  2119  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 12:38:51.262  1353  1384 D BluetoothPan: onBluetoothStateChange on: false
,08-23 12:38:51.262   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:38:51.262  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:51.263  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:38:51.263  2641  2656 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-23 12:38:51.263  2641  2656 D BluetoothAdapterProperties: Setting state to 16
08-23 12:38:51.263  2641  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-23 12:38:51.263  2641  2656 D BluetoothAdapterProperties: onBleDisable
,08-23 12:38:51.263  2641  2656 I BluetoothAdapterState: Entering PendingCommandState
08-23 12:38:51.264  2641  2657 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-23 12:38:51.264  2641  2660 D BluetoothAdapterProperties: Scan Mode:20
08-23 12:38:51.264  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:51.264  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:38:51.265  2641  2732 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-23 12:38:51.265  2641  2732 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:38:51.266  3779  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
08-23 12:38:51.266  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.268  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.271  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:51.273  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:51.286   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:38:51.301  3844  3844 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-23 12:38:51.306   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:38:51.306   872  1302 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-23 12:38:51.307   872  1302 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:51.308   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-23 12:38:51.311  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:51.312  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:51.313  3394  3394 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@e4623b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-23 12:38:51.319  3844  3844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:38:51.324  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:38:51.325   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b3678c8:true
,08-23 12:38:51.336   872  1362 I ActivityManager: Start proc 3862:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-23 12:38:51.359  3844  3844 D LocalBluetoothProfileManager: Adding local MAP profile
,08-23 12:38:51.360  3844  3844 D BluetoothMap: Create BluetoothMap proxy object
,08-23 12:38:51.364   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-23 12:38:51.370  3844  3844 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-23 12:38:51.375  3862  3862 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-23 12:38:51.384  3844  3844 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:38:51.387   872  1955 I ActivityManager: Killing 3050:com.google.android.talk/u0a61 (adj 15): empty #17
,08-23 12:38:51.474  2641  2660 I bt_hci  : shut_down
,08-23 12:38:51.486  2641  2668 D bt_hwcfg: hw_epilog_process
,08-23 12:38:51.487  2641  2668 I bt_vendor: low_power_mode_cb
,08-23 12:38:51.510  2641  2668 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-23 12:38:51.510  2641  2668 I bt_vendor: epilog_cb
,08-23 12:38:51.510  2641  2668 I bt_hci  : epilog_finished_callback
,08-23 12:38:51.515  2641  2660 I bt_hci_h4: hal_close
,08-23 12:38:51.515  2641  2660 I bt_userial_vendor: device fd = 51 close
,08-23 12:38:51.572  3862  3862 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.572  3862  3862 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.572  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.573  3862  3862 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.573  3862  3862 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.573  3862  3862 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.k.d(PG:583)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:170)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.573  3862  3862 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.573  3862  3862 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.File.exists(File.java:361)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.573  3862  3862 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:38:51.573  3862  3862 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-23 12:38:51.599   872   883 I ActivityManager: Start proc 3893:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-23 12:38:51.602   872   883 I ActivityManager: Killing 3541:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-23 12:38:51.671  3779  3779 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 12:38:51.685  2641  2657 D bt_stack_manager: event_shut_down_stack finished.
,08-23 12:38:51.685  2641  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 12:38:51.687  3893  3893 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-23 12:38:51.690  2641  2641 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 12:38:51.689  2641  2656 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-23 12:38:51.690  2641  2641 D BtGatt.GattService: Received stop request...Stopping profile...
08-23 12:38:51.690  2641  2641 D BtGatt.GattService: stop()
,08-23 12:38:51.690  2641  2641 D BtGatt.AdvertiseManager: advertise clients cleared
,08-23 12:38:51.693  2641  2641 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:38:51.693  2641  2641 V BluetoothAdapterState: isTurningOn()=false
,08-23 12:38:51.693  2641  2641 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 12:38:51.693  2641  2641 V BluetoothAdapterState: isBleTurningOff()=true
08-23 12:38:51.694  2641  2656 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-23 12:38:51.695  2641  2656 D BluetoothAdapterProperties: Setting state to 10
,08-23 12:38:51.695  2641  2656 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-23 12:38:51.696  2641  2656 I BluetoothAdapterState: Entering OffState
,08-23 12:38:51.698   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-23 12:38:51.715  2641  2641 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-23 12:38:51.715  2641  2641 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-23 12:38:51.715  2641  2657 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-23 12:38:51.717  2641  2657 D bt_stack_manager: event_clean_up_stack finished.
,08-23 12:38:51.718  2641  2641 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 12:38:51.722  2641  2641 I art     : System.exit called, status: 0
,08-23 12:38:51.722  2641  2641 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 12:38:51.776  3893  3893 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-23 12:38:51.798   872   883 I ActivityManager: Process com.android.bluetooth (pid 2641) has died
,08-23 12:38:51.827   872  1686 I ActivityManager: Start proc 3920:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-23 12:38:51.878  3920  3920 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-23 12:38:51.923  3862  3889 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-23 12:38:52.082   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36e29e6:true
,08-23 12:38:52.084  3920  3938 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
08-23 12:38:52.085  3920  3938 I Babel_SMS: MmsConfig.loadMmsSettings
08-23 12:38:52.086  3920  3938 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-23 12:38:52.086  3920  3938 I Babel_SMS: MmsConfig.loadFromDatabase
,08-23 12:38:52.139  3920  3938 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-23 12:38:52.140  3920  3938 I Babel_SMS: MmsConfig.loadFromResources
,08-23 12:38:52.142  3920  3938 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-23 12:38:52.143  3920  3938 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-23 12:38:52.179  3920  3920 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:38:52.182  3920  3920 I Babel_Crash: startup - clean
,08-23 12:38:52.224  3920  3920 I Babel_telephony: TeleModule.launchCompleted
,08-23 12:38:52.229   872  2109 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-23 12:38:52.237  3920  3920 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-23 12:38:52.248  3920  3920 W Babel   : BAM#gBA: invalid account id: -1
08-23 12:38:52.248  3920  3920 W Babel   : BAM#gBA: invalid account id: -1
08-23 12:38:52.249  3920  3920 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-23 12:38:52.252   872   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-23 12:38:52.261  3920  3943 I Babel   : deleted: false for 0
,08-23 12:38:52.268  3844  3844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:38:52.306   872  1955 I ActivityManager: Start proc 3946:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-23 12:38:52.307  3920  3920 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:52.311  3844  3844 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:38:52.405  3920  3920 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-23 12:38:52.416  3920  3920 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:52.418  3920  3920 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:52.435  3920  3920 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:52.461  3920  3920 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-23 12:38:52.466   872  1686 I ActivityManager: Killing 3394:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-23 12:38:52.588  3946  3946 D AdapterServiceConfig: Adding HeadsetService
,08-23 12:38:52.588  3946  3946 D AdapterServiceConfig: Adding A2dpService
08-23 12:38:52.588  3946  3946 D AdapterServiceConfig: Adding HidService
08-23 12:38:52.589  3946  3946 D AdapterServiceConfig: Adding HealthService
08-23 12:38:52.589  3946  3946 D AdapterServiceConfig: Adding PanService
08-23 12:38:52.589  3946  3946 D AdapterServiceConfig: Adding GattService
08-23 12:38:52.589  3946  3946 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 12:38:52.594  3920  3920 I vclib   : onServiceConnected
,08-23 12:38:52.599   872  1952 I ActivityManager: Killing 3587:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-23 12:38:52.651  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:38:52.683  1735  1735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 12:38:52.689  1735  1735 D SystemUpdateService: onCreate
,08-23 12:38:52.693  1735  1735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 12:38:52.711  1735  3960 I SystemUpdateService: active receiver: enabled
,08-23 12:38:52.725  1735  3960 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 12:38:52.726  1735  3960 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-23 12:38:52.727  1735  3960 I SystemUpdateService: now status is 0 (complete)
,08-23 12:38:52.727  1735  3960 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-23 12:38:52.727  1735  3960 I SystemUpdateService: file has been verified
,08-23 12:38:52.728  1735  1735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-23 12:38:52.730  1735  2410 I iu.UploadsManager: num queued entries: 0
,08-23 12:38:52.730  1735  2410 I iu.UploadsManager: num updated entries: 0
,08-23 12:38:52.728  1735  3960 I SystemUpdateService: OTA package size = 12249756
08-23 12:38:52.736  1735  1735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 12:38:52.737  1735  2410 I iu.SyncManager: NEXT; no task
,08-23 12:38:52.737  1735  1735 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 12:38:52.745  1735  3960 I SystemUpdateService: showing system update notification
,08-23 12:38:52.768   872   883 I ActivityManager: Start proc 3962:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-23 12:38:52.770  1735  1735 D SystemUpdateService: onDestroy
,08-23 12:38:52.799  3962  3962 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-23 12:38:52.802  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:52.808  3962  3962 D SprintDMHelper: simOperator: 
08-23 12:38:52.808  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 12:38:52.822   872  2109 I ActivityManager: Start proc 3974:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher,
08-23 12:38:52.823   872  2109 I ActivityManager: Killing 2772:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-23 12:38:52.971   872  1955 I ActivityManager: Start proc 3989:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-23 12:38:52.976  3920  3988 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-23 12:38:52.981   872  1927 I ActivityManager: Killing 3468:android.process.acore/u0a5 (adj 15): empty #17
,08-23 12:38:53.052  3989  3989 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-23 12:38:53.116  3989  3989 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-23 12:38:53.116  3989  3989 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 12:38:53.116  3989  3989 I GAv4    :   adb logcat -s GAv4
,08-23 12:38:53.142  3989  3989 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:38:53.148  3989  3989 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:38:53.179  3989  4006 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-23 12:38:53.332  3989  3989 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-23 12:38:53.376  3989  3989 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-23 12:38:53.388  3989  3989 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6461-6464)
,08-23 12:38:53.389  3989  3989 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 12:38:53.399  3989  3989 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ae502b}
,08-23 12:38:53.399  3989  3989 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-23 12:38:53.400  3989  3989 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 12:38:53.409  3989  3989 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 12:38:53.411  3989  3989 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 12:38:53.430  3989  3989 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-23 12:38:53.443  3989  3989 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 12:38:53.443  3989  3989 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 12:38:53.443  3989  3989 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 12:38:53.443  3989  3989 I Adreno  : Build Date                       : 10/20/15
08-23 12:38:53.443  3989  3989 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 12:38:53.443  3989  3989 I Adreno  : Local Branch                     : M14
08-23 12:38:53.443  3989  3989 I Adreno  : Remote Branch                    : 
08-23 12:38:53.443  3989  3989 I Adreno  : Remote Branch                    : 
08-23 12:38:53.443  3989  3989 I Adreno  : Reconstruct Branch               : 
,08-23 12:38:53.508  3989  3989 I NSApplication: Starting up...
,08-23 12:38:53.525  3989  4035 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-23 12:38:53.550   872  1952 I ActivityManager: Start proc 4040:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-23 12:38:53.554   872  1952 I ActivityManager: Killing 3664:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-23 12:38:53.656  4040  4040 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-23 12:38:53.842   872  1955 I ActivityManager: Killing 3681:com.android.musicfx/u0a18 (adj 15): empty #17
,08-23 12:38:54.206   872  3958 D WifiService: setWifiEnabled: true pid=3779, uid=10000
,08-23 12:38:54.206   872  3958 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 12:38:54.222   872  1300 D WifiConfigStore: Loading config and enabling all networks 
,08-23 12:38:54.230  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:54.230  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:54.231  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:54.231  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:38:54.233  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:54.234  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:54.234  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:54.234  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:38:54.265   872  1300 D WifiConfigStore: loaded 0 passpoint configs
,08-23 12:38:54.268   872  1300 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-23 12:38:54.271   872  1300 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 12:38:54.273   872  1300 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 12:38:54.275   872  1300 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-23 12:38:54.275   872  1300 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-23 12:38:54.275   872  1300 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 12:38:54.297   872  1300 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.25 rxSuccessRate=10.00 delta 1000 -> 994
,08-23 12:38:54.297   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-23 12:38:54.300   371   870 D CommandListener: Setting iface cfg
,08-23 12:38:54.302   872  1299 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,08-23 12:38:54.302   872  1299 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 12:38:54.308   872  1300 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-23 12:38:54.308   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:38:54.315   872  1300 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 12:38:54.351   872  1299 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 12:38:54.359   872  1299 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 12:38:54.367   872  1300 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 12:38:54.382  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 12:38:55.947  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 12:38:55.988  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-23 12:38:55.989  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 12:38:55.990   872  1300 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 12:38:55.998   872  1300 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 12:38:55.998   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-23 12:38:55.998   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 12:38:56.017   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:38:56.030   371   870 D CommandListener: Setting iface cfg
,08-23 12:38:56.031   872  1300 D WifiStateMachine: Start Dhcp Watchdog 2
,08-23 12:38:56.048   872  1302 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-23 12:38:56.052   872  1300 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 12:38:56.073   872  4067 D DhcpClient: Receive thread started
,08-23 12:38:56.157   872  1300 E native  : do suspend false
,08-23 12:38:56.179   872  1872 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 12:38:56.195   872  4067 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172694, domain null
,08-23 12:38:56.196   872  1872 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172694 seconds
,08-23 12:38:56.199   872  1872 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 12:38:56.214   872  4067 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 12:38:56.215   872  1872 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 12:38:56.220   371   870 D CommandListener: Setting iface cfg
,08-23 12:38:56.231   872  1300 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 12:38:56.231   872  1872 D DhcpClient: Scheduling renewal in 86399s
,08-23 12:38:56.246   872  1300 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 12:38:56.255   872  1300 D WifiConfigStore: No blacklist allowed without epno enabled
08-23 12:38:56.255   872  1302 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 12:38:56.257   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 12:38:56.261   872  1302 D ConnectivityService: Adding iface wlan0 to network 101
08-23 12:38:56.272   872  1300 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 12:38:56.312   872  1302 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-23 12:38:56.312   872  1302 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-23 12:38:56.313   872  1302 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-23 12:38:56.314   872  1302 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-23 12:38:56.315   872  1302 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-23 12:38:56.325   872  1302 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-23 12:38:56.329   872  1302 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-23 12:38:56.329   872  1302 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-23 12:38:56.329   872  1302 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-23 12:38:56.329   872  1300 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-23 12:38:56.329   872  1302 D ConnectivityService:    accepting network in place of null
08-23 12:38:56.330   872  1300 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 12:38:56.330   872  1302 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 12:38:56.342   872  4066 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129418, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 12:38:56.362   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:38:56.396   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:38:56.406   872  1302 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-23 12:38:56.406   872  1302 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:56.411   872  4064 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-23 12:38:56.413   872  1302 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-23 12:38:56.417   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-23 12:38:56.426  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:56.426  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:38:56.426  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:56.426  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:56.439  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:38:56.439  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:38:56.439  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:56.439  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:38:56.488   872   884 I ActivityManager: Start proc 4075:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-23 12:38:56.494  1735  1735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 12:38:56.497  1735  1735 D SystemUpdateService: onCreate
,08-23 12:38:56.501  1735  1735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 12:38:56.507  1735  4090 I SystemUpdateService: active receiver: enabled
,08-23 12:38:56.510  1735  4090 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 12:38:56.515  4075  4075 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-23 12:38:56.524  1735  1735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-23 12:38:56.525   872  4064 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 10:38:56 GMT], X-Android-Received-Millis=[1471948736523], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471948736478]}
,08-23 12:38:56.526  1735  4090 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-23 12:38:56.530   872  1302 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-23 12:38:56.531  1735  4090 I SystemUpdateService: now status is 0 (complete)
08-23 12:38:56.531   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-23 12:38:56.531   872  1302 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-23 12:38:56.531  1735  4090 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-23 12:38:56.531  1735  4090 I SystemUpdateService: file has been verified
,08-23 12:38:56.532  1735  4090 I SystemUpdateService: OTA package size = 12249756
08-23 12:38:56.532   872  1302 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-23 12:38:56.541  1735  4090 I SystemUpdateService: showing system update notification
,08-23 12:38:56.540  1735  2410 I iu.UploadsManager: num queued entries: 0
,08-23 12:38:56.542  1735  2410 I iu.UploadsManager: num updated entries: 0,
08-23 12:38:56.543  1735  2410 I iu.SyncManager: NEXT; no task
,08-23 12:38:56.547  1735  1735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 12:38:56.548  1735  1735 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 12:38:56.552  1735  1735 D SystemUpdateService: onDestroy
,08-23 12:38:56.552  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:56.555  1735  4093 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-23 12:38:56.555  1735  4093 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 12:38:56.557  1735  4093 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 12:38:56.561  3962  3962 D SprintDMHelper: simOperator: 
,08-23 12:38:56.561  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 12:38:56.564  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 12:38:56.567  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:38:56.609  1519  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-23 12:38:56.609  1519  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-23 12:38:56.609  1519  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 12:38:56.609  1519  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:56.613  4075  4075 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-23 12:38:56.622  4075  4075 I BooksApp: Created application version: 3.6.9 (30609)
08-23 12:38:56.626  1735  4093 E MDM     : [175] SitrepService.a: Error sending sitrep.
,08-23 12:38:56.646  3003  4104 V KeepSync: Connecting to GoogleApiClient
,08-23 12:38:56.647   872  1362 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-23 12:38:56.689  1519  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-23 12:38:56.689  1519  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-23 12:38:56.689  1519  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:38:56.689  1519  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:56.699  1735  4113 V BaseAuthAsyncOperation: access token request failed
,08-23 12:38:56.700  3003  4104 V KeepSync: GoogleApiClient failed to connect with error code: 4
08-23 12:38:56.701  3920  4098 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 12:38:56.715  4075  4110 I BooksSync: Starting books sync for 61035162, extras: ade
,08-23 12:38:56.795  1519  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-23 12:38:56.795  1519  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-23 12:38:56.795  1519  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:38:56.795  1519  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:56.828  3003  4104 E KeepSync: IOException
08-23 12:38:56.828  3003  4104 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-23 12:38:56.828  3003  4104 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-23 12:38:56.828  3003  4104 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-23 12:38:56.828  3003  4104 E KeepSync: 	... 10 more
,08-23 12:38:56.828  3003  4104 W KeepSync: Sync result 2
,08-23 12:38:56.847   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 127655, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-23 12:38:56.863  4075  4120 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-23 12:38:56.949  1519  2267 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 12:38:56.949  1519  2267 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-23 12:38:56.950  1519  2267 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:38:56.950  1519  2267 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:57.008  1519  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-23 12:38:57.008  1519  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-23 12:38:57.008  1519  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:38:57.008  1519  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:57.031  4075  4120 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-23 12:38:57.033  4075  4110 E BooksSync: Soft error
08-23 12:38:57.033  4075  4110 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 12:38:57.033  4075  4110 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-23 12:38:57.033  4075  4110 E BooksSync: Sync error
08-23 12:38:57.033  4075  4110 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-23 12:38:57.033  4075  4110 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-23 12:38:57.033  4075  4110 I BooksSync: Finished books sync
,08-23 12:38:57.046   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 127609, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-23 12:38:57.046   872  1952 I ActivityManager: Killing 2183:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-23 12:38:57.213   872  4103 D WifiService: setWifiEnabled: false pid=3779, uid=10000
,08-23 12:38:57.213   872  4103 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 12:38:57.229  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-23 12:38:57.232   872  1300 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-23 12:38:57.232   872  1300 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-23 12:38:57.232   872  1300 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 12:38:57.232   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:38:57.239   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-23 12:38:57.238   872  1872 D DhcpClient: Clearing IP address
08-23 12:38:57.243  1519  4112 V NativeCrypto: Read error: ssl=0x9b3bb000: I/O error during system call, Connection timed out
,08-23 12:38:57.247   371   870 D CommandListener: Setting iface cfg
,08-23 12:38:57.247  1519  4112 V NativeCrypto: SSL shutdown failed: ssl=0x9b3bb000: I/O error during system call, Broken pipe
08-23 12:38:57.250   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-23 12:38:57.250   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-23 12:38:57.255   872  1300 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-23 12:38:57.257   394   394 E Parcel  : Reading a NULL string not supported here.
08-23 12:38:57.258   872  1300 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-23 12:38:57.259   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-23 12:38:57.261   872  1302 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-23 12:38:57.271   872  4067 D DhcpClient: Receive thread stopped
,08-23 12:38:57.278   872  1300 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 12:38:57.278  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:57.278  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:38:57.278  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:57.279  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:38:57.279  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:38:57.279  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:38:57.279  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:38:57.279  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:38:57.280   872  1300 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-23 12:38:57.280  2119  2312 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-23 12:38:57.298  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 12:38:57.298  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 12:38:57.298  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:38:57.298  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:57.308   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:38:57.312  3523  4122 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-23 12:38:57.312  3523  4122 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jdm.a(PG:82)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jcs.o(PG:406)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jcn.a(PG:1379)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jcs.i(PG:143)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at blb.a(PG:3937)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at czp.a(PG:18188)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at czp.a(PG:9081)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at czq.run(PG:1686)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:38:57.312  3523  4122 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jdj.a(PG:4091)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jdj.a(PG:1125)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jdm.a(PG:77)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	... 12 more
08-23 12:38:57.312  3523  4122 E HttpOperation: Caused by: faj: BadAuthentication
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at fal.a(PG:38)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	at jdj.a(PG:4089)
08-23 12:38:57.312  3523  4122 E HttpOperation: 	... 14 more
,08-23 12:38:57.331   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:38:57.332   872  1302 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-23 12:38:57.332   872  1302 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:57.335   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-23 12:38:57.338  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:38:57.339  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:38:57.347  1519  2879 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-23 12:38:57.347  1519  2879 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-23 12:38:57.347  1519  2879 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:38:57.347  1519  2879 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:38:57.360  3523  4122 E HttpOperation: [getmobileexperiments] Unexpected exception
08-23 12:38:57.360  3523  4122 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jdm.a(PG:82)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jcs.o(PG:406)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jcn.a(PG:1379)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jcs.i(PG:143)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at hec.a(PG:42)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at hee.a(PG:102)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at czr.a(PG:65)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at kka.a(PG:108)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at czp.a(PG:19176)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at czp.a(PG:9081)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at czq.run(PG:1686)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:38:57.360  3523  4122 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jdj.a(PG:4091)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jdj.a(PG:1125)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jdm.a(PG:77)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	... 15 more
08-23 12:38:57.360  3523  4122 E HttpOperation: Caused by: faj: BadAuthentication
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at fal.a(PG:38)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	at jdj.a(PG:4089)
08-23 12:38:57.360  3523  4122 E HttpOperation: 	... 17 more
,08-23 12:38:57.360  3523  4122 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-23 12:38:57.360  3523  4122 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jdm.a(PG:82)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jcs.o(PG:406)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jcn.a(PG:1379)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jcs.i(PG:143)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at hec.a(PG:42)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at hee.a(PG:102)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at czr.a(PG:65)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at kka.a(PG:108)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at czp.a(PG:19176)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at czp.a(PG:9081)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at czq.run(PG:1686)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jdj.a(PG:4091)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jdj.a(PG:1125)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jdm.a(PG:77)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	... 15 more
08-23 12:38:57.360  3523  4122 E ExperimentLoader: Caused by: faj: BadAuthentication
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at fal.a(PG:38)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	at jdj.a(PG:4089)
08-23 12:38:57.360  3523  4122 E ExperimentLoader: 	... 17 more
,08-23 12:38:57.364  1735  1735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 12:38:57.370  1735  1735 D SystemUpdateService: onCreate
,08-23 12:38:57.373  1735  1735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 12:38:57.382  1735  1735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-23 12:38:57.389  1735  2410 I iu.UploadsManager: num queued entries: 0
,08-23 12:38:57.393  1735  1735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 12:38:57.396  1735  1735 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 12:38:57.398  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:38:57.405   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-23 12:38:57.406   872  1302 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-23 12:38:57.406   872  1302 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-23 12:38:57.407  3962  3962 D SprintDMHelper: simOperator: 
,08-23 12:38:57.407  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 12:38:57.439  1735  2410 I iu.UploadsManager: num updated entries: 0
,08-23 12:38:57.444  1735  4134 I SystemUpdateService: active receiver: enabled
,08-23 12:38:57.452  3920  4137 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-23 12:38:57.468  1735  2410 I iu.SyncManager: NEXT; no task
,08-23 12:38:57.470   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130054, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-23 12:38:57.476  1735  4134 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 12:38:57.479  1735  4134 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-23 12:38:57.479  1735  4134 I SystemUpdateService: now status is 0 (complete)
08-23 12:38:57.479  1735  4134 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-23 12:38:57.479  1735  4134 I SystemUpdateService: file has been verified
08-23 12:38:57.479  1735  4134 I SystemUpdateService: OTA package size = 12249756
,08-23 12:38:57.484  1735  4134 I SystemUpdateService: showing system update notification
,08-23 12:38:57.492  1735  1735 D SystemUpdateService: onDestroy
,08-23 12:38:57.494   872  1955 I ActivityManager: Killing 3702:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-23 12:39:00.266   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cf5c74e:true
,08-23 12:39:00.266  3946  3946 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 12:39:00.271  3946  3946 I bt_bluedroid: init
,08-23 12:39:00.272  3946  4139 I BluetoothAdapterState: Entering OffState
,08-23 12:39:00.277  3946  4140 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-23 12:39:00.278  3946  4140 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-23 12:39:00.278  3946  4140 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-23 12:39:00.278  3946  4140 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-23 12:39:00.280  3946  3946 I bt_bluedroid: get_profile_interface socket
,08-23 12:39:00.282  3946  3946 I bt_bluedroid: get_profile_interface sdp
,08-23 12:39:00.288  3946  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 12:39:00.295  3946  3957 I bt_bluedroid: config_hci_snoop_log
08-23 12:39:00.297  3946  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 12:39:00.297   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 12:39:00.306  3946  4139 D BluetoothAdapterState: Current state: OFF, message: 0
,08-23 12:39:00.306  3946  4139 D BluetoothAdapterProperties: Setting state to 14
,08-23 12:39:00.307  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 12:39:00.312  3946  4139 D BluetoothBondStateMachine: make
,08-23 12:39:00.317  3946  4144 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 12:39:00.324  3946  4139 I BluetoothAdapterState: Entering PendingCommandState
,08-23 12:39:00.327  3946  3946 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-23 12:39:00.337  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:00.338  3946  3946 D BtGatt.DebugUtils: handleDebugAction() action=null
08-23 12:39:00.339  3946  3946 D BtGatt.GattService: Received start request. Starting profile...
08-23 12:39:00.339  3946  3946 D BtGatt.GattService: start()
08-23 12:39:00.339  3946  3946 I bt_bluedroid: get_profile_interface gatt
,08-23 12:39:00.341  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
08-23 12:39:00.341  3946  3946 D BtGatt.AdvertiseManager: advertise manager created
,08-23 12:39:00.349  3946  3946 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:00.349  3946  3946 V BluetoothAdapterState: isTurningOn()=false
08-23 12:39:00.349  3946  3946 V BluetoothAdapterState: isBleTurningOn()=true
08-23 12:39:00.349  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:00.350  3946  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-23 12:39:00.353  3946  4139 I bt_bluedroid: enable
,08-23 12:39:00.354  3946  4140 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-23 12:39:00.354  3946  4140 I bt_hci  : start_up
,08-23 12:39:00.366  3946  4140 I bt_vendor: alloc value 0xb3979189
,08-23 12:39:00.366  3946  4140 I bt_vendor: init
08-23 12:39:00.366  3946  4140 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-23 12:39:00.366  3946  4140 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 12:39:00.476  3946  4140 D bt_hci  : start_up starting async portion
,08-23 12:39:00.477  3946  4147 I bt_hci  : event_finish_startup
,08-23 12:39:00.478  3946  4147 I bt_hci_h4: hal_open
08-23 12:39:00.479  3946  4147 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 12:39:00.488  3946  4147 I bt_userial_vendor: device fd = 51 open
,08-23 12:39:00.515  3946  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 12:39:00.547  3946  4147 D bt_hwcfg: Chipset BCM4354A2
,08-23 12:39:00.547  3946  4147 D bt_hwcfg: Target name = [BCM4354A2]
,08-23 12:39:00.548  3946  4147 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 12:39:01.209  3946  4147 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 12:39:01.211  3946  4147 D bt_hwcfg: Settlement delay -- 100 ms
08-23 12:39:01.211  3946  4147 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 12:39:01.328  3946  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 12:39:01.329  3946  4147 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 12:39:01.358  3946  4147 I bt_hwcfg: vendor lib fwcfg completed
,08-23 12:39:01.359  3946  4147 I bt_vendor: firmware callback
,08-23 12:39:01.359  3946  4147 I bt_hci  : firmware_config_callback
,08-23 12:39:01.371  3946  4149 I bt_btu  : btu_task pending for preload complete event
08-23 12:39:01.371  3946  4149 I bt_btu_task: Bluetooth chip preload is complete
,08-23 12:39:01.372  3946  4149 I bt_btu  : btu_task received preload complete event
,08-23 12:39:01.381  3946  4149 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 12:39:01.382  3946  4149 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 12:39:01.382  3946  4149 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-23 12:39:01.382  3946  4149 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-23 12:39:01.383  3946  4149 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 12:39:01.383  3946  4149 I         : BTE_InitTraceLevels -- TRC_A2D
,08-23 12:39:01.383  3946  4149 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 12:39:01.383  3946  4149 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 12:39:01.384  3946  4149 I         : BTE_InitTraceLevels -- TRC_GAP
,08-23 12:39:01.384  3946  4149 I         : BTE_InitTraceLevels -- TRC_PAN
08-23 12:39:01.384  3946  4149 I         : BTE_InitTraceLevels -- TRC_SDP
08-23 12:39:01.385  3946  4149 I         : BTE_InitTraceLevels -- TRC_GATT
,08-23 12:39:01.385  3946  4149 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 12:39:01.385  3946  4149 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 12:39:01.386  3946  4149 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 12:39:01.522  3946  4149 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,08-23 12:39:01.522  3946  4149 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-23 12:39:01.530  3946  4143 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-23 12:39:01.531  3946  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-23 12:39:01.532  3946  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 12:39:01.534  3946  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 12:39:01.535  3946  4143 D BluetoothAdapterProperties: Scan Mode:20
,08-23 12:39:01.535  3946  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 12:39:01.536  3946  4143 D bt_hci  : do_postload posting postload work item
,08-23 12:39:01.536  3946  4147 I bt_hci  : event_postload
08-23 12:39:01.536  3946  4147 I bt_vendor: sco_config_cb
08-23 12:39:01.536  3946  4147 I bt_hci  : sco_config_callback postload finished.
,08-23 12:39:01.538  3946  4143 D bt_bte_conf: Device ID record 1 : primary
,08-23 12:39:01.538  3946  4143 D bt_bte_conf:   vendorId            = 000f
,08-23 12:39:01.538  3946  4143 D bt_bte_conf:   vendorIdSource      = 0001
,08-23 12:39:01.538  3946  4143 D bt_bte_conf:   product             = 1200
,08-23 12:39:01.539  3946  4143 D bt_bte_conf:   version             = 1436
,08-23 12:39:01.539  3946  4143 D bt_bte_conf:   clientExecutableURL = 
08-23 12:39:01.539  3946  4143 D bt_bte_conf:   serviceDescription  = 
,08-23 12:39:01.539  3946  4143 D bt_bte_conf:   documentationURL    = 
,08-23 12:39:01.539  3946  4143 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-23 12:39:01.540  3946  4140 D bt_stack_manager: event_start_up_stack finished
,08-23 12:39:01.540  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:01.540  3946  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-23 12:39:01.541  3946  4139 D BluetoothAdapterProperties: Setting state to 15
08-23 12:39:01.541  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-23 12:39:01.542  3946  4139 I BluetoothAdapterState: Entering BleOnState
08-23 12:39:01.546  3946  4147 I bt_vendor: low_power_mode_cb
08-23 12:39:01.546  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:01.547  3946  4139 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-23 12:39:01.547  3946  4139 D BluetoothAdapterProperties: Setting state to 11
08-23 12:39:01.547  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-23 12:39:01.554  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9,
08-23 12:39:01.559  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:01.560  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:01.560  3946  3946 D HeadsetService: Received start request. Starting profile...
08-23 12:39:01.565  3946  4139 I BluetoothAdapterState: Entering PendingCommandState
08-23 12:39:01.565  3946  3946 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 12:39:01.566  3946  3946 D HeadsetStateMachine: make
,08-23 12:39:01.573  3946  3946 D HeadsetStateMachine: max_hf_connections = 1
,08-23 12:39:01.573  3946  3946 I bt_bluedroid: get_profile_interface handsfree
08-23 12:39:01.573  3946  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-23 12:39:01.573  3946  4143 E bt_btif : btif_hf_upstreams_evt: Invalid index 3,
,08-23 12:39:01.577  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:01.577  3946  3946 D A2dpService: Received start request. Starting profile...
,08-23 12:39:01.578  3946  3946 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 12:39:01.578  3946  3946 I bt_bluedroid: get_profile_interface avrcp
,08-23 12:39:01.585  3946  3946 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 12:39:01.585  3946  3946 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-23 12:39:01.585  3946  3946 D A2dpStateMachine: make
08-23 12:39:01.586  3946  3946 I bt_bluedroid: get_profile_interface a2dp
,08-23 12:39:01.587  3946  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-23 12:39:01.589  3946  4158 D A2dpStateMachine: Enter Disconnected: -2
08-23 12:39:01.589  3946  3946 I BluetoothHidServiceJni: classInitNative: succeeds
,08-23 12:39:01.590  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:01.591  3844  3844 D BluetoothInputDevice: Proxy object connected
,08-23 12:39:01.591  3946  3946 D HidService: Received start request. Starting profile...
08-23 12:39:01.591  3946  3946 I bt_bluedroid: get_profile_interface hidhost
08-23 12:39:01.592  3946  4143 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
,08-23 12:39:01.592  3946  3946 D HidService: setHidService(): set to: null
,08-23 12:39:01.592  3946  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-23 12:39:01.592  3844  3844 D HidProfile: Bluetooth service connected
08-23 12:39:01.592  3946  3946 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 12:39:01.593  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
08-23 12:39:01.594  3946  3946 D HealthService: Received start request. Starting profile...
08-23 12:39:01.596  3946  3946 I bt_bluedroid: get_profile_interface health
,08-23 12:39:01.596  3946  3946 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 12:39:01.597  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
08-23 12:39:01.598  3946  3946 D PanService: Received start request. Starting profile...
08-23 12:39:01.599  3946  3946 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-23 12:39:01.599  3946  3946 I bt_bluedroid: get_profile_interface pan
08-23 12:39:01.599  3844  3844 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 12:39:01.599  3946  4143 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 12:39:01.601  3946  3946 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:01.602  3946  3946 D BluetoothMapService: Received start request. Starting profile...
,08-23 12:39:01.603  3946  3946 D BluetoothMapService: start()
,08-23 12:39:01.603  3844  3844 D PanProfile: Bluetooth service connected
,08-23 12:39:01.604  3844  3844 D BluetoothMap: Proxy object connected
08-23 12:39:01.604  3946  3946 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-23 12:39:01.605  3844  3844 D MapProfile: Bluetooth service connected
08-23 12:39:01.605  3844  3844 D BluetoothMap: getConnectedDevices()
08-23 12:39:01.605  3946  3946 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-23 12:39:01.605  3946  3946 D BluetoothMapAppObserver: createReceiver()
08-23 12:39:01.606  3946  3946 D BluetoothMapAppObserver: initObservers()
,08-23 12:39:01.606  3844  3844 D BluetoothMap: Bluetooth is Not enabled
08-23 12:39:01.606  3946  3946 D BluetoothMapAppObserver: getEnabledAccountItems()
08-23 12:39:01.607  4075  4106 I art     : Waiting for a blocking GC DisableMovingGc
,08-23 12:39:01.611  4075  4106 I art     : Starting a blocking GC DisableMovingGc
,08-23 12:39:01.615  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:01.616  3946  4156 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-23 12:39:01.617  3946  3946 V BluetoothAdapterState: isTurningOff()=false
08-23 12:39:01.617  3946  3946 V BluetoothAdapterState: isTurningOn()=true,
08-23 12:39:01.617  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 12:39:01.617  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:39:01.618  3946  3946 V BluetoothAdapterState: isTurningOff()=false
08-23 12:39:01.618  3946  3946 V BluetoothAdapterState: isTurningOn()=true
08-23 12:39:01.618  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isTurningOn()=true
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isTurningOn()=true
,08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isTurningOff()=false
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isTurningOn()=true
08-23 12:39:01.619  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:01.620  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:01.620  3946  3946 V BluetoothAdapterState: isTurningOff()=false
08-23 12:39:01.620  3946  3946 V BluetoothAdapterState: isTurningOn()=true
,08-23 12:39:01.620  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:01.620  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:01.620  3946  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-23 12:39:01.620  3946  4139 D BluetoothAdapterProperties: ScanMode =  20
08-23 12:39:01.620  3946  4139 D BluetoothAdapterProperties: State =  11
08-23 12:39:01.621  4075  4106 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
08-23 12:39:01.622  3946  4143 D BluetoothAdapterProperties: Scan Mode:21
,08-23 12:39:01.623  3946  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 12:39:01.623  3946  4139 D BluetoothAdapterProperties: Setting state to 12
08-23 12:39:01.623  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 12:39:01.624  1353  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 12:39:01.624  3946  4139 I BluetoothAdapterState: Entering OnState
,08-23 12:39:01.625  1353  1353 D BluetoothInputDevice: Proxy object connected
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:01.626  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:39:01.626  1353  1353 D HidProfile: Bluetooth service connected
08-23 12:39:01.627   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 12:39:01.627  1912  1924 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:39:01.627  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:01.628  3844  3856 D BluetoothMap: onBluetoothStateChange: up=true
08-23 12:39:01.628   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:39:01.628  3844  3855 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 12:39:01.629   872   872 D BluetoothA2dp: Proxy object connected
08-23 12:39:01.630  1353  2009 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 12:39:01.631  1353  1353 D BluetoothA2dp: Proxy object connected
08-23 12:39:01.631  1353  2009 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 12:39:01.632  3946  3946 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 12:39:01.633  3946  3946 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:01.634  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:39:01.634  3946  3946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:01.635  1353  1384 D BluetoothMap: onBluetoothStateChange: up=true
08-23 12:39:01.636  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:01.636  1353  1353 D BluetoothMap: Proxy object connected
08-23 12:39:01.636  1353  1353 D MapProfile: Bluetooth service connected
08-23 12:39:01.636  1353  1353 D BluetoothMap: getConnectedDevices()
,08-23 12:39:01.637  3946  3946 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-23 12:39:01.637  1353  2009 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:39:01.637   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:39:01.637  1353  1375 D BluetoothPan: onBluetoothStateChange on: true
08-23 12:39:01.638  3946  3946 D ObexServerSockets: Succeed to create listening sockets 
08-23 12:39:01.638  3946  3946 D ObexServerSockets0: startAccept()
08-23 12:39:01.638  3946  3946 D ObexServerSockets0: prepareForNewConnect()
08-23 12:39:01.639  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 12:39:01.639  1353  1353 D PanProfile: Bluetooth service connected
08-23 12:39:01.639   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:39:01.639  3844  3856 D BluetoothPan: onBluetoothStateChange on: true
08-23 12:39:01.639  3844  3855 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 12:39:01.641   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-23 12:39:01.642  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:01.643  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:01.643  3844  3844 D LocalBluetoothProfileManager: Adding local A2DP profile
08-23 12:39:01.644  3946  3946 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-23 12:39:01.644  3946  3946 D BluetoothSdpJni: SDP Create record success - handle: 0
08-23 12:39:01.645  3946  3946 D BluetoothMapService: onReceive
08-23 12:39:01.645  3946  3946 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:01.645  3946  3946 D BluetoothMapService: STATE_ON
08-23 12:39:01.645  3946  4167 D ObexServerSockets0: Accepting socket connection...
,08-23 12:39:01.646  3946  4168 D ObexServerSockets0: Accepting socket connection...
,08-23 12:39:01.647  3844  3844 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-23 12:39:01.652  3844  3844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:39:01.654  3844  3844 D BluetoothA2dp: Proxy object connected
,08-23 12:39:01.657  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:01.662  3844  3844 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:39:01.665  3844  3844 D BluetoothPbap: Proxy object connected
,08-23 12:39:01.665  1353  1353 D BluetoothPbap: Proxy object connected
,08-23 12:39:01.665  3844  3844 D PbapServerProfile: Bluetooth service connected
08-23 12:39:01.665  1353  1353 D PbapServerProfile: Bluetooth service connected
,08-23 12:39:01.670  3946  3946 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 12:39:01.670  3946  3946 D ObexServerSockets0: prepareForNewConnect()
08-23 12:39:01.673  3946  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:01.686  3946  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:01.688  3946  4176 I BtOppRfcommListener: Accept thread started.
,08-23 12:39:01.729   872   872 D BluetoothHeadset: Proxy object connected
,08-23 12:39:01.730   872   872 D BluetoothHeadset: Proxy object connected
08-23 12:39:01.730   872   872 D BluetoothHeadset: Proxy object connected
08-23 12:39:01.730  1912  2162 D BluetoothHeadset: Proxy object connected
,08-23 12:39:01.731  1353  1375 D BluetoothHeadset: Proxy object connected
08-23 12:39:01.731  1353  1353 D HeadsetProfile: Bluetooth service connected
,08-23 12:39:01.737  1353  1384 D BluetoothHeadset: Proxy object connected
08-23 12:39:01.738  1353  1353 D HeadsetProfile: Bluetooth service connected
08-23 12:39:01.738   872   889 D BluetoothHeadset: Proxy object connected
08-23 12:39:01.739   872   889 D BluetoothHeadset: Proxy object connected
,08-23 12:39:01.750  3844  3856 D BluetoothHeadset: Proxy object connected
,08-23 12:39:01.751  3844  3844 D HeadsetProfile: Bluetooth service connected
,08-23 12:39:03.231  3946  4139 D BluetoothAdapterState: Current state: ON, message: 23
,08-23 12:39:03.231  3946  4139 D BluetoothAdapterProperties: Setting state to 13
,08-23 12:39:03.232  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-23 12:39:03.234  3946  4139 D BluetoothAdapterProperties: onBluetoothDisable()
,08-23 12:39:03.242  3946  3946 D BluetoothMapService: onReceive
,08-23 12:39:03.242  3946  3946 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:03.243  3946  3946 D BluetoothMapService: STATE_TURNING_OFF
08-23 12:39:03.243  3946  3946 D BluetoothMapService: MAP Service closeService in
,08-23 12:39:03.244  3946  3946 D BluetoothMapMasInstance0: MAP Service shutdown
08-23 12:39:03.244  3946  3946 D ObexServerSockets0: shutdown(block = true)
08-23 12:39:03.245  3946  4139 I BluetoothAdapterState: Entering PendingCommandState
,08-23 12:39:03.245  3946  4167 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-23 12:39:03.247  3946  3946 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-23 12:39:03.248  3946  4151 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-23 12:39:03.248  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:39:03.248  3946  4168 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:03.248  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:39:03.250  3946  3946 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-23 12:39:03.252  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-23 12:39:03.252  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:03.252  3946  4143 D BluetoothAdapterProperties: Scan Mode:20
,08-23 12:39:03.253  3946  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-23 12:39:03.256  3844  3844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:39:03.255  3946  3946 I BtOppRfcommListener: stopping Accept Thread
08-23 12:39:03.256  3946  4176 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-23 12:39:03.258  3946  4176 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-23 12:39:03.258  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:03.259  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:03.260  3779  3779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-23 12:39:03.261  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:03.263  3946  3946 D HeadsetService: Received stop request...Stopping profile...
08-23 12:39:03.266  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:03.268  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:03.270   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 12:39:03.271   872   872 D BluetoothHeadset: Proxy object disconnected
,08-23 12:39:03.271  3844  3856 D BluetoothHeadset: Proxy object disconnected
08-23 12:39:03.271  3946  3946 D A2dpService: Received stop request...Stopping profile...
08-23 12:39:03.271  3946  4158 D A2dpStateMachine: Exit Disconnected: -1
08-23 12:39:03.271   872   872 D BluetoothHeadset: Proxy object disconnected
08-23 12:39:03.272  1912  1930 D BluetoothHeadset: Proxy object disconnected
08-23 12:39:03.272  1353  2009 D BluetoothHeadset: Proxy object disconnected
08-23 12:39:03.273   872   872 D BluetoothA2dp: Proxy object disconnected
,08-23 12:39:03.274  3946  3946 D HidService: Received stop request...Stopping profile...
08-23 12:39:03.274  3946  3946 D HidService: Stopping Bluetooth HidService
08-23 12:39:03.275  3844  3844 D DockEventReceiver: finishStartingService: stopping service
08-23 12:39:03.276  1353  1353 D HeadsetProfile: Bluetooth service disconnected
08-23 12:39:03.276  3946  3946 V BluetoothAdapterState: isTurningOff()=true
,08-23 12:39:03.276  3844  3844 D HeadsetProfile: Bluetooth service disconnected
08-23 12:39:03.276  3946  3946 V BluetoothAdapterState: isTurningOn()=false
08-23 12:39:03.276  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 12:39:03.276  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:03.276  3844  3844 D BluetoothA2dp: Proxy object disconnected
,08-23 12:39:03.277  3946  3946 D HealthService: Received stop request...Stopping profile...
08-23 12:39:03.277  1353  1353 D BluetoothA2dp: Proxy object disconnected
08-23 12:39:03.277  3844  3844 D BluetoothInputDevice: Proxy object disconnected
08-23 12:39:03.277  3844  3844 D HidProfile: Bluetooth service disconnected
08-23 12:39:03.277  1353  1353 D BluetoothInputDevice: Proxy object disconnected
08-23 12:39:03.278  1353  1353 D HidProfile: Bluetooth service disconnected
,08-23 12:39:03.284  3946  3946 D PanService: Received stop request...Stopping profile...
08-23 12:39:03.286  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:03.289  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 12:39:03.289  1353  1353 D PanProfile: Bluetooth service disconnected
08-23 12:39:03.289  3844  3844 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-23 12:39:03.289  3844  3844 D PanProfile: Bluetooth service disconnected
,08-23 12:39:03.290  3946  3946 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-23 12:39:03.290  3946  3946 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-23 12:39:03.290  3946  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-23 12:39:03.290  3946  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:39:03.290  3946  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:39:03.290  3946  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:39:03.290  3946  4143 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-23 12:39:03.290  3946  3946 V BluetoothAdapterState: isTurningOff()=true
08-23 12:39:03.290  3946  3946 V BluetoothAdapterState: isTurningOn()=false
,08-23 12:39:03.290  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:03.290  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:03.291  3946  3946 D BluetoothMapService: Received stop request...Stopping profile...
08-23 12:39:03.291  3946  3946 D BluetoothMapService: stop()
08-23 12:39:03.291  3946  3946 D BluetoothMapAppObserver: deinitObservers()
,08-23 12:39:03.291  3946  3946 D BluetoothMapAppObserver: removeReceiver()
08-23 12:39:03.293  1353  1353 D BluetoothMap: Proxy object disconnected
,08-23 12:39:03.293  1353  1353 D MapProfile: Bluetooth service disconnected
,08-23 12:39:03.294  3844  3844 D BluetoothMap: Proxy object disconnected
08-23 12:39:03.294  3844  3844 D MapProfile: Bluetooth service disconnected
08-23 12:39:03.294  3946  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-23 12:39:03.294  3946  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:39:03.294  3946  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:39:03.294  3946  3946 V BluetoothAdapterState: isTurningOff()=true
,08-23 12:39:03.294  3946  4149 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:39:03.294  3946  3946 V BluetoothAdapterState: isTurningOn()=false
08-23 12:39:03.294  3946  4149 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-23 12:39:03.294  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:03.294  3946  4149 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-23 12:39:03.294  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:39:03.294  3946  4149 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-23 12:39:03.295  3946  3946 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-23 12:39:03.295  3946  3946 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-23 12:39:03.295  3946  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-23 12:39:03.295  3946  3946 V BluetoothAdapterState: isTurningOff()=true
08-23 12:39:03.295  3946  3946 V BluetoothAdapterState: isTurningOn()=false
08-23 12:39:03.295  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:03.295  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:39:03.295  3946  3946 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-23 12:39:03.295  3946  4143 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-23 12:39:03.295  3946  3946 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-23 12:39:03.297  1353  1353 D BluetoothPbap: Proxy object disconnected
,08-23 12:39:03.297  1353  1353 D PbapServerProfile: Bluetooth service disconnected
08-23 12:39:03.297  3946  3946 V BluetoothAdapterState: isTurningOff()=true
08-23 12:39:03.297  3946  3946 V BluetoothAdapterState: isTurningOn()=false
08-23 12:39:03.297  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 12:39:03.298  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:03.298  3946  3946 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-23 12:39:03.298  3946  3946 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-23 12:39:03.300  3946  3946 D BluetoothMapService: MAP Service closeService in
,08-23 12:39:03.300  3946  3946 V BluetoothAdapterState: isTurningOff()=true
08-23 12:39:03.300  3946  3946 V BluetoothAdapterState: isTurningOn()=false
08-23 12:39:03.300  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:03.300  3946  3946 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:03.300  3946  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-23 12:39:03.300  3946  4139 D BluetoothAdapterProperties: Setting state to 15
08-23 12:39:03.301  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-23 12:39:03.301  3946  3946 D BluetoothMapService: cleanup(),
08-23 12:39:03.301  3946  3946 D BluetoothMapService: MAP Service closeService in
08-23 12:39:03.301  3946  4139 I BluetoothAdapterState: Entering BleOnState
08-23 12:39:03.302  3844  3844 D BluetoothPbap: Proxy object disconnected
08-23 12:39:03.302  3844  3844 D PbapServerProfile: Bluetooth service disconnected
08-23 12:39:03.302  1353  2009 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 12:39:03.302   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 12:39:03.303  1912  2058 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:39:03.303  3844  3855 D BluetoothMap: onBluetoothStateChange: up=false
08-23 12:39:03.304   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:39:03.304  3844  3856 D BluetoothPbap: onBluetoothStateChange: up=false
08-23 12:39:03.305  1353  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:39:03.306  1353  1375 D BluetoothPbap: onBluetoothStateChange: up=false
,08-23 12:39:03.306  1353  2009 D BluetoothMap: onBluetoothStateChange: up=false
08-23 12:39:03.307  1353  1384 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:39:03.307   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-23 12:39:03.307  1353  1375 D BluetoothPan: onBluetoothStateChange on: false
,08-23 12:39:03.307   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 12:39:03.308  3844  3855 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-23 12:39:03.308  3844  3856 D BluetoothPan: onBluetoothStateChange on: false
,08-23 12:39:03.308  3844  3855 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-23 12:39:03.309  3844  3856 D BluetoothA2dp: onBluetoothStateChange: up=false
08-23 12:39:03.310  3946  4139 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-23 12:39:03.310  3946  4139 D BluetoothAdapterProperties: Setting state to 16
,08-23 12:39:03.310  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-23 12:39:03.310  3946  4139 D BluetoothAdapterProperties: onBleDisable
08-23 12:39:03.311  3946  4139 I BluetoothAdapterState: Entering PendingCommandState
,08-23 12:39:03.311  3946  4140 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-23 12:39:03.312  3946  4149 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-23 12:39:03.312  3946  4149 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-23 12:39:03.313  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:03.315  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:03.316  3946  4143 D BluetoothAdapterProperties: Scan Mode:20
,08-23 12:39:03.318  3844  3844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-23 12:39:03.318  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:03.319  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:03.325  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:03.326  3844  3844 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:39:03.513  3946  4143 I bt_hci  : shut_down
,08-23 12:39:03.513  3946  4147 D bt_hwcfg: hw_epilog_process
,08-23 12:39:03.525  3946  4147 I bt_vendor: low_power_mode_cb
,08-23 12:39:03.552  3946  4147 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-23 12:39:03.552  3946  4147 I bt_vendor: epilog_cb
,08-23 12:39:03.552  3946  4147 I bt_hci  : epilog_finished_callback
,08-23 12:39:03.559  3946  4143 I bt_hci_h4: hal_close
,08-23 12:39:03.562  3946  4143 I bt_userial_vendor: device fd = 51 close
,08-23 12:39:03.676  3946  4140 D bt_stack_manager: event_shut_down_stack finished.
,08-23 12:39:03.677  3946  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-23 12:39:03.682  3946  4139 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-23 12:39:03.683  3946  3946 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 12:39:03.686  3946  3946 D BtGatt.GattService: Received stop request...Stopping profile...
,08-23 12:39:03.686  3946  3946 D BtGatt.GattService: stop()
08-23 12:39:03.686  3946  3946 D BtGatt.AdvertiseManager: advertise clients cleared
,08-23 12:39:03.692  3946  3946 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:03.692  3946  3946 V BluetoothAdapterState: isTurningOn()=false
08-23 12:39:03.692  3946  3946 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:03.693  3946  3946 V BluetoothAdapterState: isBleTurningOff()=true
08-23 12:39:03.693  3946  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-23 12:39:03.694  3946  4139 D BluetoothAdapterProperties: Setting state to 10
08-23 12:39:03.694  3946  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-23 12:39:03.696  3946  4139 I BluetoothAdapterState: Entering OffState
,08-23 12:39:03.698   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-23 12:39:03.726  3946  3946 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-23 12:39:03.727  3946  3946 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-23 12:39:03.728  3946  4140 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-23 12:39:03.734  3946  4140 D bt_stack_manager: event_clean_up_stack finished.
08-23 12:39:03.735  3946  3946 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-23 12:39:03.743  3946  3946 I art     : System.exit called, status: 0
08-23 12:39:03.744  3946  3946 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-23 12:39:03.803   872  1542 I ActivityManager: Process com.android.bluetooth (pid 3946) has died
,08-23 12:39:04.336   872  1302 D ConnectivityService: handlePromptUnvalidated 101
,08-23 12:39:06.229  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:39:06.230  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:06.669  3486  3567 D Finsky  : [290] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-23 12:39:06.682  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:39:06.698  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:39:06.704  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:39:06.762  1519  2059 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-23 12:39:06.763  1519  2059 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-23 12:39:06.763  1519  2059 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 12:39:06.763  1519  2059 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:39:06.794  3486  3567 D Finsky  : [290] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-23 12:39:09.237  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:09.238  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2570b17 added. We now have 6 listener(s)
,08-23 12:39:09.238  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:09.242  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:09.242  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3aeb04 added. We now have 7 listener(s)
,08-23 12:39:09.243  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:09.244  3779  3829 I System.out: IsBluetoothEnabled
,08-23 12:39:09.255  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:09.297   872   889 I ActivityManager: Start proc 4188:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-23 12:39:09.431  4188  4188 D AdapterServiceConfig: Adding HeadsetService
,08-23 12:39:09.431  4188  4188 D AdapterServiceConfig: Adding A2dpService
,08-23 12:39:09.432  4188  4188 D AdapterServiceConfig: Adding HidService
,08-23 12:39:09.432  4188  4188 D AdapterServiceConfig: Adding HealthService
,08-23 12:39:09.432  4188  4188 D AdapterServiceConfig: Adding PanService
,08-23 12:39:09.432  4188  4188 D AdapterServiceConfig: Adding GattService
,08-23 12:39:09.432  4188  4188 D AdapterServiceConfig: Adding BluetoothMapService
,08-23 12:39:09.448   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6857835:true
,08-23 12:39:09.449  4188  4188 D BluetoothAdapterState: make() - Creating AdapterState
,08-23 12:39:09.457  4188  4188 I bt_bluedroid: init
,08-23 12:39:09.458  4188  4200 I BluetoothAdapterState: Entering OffState
,08-23 12:39:09.465  4188  4201 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-23 12:39:09.466  4188  4201 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-23 12:39:09.466  4188  4201 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-23 12:39:09.466  4188  4201 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-23 12:39:09.468  4188  4188 I bt_bluedroid: get_profile_interface socket
,08-23 12:39:09.471  4188  4188 I bt_bluedroid: get_profile_interface sdp
,08-23 12:39:09.471  4188  4204 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 12:39:09.474  4188  4204 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 12:39:09.476  4188  4198 I bt_bluedroid: config_hci_snoop_log
,08-23 12:39:09.479   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-23 12:39:09.488  4188  4200 D BluetoothAdapterState: Current state: OFF, message: 0
,08-23 12:39:09.489  4188  4200 D BluetoothAdapterProperties: Setting state to 14
08-23 12:39:09.489  4188  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-23 12:39:09.493  4188  4200 D BluetoothBondStateMachine: make
,08-23 12:39:09.499  4188  4205 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-23 12:39:09.507  4188  4200 I BluetoothAdapterState: Entering PendingCommandState
,08-23 12:39:09.509  4188  4188 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-23 12:39:09.516  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:09.518  4188  4188 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-23 12:39:09.520  4188  4188 D BtGatt.GattService: Received start request. Starting profile...
,08-23 12:39:09.520  4188  4188 D BtGatt.GattService: start()
,08-23 12:39:09.521  4188  4188 I bt_bluedroid: get_profile_interface gatt
,08-23 12:39:09.523  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:09.524  4188  4188 D BtGatt.AdvertiseManager: advertise manager created
,08-23 12:39:09.540  4188  4188 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:09.541  4188  4188 V BluetoothAdapterState: isTurningOn()=false
,08-23 12:39:09.541  4188  4188 V BluetoothAdapterState: isBleTurningOn()=true
,08-23 12:39:09.541  4188  4188 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:09.542  4188  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-23 12:39:09.543  4188  4200 I bt_bluedroid: enable
,08-23 12:39:09.543  4188  4201 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-23 12:39:09.544  4188  4201 I bt_hci  : start_up
,08-23 12:39:09.563  4188  4201 I bt_vendor: alloc value 0xb39dc189
,08-23 12:39:09.563  4188  4201 I bt_vendor: init
08-23 12:39:09.564  4188  4201 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-23 12:39:09.564  4188  4201 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-23 12:39:09.674  4188  4201 D bt_hci  : start_up starting async portion
,08-23 12:39:09.674  4188  4208 I bt_hci  : event_finish_startup
08-23 12:39:09.675  4188  4208 I bt_hci_h4: hal_open
08-23 12:39:09.675  4188  4208 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-23 12:39:09.688  4188  4208 I bt_userial_vendor: device fd = 51 open
,08-23 12:39:09.715  4188  4208 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 12:39:09.746  4188  4208 D bt_hwcfg: Chipset BCM4354A2
,08-23 12:39:09.747  4188  4208 D bt_hwcfg: Target name = [BCM4354A2]
08-23 12:39:09.748  4188  4208 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-23 12:39:10.421  4188  4208 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-23 12:39:10.422  4188  4208 D bt_hwcfg: Settlement delay -- 100 ms
,08-23 12:39:10.423  4188  4208 I bt_hwcfg: Setting fw settlement delay to 100 
,08-23 12:39:10.540  4188  4208 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-23 12:39:10.542  4188  4208 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-23 12:39:10.570  4188  4208 I bt_hwcfg: vendor lib fwcfg completed
,08-23 12:39:10.571  4188  4208 I bt_vendor: firmware callback
08-23 12:39:10.571  4188  4208 I bt_hci  : firmware_config_callback
,08-23 12:39:10.583  4188  4210 I bt_btu  : btu_task pending for preload complete event
,08-23 12:39:10.584  4188  4210 I bt_btu_task: Bluetooth chip preload is complete
08-23 12:39:10.584  4188  4210 I bt_btu  : btu_task received preload complete event
,08-23 12:39:10.596  4188  4210 I         : BTE_InitTraceLevels -- TRC_HCI
08-23 12:39:10.597  4188  4210 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-23 12:39:10.597  4188  4210 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-23 12:39:10.597  4188  4210 I         : BTE_InitTraceLevels -- TRC_AVDT
08-23 12:39:10.598  4188  4210 I         : BTE_InitTraceLevels -- TRC_AVRC
08-23 12:39:10.598  4188  4210 I         : BTE_InitTraceLevels -- TRC_A2D
08-23 12:39:10.598  4188  4210 I         : BTE_InitTraceLevels -- TRC_BNEP
08-23 12:39:10.598  4188  4210 I         : BTE_InitTraceLevels -- TRC_BTM
08-23 12:39:10.599  4188  4210 I         : BTE_InitTraceLevels -- TRC_GAP
08-23 12:39:10.599  4188  4210 I         : BTE_InitTraceLevels -- TRC_PAN
,08-23 12:39:10.599  4188  4210 I         : BTE_InitTraceLevels -- TRC_SDP
,08-23 12:39:10.599  4188  4210 I         : BTE_InitTraceLevels -- TRC_GATT
08-23 12:39:10.600  4188  4210 I         : BTE_InitTraceLevels -- TRC_SMP
08-23 12:39:10.600  4188  4210 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-23 12:39:10.600  4188  4210 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-23 12:39:10.731  4188  4210 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3959d9d
,08-23 12:39:10.732  4188  4210 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3959d9d 
,08-23 12:39:10.743  4188  4204 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-23 12:39:10.745  4188  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-23 12:39:10.746  4188  4204 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-23 12:39:10.749  4188  4204 D BluetoothAdapterProperties: Name is: Nexus 6
,08-23 12:39:10.753  4188  4204 D BluetoothAdapterProperties: Scan Mode:20
08-23 12:39:10.753  4188  4204 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-23 12:39:10.754  4188  4204 D bt_hci  : do_postload posting postload work item
,08-23 12:39:10.754  4188  4208 I bt_hci  : event_postload
,08-23 12:39:10.755  4188  4208 I bt_vendor: sco_config_cb
,08-23 12:39:10.755  4188  4208 I bt_hci  : sco_config_callback postload finished.
08-23 12:39:10.760  4188  4204 D bt_bte_conf: Device ID record 1 : primary
08-23 12:39:10.760  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:10.761  4188  4204 D bt_bte_conf:   vendorId            = 000f
,08-23 12:39:10.761  4188  4204 D bt_bte_conf:   vendorIdSource      = 0001
,08-23 12:39:10.761  4188  4204 D bt_bte_conf:   product             = 1200
08-23 12:39:10.762  4188  4204 D bt_bte_conf:   version             = 1436
,08-23 12:39:10.762  4188  4204 D bt_bte_conf:   clientExecutableURL = 
08-23 12:39:10.762  4188  4204 D bt_bte_conf:   serviceDescription  = 
,08-23 12:39:10.763  4188  4204 D bt_bte_conf:   documentationURL    = 
08-23 12:39:10.763  4188  4204 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-23 12:39:10.763  4188  4201 D bt_stack_manager: event_start_up_stack finished
,08-23 12:39:10.765  4188  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-23 12:39:10.766  4188  4200 D BluetoothAdapterProperties: Setting state to 15
08-23 12:39:10.766  4188  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-23 12:39:10.766  4188  4208 I bt_vendor: low_power_mode_cb
08-23 12:39:10.767  4188  4200 I BluetoothAdapterState: Entering BleOnState
08-23 12:39:10.772  4188  4200 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-23 12:39:10.772  4188  4200 D BluetoothAdapterProperties: Setting state to 11
08-23 12:39:10.772  4188  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-23 12:39:10.778  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:10.779  4188  4188 D HeadsetService: Received start request. Starting profile...
,08-23 12:39:10.782  4188  4188 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-23 12:39:10.782  4188  4188 D HeadsetStateMachine: make
,08-23 12:39:10.790  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:10.797  4188  4188 D HeadsetStateMachine: max_hf_connections = 1
,08-23 12:39:10.797  4188  4188 I bt_bluedroid: get_profile_interface handsfree
,08-23 12:39:10.798  4188  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-23 12:39:10.798  4188  4204 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-23 12:39:10.806  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:10.807  4188  4200 I BluetoothAdapterState: Entering PendingCommandState
08-23 12:39:10.807  4188  4188 D A2dpService: Received start request. Starting profile...
,08-23 12:39:10.808  4188  4188 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-23 12:39:10.808  4188  4188 I bt_bluedroid: get_profile_interface avrcp
,08-23 12:39:10.815  4188  4188 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-23 12:39:10.815  4188  4188 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-23 12:39:10.815  4188  4188 D A2dpStateMachine: make
,08-23 12:39:10.817  4188  4188 I bt_bluedroid: get_profile_interface a2dp
,08-23 12:39:10.818  4188  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-23 12:39:10.819  4188  4219 D A2dpStateMachine: Enter Disconnected: -2
08-23 12:39:10.819  4188  4188 I BluetoothHidServiceJni: classInitNative: succeeds
08-23 12:39:10.820  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
08-23 12:39:10.821  4188  4188 D HidService: Received start request. Starting profile...
08-23 12:39:10.821  4188  4188 I bt_bluedroid: get_profile_interface hidhost
,08-23 12:39:10.821  4188  4188 D HidService: setHidService(): set to: null
08-23 12:39:10.821  4188  4204 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393b3e5
08-23 12:39:10.821  4188  4204 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-23 12:39:10.823  4188  4188 I BluetoothHealthServiceJni: classInitNative: succeeds
08-23 12:39:10.823  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:10.824  4188  4188 D HealthService: Received start request. Starting profile...
,08-23 12:39:10.826  4188  4188 I bt_bluedroid: get_profile_interface health
,08-23 12:39:10.828  4188  4188 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-23 12:39:10.828  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:10.829  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:10.829  4188  4188 D PanService: Received start request. Starting profile...
08-23 12:39:10.829  4188  4188 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-23 12:39:10.829  4188  4188 I bt_bluedroid: get_profile_interface pan
,08-23 12:39:10.830  4188  4204 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-23 12:39:10.835  4188  4188 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:10.835  4188  4188 V BluetoothAdapterState: isTurningOn()=true
,08-23 12:39:10.835  4188  4188 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:10.835  4188  4188 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:39:10.839  4188  4215 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-23 12:39:10.842  4188  4188 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:10.843  4188  4188 D BluetoothMapService: Received start request. Starting profile...
,08-23 12:39:10.843  4188  4188 D BluetoothMapService: start()
,08-23 12:39:10.846  4188  4188 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-23 12:39:10.847  4188  4188 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-23 12:39:10.847  4188  4188 D BluetoothMapAppObserver: createReceiver()
,08-23 12:39:10.848  4188  4188 D BluetoothMapAppObserver: initObservers()
,08-23 12:39:10.848  4188  4188 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-23 12:39:10.853  4188  4188 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isTurningOn()=true
08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isTurningOff()=false
08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isTurningOn()=true
,08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isTurningOff()=false
,08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isTurningOn()=true
,08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isBleTurningOn()=false
08-23 12:39:10.854  4188  4188 V BluetoothAdapterState: isBleTurningOff()=false
,08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isTurningOff()=false
08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isTurningOn()=true
,08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isTurningOff()=false
08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isTurningOn()=true
08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isBleTurningOn()=false
,08-23 12:39:10.855  4188  4188 V BluetoothAdapterState: isBleTurningOff()=false
08-23 12:39:10.856  4188  4200 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-23 12:39:10.856  4188  4200 D BluetoothAdapterProperties: ScanMode =  20
08-23 12:39:10.856  4188  4200 D BluetoothAdapterProperties: State =  11
08-23 12:39:10.859  4188  4204 D BluetoothAdapterProperties: Scan Mode:21
08-23 12:39:10.859  4188  4204 D BluetoothAdapterProperties: Discoverable Timeout:120
08-23 12:39:10.859  4188  4200 D BluetoothAdapterProperties: Setting state to 12
,08-23 12:39:10.859  4188  4200 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-23 12:39:10.860  1353  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-23 12:39:10.860  4188  4200 I BluetoothAdapterState: Entering OnState
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:10.863  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-23 12:39:10.863   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 12:39:10.864  1912  2058 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:39:10.864  1353  1353 D BluetoothInputDevice: Proxy object connected
08-23 12:39:10.864  1353  1353 D HidProfile: Bluetooth service connected
08-23 12:39:10.865  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-23 12:39:10.865  3844  3856 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 12:39:10.867   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-23 12:39:10.868  3844  3856 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 12:39:10.869   872   872 D BluetoothA2dp: Proxy object connected
,08-23 12:39:10.870  1353  2009 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 12:39:10.874  4188  4188 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-23 12:39:10.875  4188  4188 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-23 12:39:10.877  1353  1353 D BluetoothA2dp: Proxy object connected
,08-23 12:39:10.875  3844  3844 D BluetoothMap: Proxy object connected
08-23 12:39:10.877  3844  3844 D MapProfile: Bluetooth service connected
,08-23 12:39:10.877  3844  3844 D BluetoothMap: getConnectedDevices()
,08-23 12:39:10.877  1353  1375 D BluetoothPbap: onBluetoothStateChange: up=true
08-23 12:39:10.877  4188  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:10.880  4188  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:10.881  1353  1384 D BluetoothMap: onBluetoothStateChange: up=true
,08-23 12:39:10.881  4188  4188 D ObexServerSockets: Succeed to create listening sockets 
08-23 12:39:10.882  4188  4188 D ObexServerSockets0: startAccept()
08-23 12:39:10.882  4188  4188 D ObexServerSockets0: prepareForNewConnect()
,08-23 12:39:10.883  1353  1353 D BluetoothMap: Proxy object connected
08-23 12:39:10.883  1353  1353 D MapProfile: Bluetooth service connected
08-23 12:39:10.883  1353  2009 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:39:10.883  1353  1353 D BluetoothMap: getConnectedDevices()
,08-23 12:39:10.883   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 12:39:10.883  1353  1375 D BluetoothPan: onBluetoothStateChange on: true
08-23 12:39:10.883  4188  4188 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-23 12:39:10.884  4188  4188 D BluetoothSdpJni: SDP Create record success - handle: 0
08-23 12:39:10.885  4188  4224 D ObexServerSockets0: Accepting socket connection...
08-23 12:39:10.885   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-23 12:39:10.885  3844  3855 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-23 12:39:10.885  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
08-23 12:39:10.885  1353  1353 D PanProfile: Bluetooth service connected
08-23 12:39:10.885  3844  3856 D BluetoothPan: onBluetoothStateChange on: true
08-23 12:39:10.885  4188  4225 D ObexServerSockets0: Accepting socket connection...
08-23 12:39:10.887  3844  3855 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-23 12:39:10.888  3844  3856 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-23 12:39:10.890   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-23 12:39:10.893  4188  4188 D BluetoothMapService: onReceive
08-23 12:39:10.893  4188  4188 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-23 12:39:10.893  4188  4188 D BluetoothMapService: STATE_ON
,08-23 12:39:10.894  3844  3844 D BluetoothPan: BluetoothPAN Proxy object connected
,08-23 12:39:10.895  3844  3844 D PanProfile: Bluetooth service connected
08-23 12:39:10.895  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:10.895  3844  3844 D BluetoothInputDevice: Proxy object connected
08-23 12:39:10.896  3844  3844 D HidProfile: Bluetooth service connected
,08-23 12:39:10.897  3844  3844 D BluetoothA2dp: Proxy object connected
,08-23 12:39:10.901  3844  3844 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-23 12:39:10.907  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-23 12:39:10.911  3844  3844 D DockEventReceiver: finishStartingService: stopping service
,08-23 12:39:10.914  1353  1353 D BluetoothPbap: Proxy object connected
,08-23 12:39:10.914  1353  1353 D PbapServerProfile: Bluetooth service connected
08-23 12:39:10.914  3844  3844 D BluetoothPbap: Proxy object connected
08-23 12:39:10.914  3844  3844 D PbapServerProfile: Bluetooth service connected
,08-23 12:39:10.920  4188  4188 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-23 12:39:10.920  4188  4188 D ObexServerSockets0: prepareForNewConnect()
,08-23 12:39:10.922  4188  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:10.939  4188  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-23 12:39:10.940  4188  4235 I BtOppRfcommListener: Accept thread started.
,08-23 12:39:10.965   872   872 D BluetoothHeadset: Proxy object connected
,08-23 12:39:10.965   872   872 D BluetoothHeadset: Proxy object connected
08-23 12:39:10.966  3844  4226 D BluetoothHeadset: Proxy object connected
,08-23 12:39:10.966   872   872 D BluetoothHeadset: Proxy object connected
08-23 12:39:10.966  3844  3844 D HeadsetProfile: Bluetooth service connected
,08-23 12:39:10.966  1912  1924 D BluetoothHeadset: Proxy object connected
,08-23 12:39:10.967  1353  1375 D BluetoothHeadset: Proxy object connected
08-23 12:39:10.968  1353  1353 D HeadsetProfile: Bluetooth service connected
,08-23 12:39:10.983  1353  1384 D BluetoothHeadset: Proxy object connected
,08-23 12:39:10.983  1353  1353 D HeadsetProfile: Bluetooth service connected
08-23 12:39:10.983   872   889 D BluetoothHeadset: Proxy object connected
08-23 12:39:10.985   872   889 D BluetoothHeadset: Proxy object connected
,08-23 12:39:10.985  3844  3856 D BluetoothHeadset: Proxy object connected
,08-23 12:39:10.986  3844  3844 D HeadsetProfile: Bluetooth service connected
,08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:11.278  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:11.285  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:11.289  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:11.289  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c978ed added. We now have 8 listener(s)
,08-23 12:39:11.290  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:11.295   872  1955 D WifiService: setWifiEnabled: false pid=3779, uid=10000
,08-23 12:39:11.296   872  1955 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 12:39:11.308  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:11.309   872  1362 D WifiService: setWifiEnabled: true pid=3779, uid=10000
,08-23 12:39:11.309   872  1362 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-23 12:39:11.321   872  1300 D WifiConfigStore: Loading config and enabling all networks 
,08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-23 12:39:11.336  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-23 12:39:11.343  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-23 12:39:11.348   872  1300 D WifiConfigStore: loaded 0 passpoint configs
,08-23 12:39:11.349   872  1300 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-23 12:39:11.350   872  1300 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-23 12:39:11.352   872  1300 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-23 12:39:11.352   872  1300 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-23 12:39:11.352   872  1300 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-23 12:39:11.353   872  1300 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-23 12:39:11.374   872  1300 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.67 rxSuccessRate=0.80 delta 1000 -> 1000
,08-23 12:39:11.374   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-23 12:39:11.377   371   870 D CommandListener: Setting iface cfg
,08-23 12:39:11.379   872  1299 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '153 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 153 Failed to set address (No such device)'
,08-23 12:39:11.379   872  1299 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-23 12:39:11.384   872  1300 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-23 12:39:11.384   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:39:11.394   872  1300 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-23 12:39:11.427   872  1300 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-23 12:39:11.428   872  1299 D WifiNative-HAL: p2pGetDeviceAddress
,08-23 12:39:11.430  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-23 12:39:11.440   872  1299 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-23 12:39:11.851  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-23 12:39:11.902  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-23 12:39:11.902  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-23 12:39:11.908   872  1300 D WifiConfigStore: Retrieve network priorities after PNO.
,08-23 12:39:11.916   872  1300 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 12:39:11.916   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:39:11.917   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-23 12:39:11.938   872  1300 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-23 12:39:11.952   371   870 D CommandListener: Setting iface cfg
,08-23 12:39:11.953   872  1300 D WifiStateMachine: Start Dhcp Watchdog 3
,08-23 12:39:11.969   872  1302 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-23 12:39:11.969   872  1302 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-23 12:39:11.971   872  1300 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-23 12:39:11.976   872  4244 D DhcpClient: Receive thread started
,08-23 12:39:12.059   872  1300 E native  : do suspend false
,08-23 12:39:12.080   872  1872 D DhcpClient: Broadcasting DHCPDISCOVER
,08-23 12:39:12.099   872  4244 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172784, domain null
,08-23 12:39:12.100   872  1872 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172784 seconds
,08-23 12:39:12.103   872  1872 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-23 12:39:12.119   872  4244 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-23 12:39:12.120   872  1872 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-23 12:39:12.125   371   870 D CommandListener: Setting iface cfg
,08-23 12:39:12.139   872  1300 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-23 12:39:12.142   872  1872 D DhcpClient: Scheduling renewal in 86399s
,08-23 12:39:12.154   872  1300 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-23 12:39:12.157   872  1300 D WifiConfigStore: No blacklist allowed without epno enabled
08-23 12:39:12.159   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-23 12:39:12.162   872  1302 D ConnectivityService: Adding iface wlan0 to network 102
,08-23 12:39:12.171   872  1300 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-23 12:39:12.214   872  1302 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-23 12:39:12.214   872  1302 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-23 12:39:12.216   872  1302 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-23 12:39:12.218   872  1302 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-23 12:39:12.219   872  1302 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-23 12:39:12.229   872  1302 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-23 12:39:12.234   872  1302 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-23 12:39:12.234   872  1302 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-23 12:39:12.235   872  1300 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-23 12:39:12.235   872  1300 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-23 12:39:12.235   872  1302 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-23 12:39:12.236   872  1302 D ConnectivityService:    accepting network in place of null
,08-23 12:39:12.237   872  1302 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -54]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-23 12:39:12.246   872  4242 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145322, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-23 12:39:12.276   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:39:12.305   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-23 12:39:12.316   872  1302 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-23 12:39:12.316   872  1302 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:39:12.321   872  1302 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-23 12:39:12.322   872  4241 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:401b:801::200e
,08-23 12:39:12.322   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:12.341  3779  3779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:12.346  3779  3779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:12.353  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:12.355  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:39:12.358  3779  3829 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-23 12:39:12.359  3779  3829 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-23 12:39:12.361  3779  3829 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ed98a75 Bundle[{}]
,08-23 12:39:12.361  3779  3829 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 12:39:12.361  3779  3829 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 12:39:12.362  3779  3829 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-23 12:39:12.363  3779  3829 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-23 12:39:12.363  3779  3829 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 12:39:12.364  3779  3829 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-23 12:39:12.368  3779  3829 I System.out: Running OutgoingSocketThread
,08-23 12:39:12.369  1735  1735 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-23 12:39:12.370  3779  4252 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 420)
,08-23 12:39:12.372  3779  4252 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48707
,08-23 12:39:12.372  3779  4252 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-23 12:39:12.374  1735  1735 D SystemUpdateService: onCreate
,08-23 12:39:12.382  1735  1735 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-23 12:39:12.405  1735  4254 I SystemUpdateService: active receiver: enabled
,08-23 12:39:12.406   872  4241 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 23 Aug 2016 10:39:12 GMT], X-Android-Received-Millis=[1471948752405], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471948752379]}
,08-23 12:39:12.407   872  1302 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-23 12:39:12.407   872  1302 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-23 12:39:12.407   872  1302 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-23 12:39:12.408   872  1302 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-23 12:39:12.408  1735  1735 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-23 12:39:12.414  1735  2410 I iu.UploadsManager: num queued entries: 0
,08-23 12:39:12.436  1735  1735 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-23 12:39:12.437  1735  1735 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-23 12:39:12.441  3962  3962 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-23 12:39:12.452  3962  3962 D SprintDMHelper: simOperator: 
,08-23 12:39:12.452  3962  3962 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-23 12:39:12.465  1735  4257 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-23 12:39:12.465  1735  4257 W BaseAppContext: Using Auth Proxy for data requests.
,08-23 12:39:12.466  1735  4257 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-23 12:39:12.469  1735  2410 I iu.UploadsManager: num updated entries: 0
,08-23 12:39:12.472  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:39:12.472  1735  4254 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-23 12:39:12.475  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-23 12:39:12.476  1735  2410 I iu.SyncManager: NEXT; no task
,08-23 12:39:12.477  1735  4254 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-23 12:39:12.479  1735  4254 I SystemUpdateService: now status is 0 (complete)
08-23 12:39:12.479  1735  4254 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-23 12:39:12.479  1735  4254 I SystemUpdateService: file has been verified
08-23 12:39:12.479  1735  4254 I SystemUpdateService: OTA package size = 12249756
,08-23 12:39:12.484  1735  4254 I SystemUpdateService: showing system update notification
,08-23 12:39:12.503  1519  2953 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-23 12:39:12.503  1519  2953 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-23 12:39:12.503  1519  2953 I GLSUser : [GLSUser] Extracting token using key: Auth
08-23 12:39:12.503  1519  2953 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:39:12.522  1735  1735 D SystemUpdateService: onDestroy
,08-23 12:39:12.538  1735  4257 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-23 12:39:12.557  3920  4260 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-23 12:39:13.076  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-23 12:39:13.145  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-23 12:39:13.146  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-23 12:39:13.146  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-23 12:39:13.146  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-23 12:39:13.202  3486  3486 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-23 12:39:13.203  3486  3486 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-23 12:39:13.208  3486  3486 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-23 12:39:13.372  3779  3829 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 421)
,08-23 12:39:13.372  3779  3829 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 421)
,08-23 12:39:13.382  3779  3829 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
,08-23 12:39:13.384  3779  3829 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-23 12:39:13.384  3779  3829 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 427)
,08-23 12:39:13.390  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 12:39:13.390  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4eee322 added. We now have 2 listener(s)
,08-23 12:39:13.391  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 12:39:13.392  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:13.392  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:13.392  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:13.392  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13741b3 added. We now have 9 listener(s)
08-23 12:39:13.392  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:13.393  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:13.396  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:13.404  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:13.407  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:39:13.407  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:39:13.408  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 12:39:13.408  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a51b6e9 added. We now have 3 listener(s)
,08-23 12:39:13.410  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:13.415  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 12:39:13.416  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:39:13.416  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:13.416  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:13.417  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbc0f6e added. We now have 10 listener(s)
08-23 12:39:13.417  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:13.417  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:13.417  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:39:13.418  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:13.418  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 12:39:13.418  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:13.418  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.419  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:13.419  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 12:39:13.419  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4eee322 removed from the list
08-23 12:39:13.419  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.420  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13741b3 removed from the list
,08-23 12:39:13.420  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:39:13.420  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:13.422  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.423  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.424  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:13.424  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:13.425  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.425  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13741b3 not in the list
08-23 12:39:13.425  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.426  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:13.427  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:13.427  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:13.427  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:39:13.428  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bbc0f6e removed from the list
08-23 12:39:13.428  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:13.428  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.428  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:13.429  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:13.429  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a51b6e9 removed from the list
08-23 12:39:13.431  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:13.431  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8da460f added. We now have 2 listener(s)
,08-23 12:39:13.437  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 12:39:13.438  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:13.438  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:13.438  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:13.439  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e2969c added. We now have 9 listener(s)
,08-23 12:39:13.439  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:13.440  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:13.446  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:13.452  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:13.454  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:39:13.454  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:39:13.454  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:13.454  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1db47a added. We now have 3 listener(s)
08-23 12:39:13.456  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 12:39:13.456  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:13.456  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:13.456  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:13.457  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bff342b added. We now have 10 listener(s)
08-23 12:39:13.457  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:13.457  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:13.457  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:13.457  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:39:13.457  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-23 12:39:13.457  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:13.457  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-23 12:39:13.460  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:13.461  3779  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-23 12:39:13.461  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:39:13.465  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:39:13.465  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 12:39:13.466  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:39:13.469  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 12:39:13.469  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:39:13.469  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-23 12:39:13.470  3779  3829 D BluetoothAdapter: STATE_ON
,08-23 12:39:13.473  4188  4227 D BtGatt.GattService: registerClient() - UUID=7229d11f-e364-4809-85d3-c008acca75e8
,08-23 12:39:13.474  4188  4204 D BtGatt.GattService: onClientRegistered() - UUID=7229d11f-e364-4809-85d3-c008acca75e8, clientIf=5
,08-23 12:39:13.475  3779  3791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-23 12:39:13.476  4188  4236 D BtGatt.GattService: start scan with filters
,08-23 12:39:13.481  4188  4207 D BtGatt.ScanManager: handling starting scan
,08-23 12:39:13.481  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:39:13.481  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:39:13.481  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 12:39:13.482  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,08-23 12:39:13.482  4188  4207 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@93eebb9
,08-23 12:39:13.486  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:13.486  4188  4204 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-23 12:39:13.487  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:13.487  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.487  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 12:39:13.487  4188  4207 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 12:39:13.490  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:39:13.494  4188  4204 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-23 12:39:13.495  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.495  4188  4207 D BtGatt.ScanManager: Starting BLE batch scan
,08-23 12:39:13.495  4188  4207 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 12:39:13.496  3779  3829 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-23 12:39:13.497  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:13.497  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-23 12:39:13.497  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:39:13.497  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-23 12:39:13.497  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-23 12:39:13.497  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-23 12:39:13.497  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:39:13.498  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:39:13.498  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:39:13.498  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-23 12:39:13.499  3779  3829 D BluetoothAdapter: STATE_ON
08-23 12:39:13.500  4188  4236 D BtGatt.GattService: stopScan() - queue size =1
08-23 12:39:13.501  4188  4198 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 12:39:13.501  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-23 12:39:13.501  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 12:39:13.502  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-23 12:39:13.502  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-23 12:39:13.502  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:39:13.504  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:39:13.504  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 12:39:13.504  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:39:13.504  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-23 12:39:13.505  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-23 12:39:13.507  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 12:39:13.507  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:13.507  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:13.508  4188  4204 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-23 12:39:13.508  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.510  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:39:13.511  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-23 12:39:13.511  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:39:13.511  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:13.511  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:39:13.512  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:13.512  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 12:39:13.512  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8da460f removed from the list
08-23 12:39:13.512  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-23 12:39:13.512  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e2969c removed from the list
08-23 12:39:13.512  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:39:13.512  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:13.513  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.513  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:13.515  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:13.515  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-23 12:39:13.515  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.515  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4e2969c not in the list
,08-23 12:39:13.515  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.516  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.516  4188  4204 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 12:39:13.516  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.517  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:13.517  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:39:13.517  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.517  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bff342b removed from the list
,08-23 12:39:13.517  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:39:13.517  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.517  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.518  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 12:39:13.518  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1db47a removed from the list
08-23 12:39:13.519  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:13.519  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ae807 added. We now have 2 listener(s)
,08-23 12:39:13.522  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 12:39:13.522  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:39:13.523  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:13.523  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:13.523  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8311d34 added. We now have 9 listener(s)
08-23 12:39:13.523  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:13.524  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:13.525  4188  4204 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 12:39:13.525  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-23 12:39:13.525  4188  4207 D BtGatt.ScanManager: stopping BLe Batch
,08-23 12:39:13.528  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:13.533  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:13.534  4188  4204 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 12:39:13.534  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.534  4188  4207 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-23 12:39:13.535  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:13.535  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:39:13.535  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:13.535  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7a58d2 added. We now have 3 listener(s)
,08-23 12:39:13.538  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:13.539  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 12:39:13.539  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:13.539  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:13.540  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:13.540  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@593fda3 added. We now have 10 listener(s)
08-23 12:39:13.540  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:13.541  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:13.541  4188  4204 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-23 12:39:13.541  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.542  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:13.543  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-23 12:39:13.543  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-23 12:39:13.543  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:39:13.543  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:39:13.543  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 12:39:13.546  3779  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 12:39:13.547  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:39:13.551  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:39:13.552  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-23 12:39:13.552  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-23 12:39:13.556  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-23 12:39:13.556  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:39:13.556  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 12:39:13.557  3779  3829 D BluetoothAdapter: STATE_ON
,08-23 12:39:13.559  4188  4227 D BtGatt.GattService: registerClient() - UUID=fe71a8d5-7338-40d6-a8d7-fe7c7bcdcc5e
,08-23 12:39:13.559  4188  4204 D BtGatt.GattService: onClientRegistered() - UUID=fe71a8d5-7338-40d6-a8d7-fe7c7bcdcc5e, clientIf=5
08-23 12:39:13.560  3779  3790 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 12:39:13.560  4188  4199 D BtGatt.GattService: start scan with filters
,08-23 12:39:13.563  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-23 12:39:13.563  4188  4207 D BtGatt.ScanManager: handling starting scan
08-23 12:39:13.563  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:39:13.563  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-23 12:39:13.563  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-23 12:39:13.567  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:13.568  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-23 12:39:13.568  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-23 12:39:13.572  4188  4204 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 12:39:13.572  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-23 12:39:13.572  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.572  4188  4207 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-23 12:39:13.577  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 12:39:13.577  3779  3829 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-23 12:39:13.577  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:39:13.577  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:13.578  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:39:13.578  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:13.578  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:39:13.578  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 12:39:13.578  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 12:39:13.578  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ae807 removed from the list
08-23 12:39:13.578  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.579  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8311d34 removed from the list
08-23 12:39:13.579  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
,08-23 12:39:13.579  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:13.579  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.580  4188  4204 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 12:39:13.580  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-23 12:39:13.580  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.580  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.580  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:13.580  4188  4207 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:39:13.580  4188  4207 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-23 12:39:13.581  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:13.581  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:39:13.581  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.582  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8311d34 not in the list
08-23 12:39:13.582  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:39:13.582  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:39:13.582  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-23 12:39:13.582  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:39:13.582  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 12:39:13.583  3779  3829 D BluetoothAdapter: STATE_ON
,08-23 12:39:13.584  4188  4199 D BtGatt.GattService: stopScan() - queue size =1
08-23 12:39:13.585  4188  4236 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 12:39:13.586  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:39:13.586  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-23 12:39:13.586  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:39:13.586  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:39:13.586  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-23 12:39:13.588  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:39:13.588  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-23 12:39:13.588  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:39:13.588  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:39:13.589  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.590  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:39:13.591  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:13.591  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.591  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:13.591  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@593fda3 removed from the list
,08-23 12:39:13.591  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:13.591  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.591  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:13.591  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.591  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:13.591  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:39:13.591  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7a58d2 removed from the list
,08-23 12:39:13.592  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:13.592  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bded0ff added. We now have 2 listener(s)
08-23 12:39:13.594  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 12:39:13.594  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:39:13.594  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:13.594  4188  4204 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-23 12:39:13.594  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:13.594  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.594  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c6decc added. We now have 9 listener(s)
08-23 12:39:13.595  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:13.595  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:13.597  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:39:13.600  4188  4204 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-23 12:39:13.600  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:13.602  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:13.604  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:39:13.604  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 12:39:13.604  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-23 12:39:13.605  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98c302a added. We now have 3 listener(s)
,08-23 12:39:13.607  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:13.608  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-23 12:39:13.608  4188  4204 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-23 12:39:13.608  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.608  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:13.608  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:13.608  4188  4207 D BtGatt.ScanManager: stopping BLe Batch
,08-23 12:39:13.608  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:13.608  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d97e1b added. We now have 10 listener(s)
,08-23 12:39:13.608  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:13.608  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
,08-23 12:39:13.609  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-23 12:39:13.609  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-23 12:39:13.609  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:39:13.609  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-23 12:39:13.610  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:13.613  3779  3829 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-23 12:39:13.613  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-23 12:39:13.615  4188  4204 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-23 12:39:13.616  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.616  4188  4207 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-23 12:39:13.621  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-23 12:39:13.622  4188  4204 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 12:39:13.622  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.622  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-23 12:39:13.622  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-23 12:39:13.625  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-23 12:39:13.625  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-23 12:39:13.625  3779  3829 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-23 12:39:13.626  3779  3829 D BluetoothAdapter: STATE_ON
08-23 12:39:13.628  4188  4198 D BtGatt.GattService: registerClient() - UUID=7f7cf82a-48d8-463f-af78-cb736d44828d
08-23 12:39:13.629  4188  4204 D BtGatt.GattService: onClientRegistered() - UUID=7f7cf82a-48d8-463f-af78-cb736d44828d, clientIf=5
08-23 12:39:13.629  3779  3791 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-23 12:39:13.629  4188  4227 D BtGatt.GattService: start scan with filters
08-23 12:39:13.632  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-23 12:39:13.632  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-23 12:39:13.632  4188  4207 D BtGatt.ScanManager: handling starting scan
08-23 12:39:13.632  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-23 12:39:13.632  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-23 12:39:13.635  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:39:13.635  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-23 12:39:13.635  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-23 12:39:13.637  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-23 12:39:13.638  4188  4204 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-23 12:39:13.639  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.639  4188  4207 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-23 12:39:13.644  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-23 12:39:13.644  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:13.644  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-23 12:39:13.645  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:13.645  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.645  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-23 12:39:13.645  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:13.645  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bded0ff removed from the list
08-23 12:39:13.645  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.645  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c6decc removed from the list
08-23 12:39:13.645  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:39:13.645  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:13.645  4188  4204 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-23 12:39:13.646  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.646  4188  4207 D BtGatt.ScanManager: Starting BLE batch scan
08-23 12:39:13.646  4188  4207 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-23 12:39:13.647  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.647  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-23 12:39:13.647  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.647  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:13.648  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:13.648  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:13.648  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.648  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c6decc not in the list
08-23 12:39:13.648  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-23 12:39:13.649  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-23 12:39:13.649  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-23 12:39:13.649  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-23 12:39:13.649  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-23 12:39:13.649  3779  3829 D BluetoothAdapter: STATE_ON
08-23 12:39:13.650  4188  4199 D BtGatt.GattService: stopScan() - queue size =1
08-23 12:39:13.651  4188  4227 D BtGatt.GattService: unregisterClient() - clientIf=5
08-23 12:39:13.651  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-23 12:39:13.651  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-23 12:39:13.651  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-23 12:39:13.652  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-23 12:39:13.652  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-23 12:39:13.653  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-23 12:39:13.653  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-23 12:39:13.653  3779  3829 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-23 12:39:13.653  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-23 12:39:13.654  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:13.655  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:13.655  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:39:13.655  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.655  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-23 12:39:13.655  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d97e1b removed from the list
08-23 12:39:13.655  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:39:13.655  3779  3779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-23 12:39:13.655  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.656  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.656  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:13.656  3779  3779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-23 12:39:13.656  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98c302a removed from the list
08-23 12:39:13.656  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 12:39:13.657  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a07e0f7 added. We now have 2 listener(s)
08-23 12:39:13.658  4188  4204 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-23 12:39:13.659  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 12:39:13.659  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 12:39:13.658  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.659  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 12:39:13.659  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-23 12:39:13.659  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f03b64 added. We now have 9 listener(s)
,08-23 12:39:13.660  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 12:39:13.660  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-23 12:39:13.662  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 12:39:13.666  4188  4204 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-23 12:39:13.666  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:39:13.667  3779  3829 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 12:39:13.670  3779  3829 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 12:39:13.670  3779  3829 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:39:13.670  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-23 12:39:13.670  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@669a82 added. We now have 3 listener(s)
08-23 12:39:13.673  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-23 12:39:13.673  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:39:13.673  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:39:13.673  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-23 12:39:13.673  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f9593 added. We now have 10 listener(s)
08-23 12:39:13.673  3779  3829 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:39:13.673  3779  3829 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-23 12:39:13.674  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:39:13.674  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:13.674  3779  3829 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-23 12:39:13.674  4188  4204 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-23 12:39:13.674  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:39:13.674  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.675  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:39:13.675  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-23 12:39:13.675  4188  4207 D BtGatt.ScanManager: stopping BLe Batch
08-23 12:39:13.675  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 12:39:13.675  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a07e0f7 removed from the list
08-23 12:39:13.675  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.676  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f03b64 removed from the list
08-23 12:39:13.677  3779  3779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 12:39:13.677  3779  3829 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:39:13.677  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.678  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.678  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.679  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-23 12:39:13.679  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-23 12:39:13.679  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.679  3779  3829 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f03b64 not in the list
08-23 12:39:13.679  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-23 12:39:13.679  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:39:13.680  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-23 12:39:13.680  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-23 12:39:13.680  3779  3829 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:39:13.680  3779  3829 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f9593 removed from the list
08-23 12:39:13.681  3779  3829 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-23 12:39:13.681  3779  3829 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:39:13.681  3779  3829 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-23 12:39:13.681  3779  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:39:13.681  3779  3829 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@669a82 removed from the list
08-23 12:39:13.681  4188  4204 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-23 12:39:13.682  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-23 12:39:13.682  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-23 12:39:13.682  4188  4207 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-23 12:39:13.682  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-23 12:39:13.682  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-23 12:39:13.682  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-23 12:39:13.682  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-23 12:39:13.682  3779  3829 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-23 12:39:13.688  3779  4266 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: My test thread name)
,08-23 12:39:13.688  4188  4204 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-23 12:39:13.689  4188  4204 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-23 12:39:13.689  3779  4266 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 434, thread name: My test thread name)
,08-23 12:39:13.689  3779  4266 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 434, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 12:39:13.691  3779  4267 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
,08-23 12:39:13.691  3779  4267 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
08-23 12:39:13.691  3779  4267 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-23 12:39:13.693  3779  3829 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-23 12:39:13.693  3779  3829 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-23 12:39:13.693  3779  3829 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-23 12:39:13.693  3779  3829 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-23 12:39:13.693  3779  3829 D com.test.thalitest.ThaliTestRunner: Total duration: 22766 ms
08-23 12:39:13.695  3779  3829 I jxcore-log: Total number of executed tests:  80
08-23 12:39:13.695  3779  3829 I jxcore-log: 
08-23 12:39:13.695  3779  3829 I jxcore-log: Number of passed tests:  80
08-23 12:39:13.695  3779  3829 I jxcore-log: 
,08-23 12:39:13.695  3779  3829 I jxcore-log: Number of failed tests:  0
08-23 12:39:13.695  3779  3829 I jxcore-log: 
08-23 12:39:13.695  3779  3829 I jxcore-log: Number of ignored tests:  0
08-23 12:39:13.695  3779  3829 I jxcore-log: 
,08-23 12:39:13.696  3779  3829 I jxcore-log: Total duration:  22766
08-23 12:39:13.696  3779  3829 I jxcore-log: 
08-23 12:39:13.696  3779  3829 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-23 12:39:13.696  3779  3829 I jxcore-log: 
,08-23 12:39:13.701  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.701  3779  3829 I jxcore-log: 
08-23 12:39:13.704  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.704  3779  3829 I jxcore-log: 
08-23 12:39:13.705  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.705  3779  3829 I jxcore-log: 
08-23 12:39:13.706  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.706  3779  3829 I jxcore-log: 
08-23 12:39:13.707  3779  3779 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-23 12:39:13.708  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.708  3779  3829 I jxcore-log: 
08-23 12:39:13.709  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.709  3779  3829 I jxcore-log: 
08-23 12:39:13.712  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.712  3779  3829 I jxcore-log: 
08-23 12:39:13.713  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.713  3779  3829 I jxcore-log: 
08-23 12:39:13.714  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.714  3779  3829 I jxcore-log: 
,08-23 12:39:13.714  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:13.714  3779  3829 I jxcore-log: 
08-23 12:39:13.715  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:39:13.715  3779  3829 I jxcore-log: 
,08-23 12:39:13.716  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-23 12:39:13.716  3779  3829 I jxcore-log: 
,08-23 12:39:13.716  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.716  3779  3829 I jxcore-log: 
,08-23 12:39:13.717  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.717  3779  3829 I jxcore-log: 
08-23 12:39:13.717  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.717  3779  3829 I jxcore-log: 
,08-23 12:39:13.718  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.718  3779  3829 I jxcore-log: 
08-23 12:39:13.718  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.718  3779  3829 I jxcore-log: 
,08-23 12:39:13.719  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.719  3779  3829 I jxcore-log: 
08-23 12:39:13.719  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.719  3779  3829 I jxcore-log: 
,08-23 12:39:13.720  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.720  3779  3829 I jxcore-log: 
08-23 12:39:13.720  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.720  3779  3829 I jxcore-log: 
,08-23 12:39:13.721  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-23 12:39:13.721  3779  3829 I jxcore-log: 
,08-23 12:39:13.721  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-23 12:39:13.721  3779  3829 I jxcore-log: 
08-23 12:39:13.722  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.722  3779  3829 I jxcore-log: 
,08-23 12:39:13.722  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.722  3779  3829 I jxcore-log: 
08-23 12:39:13.723  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.723  3779  3829 I jxcore-log: 
,08-23 12:39:13.723  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.723  3779  3829 I jxcore-log: 
08-23 12:39:13.724  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.724  3779  3829 I jxcore-log: 
,08-23 12:39:13.724  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.724  3779  3829 I jxcore-log: 
08-23 12:39:13.725  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 12:39:13.725  3779  3829 I jxcore-log: 
,08-23 12:39:14.008  3779  3779 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 12:39:14.012  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:14.012  3779  3829 I jxcore-log: 
,08-23 12:39:14.092  3779  3779 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 12:39:14.096  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:14.096  3779  3829 I jxcore-log: 
,08-23 12:39:14.156  3779  3779 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-23 12:39:14.161  3779  3829 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-23 12:39:14.161  3779  3829 I jxcore-log: 
,08-23 12:39:14.342  4268  4268 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-23 12:39:14.347  4268  4268 D AndroidRuntime: CheckJNI is OFF
,08-23 12:39:14.390  4268  4268 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-23 12:39:14.438  4268  4268 I Radio-JNI: register_android_hardware_Radio DONE
,08-23 12:39:14.460  4268  4268 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 12:39:14.477   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-23 12:39:14.479   872   885 I ActivityManager: Killing 3779:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-23 12:39:14.574   872   882 D GraphicsStats: Buffer count: 2
,08-23 12:39:14.574   872  1362 I WindowState: WIN DEATH: Window{1a94cdd u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 12:39:14.574   872  1301 D WifiService: Client connection lost with reason: 4
,08-23 12:39:14.585   872   895 W PackageSettings: Skipping PackageSetting{43f6582 com.example.hello/10273} due to missing metadata
,08-23 12:39:14.596   872   885 W ActivityManager: Force removing ActivityRecord{d5b589a u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,08-23 12:39:14.623   872   895 I art     : Starting a blocking GC Explicit
,08-23 12:39:14.626   872   882 W ActivityManager: Spurious death for ProcessRecord{541c5bb 0:com.test.thalitest/u0a0}, curProc for 3779: null
,08-23 12:39:14.665   872  1927 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3779 uid 10000
,08-23 12:39:14.666  1853  1853 I Keyboard.Facilitator: onFinishInput()
,08-23 12:39:14.691   872   895 I art     : Explicit concurrent mark sweep GC freed 24749(1618KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.091ms total 60.968ms
,08-23 12:39:14.726   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-23 12:39:14.728  4268  4268 I art     : System.exit called, status: 0
08-23 12:39:14.728  4268  4268 I AndroidRuntime: VM exiting with result code 0.
,08-23 12:39:14.735  1987  4282 I MicroRecognitionRnrImpl: Starting detection.
,08-23 12:39:14.737  1987  4283 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@fe4bb81
08-23 12:39:14.739   375  4285 I AudioFlinger: AudioFlinger's thread 0xb1b80000 ready to run
08-23 12:39:14.741   375  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-23 12:39:14.742   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-23 12:39:14.742  1987  4283 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@fe4bb81
,08-23 12:39:14.751   375  4285 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(61: voice-rec-mic)
,08-23 12:39:14.751   375  4285 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(61) acdb_id(62)
08-23 12:39:14.752   375  4285 D audio_hw_primary: enable_snd_device: snd_device(61: voice-rec-mic)
,08-23 12:39:14.757   375  4285 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,08-23 12:39:14.761  4188  4188 D BluetoothMapAppObserver: onReceive
08-23 12:39:14.762  4188  4188 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-23 12:39:14.762  1853  1853 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-23 12:39:14.765  2119  2237 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 12:39:14.767   872  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 12:39:14.768  1853  4287 I Keyboard.Facilitator.DecoderInitializer: run()
,08-23 12:39:14.770  1853  4287 I Decoder : createOrResetDecoder
,08-23 12:39:14.795  3650  3650 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-23 12:39:14.804  1912  1912 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-23 12:39:14.820   872  1955 I ActivityManager: Start proc 4290:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-23 12:39:14.830  1519  1519 I ConfigService: onCreate
,08-23 12:39:14.837  1987  1987 I HotwordWorkerImpl: onReady
,08-23 12:39:14.862  1853  4287 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-23 12:39:14.873   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 12:39:14.881  4290  4290 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-23 12:39:14.895  1925  2005 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-23 12:39:14.896   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-23 12:39:14.896   872   884 E PackageManager: Failed to write settings, restoring backup
08-23 12:39:14.896   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-23 12:39:14.896   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-23 12:39:14.896   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-23 12:39:14.896   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-23 12:39:14.896   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-23 12:39:14.896   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:14.896   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:39:14.896   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:39:14.901   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-23 12:39:14.901   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-23 12:39:14.901   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:39:14.901   872   885 E DropBoxManagerService: 	... 13 more
,08-23 12:39:14.909   872   882 I ActivityManager: Start proc 4304:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-23 12:39:14.909  1925  2005 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-23 12:39:14.909  1925  2005 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1925
08-23 12:39:14.909  1925  2005 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	,at android.os.Looper.loop(Looper.java:148)
08-23 12:39:14.909  1925  2005 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:39:14.911   872  1927 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-23 12:39:14.911   872  4312 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:39:14.911   872  4312 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: ,	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:39:14.911   872  4312 E DropBoxManagerService: 	... 5 more
,08-23 12:39:14.916  1987  2004 W SearchService: Abort, client detached.
,08-23 12:39:14.918  1987  1987 I HotwordDetector: Closing mic
08-23 12:39:14.919  1987  2297 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fe4bb81
08-23 12:39:14.919  1987  4283 E AudioRecord-JNI: Error -4 during AudioRecord native read,
,08-23 12:39:14.927   872  4318 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-23 12:39:14.929  1853  4287 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-23 12:39:14.930  1853  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-23 12:39:14.931  1853  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-23 12:39:14.938  1987  4320 E Search.SharedPreferencesProto: Failed to rename to backup file /data/user/0/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,08-23 12:39:14.938  1853  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-23 12:39:14.938  1853  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-23 12:39:14.939  1853  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,08-23 12:39:14.939  1853  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-23 12:39:14.940  1853  4287 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-23 12:39:14.940  1853  4287 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-23 12:39:14.940  1853  4287 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-23 12:39:14.940  1853  4287 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-23 12:39:14.940  1853  4287 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-23 12:39:14.940  1853  4287 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-23 12:39:14.957   872  4318 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-23 12:39:14.957   872  4318 I Adreno  : Build Date                       : 10/20/15
08-23 12:39:14.957   872  4318 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-23 12:39:14.957   872  4318 I Adreno  : Local Branch                     : M14
08-23 12:39:14.957   872  4318 I Adreno  : Remote Branch                    : 
08-23 12:39:14.957   872  4318 I Adreno  : Remote Branch                    : 
08-23 12:39:14.957   872  4318 I Adreno  : Reconstruct Branch               : 
,08-23 12:39:14.962   872  4318 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 12:39:14.965  4290  4290 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-23 12:39:14.976  4290  4323 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 12:39:14.981   375  4285 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,08-23 12:39:14.982   872  3958 I ActivityManager: Start proc 4326:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-23 12:39:14.983   375  4285 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-23 12:39:14.991   375  1272 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0,
08-23 12:39:14.994  1987  2306 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-23 12:39:14.994  1987  4282 I MicroRecognitionRnrImpl: Detection finished
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
,08-23 12:39:14.997  4290  4321 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:39:14.997  4290  4321 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:39:14.997   872  1302 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102],
,08-23 12:39:15.021  4326  4326 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-23 12:39:15.052  1519  1519 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-23 12:39:15.053  1519  1519 D AndroidRuntime: Shutting down VM
08-23 12:39:15.054  1519  1519 E AndroidRuntime: FATAL EXCEPTION: main
08-23 12:39:15.054  1519  1519 E AndroidRuntime: Process: com.google.process.gapps, PID: 1519
08-23 12:39:15.054  1519  1519 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-23 12:39:15.054  1519  1519 E AndroidRuntime: 	... 8 more
,08-23 12:39:15.057   872  4343 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:39:15.057   872  4343 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:39:15.057   872  4343 E DropBoxManagerService: 	... 5 more
,08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:39:15.074  4290  4321 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-23 12:39:15.084  1735  4345 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-23 12:39:15.084  1735  4345 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-23 12:39:15.102  4290  4321 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-23 12:39:15.107  4290  4323 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:39:15.107  4290  4323 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-23 12:39:15.109  4290  4323 E AndroidRuntime: Process: android.process.acore, PID: 4290
08-23 12:39:15.109  4290  4323 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-23 12:39:15.109  4290  4323 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-23 12:39:15.109  4290  4323 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:39:15.111   872  4346 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:39:15.111   872  4346 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-23 12:39:15.111   872  4346 ,E DropBoxManagerService: 	... 5 more
08-23 12:39:15.111  4290  4321 I Process : Sending signal. PID: 4290 SIG: 9
,08-23 12:39:15.155   872  1542 I ActivityManager: Process android.process.acore (pid 4290) has died
08-23 12:39:15.157   872  1542 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-23 12:39:15.255   282   282 E qdoverlay: Bad ov dump:  mdp_overlay z=0 fg=0 alpha=255 mask=-1 flags=0x20000 id=8
,08-23 12:39:15.255   282   282 E qdoverlay: src msmfb_img w=1664 h=2560 format=13 MDP_RGBA_8888
08-23 12:39:15.255   282   282 E qdoverlay: src_rect mdp_rect x=0 y=0 w=720 h=2560
,08-23 12:39:15.256   282   282 E qdoverlay: dst_rect mdp_rect x=0 y=0 w=720 h=2560
08-23 12:39:15.256   282   282 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_UNSET err=Operation not permitted
,08-23 12:39:15.256   282   282 E qdoverlay: MdpCtrl close error in unset

```
